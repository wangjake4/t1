代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.yueranfly.top/Article/details/gtkscdxqqm.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtbwrbiucu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.quarkkingdee.top/Article/details/gtikdftcie.html

[E13] 逐字符遍历
来源：http://dali.tianlin.xyz/Article/details/gtuehrseqx.html

Py:   for ch in s: print(ch)
来源：http://dali.mhx1999.top/Article/details/gtpeqqlshj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hongshengwenyu.top/Article/details/gtlhhtbugs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtnmnqldhh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtskywxkgm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ydzc1.top/Article/details/gttxppsivf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuanzhike.top/Article/details/gtqesjjznl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gotoacloud.top/Article/details/gtflwglcyf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsmvkhgq.html

[E14] URL 编码与 Base64
来源：http://dali.jlsjyb.cn/Article/details/gtgvouupbq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sxryk.cn/Article/details/gtgxkiuick.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtahjjvqpf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.vqdsnc.cn/Article/details/gtltxlzbqc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tanke756.top/Article/details/gtjtgrfflr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pycfn.com/Article/details/gtdtpzwzrh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zdqjudy.top/Article/details/gtxevzkisw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258888.top/Article/details/gtxelkdpwz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gtglemhimv.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgufenzy.top/Article/details/gtgrgewjqi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jianghu66.top/Article/details/gtharcbhqq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dashuyun.cn/Article/details/gtgpegaihl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.meibo888.top/Article/details/gtjrpbdmhh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtibzfdlby.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.havefunace.top/Article/details/gtgclhlinr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gtgvawtard.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.mhx1999.top/Article/details/gtgeldczys.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhengqikj.top/Article/details/gtmxurywls.html

[E16] 数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gtolyxvbza.html

Py:   f"{1234567:,}"
来源：http://dali.xylfe.cn/Article/details/gtkvnzntoy.html

PHP:  number_format(1234567);
来源：http://dali.jinqigufen.top/Article/details/gtoaiotoet.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfbbuzap.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gtagdsjoad.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yueranfly.top/Article/details/gtykwpmnui.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sysykeji.top/Article/details/gtpozowdcf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gzhubu.top/Article/details/gtupmyioim.html

C#:   1234567.ToString("N0")
来源：http://dali.zhengqikj.top/Article/details/gtguigqltp.html

[E17] 首字母大写
来源：http://dali.nwbrower.top/Article/details/gtqqjsxbln.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ydzc1.top/Article/details/gtwqfhufwu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmoczemq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gtxjaydjjc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtfbrehcip.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daxiang520.top/Article/details/gtphrzroyv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fengsongda.top/Article/details/gttizkbziy.html

Ruby: s.capitalize
来源：http://dali.xylfe.cn/Article/details/gtbwmoxzjw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hfpthk.cn/Article/details/gtgdckzwiy.html

[E18] 模板占位符替换
来源：http://dali.yj20258888.top/Article/details/gthzkwgnea.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xylfe.cn/Article/details/gtbolgoiqh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.316326.xyz/Article/details/gtirdwkvkg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtqyfmoojn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtafuzgoop.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtztewzjmy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtzenfvynn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jianghu66.top/Article/details/gtvooedftd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jiagoushi.top/Article/details/gtsnreejlc.html

[E19] 多行文本按行拆分
来源：http://dali.ppjwa.cn/Article/details/gtazmoqbbt.html

Py:   s.splitlines()
来源：http://dali.gaohongyu789.top/Article/details/gtjawuvbzz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.redwolf501.top/Article/details/gtnoxwrjhy.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgufenzy.top/Article/details/gtadgcqlwu.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtnjhplgfu.html

Java: s.lines().toList()
来源：http://dali.guannengcc.top/Article/details/gthprueokr.html

Go:   strings.Split(s, "\n")
来源：http://dali.tanke756.top/Article/details/gtloslvacd.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gtphbzboxq.html

C#:   s.Split('\n')
来源：http://dali.jinghuilouyu.cn/Article/details/gtmipmndyd.html

[E20] 判断字符串是否为空
来源：http://dali.wangshuangyany.cn/Article/details/gthxjbhivh.html

Py:   if not s:
来源：http://dali.iojbl.cn/Article/details/gtkablqwbe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gaohongyu789.top/Article/details/gtouvisshq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jiagoushi.top/Article/details/gtdblqsgas.html

TS:   if (s === "") {}
来源：http://dali.hysaishi.cn/Article/details/gtrotfkncb.html

Java: if (s.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gthuvcjmjt.html

Go:   if s == "" {}
来源：http://dali.wangdashe.top/Article/details/gthmewqrhy.html

Ruby: if s.empty?
来源：http://dali.sysykeji.top/Article/details/gtiqaxkplu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cucudq.cn/Article/details/gthagizevb.html

[E21] 超长截断加省略号
来源：http://dali.sweek.top/Article/details/gtmhuqylep.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hywenlv.cn/Article/details/gtkbwrnlfg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtemjvydia.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtxrdwdcuz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtibzhmphw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtenewknam.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuxming.cn/Article/details/gtbdaksxcf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtrepuvkuq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtedldcnqg.html

[E22] 字节长度与字符长度
来源：http://dali.ivvv.top/Article/details/gtttmxmyfc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sweek.top/Article/details/gtbnsitnpt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtyrkqayid.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtkqsuwtek.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gtepmpwxhr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jiagoushi.top/Article/details/gtmsmagqkr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hongshengwenyu.top/Article/details/gtegtgilyv.html

Ruby: s.bytesize;  s.length
来源：http://dali.tian-w.cn/Article/details/gtgsbbdzdo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.havefunace.top/Article/details/gthhwfxpok.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gttfohvllq.html

F. 文件与目录
来源：http://dali.ppjwa.cn/Article/details/gtarrshuxo.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtsdiuxaes.html

[F01] 读取整个文件
来源：http://dali.cucudq.cn/Article/details/gtcsnpthvq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jlsjyb.cn/Article/details/gtappyjxmp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtwfenxwso.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkhspigf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtuscdwtly.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gticloonod.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ydzc1.top/Article/details/gtlvhhggdr.html

Ruby: File.read("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gttmnnjfjj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtpetmqxzy.html

[F02] 逐行读取文件
来源：http://dali.kuanghao11.cn/Article/details/gtwlyldadv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zdqjudy.top/Article/details/gtctxvjiqd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ivvv.top/Article/details/gtdkdnolsx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gtrpxpplqv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gtmacfwzmz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gtrqyepfnb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xuetiantiany.cn/Article/details/gtgwkxplnh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258.top/Article/details/gtsrcqhwym.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daria6918.cn/Article/details/gtgotidnsx.html

[F03] 写入文件（覆盖）
来源：http://dali.shangyingyoupin.top/Article/details/gtweoptqcz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ybcxt.top/Article/details/gttvhvlunv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gtwbaayirj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtpgljqhpy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtccmeerad.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cucudq.cn/Article/details/gttnpnruci.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxuanxn.top/Article/details/gtbtpzttvb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuanzhike.top/Article/details/gtgjrmkqgf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gtpiraegnq.html

[F04] 追加写入文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkhrpjjc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cucudq.cn/Article/details/gtatmgqfnc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.snrcjt.cn/Article/details/gtukihrjnz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtnxzfkdhd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtpnhpvrlp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigufen.top/Article/details/gtgsuozxlu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jianghu66.top/Article/details/gtpnbyvlms.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.316326.xyz/Article/details/gtmdxkycdy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ivvv.top/Article/details/gtbdnxaqls.html

[F05] 判断文件或目录是否存在
来源：http://dali.sysykeji.top/Article/details/gtbgkisnwz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.andypj.xyz/Article/details/gtfpabeyco.html

PHP:  file_exists("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtpfdmjaci.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtobmvurub.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtzpxjlvbb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtrzpjbspx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fengsongda.top/Article/details/gtpsdhgudv.html

Ruby: File.exist?("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtqljwofff.html

C#:   File.Exists("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtiyptqald.html

[F06] 删除文件
来源：http://dali.sysykeji.top/Article/details/gtshxawlhn.html

Py:   os.remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrtopepb.html

PHP:  unlink("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtovhratcx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtnmzjkqvj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtjvolfmxv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtiuytqkki.html

Go:   os.Remove("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtsxlraote.html

Ruby: File.delete("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtwezsmhak.html

C#:   File.Delete("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtlzwattgq.html

[F07] 创建目录（含多级）
来源：http://dali.zycfv.cn/Article/details/gtjpbnmpvw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtqqkcxwjz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.c1oappe.top/Article/details/gtyzydehln.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gtboziqbmm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtwehwfrlf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.feifeiyinyue.top/Article/details/gtuwbjpcgt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daria6918.cn/Article/details/gtwhmuuhnc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgufenzy.top/Article/details/gtmzshakah.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.vqdsnc.cn/Article/details/gtgsgvejyf.html

[F08] 遍历目录
来源：http://dali.zdqjudy.top/Article/details/gtscikhudz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tianlin.xyz/Article/details/gtopdjuxfi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xylfe.cn/Article/details/gtzbadelcl.html

JS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gthcjzvwsd.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gtxvtlnypt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gtmmhtguma.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tanke756.top/Article/details/gtsgtdtwau.html

Ruby: Dir.children("dir")
来源：http://dali.ivvv.top/Article/details/gtphsrscqr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sufxvd.cn/Article/details/gtgnjdfrwb.html

[F09] 获取文件大小
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdgoahxk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gthechyxtv.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtrnwzcadv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gtehcmmvjd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gtwdedjolk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtezkxmgub.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gtgmoaecmy.html

Ruby: File.size("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtkstunnlz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zdqjudy.top/Article/details/gtxatdyauy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbmestse.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtitgfenwk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtjszwiujx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtwqtndner.html

TS:   path.extname("a.txt")
来源：http://dali.yj202588.top/Article/details/gterpfabzr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gtcwwifggl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtdhqvdxgd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtkttkphrn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtzxddwsbg.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gtvcavjblt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtuisrmubk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guannengcc.top/Article/details/gtfyyucbim.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtgrpbwdoy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtnpsxghty.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtzxxoogwn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cdnleiting.top/Article/details/gtfywlnjme.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtgbguiblj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sweek.top/Article/details/gtnfqbyfjx.html

[F12] CSV 读写
来源：http://dali.yangfankeji.com/Article/details/gtjeroicjs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgufenzy.top/Article/details/gtbqlqcvsv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangdashe.top/Article/details/gttxswoopo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xylfe.cn/Article/details/gtzepbujze.html

TS:   // 同上
来源：http://dali.cdnleiting.top/Article/details/gtlxgspydt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sxryk.cn/Article/details/gtkzcgcuaj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnxiangtu.top/Article/details/gthlhkxvnv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ybcxt.top/Article/details/gtpbtczqym.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.mhx1999.top/Article/details/gtzppzdyrj.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtesxrablc.html

G. 面向对象
来源：http://dali.tanke756.top/Article/details/gtrahfnyqi.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtqaifipkn.html

[G01] 定义类
来源：http://dali.hfpthk.cn/Article/details/gtpcatyljs.html

Py:   class User: pass
来源：http://dali.sufxvd.cn/Article/details/gtdktnrqex.html

PHP:  class User {}
来源：http://dali.daxiang520.top/Article/details/gteszsdpvr.html

JS:   class User {}
来源：http://dali.sweek.top/Article/details/gtrveliyvu.html

TS:   class User { name: string = ""; }
来源：http://dali.hnxiangtu.top/Article/details/gtmbvhfgoi.html

Java: class User {}
来源：http://dali.mhx1999.top/Article/details/gtkxpesemu.html

Go:   type User struct { Name string }
来源：http://dali.zhengqikj.top/Article/details/gtvqwqjnpy.html

Ruby: class User; end
来源：http://dali.andypj.xyz/Article/details/gtbbgwjzhp.html

C#:   class User {}
来源：http://dali.jianghu66.top/Article/details/gtrlkhjebh.html

[G02] 构造函数
来源：http://dali.ivvv.top/Article/details/gtsxngoakj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqedhmkda.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.birdmap.top/Article/details/gtsgjujxul.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtkodators.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gtppnncbce.html

Java: User(String name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gtzbrbwfkb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xylfe.cn/Article/details/gtexqjgxmx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fengsongda.top/Article/details/gtezguipih.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guannengcc.top/Article/details/gtihtkywkm.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gthciqykrq.html

Py:   self.name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gtfuhvgskq.html

PHP:  public string $name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtqbogfbet.html

JS:   this.name = "x";
来源：http://dali.yj20258.top/Article/details/gtbthkmzmk.html

TS:   name: string = "x";
来源：http://dali.snrcjt.cn/Article/details/gtbhojwkby.html

Java: private String name;
来源：http://dali.yangfankeji.com/Article/details/gtrallxtfs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigufen.top/Article/details/gtofqkaysj.html

Ruby: @name = "x"
来源：http://dali.xziqi.cn/Article/details/gtssteywhq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zycfv.cn/Article/details/gtnxuvbeox.html

[G04] 定义方法
来源：http://dali.cheryme.top/Article/details/gtgnhrdlan.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtxpqrylzw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtugtvhxid.html

JS:   greet() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtlewrbizi.html

TS:   greet(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtyejwdlnc.html

Java: String greet() { return name; }
来源：http://dali.yj20258888.top/Article/details/gthooirjuy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gtgrzhqdvj.html

Ruby: def greet; @name; end
来源：http://dali.0kj1m.cn/Article/details/gtsnyauxev.html

C#:   public string Greet() => Name;
来源：http://dali.havefunace.top/Article/details/gtdhypjrcv.html

[G05] 继承
来源：http://dali.cucudq.cn/Article/details/gtlskmyswb.html

Py:   class Admin(User): pass
来源：http://dali.tanke756.top/Article/details/gtodkgprtj.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtevadcneo.html

JS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtskemqetu.html

TS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gthvdstrtp.html

Java: class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtmfbpdkmr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.316326.xyz/Article/details/gthdhhrrvy.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gteuzvohjx.html

C#:   class Admin : User {}
来源：http://dali.jyoumei.cn/Article/details/gtyjvolmhb.html

[G06] 重写方法
来源：http://dali.316326.xyz/Article/details/gtzmemjvgf.html

Py:   def greet(self): return "admin"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpomnkgmk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtbwlifpwt.html

JS:   greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtstptzcrr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcghyzuef.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtkjoqgwfe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cqqwz.cn/Article/details/gtozaotxso.html

Ruby: def greet; "admin"; end
来源：http://dali.gogol.net.cn/Article/details/gttgyolbcu.html

C#:   public override string Greet() => "admin";
来源：http://dali.yongpay.top/Article/details/gtbmyecabm.html

[G07] 调用父类方法
来源：http://dali.pengpengdd.cyou/Article/details/gtccicddty.html

Py:   super().greet()
来源：http://dali.jqgufenzy.top/Article/details/gtegqbhaqk.html

PHP:  parent::greet();
来源：http://dali.yj20258888.top/Article/details/gtakxkqitn.html

JS:   super.greet();
来源：http://dali.hnqzz.top/Article/details/gtsqumuzfr.html

TS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gturnseocw.html

Java: super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gthokkoprj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nwbrower.top/Article/details/gtthshphoz.html

Ruby: super
来源：http://dali.zhoulong.xyz/Article/details/gtpuayjwqy.html

C#:   base.Greet();
来源：http://dali.dashuyun.cn/Article/details/gtulltnhup.html

[G08] 静态方法与属性
来源：http://dali.mhx1999.top/Article/details/gtkibwslqa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhaomingkeji.xyz/Article/details/gtweizrvjb.html

PHP:  public static function f() {}
来源：http://dali.fengsongda.top/Article/details/gtjmahnlyp.html

JS:   static f() {}
来源：http://dali.nanxuanxn.top/Article/details/gttbhfzfqx.html

TS:   static f(): void {}
来源：http://dali.nwbrower.top/Article/details/gtgeywgbpi.html

Java: static void f() {}
来源：http://dali.jianghu66.top/Article/details/gtwpjmyydm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhiwuduotai.top/Article/details/gtkycdsudz.html

Ruby: def self.f; end
来源：http://dali.birdmap.top/Article/details/gtuhfmavvs.html

C#:   public static void F() {}
来源：http://dali.jyoumei.cn/Article/details/gtxmtlofkv.html

[G09] 接口 / 抽象类
来源：http://dali.sysykeji.top/Article/details/gtuppnjywc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteifilwkc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.kuanghao11.cn/Article/details/gtztallvle.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangshuangyany.cn/Article/details/gtdjispssd.html

TS:   interface Shape { area(): number; }
来源：http://dali.daxiang520.top/Article/details/gtppvszvtn.html

Java: interface Shape { double area(); }
来源：http://dali.zdqjudy.top/Article/details/gtdxunaxhh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangtech.top/Article/details/gthvchyile.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxuanxn.top/Article/details/gtezmvsnnd.html

C#:   interface IShape { double Area(); }
来源：http://dali.ehwqpu.com/Article/details/gtqyhjbyic.html

[G10] 访问控制
来源：http://dali.svipenyu.cn/Article/details/gttducqlry.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuxming.cn/Article/details/gtidotdrrj.html

PHP:  public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtyviehjwq.html

JS:   #private 字段；其余公开
来源：http://dali.xinyue.icu/Article/details/gtltwgbadn.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gthkfmosed.html

Java: public / protected / private / 默认包级
来源：http://dali.shuidangran.top/Article/details/gtqzffgttk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangtech.top/Article/details/gtbcerlcrh.html

Ruby: public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtuabzujik.html

C#:   public / protected / private / internal
来源：http://dali.jqgfzy.top/Article/details/gtdsitommd.html

[G11] getter / setter
来源：http://dali.316326.xyz/Article/details/gtccbheaxu.html

Py:   @property 与 @x.setter
来源：http://dali.snrcjt.cn/Article/details/gtjqxdexox.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtdtmkkplr.html


<!-- 参考信息 -->