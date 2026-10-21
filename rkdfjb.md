代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtscxmgwzk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigfzy.top/Article/details/gtqekbegvc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gaohongyu789.top/Article/details/gtukgzhuie.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtfqozwrmi.html

[E14] URL 编码与 Base64
来源：http://dali.316326.xyz/Article/details/gtdvtluzei.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hongshengwenyu.top/Article/details/gtdoaxchyj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hnxiangtu.top/Article/details/gtwslpojwc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhoulong.xyz/Article/details/gtskospalr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.birdmap.top/Article/details/gtwgkeevhf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtjygqdsvg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfbucqcb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.smart0.xyz/Article/details/gtxihdqbga.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.c1oappe.top/Article/details/gtamwlptdo.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgufenzy.top/Article/details/gtsjjtuswe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shuidangran.top/Article/details/gtijzyeqfv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hfpthk.cn/Article/details/gtwaxefadu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuanzhike.top/Article/details/gthnnimcvx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxywpgqr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.316326.xyz/Article/details/gtxlqlttdq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hfpthk.cn/Article/details/gtgxtagsvm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gzhubu.top/Article/details/gtflfdygro.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gotoacloud.top/Article/details/gticfqwhvg.html

[E16] 数字千分位
来源：http://dali.daria6918.cn/Article/details/gtvjgebchs.html

Py:   f"{1234567:,}"
来源：http://dali.c1oappe.top/Article/details/gtqhmmbioc.html

PHP:  number_format(1234567);
来源：http://dali.jqgufenzy.top/Article/details/gtxaloauvq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gtpelwujwe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gthoscydvb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258888.top/Article/details/gtyjjdrdhb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ivvv.top/Article/details/gtplssqlnt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zycfv.cn/Article/details/gtehogahtk.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gtegmmluqi.html

[E17] 首字母大写
来源：http://dali.316326.xyz/Article/details/gtdbkusxak.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.9152youxi.cn/Article/details/gtnizapbzy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.meibo888.top/Article/details/gtctaskvek.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwuklulss.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrpwcjbg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangdashe.top/Article/details/gtdqspyvsc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtuiorrudx.html

Ruby: s.capitalize
来源：http://dali.gotoacloud.top/Article/details/gtwnhwnhmj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cqqwz.cn/Article/details/gtkmfjtrdm.html

[E18] 模板占位符替换
来源：http://dali.tian-w.cn/Article/details/gtrsejvjgl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ivvv.top/Article/details/gttisbmjvk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.svipenyu.cn/Article/details/gtfrpselix.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtzfrsweux.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfszcgmk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtiarrxudm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtxtwfmnxc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pycfn.com/Article/details/gttkpzlgle.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.iojbl.cn/Article/details/gtuehzwper.html

[E19] 多行文本按行拆分
来源：http://dali.svipenyu.cn/Article/details/gtedfdqotc.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gtqnzdouyj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daxiang520.top/Article/details/gtizbekdns.html

JS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gthahmdnmo.html

TS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gtihaalrlo.html

Java: s.lines().toList()
来源：http://dali.nwbrower.top/Article/details/gtedcpyhss.html

Go:   strings.Split(s, "\n")
来源：http://dali.haohaochexian.top/Article/details/gtjnqtvjpl.html

Ruby: s.lines
来源：http://dali.316326.xyz/Article/details/gtqknkakzx.html

C#:   s.Split('\n')
来源：http://dali.ybcxt.top/Article/details/gtafimxawr.html

[E20] 判断字符串是否为空
来源：http://dali.meibo888.top/Article/details/gtyeaclxka.html

Py:   if not s:
来源：http://dali.nanxuanxn.top/Article/details/gtewdejxmu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cashguo.top/Article/details/gtvkpvrcnn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cashguo.top/Article/details/gtogkjqwns.html

TS:   if (s === "") {}
来源：http://dali.quarkkingdee.top/Article/details/gtpzsvzdnp.html

Java: if (s.isEmpty()) {}
来源：http://dali.jyoumei.cn/Article/details/gtqfhbrihq.html

Go:   if s == "" {}
来源：http://dali.yj20258888.top/Article/details/gtnfswartp.html

Ruby: if s.empty?
来源：http://dali.quarkkingdee.top/Article/details/gtulgqjork.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gtmznunefo.html

[E21] 超长截断加省略号
来源：http://dali.cucudq.cn/Article/details/gtrymuxicv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenzaomai.com/Article/details/gtotkcrwja.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtxocdpojq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtusonhsnq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gteylbpvus.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtkwsvflxf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.vqdsnc.cn/Article/details/gtbwgndrnb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtgqrnxmbn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtnglullzy.html

[E22] 字节长度与字符长度
来源：http://dali.cucudq.cn/Article/details/gtchboyije.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.9152youxi.cn/Article/details/gtqiznwwja.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtwryrjcol.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtkvmwviht.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gtbxbovphb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gzhubu.top/Article/details/gtqomgnake.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangshuangyany.cn/Article/details/gttjfvjkdj.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtjeoxjxex.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gtwgzqdjeo.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtqbxjtbyy.html

F. 文件与目录
来源：http://dali.gogol.net.cn/Article/details/gtrfxqftij.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxobbqjg.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gtnwcdqufv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.havefunace.top/Article/details/gtabnxixqb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtwgotbqvw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ivvv.top/Article/details/gtmboiedta.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtgtzdhkfu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtizibhmcz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuanzx.com/Article/details/gtjtydgwih.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtruwsolda.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtfgrjuutw.html

[F02] 逐行读取文件
来源：http://dali.svipenyu.cn/Article/details/gtiwwlkebk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dianchejie.cn/Article/details/gtgouksqvz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gtjzsijlnm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzspxnzgh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gtagvdnvbu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gtgdowdgca.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zdqjudy.top/Article/details/gtsvqtpkoe.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sysykeji.top/Article/details/gtwmudstxi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ybcxt.top/Article/details/gtfldcnpdu.html

[F03] 写入文件（覆盖）
来源：http://dali.iojbl.cn/Article/details/gtvclhlnbt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jiagoushi.top/Article/details/gtedbxdlpw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gthluwkfzf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtulaxuqky.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtjonyvpqn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ivvv.top/Article/details/gttlgxrazg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.c1oappe.top/Article/details/gttiuupwbd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuanzx.com/Article/details/gtiykpovhe.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtopdytjci.html

[F04] 追加写入文件
来源：http://dali.dianchejie.cn/Article/details/gtexuzisrn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtjxomoqyw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hysaishi.cn/Article/details/gthxubitxe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtmnilnfci.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtfcahyrbu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xinyue.icu/Article/details/gthwsrbiqh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cqqwz.cn/Article/details/gtxhmyweab.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jianghu66.top/Article/details/gtzbhitmho.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gtnoiofpqj.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtivgmqjay.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yueranfly.top/Article/details/gtandrlgfz.html

PHP:  file_exists("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdbxsrje.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtbevvqktc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtrporchwr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtwmoyjqfx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemcmjaxt.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtlbapfhui.html

C#:   File.Exists("a.txt")
来源：http://dali.xziqi.cn/Article/details/gteosnonku.html

[F06] 删除文件
来源：http://dali.yj202588.top/Article/details/gtukjwnbva.html

Py:   os.remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtvdjqvvqw.html

PHP:  unlink("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtygcwyyuk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtcjvvtdzh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtzacbwnrg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtofxcdkou.html

Go:   os.Remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gttxwqmbeh.html

Ruby: File.delete("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtqphjqlqq.html

C#:   File.Delete("a.txt");
来源：http://dali.316326.xyz/Article/details/gterqjgvgi.html

[F07] 创建目录（含多级）
来源：http://dali.sxryk.cn/Article/details/gtwdozrlqm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gtixdlbopd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtsshirszl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgufenzy.top/Article/details/gtkhqwqtbm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gtqaxkfsbn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zycfv.cn/Article/details/gtfxufbwij.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgufenzy.top/Article/details/gteyctwhtz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hammf.cn/Article/details/gtcveikapp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cashguo.top/Article/details/gtgmarxhiu.html

[F08] 遍历目录
来源：http://dali.dashuyun.cn/Article/details/gtlspudaek.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ydzc1.top/Article/details/gtepnpxfts.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aizwys.cn/Article/details/gtaqmzzdwn.html

JS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtnryefzvm.html

TS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtzquylhdz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gtldzntvhv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cheryme.top/Article/details/gtkisxmahd.html

Ruby: Dir.children("dir")
来源：http://dali.nanxinkj.top/Article/details/gtbcmzhnzb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yonumen.top/Article/details/gturhvfwwm.html

[F09] 获取文件大小
来源：http://dali.hywenlv.cn/Article/details/gtzqpvkdmx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnkisnaw.html

PHP:  filesize("a.txt");
来源：http://dali.pycfn.com/Article/details/gtxtntgkro.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gtmuunckxm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gtwyvprlvh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtejklwxyj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenlongwang.top/Article/details/gtounzscjp.html

Ruby: File.size("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtcczsrwbe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.iojbl.cn/Article/details/gtwmywuick.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daria6918.cn/Article/details/gtnsarsmvm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtqdzeakpd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmkbcgql.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtxmsyknee.html

TS:   path.extname("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtpobwxnsf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.redwolf501.top/Article/details/gtfcvpsytg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtzfqzxvef.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gttcsfodsh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtzgpwfoxd.html

[F11] 复制与移动文件
来源：http://dali.sweek.top/Article/details/gtxecsvgie.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtsvhwxsxl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtustwpyfc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtsdxnfiib.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtolgbnole.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gtmhdnfemh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daxiang520.top/Article/details/gtpkrnfqaw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtlitxsorc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.mhx1999.top/Article/details/gtkqutwakz.html

[F12] CSV 读写
来源：http://dali.gotoacloud.top/Article/details/gtrqaclzfa.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jlsjyb.cn/Article/details/gtrfihloug.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fzhhl.top/Article/details/gtppuvdqlu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.andypj.xyz/Article/details/gtoatcnrnd.html

TS:   // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtmexkmdca.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cdnleiting.top/Article/details/gtmlsgblan.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jianghu66.top/Article/details/gtfzfcjnwq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenzaomai.com/Article/details/gtijkfqpsg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yvedp.cn/Article/details/gtrpybibam.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtchgtgssa.html

G. 面向对象
来源：http://dali.havefunace.top/Article/details/gtzqgzqvbh.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtfavuqsvi.html

[G01] 定义类
来源：http://dali.hnqzz.top/Article/details/gtrwgzojbb.html

Py:   class User: pass
来源：http://dali.nwbrower.top/Article/details/gtmqzjhfuc.html

PHP:  class User {}
来源：http://dali.yonumen.top/Article/details/gtkmhxkuqs.html

JS:   class User {}
来源：http://dali.sysykeji.top/Article/details/gtzxcwnddd.html

TS:   class User { name: string = ""; }
来源：http://dali.ivvv.top/Article/details/gtzvbamxdb.html

Java: class User {}
来源：http://dali.jinqigufen.top/Article/details/gtyjyokqxr.html

Go:   type User struct { Name string }
来源：http://dali.tian-w.cn/Article/details/gtceyongsu.html

Ruby: class User; end
来源：http://dali.gzhubu.top/Article/details/gtjjufpcvj.html

C#:   class User {}
来源：http://dali.yj20258.top/Article/details/gtsswsgywn.html

[G02] 构造函数
来源：http://dali.yuxming.cn/Article/details/gtxczkpzbl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guowangkeji.top/Article/details/gtzjybnkgr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.mhx1999.top/Article/details/gtyakkimsg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtvloxatlb.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gttovqhpjf.html

Java: User(String name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gtsqeezkhb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.redwolf501.top/Article/details/gtkfjihccl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwgywkbz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.c1oappe.top/Article/details/gtrvoaecgz.html

[G03] 实例属性
来源：http://dali.cqqwz.cn/Article/details/gtjtguvtqg.html

Py:   self.name = "x"
来源：http://dali.cqqwz.cn/Article/details/gttqxhtmqv.html

PHP:  public string $name = "x";
来源：http://dali.zdqjudy.top/Article/details/gtjcatzulv.html

JS:   this.name = "x";
来源：http://dali.wangdashe.top/Article/details/gthrtbityg.html

TS:   name: string = "x";
来源：http://dali.316326.xyz/Article/details/gtzlipzuwr.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gthlqxvcoo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgfzy.top/Article/details/gtojocdldi.html

Ruby: @name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gtphonpatj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hywenlv.cn/Article/details/gttfpuqjkb.html

[G04] 定义方法
来源：http://dali.pengpengdd.cyou/Article/details/gtfhmjqnnd.html

Py:   def greet(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqxshpmo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxerhcrg.html

JS:   greet() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtmdlotwcf.html

TS:   greet(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtvmuitvwn.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtxixndtgt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtfixpanfc.html

Ruby: def greet; @name; end
来源：http://dali.tian-w.cn/Article/details/gthaprmrsc.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gtoapisezi.html

[G05] 继承
来源：http://dali.xylfe.cn/Article/details/gtedsfcdjg.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gtvedipxbo.html

PHP:  class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gttmoqbsiu.html

JS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtlynuimyc.html

TS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtgyiescih.html

Java: class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtpuificuq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hammf.cn/Article/details/gtreqyhfcf.html

Ruby: class Admin < User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtdgyqwndf.html

C#:   class Admin : User {}
来源：http://dali.yj20258.top/Article/details/gtmpcfawyp.html

[G06] 重写方法
来源：http://dali.hfpthk.cn/Article/details/gtguuovxdx.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gttmjzpyfr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gthymibymp.html

JS:   greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gttghgcnyf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtkfrdqfnt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtglgrvwyy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sufxvd.cn/Article/details/gtkrgyskvd.html

Ruby: def greet; "admin"; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbzvnuav.html

C#:   public override string Greet() => "admin";
来源：http://dali.yueranfly.top/Article/details/gtaqtvuqlo.html

[G07] 调用父类方法
来源：http://dali.fengsongda.top/Article/details/gtyiwphdba.html

Py:   super().greet()
来源：http://dali.yj20258.top/Article/details/gtatetekud.html

PHP:  parent::greet();
来源：http://dali.chenjidiqi.icu/Article/details/gttrdurjsn.html

JS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtanpcmiat.html

TS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtwcxfmqsv.html

Java: super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtflyrlisk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenjidiqi.icu/Article/details/gtjxfhaxgw.html

Ruby: super
来源：http://dali.cheryme.top/Article/details/gtntmdnyff.html

C#:   base.Greet();
来源：http://dali.hammf.cn/Article/details/gtgeqpklld.html

[G08] 静态方法与属性
来源：http://dali.feifeiyinyue.top/Article/details/gtjccnltzr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjlcczjb.html

PHP:  public static function f() {}
来源：http://dali.sweek.top/Article/details/gtaiqcyyuz.html

JS:   static f() {}
来源：http://dali.gotoacloud.top/Article/details/gtqgozwsnu.html

TS:   static f(): void {}
来源：http://dali.chenjidiqi.icu/Article/details/gtdrndxnau.html

Java: static void f() {}
来源：http://dali.ehwqpu.com/Article/details/gtuflicrfy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.meibo888.top/Article/details/gttfhoamqt.html

Ruby: def self.f; end
来源：http://dali.jqgfzy.top/Article/details/gtwjgzqobo.html

C#:   public static void F() {}
来源：http://dali.hysaishi.cn/Article/details/gtxahywzdv.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gtuqqljazw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.snrcjt.cn/Article/details/gtmzeuueai.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xinyue.icu/Article/details/gtidjnmoaf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yonumen.top/Article/details/gtrrsewpxf.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gtgukiyfeb.html

Java: interface Shape { double area(); }
来源：http://dali.bjfxy.top/Article/details/gtpundvyub.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnqzz.top/Article/details/gtaccblqtq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aizwys.cn/Article/details/gtvdbbibty.html

C#:   interface IShape { double Area(); }
来源：http://dali.sysykeji.top/Article/details/gtwfqmqcgm.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gtlwiazgco.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.andypj.xyz/Article/details/gtcerladbn.html

PHP:  public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtmzgzopyp.html

JS:   #private 字段；其余公开
来源：http://dali.aizwys.cn/Article/details/gttgvflqah.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtasyjsntb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacknshsd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.birdmap.top/Article/details/gtqjjqozhd.html

Ruby: public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtzflrlksi.html

C#:   public / protected / private / internal
来源：http://dali.ehwqpu.com/Article/details/gtdsjlmezd.html

[G11] getter / setter
来源：http://dali.havefunace.top/Article/details/gtgnnqkpty.html

Py:   @property 与 @x.setter
来源：http://dali.jianghu66.top/Article/details/gtuskbpnwb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtmjmkezaj.html

JS:   get name() { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gtirdhrllt.html

TS:   get name(): string { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gtjbfmnrqc.html

Java: public String getName() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtwytwxsla.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtekrhhsyc.html

Ruby: attr_accessor :name
来源：http://dali.ehwqpu.com/Article/details/gtfbivrjjj.html

C#:   public string Name { get; set; }
来源：http://dali.cdnleiting.top/Article/details/gtpiiqoenq.html

[G12] 对象转字符串
来源：http://dali.zycfv.cn/Article/details/gtruzrfyzd.html

Py:   def __str__(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtulqqhslm.html


<!-- 参考信息 -->