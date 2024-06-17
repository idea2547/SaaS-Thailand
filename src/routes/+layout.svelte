<script lang="ts">
    import * as Menubar from "$lib/components/ui/menubar";
    import "../app.css";
  </script>
   

<div class="py-5 flex w-full items-center justify-center">
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
            <Menubar.Trigger>Template</Menubar.Trigger>
            <Menubar.Content>               
                <a href="https://saas.in.th">
                    <Menubar.Item>
                        Template ทำเว็บ SaaS
                        <Menubar.Shortcut>⌘T</Menubar.Shortcut>
                      </Menubar.Item>
                
                </a>              
              <!-- <Menubar.Item>New Window</Menubar.Item>
              <Menubar.Separator />
              <Menubar.Item>Share</Menubar.Item>
              <Menubar.Separator />
              <Menubar.Item>Print</Menubar.Item> -->
            </Menubar.Content>
          </Menubar.Menu>
          <Menubar.Menu>
            <Menubar.Trigger>ข่าวสาร</Menubar.Trigger>
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
      </Menubar.Root>
    


</div>
  


<slot></slot><style></style>