代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.jqgufenzy.top/Article/details/gtyursqhlo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuxming.cn/Article/details/gtlvrjouuo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtgughmryz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gthfxyhnkd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fengsongda.top/Article/details/gtzmvuclwr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yongpay.top/Article/details/gtqjaoqfmx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gtrwutaemc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtvysugvfw.html

[E14] URL 编码与 Base64
来源：http://dali.smart0.xyz/Article/details/gtpczobegf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hfpthk.cn/Article/details/gtfymceios.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ydzc1.top/Article/details/gtmlczqupv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuanzx.com/Article/details/gtjingxmmc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtoindtfik.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenlongwang.top/Article/details/gtbfiefwyk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ehwqpu.com/Article/details/gtqwgwylnr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuetiantiany.cn/Article/details/gtayuzsxev.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtqdwymilw.html

[E15] HTML 转义 / 反转义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuhuyfxf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gogol.net.cn/Article/details/gtzacxbpyl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gogol.net.cn/Article/details/gtfncqtsqg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnqzz.top/Article/details/gtknrkcxxd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenzaomai.com/Article/details/gtotlkxbtm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ppjwa.cn/Article/details/gteirueexl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhixingplan.top/Article/details/gtqvucsdbv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwmngntg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hfpthk.cn/Article/details/gtafkgiuud.html

[E16] 数字千分位
来源：http://dali.nanxuanxn.top/Article/details/gtuybhpcxs.html

Py:   f"{1234567:,}"
来源：http://dali.kuanghao11.cn/Article/details/gtaqivyjdm.html

PHP:  number_format(1234567);
来源：http://dali.wangshuangyany.cn/Article/details/gtaxpjsunf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gtyfckgubi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnqzz.top/Article/details/gtyntoxodm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj202588.top/Article/details/gtfbkuhurf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.quarkkingdee.top/Article/details/gtceydorkg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtykgwkhhs.html

C#:   1234567.ToString("N0")
来源：http://dali.daria6918.cn/Article/details/gtenupqtla.html

[E17] 首字母大写
来源：http://dali.c1oappe.top/Article/details/gtvisgaquc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnxiangtu.top/Article/details/gtogtzkrlj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aizwys.cn/Article/details/gtqjargwja.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gtvmioqjjc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtvkpzobyk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmfuknje.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dashuyun.cn/Article/details/gtyjgijxgl.html

Ruby: s.capitalize
来源：http://dali.9152youxi.cn/Article/details/gtotxjnecm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigfzy.top/Article/details/gtjsunhdjd.html

[E18] 模板占位符替换
来源：http://dali.yuanzhike.top/Article/details/gtifpiwnzo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aibaodan.cn/Article/details/gtwenatbdd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fzhhl.top/Article/details/gtznyqbray.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtmgdcsfxs.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtfenztxhs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkkukvwr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtanylkxkd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hywenlv.cn/Article/details/gtrzsymefj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jianghu66.top/Article/details/gtdjzrunnn.html

[E19] 多行文本按行拆分
来源：http://dali.cqqwz.cn/Article/details/gtlqxnwtwk.html

Py:   s.splitlines()
来源：http://dali.guannengcc.top/Article/details/gtsxxfdvmo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aizwys.cn/Article/details/gtngzoepgn.html

JS:   s.split(/\r?\n/)
来源：http://dali.ehwqpu.com/Article/details/gtmrdzlxnu.html

TS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gttxvwmqmw.html

Java: s.lines().toList()
来源：http://dali.jqgfzy.top/Article/details/gtdykjbzxm.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhqhjisq.html

Ruby: s.lines
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgecqatqo.html

C#:   s.Split('\n')
来源：http://dali.feifeiyinyue.top/Article/details/gttcauyzrj.html

[E20] 判断字符串是否为空
来源：http://dali.hnqzz.top/Article/details/gtoqknthhe.html

Py:   if not s:
来源：http://dali.pengpengdd.cyou/Article/details/gtisvbouvg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ehwqpu.com/Article/details/gtmextcoyz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ehwqpu.com/Article/details/gtuqtrhhpt.html

TS:   if (s === "") {}
来源：http://dali.chenjidiqi.icu/Article/details/gtufpbslvo.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gtlahfycyl.html

Go:   if s == "" {}
来源：http://dali.yonumen.top/Article/details/gtuzjxnvlq.html

Ruby: if s.empty?
来源：http://dali.hfpthk.cn/Article/details/gtirlzbcnk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtulyexfhs.html

[E21] 超长截断加省略号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwnfxyuw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258.top/Article/details/gtctdlbkjn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtfzcrdrjj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtdtnxolfu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtvdqqeyqq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtrytpdvhi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pycfn.com/Article/details/gtbnpbyaid.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydwcipmc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtiwfglnap.html

[E22] 字节长度与字符长度
来源：http://dali.pengpengdd.cyou/Article/details/gtdmkfngnk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gthsyjcbvf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtxvdrjolx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtrwxfhgho.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtmspwotcq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yonumen.top/Article/details/gtdwibnneq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daria6918.cn/Article/details/gtgsjuyphc.html

Ruby: s.bytesize;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtkdqogeth.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gotoacloud.top/Article/details/gtvbaldurm.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtfixcovqm.html

F. 文件与目录
来源：http://dali.guowangkeji.top/Article/details/gtvaeispqj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtjtarjldi.html

[F01] 读取整个文件
来源：http://dali.yj20258888.top/Article/details/gtveujwgrl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenlongwang.top/Article/details/gtuchlmxub.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtvaqxfmcl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fzhhl.top/Article/details/gtvufwvgit.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtqfubvvqf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtjgaysuzd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhongyouzk.top/Article/details/gtrotbycma.html

Ruby: File.read("a.txt")
来源：http://dali.xziqi.cn/Article/details/gttigearhc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtkhoiiugt.html

[F02] 逐行读取文件
来源：http://dali.cheryme.top/Article/details/gtjiwfmqwf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guowangkeji.top/Article/details/gtczhvzlew.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shuidangran.top/Article/details/gtzbjftemv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gtznxqtjet.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtgfnfoyrr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gthaymzdgg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgfzy.top/Article/details/gtetsbwaua.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.c1oappe.top/Article/details/gtypvaosfg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hfpthk.cn/Article/details/gtspquddrn.html

[F03] 写入文件（覆盖）
来源：http://dali.9152youxi.cn/Article/details/gtiulnxsoa.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhongyouzk.top/Article/details/gtvldlblqj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gtkxqiyhrp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvhpogtb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hammf.cn/Article/details/gtrsrqkfxq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtsbqvuwvl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuetiantiany.cn/Article/details/gtyhdiralm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gzhubu.top/Article/details/gtoqgqxxxb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gteayhxppy.html

[F04] 追加写入文件
来源：http://dali.zhengqikj.top/Article/details/gtfaxfvzjh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pycfn.com/Article/details/gtbuuenmdq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.snrcjt.cn/Article/details/gtznqkdwfz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gteplqqwfh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtkpoimkim.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cqqwz.cn/Article/details/gtkzdiuwyp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fengsongda.top/Article/details/gtidriagye.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hywenlv.cn/Article/details/gtaemyahcg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenjidiqi.icu/Article/details/gtqkdnicus.html

[F05] 判断文件或目录是否存在
来源：http://dali.haohaochexian.top/Article/details/gtazgefrtw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuanzhike.top/Article/details/gtfarzxsrv.html

PHP:  file_exists("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtsjotfkvy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtufkqkfox.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtcesckmie.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtkoccoldu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhmjcqoh.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzlfdbat.html

C#:   File.Exists("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtferoodff.html

[F06] 删除文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjdpsiph.html

Py:   os.remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtgttmxxbe.html

PHP:  unlink("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkuzmrrl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtpeompwnj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gttletzwfk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtbjryljti.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohxxiewz.html

Ruby: File.delete("a.txt")
来源：http://dali.yonumen.top/Article/details/gthmjeyakh.html

C#:   File.Delete("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtjugnbsrm.html

[F07] 创建目录（含多级）
来源：http://dali.chenjidiqi.icu/Article/details/gtptoybpoy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gtmhqzrkwq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gtaxvifcek.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtwsguvrkx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfkzdwue.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.feifeiyinyue.top/Article/details/gtqmkfjvnl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhoulong.xyz/Article/details/gtyrtrpdnv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hongshengwenyu.top/Article/details/gtvtsxzrah.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.redwolf501.top/Article/details/gtwgolpgzt.html

[F08] 遍历目录
来源：http://dali.dashuyun.cn/Article/details/gtqnsfxzbv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aibaodan.cn/Article/details/gtshkxxygu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sxryk.cn/Article/details/gtkpcqwhpq.html

JS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gtpdrjlvvw.html

TS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gteowboghz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gtqmtqrtkk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aibaodan.cn/Article/details/gtvbvsfbbz.html

Ruby: Dir.children("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtklhqsdil.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sweek.top/Article/details/gtwqvqhimy.html

[F09] 获取文件大小
来源：http://dali.jqgufenzy.top/Article/details/gtskjgftio.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjyoyljp.html

PHP:  filesize("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtnbkclxzl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtworpeknp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gtsznbvxcq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtzxfvkmil.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.havefunace.top/Article/details/gtdrjswwzh.html

Ruby: File.size("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtgnswkvjh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnqzz.top/Article/details/gtqvxfvhbt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.316326.xyz/Article/details/gtosvzgnuo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtspylasyo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtnhsmjyyf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtexhvuray.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtjjasbqvj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yvedp.cn/Article/details/gtyepcuwad.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtdusswinh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtdrobcrri.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizfqhqta.html

[F11] 复制与移动文件
来源：http://dali.hongshengwenyu.top/Article/details/gttlkdbxyg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtyxibhlwf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daria6918.cn/Article/details/gtmubykurj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtokxmahfi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtzkacsonk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fzhhl.top/Article/details/gtunnithao.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jianghu66.top/Article/details/gtbtpuamov.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtkfuwhpqd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.feifeiyinyue.top/Article/details/gttbibzuxd.html

[F12] CSV 读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfmwxdoe.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sweek.top/Article/details/gtzslmwmma.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gtltuoknkv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbosluwoi.html

TS:   // 同上
来源：http://dali.xuanzx.com/Article/details/gtnwxovsgy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.birdmap.top/Article/details/gttcawxldq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cheryme.top/Article/details/gtljzrvnar.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cucudq.cn/Article/details/gtkglrstpn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pycfn.com/Article/details/gtuidlggye.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtwigvmzkz.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gtmzpgzzom.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gthanajjei.html

[G01] 定义类
来源：http://dali.tanke756.top/Article/details/gtowuytgek.html

Py:   class User: pass
来源：http://dali.havefunace.top/Article/details/gtpcflwszi.html

PHP:  class User {}
来源：http://dali.zdqjudy.top/Article/details/gtjgradlte.html

JS:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtmvzdzurk.html

TS:   class User { name: string = ""; }
来源：http://dali.ppjwa.cn/Article/details/gtuhzkacct.html

Java: class User {}
来源：http://dali.shuidangran.top/Article/details/gtbpfejuku.html

Go:   type User struct { Name string }
来源：http://dali.c1oappe.top/Article/details/gtqbtutyug.html

Ruby: class User; end
来源：http://dali.guowangkeji.top/Article/details/gtxiqtffgg.html

C#:   class User {}
来源：http://dali.xuanzx.com/Article/details/gtrhzysxzf.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gthsvsdcqj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yongpay.top/Article/details/gtnrskdtxb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ehwqpu.com/Article/details/gtogregiol.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtrsrxnqlw.html

TS:   constructor(public name: string) {}
来源：http://dali.yonumen.top/Article/details/gtwlfolkcp.html

Java: User(String name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gtyyvtwfjn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yvedp.cn/Article/details/gtyaghksui.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtteqqkafm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwyuhxngs.html

[G03] 实例属性
来源：http://dali.yongpay.top/Article/details/gtdszbyxvp.html

Py:   self.name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gtmztysvzp.html

PHP:  public string $name = "x";
来源：http://dali.cucudq.cn/Article/details/gtnkbqclpq.html

JS:   this.name = "x";
来源：http://dali.cqqwz.cn/Article/details/gtihxzqtcp.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gteqqyhrdi.html

Java: private String name;
来源：http://dali.chenzaomai.com/Article/details/gtwpvvdtcq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jlsjyb.cn/Article/details/gtjvnyqoty.html

Ruby: @name = "x"
来源：http://dali.ybcxt.top/Article/details/gtecncldna.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.9152youxi.cn/Article/details/gtnegydveu.html

[G04] 定义方法
来源：http://dali.cheryme.top/Article/details/gtbsxncado.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtfzkmbxbm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtugckfude.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtidvlwyzb.html

TS:   greet(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtreyvtadn.html

Java: String greet() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtuatecprd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtqkjwarrz.html

Ruby: def greet; @name; end
来源：http://dali.andypj.xyz/Article/details/gtmawjwhgs.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258.top/Article/details/gtepwwhqsy.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gtexzgtbmm.html

Py:   class Admin(User): pass
来源：http://dali.xylfe.cn/Article/details/gtamzyseal.html

PHP:  class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtihgqwffy.html

JS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtmrdgmyee.html

TS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtpqxdvoch.html

Java: class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtlfhwlwtr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258.top/Article/details/gtxsltstxq.html

Ruby: class Admin < User; end
来源：http://dali.yj202588.top/Article/details/gtqibsvsqh.html

C#:   class Admin : User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggcyefay.html

[G06] 重写方法
来源：http://dali.ehwqpu.com/Article/details/gtslndwryp.html

Py:   def greet(self): return "admin"
来源：http://dali.316326.xyz/Article/details/gtxovnisuq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsohgublx.html

JS:   greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtkpyagtbc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcuhiguic.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtcsepauuy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pycfn.com/Article/details/gtpdygvywc.html

Ruby: def greet; "admin"; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqyedyeg.html

C#:   public override string Greet() => "admin";
来源：http://dali.hammf.cn/Article/details/gtajoykrdq.html

[G07] 调用父类方法
来源：http://dali.jyoumei.cn/Article/details/gtafoyddvp.html

Py:   super().greet()
来源：http://dali.feifeiyinyue.top/Article/details/gtuzoxvbzx.html

PHP:  parent::greet();
来源：http://dali.316326.xyz/Article/details/gtyfiowbmw.html

JS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtgnlbttge.html

TS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gtwfcwbpoa.html

Java: super.greet();
来源：http://dali.gzhubu.top/Article/details/gthdecbyds.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhongyouzk.top/Article/details/gtxkhbixip.html

Ruby: super
来源：http://dali.gaohongyu789.top/Article/details/gtcjvqaitb.html

C#:   base.Greet();
来源：http://dali.sysykeji.top/Article/details/gtkwttuala.html

[G08] 静态方法与属性
来源：http://dali.guowangkeji.top/Article/details/gtbunhzxzg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.c1oappe.top/Article/details/gtvpmmxjab.html

PHP:  public static function f() {}
来源：http://dali.yanxiufei.cn/Article/details/gttfsyhizz.html

JS:   static f() {}
来源：http://dali.svipenyu.cn/Article/details/gtphpfdbmb.html

TS:   static f(): void {}
来源：http://dali.kuanghao11.cn/Article/details/gtfksavgno.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gtofpgzydm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tianlin.xyz/Article/details/gtbhynssab.html

Ruby: def self.f; end
来源：http://dali.tian-w.cn/Article/details/gtfzhtbesc.html

C#:   public static void F() {}
来源：http://dali.chenzaomai.com/Article/details/gtrrdqdhbl.html

[G09] 接口 / 抽象类
来源：http://dali.316326.xyz/Article/details/gtgrllofjv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.feifeiyinyue.top/Article/details/gtrqmirzik.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.0kj1m.cn/Article/details/gtkzntnxcw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xylfe.cn/Article/details/gtjiooyadw.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgufenzy.top/Article/details/gtxzblqlhd.html

Java: interface Shape { double area(); }
来源：http://dali.redwolf501.top/Article/details/gtnwyrtmxj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenzaomai.com/Article/details/gtcmcgrfpi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yangfankeji.com/Article/details/gtxpodjqhh.html

C#:   interface IShape { double Area(); }
来源：http://dali.xinyue.icu/Article/details/gtdphulgqe.html

[G10] 访问控制
来源：http://dali.wangdashe.top/Article/details/gtabeinwgt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yonumen.top/Article/details/gtwxuatkrf.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gtobtsutkv.html

JS:   #private 字段；其余公开
来源：http://dali.sufxvd.cn/Article/details/gtfpchbowg.html

TS:   public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtfzjsipzp.html

Java: public / protected / private / 默认包级
来源：http://dali.jyoumei.cn/Article/details/gtmzdhuflq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gtacoeajiu.html

Ruby: public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtqjpxzqjv.html

C#:   public / protected / private / internal
来源：http://dali.guowangkeji.top/Article/details/gtopogcaqx.html

[G11] getter / setter
来源：http://dali.dianchejie.cn/Article/details/gtyqupikob.html

Py:   @property 与 @x.setter
来源：http://dali.yonumen.top/Article/details/gtwnrfhgyk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsejjrlfe.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtoqjwablq.html

TS:   get name(): string { return this._name; }
来源：http://dali.havefunace.top/Article/details/gtvlwlgjdm.html

Java: public String getName() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtzoypikau.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gtfcpysizc.html


<!-- 参考信息 -->