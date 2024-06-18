<script lang="ts">
	import * as Menubar from '$lib/components/ui/menubar';
	import '../app.css';
	import * as Drawer from '$lib/components/ui/drawer';
	import Button from '$lib/components/ui/button/button.svelte';
</script>


<Drawer.Root>
	<Drawer.Trigger>
        <button data-drawer-target="default-sidebar" data-drawer-toggle="default-sidebar" aria-controls="default-sidebar" type="button" class="mx-auto inline-flex items-center p-2 mt-2 ml-3 text-sm rounded-lg sm:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:hover:bg-gray-700 dark:focus:ring-gray-600">
            <svg class="w-6 h-6" aria-hidden="true" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
            <path clip-rule="evenodd" fill-rule="evenodd" d="M2 4.75A.75.75 0 012.75 4h14.5a.75.75 0 010 1.5H2.75A.75.75 0 012 4.75zm0 10.5a.75.75 0 01.75-.75h7.5a.75.75 0 010 1.5h-7.5a.75.75 0 01-.75-.75zM2 10a.75.75 0 01.75-.75h14.5a.75.75 0 010 1.5H2.75A.75.75 0 012 10z"></path>
            </svg>
        </button>
    </Drawer.Trigger>
	<Drawer.Content class="p-5">
		<Drawer.Header>
            <!-- <Menubar.Trigger>ชุมชน</Menubar.Trigger> -->
			<Drawer.Title>Menu</Drawer.Title>
			<Drawer.Description>คุณสนใจไปที่ไหนดี?</Drawer.Description>
		</Drawer.Header>
		<Drawer.Footer>

            
            <Menubar.Root class="flex items-center justify-center">
                <Menubar.Menu>
                    <Menubar.Trigger>ชุมชน</Menubar.Trigger>
                    <Menubar.Content>
                        <a href="https://saas.in.th">
                            <Menubar.Item>
                                Test
                                <Menubar.Shortcut>⌘T</Menubar.Shortcut>
                            </Menubar.Item>
                        </a>
                    </Menubar.Content>
                </Menubar.Menu>

                <Menubar.Menu>
                    <Menubar.Trigger>Template</Menubar.Trigger>
                    <Menubar.Content>
                        <a href="https://saas.in.th">
                            <Menubar.Item>
                                Template ทำเว็บ SaaS
                                <Menubar.Shortcut>⌘T</Menubar.Shortcut>
                            </Menubar.Item>
                        </a>
                    </Menubar.Content>
                </Menubar.Menu>


                <Menubar.Menu>
                    <Menubar.Trigger>ข่าวสาร</Menubar.Trigger>
                </Menubar.Menu>
                <Menubar.Menu>
                    <Menubar.Trigger>บทความ</Menubar.Trigger>
                </Menubar.Menu>
                <Menubar.Menu>
                    <Menubar.Trigger>ส่ง SaaS ของคุณ</Menubar.Trigger>
                </Menubar.Menu>
            </Menubar.Root>
            
			
			<Drawer.Close class="mt-5"><Button>ปิดหน้าต่าง</Button></Drawer.Close>
		</Drawer.Footer>
	</Drawer.Content>
</Drawer.Root>

<nav class="flex hidden w-full items-center justify-center p-5 py-5 backdrop-blur sm:flex">
	<Menubar.Root>
		<Menubar.Menu>
			<Menubar.Trigger>การเปิดตัว</Menubar.Trigger>
			<!-- <Menubar.Content>
            <Menubar.Item>
              New Tab
              <Menubar.Shortcut>⌘T</Menubar.Shortcut>
            </Menubar.Item>
            <Menubar.Item>New Window</Menubar.Item>
            <Menubar.Separator />
            <Menubar.Item>Share</Menubar.Item>
            <Menubar.Separator />
            <Menubar.Item>Print</Menubar.Item>
          </Menubar.Content> -->
		</Menubar.Menu>
		<Menubar.Menu>
			<Menubar.Trigger>ชุมชน</Menubar.Trigger>
		</Menubar.Menu>
		<Menubar.Menu>
			<Menubar.Trigger>Template</Menubar.Trigger>
			<Menubar.Content>
				<a href="https://saas.in.th">
					<Menubar.Item>
						Template ทำเว็บ SaaS
						<Menubar.Shortcut>⌘T</Menubar.Shortcut>
					</Menubar.Item>
				</a>
			</Menubar.Content>
		</Menubar.Menu>
		<Menubar.Menu>
			<Menubar.Trigger>ข่าวสาร</Menubar.Trigger>
		</Menubar.Menu>
		<Menubar.Menu>
			<Menubar.Trigger>บทความ</Menubar.Trigger>
		</Menubar.Menu>
		<Menubar.Menu>
			<Menubar.Trigger>ส่ง SaaS ของคุณ</Menubar.Trigger>
		</Menubar.Menu>
	</Menubar.Root>
</nav>

<slot></slot>

<style></style>
