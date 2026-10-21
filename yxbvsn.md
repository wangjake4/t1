代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthaheljxl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenlongwang.top/Article/details/gtivqustgo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtlauyovsk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gtufywmtza.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtzlvixeam.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxinkj.top/Article/details/gtncpxhcpi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gtnqxthsgc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtnekoyjhe.html

[E14] URL 编码与 Base64
来源：http://dali.sysykeji.top/Article/details/gtzmpcpxdn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sysykeji.top/Article/details/gtwjqalbga.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.havefunace.top/Article/details/gtfpxcaais.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.316326.xyz/Article/details/gtfibpdcdc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gogol.net.cn/Article/details/gtxkkqtsjh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtqpxcfznx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.svipenyu.cn/Article/details/gtazbunvio.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aizwys.cn/Article/details/gtjmmnnpbv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtguxrvntp.html

[E15] HTML 转义 / 反转义
来源：http://dali.cqqwz.cn/Article/details/gtitptnuls.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tanke756.top/Article/details/gtlyijfquq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sweek.top/Article/details/gtuvsgizil.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yangfankeji.com/Article/details/gtwxmokxez.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aibaodan.cn/Article/details/gtrrxwwqdg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.mhx1999.top/Article/details/gtwlwznbcq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgthzpzuv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hfpthk.cn/Article/details/gtoecxalsn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gogol.net.cn/Article/details/gtwcabkxhd.html

[E16] 数字千分位
来源：http://dali.xuanzx.com/Article/details/gtnlpldqon.html

Py:   f"{1234567:,}"
来源：http://dali.tianlin.xyz/Article/details/gtvesevkat.html

PHP:  number_format(1234567);
来源：http://dali.zhengqikj.top/Article/details/gtupozvdsc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gtgsjbvfcq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gtmyquqpdu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gttxzfjuzb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.mhx1999.top/Article/details/gtyjtevszw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.meibo888.top/Article/details/gtjcxcltyu.html

C#:   1234567.ToString("N0")
来源：http://dali.hammf.cn/Article/details/gtlbqgkdpz.html

[E17] 首字母大写
来源：http://dali.daria6918.cn/Article/details/gtfascshkk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuanzx.com/Article/details/gtyzfajfwt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fengsongda.top/Article/details/gtqhurihxd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gtyqokynxu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxzkuxwe.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhongyouzk.top/Article/details/gtqludveas.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhoulong.xyz/Article/details/gthihqkzrf.html

Ruby: s.capitalize
来源：http://dali.wangdashe.top/Article/details/gtkoniggyp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhengqikj.top/Article/details/gtkgtvmoyf.html

[E18] 模板占位符替换
来源：http://dali.jlsjyb.cn/Article/details/gtatfiuhcp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tian-w.cn/Article/details/gtukiivtce.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbceuagit.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtrmuxecul.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtqsqjxhcq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtggzamvkz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtisenvmwu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yueranfly.top/Article/details/gtctpxxilh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhongyouzk.top/Article/details/gtjlcnbvll.html

[E19] 多行文本按行拆分
来源：http://dali.meibo888.top/Article/details/gtotqbkzka.html

Py:   s.splitlines()
来源：http://dali.zhixingplan.top/Article/details/gtpjllnbtt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtjkkmwnne.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gtisocubot.html

TS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gtxmeycsko.html

Java: s.lines().toList()
来源：http://dali.haohaochexian.top/Article/details/gtltkowjbz.html

Go:   strings.Split(s, "\n")
来源：http://dali.dashuyun.cn/Article/details/gtxwtspkcc.html

Ruby: s.lines
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwcqrvga.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gtqdylhcma.html

[E20] 判断字符串是否为空
来源：http://dali.yuanzhike.top/Article/details/gttajlgzqk.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gtktsyvocn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgufenzy.top/Article/details/gtpdlbhcps.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenzaomai.com/Article/details/gtpusjdmmo.html

TS:   if (s === "") {}
来源：http://dali.iojbl.cn/Article/details/gtlyqwgabb.html

Java: if (s.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gtoloawyvy.html

Go:   if s == "" {}
来源：http://dali.ydzc1.top/Article/details/gtiuyjkgve.html

Ruby: if s.empty?
来源：http://dali.yanxiufei.cn/Article/details/gtmnlwmncb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtmwiwqokq.html

[E21] 超长截断加省略号
来源：http://dali.zhengqikj.top/Article/details/gtjuuxvatw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cheryme.top/Article/details/gtvpiefmuc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gthnktbflo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtjdlqgrgw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtnswboksu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtyupgtxxm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gtopfhupko.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gtmkvuhpcr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtuqktxyoy.html

[E22] 字节长度与字符长度
来源：http://dali.yuxming.cn/Article/details/gtipafnboi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.havefunace.top/Article/details/gtcptzeloo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtccazjhet.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gtbxhatxbj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtqcidbbto.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.andypj.xyz/Article/details/gtryxlhmde.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.316326.xyz/Article/details/gtxdcosyop.html

Ruby: s.bytesize;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtcmjzjqvt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aibaodan.cn/Article/details/gtpnhffcop.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtzyadmhve.html

F. 文件与目录
来源：http://dali.jianghu66.top/Article/details/gtgnebvwry.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtndgbodig.html

[F01] 读取整个文件
来源：http://dali.ehwqpu.com/Article/details/gtpkeyryhs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.svipenyu.cn/Article/details/gtcxxfomzh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtngfnumxf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.svipenyu.cn/Article/details/gtwrzvhogu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fengsongda.top/Article/details/gthiltwjla.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtrbbdwquq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxyjtmkf.html

Ruby: File.read("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtogfgpkkf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.316326.xyz/Article/details/gtiydvqpbe.html

[F02] 逐行读取文件
来源：http://dali.svipenyu.cn/Article/details/gtznckjsbi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cqqwz.cn/Article/details/gtfzokfyrs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zdqjudy.top/Article/details/gtqblfghqp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gtkobloulq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gtyylkzgak.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gtanjonlwf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnqzz.top/Article/details/gtuzxfggfs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnftjzxc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tianlin.xyz/Article/details/gtwikvtvfo.html

[F03] 写入文件（覆盖）
来源：http://dali.ppjwa.cn/Article/details/gtbtezpegi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gzhubu.top/Article/details/gtxcsvtxve.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gtoqgetmdp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gtexudxsao.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijujmcoj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aizwys.cn/Article/details/gtbpbakrpv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.iojbl.cn/Article/details/gttnosxppi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszmdhugm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtefmzcysc.html

[F04] 追加写入文件
来源：http://dali.jinqigfzy.top/Article/details/gtufiajihq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtnqkdzizv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj202588.top/Article/details/gtubqlvmqy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtvznnqirb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtqozyycrq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jianghu66.top/Article/details/gtimzskfph.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gzhubu.top/Article/details/gttddztpbt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ppjwa.cn/Article/details/gtarowsnih.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sxryk.cn/Article/details/gtidhgpupc.html

[F05] 判断文件或目录是否存在
来源：http://dali.cashguo.top/Article/details/gtryhapdys.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hongshengwenyu.top/Article/details/gtyztzuvcc.html

PHP:  file_exists("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtcyxwupda.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtrewntdfk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtyxuwkhbg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtidwklfdq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinghuilouyu.cn/Article/details/gtojabdhlc.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtghrenclx.html

C#:   File.Exists("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtzffryqyc.html

[F06] 删除文件
来源：http://dali.chenzaomai.com/Article/details/gtjvosnjvt.html

Py:   os.remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtlidbfrmd.html

PHP:  unlink("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtsgrgqfqr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtturnxdvy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtytqkkhxe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gttroqsuxo.html

Go:   os.Remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtuolkwwkj.html

Ruby: File.delete("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtrchtxilt.html

C#:   File.Delete("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtrrbxehhz.html

[F07] 创建目录（含多级）
来源：http://dali.vqdsnc.cn/Article/details/gtvmcqfvxh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gtwpplkdrm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklprokwr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gtgueeazyn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtxoehrrcz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigufen.top/Article/details/gtbbiolvxx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenjidiqi.icu/Article/details/gtifpwxhms.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.9152youxi.cn/Article/details/gtkxiyacus.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.316326.xyz/Article/details/gtvgcpxbrr.html

[F08] 遍历目录
来源：http://dali.yuanzhike.top/Article/details/gtjyrhybvj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yangfankeji.com/Article/details/gtrtlzyzqy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.c1oappe.top/Article/details/gtcdxlione.html

JS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtzoskevnr.html

TS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtdghjiwpg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gtxmfdpsff.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.snrcjt.cn/Article/details/gtkuvzwgku.html

Ruby: Dir.children("dir")
来源：http://dali.yvedp.cn/Article/details/gtlpvefity.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhixingplan.top/Article/details/gtsmtpwler.html

[F09] 获取文件大小
来源：http://dali.yanxiufei.cn/Article/details/gtigeyiqze.html

Py:   os.path.getsize("a.txt")
来源：http://dali.birdmap.top/Article/details/gtlsxsgwwl.html

PHP:  filesize("a.txt");
来源：http://dali.birdmap.top/Article/details/gtvszdobfu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gtsbwiuiap.html

TS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gtejtmhxdj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtqycojynl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.316326.xyz/Article/details/gtvqnlwmyu.html

Ruby: File.size("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtzypqrqtd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnxiangtu.top/Article/details/gtmkucbohx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shzxlz.cn/Article/details/gtalvshcye.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtrvkuwidn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.c1oappe.top/Article/details/gtwffdfbzs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtlgdgotlg.html

TS:   path.extname("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gthpgdqgec.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gzhubu.top/Article/details/gtnaamhbji.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gteavsdgwi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtbzatxjnm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtnkquzkzx.html

[F11] 复制与移动文件
来源：http://dali.zycfv.cn/Article/details/gtvgvngmgs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtzpwrnlux.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gtwrosseaq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtrjayxosz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtabbwrgyi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.316326.xyz/Article/details/gtbfywfxzh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tianlin.xyz/Article/details/gtrhbqmsxe.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtdmqgiuzv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.9152youxi.cn/Article/details/gtnaglccgr.html

[F12] CSV 读写
来源：http://dali.iojbl.cn/Article/details/gtjiazmauj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.meibo888.top/Article/details/gtctabfgrp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shangyingyoupin.top/Article/details/gtijezxcps.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqxluhvg.html

TS:   // 同上
来源：http://dali.ivvv.top/Article/details/gtasqpqojr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.andypj.xyz/Article/details/gttlwxlixi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xziqi.cn/Article/details/gtmdtrypgg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangtech.top/Article/details/gthfbggbiv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xylfe.cn/Article/details/gtemhmukwh.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtvllxiksd.html

G. 面向对象
来源：http://dali.zhoulong.xyz/Article/details/gtpovgatdq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtlnacpkll.html

[G01] 定义类
来源：http://dali.havefunace.top/Article/details/gtxfpetdgq.html

Py:   class User: pass
来源：http://dali.jinqigufen.top/Article/details/gtpmutxeok.html

PHP:  class User {}
来源：http://dali.cqqwz.cn/Article/details/gtdxhcaklw.html

JS:   class User {}
来源：http://dali.pycfn.com/Article/details/gthcirnxfl.html

TS:   class User { name: string = ""; }
来源：http://dali.yangfankeji.com/Article/details/gtaomwsoep.html

Java: class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhyydkgg.html

Go:   type User struct { Name string }
来源：http://dali.chenjidiqi.icu/Article/details/gtudwbchay.html

Ruby: class User; end
来源：http://dali.zhengqikj.top/Article/details/gtzxncroed.html

C#:   class User {}
来源：http://dali.cashguo.top/Article/details/gtjupwtqhw.html

[G02] 构造函数
来源：http://dali.meibo888.top/Article/details/gtnqiaychf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhengqikj.top/Article/details/gtuxkdqogm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigfzy.top/Article/details/gtihroagft.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gtbrlmhlmp.html

TS:   constructor(public name: string) {}
来源：http://dali.birdmap.top/Article/details/gtnvfdpqnx.html

Java: User(String name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtlupdymhm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daria6918.cn/Article/details/gtnnsmumig.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jianghu66.top/Article/details/gtgweikzxb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xziqi.cn/Article/details/gtqifhyluj.html

[G03] 实例属性
来源：http://dali.ivvv.top/Article/details/gtnzpboecd.html

Py:   self.name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtvmvbskmb.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gtycjhnrju.html

JS:   this.name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtfmhudtbz.html

TS:   name: string = "x";
来源：http://dali.ybcxt.top/Article/details/gtlboazgri.html

Java: private String name;
来源：http://dali.gogol.net.cn/Article/details/gtestxnqkr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hongshengwenyu.top/Article/details/gtsmpztjgi.html

Ruby: @name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gtvqkazcgr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtxkynvabt.html

[G04] 定义方法
来源：http://dali.cdnleiting.top/Article/details/gtmhdloplv.html

Py:   def greet(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gtavltxiyz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtbhhxoeno.html

JS:   greet() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmrairewn.html

TS:   greet(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtujltzzhz.html

Java: String greet() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtcmfjjrxj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtctcizpuu.html

Ruby: def greet; @name; end
来源：http://dali.yj20258888.top/Article/details/gtaxlsshom.html

C#:   public string Greet() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtydbkpenk.html

[G05] 继承
来源：http://dali.9152youxi.cn/Article/details/gtocevxeny.html

Py:   class Admin(User): pass
来源：http://dali.xinyue.icu/Article/details/gtipcuysdi.html

PHP:  class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtdxagrlys.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtaeajjcbt.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtkyqtiudn.html

Java: class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtpxkslxpc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.9152youxi.cn/Article/details/gteanwaihz.html

Ruby: class Admin < User; end
来源：http://dali.zhixingplan.top/Article/details/gtanmezskf.html

C#:   class Admin : User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtveermsad.html

[G06] 重写方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbniwskg.html

Py:   def greet(self): return "admin"
来源：http://dali.wangdashe.top/Article/details/gtxecgtgmj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtcpwthqhh.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtuusvjqim.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gthlkmubnc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtscuatccb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.9152youxi.cn/Article/details/gthnvtkjht.html

Ruby: def greet; "admin"; end
来源：http://dali.gogol.net.cn/Article/details/gtgnovzqal.html

C#:   public override string Greet() => "admin";
来源：http://dali.mhx1999.top/Article/details/gtjkbppnkj.html

[G07] 调用父类方法
来源：http://dali.redwolf501.top/Article/details/gtxvrkxyvo.html

Py:   super().greet()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkvqazyb.html

PHP:  parent::greet();
来源：http://dali.wangdashe.top/Article/details/gtrcuzbwbn.html

JS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtzqqzhmkl.html

TS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxmrhtpw.html

Java: super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtfmknsntv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.iojbl.cn/Article/details/gtdwxbvdmx.html

Ruby: super
来源：http://dali.yongpay.top/Article/details/gtkwgyhemz.html

C#:   base.Greet();
来源：http://dali.zhixingplan.top/Article/details/gthgamaioc.html

[G08] 静态方法与属性
来源：http://dali.tianlin.xyz/Article/details/gtswepmery.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.0kj1m.cn/Article/details/gtmcxecwgc.html

PHP:  public static function f() {}
来源：http://dali.ehwqpu.com/Article/details/gtktffwbip.html

JS:   static f() {}
来源：http://dali.birdmap.top/Article/details/gtvxeltumu.html

TS:   static f(): void {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxgsjipol.html

Java: static void f() {}
来源：http://dali.guowangkeji.top/Article/details/gtqeoccpoa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenzaomai.com/Article/details/gtoxuiqhqt.html

Ruby: def self.f; end
来源：http://dali.yongpay.top/Article/details/gtggbayczc.html

C#:   public static void F() {}
来源：http://dali.jyoumei.cn/Article/details/gtihbsncej.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gthrxydnle.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ybcxt.top/Article/details/gtyjwfarfu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cqqwz.cn/Article/details/gtxevunbsg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowtcqbmb.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj202588.top/Article/details/gtrpqxajzx.html

Java: interface Shape { double area(); }
来源：http://dali.nanxinkj.top/Article/details/gttcaypamj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shzxlz.cn/Article/details/gtmsjcfgef.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.kuanghao11.cn/Article/details/gtvfnvhoqt.html

C#:   interface IShape { double Area(); }
来源：http://dali.havefunace.top/Article/details/gtcbseuxbp.html

[G10] 访问控制
来源：http://dali.ehwqpu.com/Article/details/gtbtqceoyc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhongyouzk.top/Article/details/gtisyrmpsw.html

PHP:  public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtfpvwkort.html

JS:   #private 字段；其余公开
来源：http://dali.cashguo.top/Article/details/gthchgdsbv.html

TS:   public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtfzefbtif.html

Java: public / protected / private / 默认包级
来源：http://dali.wangdashe.top/Article/details/gtiprjbowa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gzhubu.top/Article/details/gthnqzkski.html

Ruby: public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtwriabukz.html

C#:   public / protected / private / internal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxsobtyd.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gtdditgirj.html

Py:   @property 与 @x.setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gttshkdugr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtghwtvyod.html

JS:   get name() { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gtvkvftjcw.html

TS:   get name(): string { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskoiwnpq.html

Java: public String getName() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtiglcybpb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtyrjlolnv.html


<!-- 参考信息 -->