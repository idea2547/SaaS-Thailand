<script lang="ts">
    import * as Table from "$lib/components/ui/table";
</script>

<div class="flex flex-col items-center justify-center py-5 sm:p-10 md:p-20 lg:p-48 w-full">
    <h2
        class="mb-5 scroll-m-20 border-b pb-2 text-3xl font-semibold tracking-tight transition-colors first:mt-0"
    >
        SaaS Product ยอดนิยมในวันนี้
    </h2>
    <div class="w-full max-w-[800px]">
        <Table.Root class="w-full min-w-[300px] overflow-x-auto">
            <Table.Caption class="text-center mb-4">A list of your recent invoices.</Table.Caption>
            <Table.Header>
                <Table.Row>
                    <Table.Head class="w-[100px]">ไอคอน</Table.Head>
                    <Table.Head>ชื่อ</Table.Head>
                    <Table.Head>รายละเอียด</Table.Head>
                    <Table.Head class="text-right">จำนวนการโหวต</Table.Head>
                </Table.Row>
            </Table.Header>
            <Table.Body>
                <Table.Row>
                    <Table.Cell class="font-medium">INV001</Table.Cell>
                    <Table.Cell>Paid</Table.Cell>
                    <Table.Cell>Credit Card</Table.Cell>
                    <Table.Cell class="text-right">$250.00</Table.Cell>
                </Table.Row>
                <Table.Row>
                    <Table.Cell class="font-medium">INV002</Table.Cell>
                    <Table.Cell>Paid</Table.Cell>
                    <Table.Cell>Credit Card</Table.Cell>
                    <Table.Cell class="text-right">$250.00</Table.Cell>
                </Table.Row>
            </Table.Body>
        </Table.Root>
    </div>
</div>
