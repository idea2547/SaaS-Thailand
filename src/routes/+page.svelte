<script lang="ts">
    import { Button } from "$lib/components/ui/button";
    import * as Table from "$lib/components/ui/table";
    import Icon from '@iconify/svelte';
</script>


<div class="flex flex-col w-full items-center justify-center mt-24">
   
    <h1 class="scroll-m-20 text-4xl font-extrabold tracking-tight lg:text-5xl">
        SaaS Thailand
    </h1>
    <div class="p-5 text-center">
        <p class="leading-5 sm:leading-6 md:leading-7 lg:leading-8 [&:not(:first-child)]:mb-5">
            เว็บไซต์ที่สนับสนุนและรวบรวม SaaS ( Software-as-a-Service ) ต่างๆ
            แห่งประเทศไทย
        </p>

    </div>
    
    <a href="https://docs.google.com/forms/d/e/1FAIpQLSfY2ougjKrJ5aRfpSqEY59aq9_7scY1o8Jtf5f597wdBsbmnw/viewform?usp=sf_link">
        <Button>เรียนรู้เพิ่มเติม</Button>
    </a>
    <!-- grid-cols-2 gap-4 p-3 lg:grid-cols-3 -->
    <div class="grid p-3">
        <a href="https://web.facebook.com/profile.php?id=61560121365380">
            <Icon icon="ic:baseline-facebook" style="font-size: 2.5rem;" />
        </a>
        
    </div>
    
    
</div>

<div class="flex flex-col items-center justify-center py-5 sm:p-10 md:p-20 lg:p-48 w-full">
    <h2
        class="mb-5 scroll-m-20 border-b pb-2 text-3xl font-semibold tracking-tight transition-colors first:mt-0"
    >
        SaaS Product ยอดนิยมในวันนี้
    </h2>
    <div class="w-full max-w-[800px]">
        <Table.Root class="w-full min-w-[300px] overflow-x-auto">
            <Table.Caption class="text-center mb-4">List รายชื่อ SaaS</Table.Caption>
            <Table.Header>
                <Table.Row>
                    <Table.Head class="w-[100px]">อันดับที่</Table.Head>
                    <Table.Head class="w-[100px]">Icon</Table.Head>
                    <Table.Head>ชื่อ</Table.Head>
                    <Table.Head>รายละเอียด</Table.Head>
                    <Table.Head class="text-right">จำนวนการโหวต</Table.Head>
                </Table.Row>
            </Table.Header>
            <Table.Body>
                <Table.Row>
                    <Table.Cell class="font-medium">#1</Table.Cell>
                    <Table.Cell>[icon]</Table.Cell>
                    <Table.Cell>SaaS Thailand</Table.Cell>
                    <Table.Cell class="text-right">เว็บไซต์ที่สนับสนุนและรวบรวม SaaS ( Software-as-a-Service ) ต่างๆ แห่งประเทศไทย</Table.Cell>
                </Table.Row>
                <Table.Row>
                    <Table.Cell class="font-medium">#2</Table.Cell>
                    <Table.Cell>[icon]</Table.Cell>
                    <Table.Cell>SaaS Thailand</Table.Cell>
                    <Table.Cell class="text-right">เว็บไซต์ที่สนับสนุนและรวบรวม SaaS ( Software-as-a-Service ) ต่างๆ แห่งประเทศไทย</Table.Cell>
                </Table.Row>
            </Table.Body>
        </Table.Root>
    </div>
</div>

