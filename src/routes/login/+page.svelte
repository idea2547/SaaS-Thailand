<script lang="ts">
    import { Button } from "$lib/components/ui/button/index.js";
    import * as Card from "$lib/components/ui/card/index.js";
    import { Input } from "$lib/components/ui/input/index.js";
    import { Label } from "$lib/components/ui/label/index.js";
  </script>
  


  <div class="flex flex-col items-center justify-center py-5 sm:p-10 md:p-20 lg:p-32 w-full">
    <Card.Root class="w-full max-w-sm">
        <Card.Header>
          <Card.Title class="text-2xl">เข้าสู่ระบบ</Card.Title>
          <Card.Description>ใส่อีเมล</Card.Description>
        </Card.Header>
        <Card.Content class="grid gap-4">
          <div class="grid gap-2">
            <Label for="email">อีเมล</Label>
            <Input id="email" type="email" placeholder="m@example.com" required />
          </div>
          <div class="grid gap-2">
            <Label for="password">รหัสผ่าน</Label>
            <Input id="password" type="password" required />
          </div>
        </Card.Content>
        <Card.Footer>
          <Button class="w-full">เข้าสู่ระบบ</Button>
        </Card.Footer>
      </Card.Root>
      

  </div>
  