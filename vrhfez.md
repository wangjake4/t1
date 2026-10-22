代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gtityzqfcv.html

JS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gtifxyjmsn.html

TS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gtympoxjys.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ehwqpu.com/Article/details/gtovmmtnsa.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgfzy.top/Article/details/gtplujqcnl.html

Ruby: s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gttqyjzmvx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yueranfly.top/Article/details/gtxqvznytt.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gtyqowxzvo.html

Py:   for ch in s: print(ch)
来源：http://dali.ydzc1.top/Article/details/gtexatxyax.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.havefunace.top/Article/details/gtuchndziy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtkhiycnwu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gtwlrkybzj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtmmjfewaf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.0kj1m.cn/Article/details/gtlllraubg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqtxsogt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zycfv.cn/Article/details/gtveztjsxl.html

[E14] URL 编码与 Base64
来源：http://dali.snrcjt.cn/Article/details/gtuffmoeiz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.meibo888.top/Article/details/gtlfufyosa.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.316326.xyz/Article/details/gthrcenhvk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fzhhl.top/Article/details/gttulsjusq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jianghu66.top/Article/details/gtsowwtand.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtswgysbqd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hywenlv.cn/Article/details/gtmkppwgjs.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gtervoluii.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.316326.xyz/Article/details/gtijpchtpu.html

[E15] HTML 转义 / 反转义
来源：http://dali.gaohongyu789.top/Article/details/gteqcnmrzk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigfzy.top/Article/details/gtwxoxphzg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgufenzy.top/Article/details/gtfpelbznb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aibaodan.cn/Article/details/gtwtykbaum.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.dashuyun.cn/Article/details/gtmevkstnp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zycfv.cn/Article/details/gttlmafmox.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fzhhl.top/Article/details/gtoyauogts.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.smart0.xyz/Article/details/gtsjznkazb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgufenzy.top/Article/details/gttvabhtcv.html

[E16] 数字千分位
来源：http://dali.nanxuanxn.top/Article/details/gtewworjwb.html

Py:   f"{1234567:,}"
来源：http://dali.cashguo.top/Article/details/gtwqgsccql.html

PHP:  number_format(1234567);
来源：http://dali.jianghu66.top/Article/details/gtumdtqjro.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gtjqyuqpnw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gtcwffoeaz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shzxlz.cn/Article/details/gtsbfikpep.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pengpengdd.cyou/Article/details/gtmzsegwmj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sxryk.cn/Article/details/gtogfgwjea.html

C#:   1234567.ToString("N0")
来源：http://dali.zhongyouzk.top/Article/details/gtvgezqbtz.html

[E17] 首字母大写
来源：http://dali.tian-w.cn/Article/details/gtjhqrnjji.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daxiang520.top/Article/details/gtzvfyphws.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sxryk.cn/Article/details/gtohgawdka.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gtikdwanrj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gtztzyrvax.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtchffnyic.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.birdmap.top/Article/details/gtkdtffmzt.html

Ruby: s.capitalize
来源：http://dali.hfpthk.cn/Article/details/gtmvxbzrxc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cdnleiting.top/Article/details/gtcwrzdqdp.html

[E18] 模板占位符替换
来源：http://dali.jiagoushi.top/Article/details/gtfwduewod.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.vqdsnc.cn/Article/details/gtbrnbhvwu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ehwqpu.com/Article/details/gtnmggaray.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtatqrbdix.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtcdvkqlmn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtqitwupwx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtpftazbit.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zycfv.cn/Article/details/gttocnbytv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnqzz.top/Article/details/gtwivyjvbd.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gtrelyyfao.html

Py:   s.splitlines()
来源：http://dali.yuxming.cn/Article/details/gtqkmfqdsj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtexvodzrh.html

JS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gtzztkdqau.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gtshsndblu.html

Java: s.lines().toList()
来源：http://dali.aibaodan.cn/Article/details/gthtlcuwzp.html

Go:   strings.Split(s, "\n")
来源：http://dali.316326.xyz/Article/details/gtponqznha.html

Ruby: s.lines
来源：http://dali.zycfv.cn/Article/details/gtssevrhdx.html

C#:   s.Split('\n')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjyybnsk.html

[E20] 判断字符串是否为空
来源：http://dali.yj202588.top/Article/details/gtgujtmfnj.html

Py:   if not s:
来源：http://dali.smart0.xyz/Article/details/gtqafqwpmr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fzhhl.top/Article/details/gtcrjhfeqf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.snrcjt.cn/Article/details/gtnjitzlfd.html

TS:   if (s === "") {}
来源：http://dali.xinyue.icu/Article/details/gtomuimonu.html

Java: if (s.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtesslnrlg.html

Go:   if s == "" {}
来源：http://dali.ehwqpu.com/Article/details/gtrdtzqpur.html

Ruby: if s.empty?
来源：http://dali.daria6918.cn/Article/details/gtxwohbvnc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.meibo888.top/Article/details/gtgpyeuwuz.html

[E21] 超长截断加省略号
来源：http://dali.redwolf501.top/Article/details/gtberuzier.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yanxiufei.cn/Article/details/gtoezupwqx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtaamsjfyb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gthyjxnbgs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtqxdxjmhh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtjgefaxpe.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daxiang520.top/Article/details/gtyrfbjjhs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtgmqvliwk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtbemiqrjb.html

[E22] 字节长度与字符长度
来源：http://dali.smart0.xyz/Article/details/gtuvxjkbtd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jiagoushi.top/Article/details/gtlifnfixs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtktoluhhy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtaoximvqt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gtvbxzlnud.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tanke756.top/Article/details/gtgbmlpjkd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yonumen.top/Article/details/gttoegpygv.html

Ruby: s.bytesize;  s.length
来源：http://dali.gotoacloud.top/Article/details/gtlqfvdxrd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cqqwz.cn/Article/details/gtioocgoxs.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtfeotrwgm.html

F. 文件与目录
来源：http://dali.yueranfly.top/Article/details/gtpbxusjkq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjhfouas.html

[F01] 读取整个文件
来源：http://dali.gzhubu.top/Article/details/gtkpkqmllk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenjidiqi.icu/Article/details/gtqyxhuvzt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtvhknvmcw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zdqjudy.top/Article/details/gttfxrzreu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtkqaoucsq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtffndxorw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhixingplan.top/Article/details/gtcalhdfuw.html

Ruby: File.read("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtkuqmytgo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtldjhlctl.html

[F02] 逐行读取文件
来源：http://dali.fengsongda.top/Article/details/gtifyyhydl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258888.top/Article/details/gtbbrfwsiv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gtncsnsfyu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gtmqfjsndy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtfcrwjifu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sysykeji.top/Article/details/gtvbzcklsl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtchabyykh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgufenzy.top/Article/details/gtkktblmhy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxinkj.top/Article/details/gtunthpyke.html

[F03] 写入文件（覆盖）
来源：http://dali.xuetiantiany.cn/Article/details/gtjjnbivpn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxuanxn.top/Article/details/gtgtmznslz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gtqxipkpcc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gtkjsnsaaq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtzplqyzdg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.iojbl.cn/Article/details/gttwhwpqdn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gaohongyu789.top/Article/details/gtdwjmyyod.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtlhmvtxcw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkuqimyo.html

[F04] 追加写入文件
来源：http://dali.mhx1999.top/Article/details/gtchdghqlp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sysykeji.top/Article/details/gtddpnuvgo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daria6918.cn/Article/details/gtlfjosmul.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtvmrtkyul.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtixewlswz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gtjxzeeqyx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cashguo.top/Article/details/gtqaprhocd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yongpay.top/Article/details/gtcvttkqxi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhiwuduotai.top/Article/details/gtdcqgfiyq.html

[F05] 判断文件或目录是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtrmhjmqgl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zdqjudy.top/Article/details/gtwzhpvxsj.html

PHP:  file_exists("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtubjdxpvv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtrddlsfic.html

TS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtqzhfoggm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtacgbuggp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ehwqpu.com/Article/details/gtsybguctl.html

Ruby: File.exist?("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtyzqadzts.html

C#:   File.Exists("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtxjwehpmf.html

[F06] 删除文件
来源：http://dali.dianchejie.cn/Article/details/gtfofdazds.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gtsrcbfiwi.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjwthsab.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gteirrpxrd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtqzfzvacf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtijfnurfv.html

Go:   os.Remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtmpvzakfr.html

Ruby: File.delete("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtusnjtqwm.html

C#:   File.Delete("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtjpfmfxcx.html

[F07] 创建目录（含多级）
来源：http://dali.kuanghao11.cn/Article/details/gtacrrchdp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gteamgweux.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtiugjpglu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gtvczczxyp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtkilblhlv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sufxvd.cn/Article/details/gtpuphgsth.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gttqzdlnle.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gtxcxoxuvg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xziqi.cn/Article/details/gtkixkdyva.html

[F08] 遍历目录
来源：http://dali.hnqzz.top/Article/details/gtexzboqha.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gtssjcjpgd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuanzhike.top/Article/details/gtmobvltkc.html

JS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gtdgbwmlsn.html

TS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtidxxkmnz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gtrktvgfjh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yvedp.cn/Article/details/gtgjaoxmiy.html

Ruby: Dir.children("dir")
来源：http://dali.haohaochexian.top/Article/details/gtsotysmbs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sysykeji.top/Article/details/gtbgsaajub.html

[F09] 获取文件大小
来源：http://dali.guowangkeji.top/Article/details/gtymutnjsv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtficmxrub.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtgoegmweo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gtucuynnnp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gtxyeafpfb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtxktswrgm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xylfe.cn/Article/details/gtraksciui.html

Ruby: File.size("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtimzsjfyr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pycfn.com/Article/details/gtretkandx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258.top/Article/details/gtfivbrpxy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtathxmvtj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtpbwqahsl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkeatpsks.html

TS:   path.extname("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtajlkcxww.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258.top/Article/details/gtjubcwdqi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtyargjjqq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtgyrsjodp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtiqeibavh.html

[F11] 复制与移动文件
来源：http://dali.gogol.net.cn/Article/details/gtplbevonz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtnsdddbst.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sweek.top/Article/details/gttaizcapu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtmipphnbd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthphgiqod.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gtxfmtpamj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ydzc1.top/Article/details/gtvbjgrdcp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtvczvazhr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pycfn.com/Article/details/gthvyzbljb.html

[F12] CSV 读写
来源：http://dali.feifeiyinyue.top/Article/details/gtmcufwztk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gtnryhpmfv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.haohaochexian.top/Article/details/gtbxhzvtke.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.vqdsnc.cn/Article/details/gtlyzhpjci.html

TS:   // 同上
来源：http://dali.chenzaomai.com/Article/details/gtzyzvifdt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hammf.cn/Article/details/gtboextnrk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hysaishi.cn/Article/details/gtoltthggj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jlsjyb.cn/Article/details/gtfbvrkovb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ppjwa.cn/Article/details/gtftnpyyoy.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtompahpsi.html

G. 面向对象
来源：http://dali.9152youxi.cn/Article/details/gtzpswpspt.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtnwervhlq.html

[G01] 定义类
来源：http://dali.xinyue.icu/Article/details/gtgtocartw.html

Py:   class User: pass
来源：http://dali.sysykeji.top/Article/details/gtxxmsmgvf.html

PHP:  class User {}
来源：http://dali.shuidangran.top/Article/details/gthfsthgrf.html

JS:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gtfdptztyy.html

TS:   class User { name: string = ""; }
来源：http://dali.havefunace.top/Article/details/gtgyzefalv.html

Java: class User {}
来源：http://dali.redwolf501.top/Article/details/gtrnhnamew.html

Go:   type User struct { Name string }
来源：http://dali.dashuyun.cn/Article/details/gtaxcdiqcp.html

Ruby: class User; end
来源：http://dali.jinqigfzy.top/Article/details/gtlatzfudj.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtfbvsfbap.html

[G02] 构造函数
来源：http://dali.xylfe.cn/Article/details/gtueaprytc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258.top/Article/details/gtykwcyahc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yongpay.top/Article/details/gtsypsglbc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtpoegkdaa.html

TS:   constructor(public name: string) {}
来源：http://dali.xziqi.cn/Article/details/gtjycntvno.html

Java: User(String name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gttrixprmp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yvedp.cn/Article/details/gtsdxhwqdq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtysmiuccf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtritsswag.html

[G03] 实例属性
来源：http://dali.yj20258888.top/Article/details/gtsxbzsdia.html

Py:   self.name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqsvczmq.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtswphdhpa.html

JS:   this.name = "x";
来源：http://dali.c1oappe.top/Article/details/gtklhhrfaf.html

TS:   name: string = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtjahxvsho.html

Java: private String name;
来源：http://dali.ydzc1.top/Article/details/gthupylwmo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aibaodan.cn/Article/details/gtfsfmlsvm.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtxzjluzgp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhixingplan.top/Article/details/gtzillhsvx.html

[G04] 定义方法
来源：http://dali.yvedp.cn/Article/details/gtsujetsqk.html

Py:   def greet(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtnlohbcml.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtybmgshvl.html

JS:   greet() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtgamjvnpp.html

TS:   greet(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtvzieafaq.html

Java: String greet() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtjbzpmarc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtramkzwdg.html

Ruby: def greet; @name; end
来源：http://dali.fengsongda.top/Article/details/gtleybfjmu.html

C#:   public string Greet() => Name;
来源：http://dali.wangshuangyany.cn/Article/details/gtsbufyjmt.html

[G05] 继承
来源：http://dali.havefunace.top/Article/details/gtgsqeimqq.html

Py:   class Admin(User): pass
来源：http://dali.cqqwz.cn/Article/details/gtvgoltvzr.html

PHP:  class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtfvptxnzf.html

JS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtbtgkajbp.html

TS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtrfwekjwj.html

Java: class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtrrfhcrrx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xinyue.icu/Article/details/gtwnpfthal.html

Ruby: class Admin < User; end
来源：http://dali.zhengqikj.top/Article/details/gtptdxlymg.html

C#:   class Admin : User {}
来源：http://dali.jianghu66.top/Article/details/gtzlrclnrk.html

[G06] 重写方法
来源：http://dali.bjfxy.top/Article/details/gtluieobfn.html

Py:   def greet(self): return "admin"
来源：http://dali.wangdashe.top/Article/details/gtysssbecu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtydaiyore.html

JS:   greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtgwbiazul.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtxqpjxmxo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtghczquvp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaspbnllg.html

Ruby: def greet; "admin"; end
来源：http://dali.dashuyun.cn/Article/details/gtsdexdfuo.html

C#:   public override string Greet() => "admin";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrugkfxjr.html

[G07] 调用父类方法
来源：http://dali.ydzc1.top/Article/details/gtbodivaku.html

Py:   super().greet()
来源：http://dali.yuanzhike.top/Article/details/gtgsbceumm.html

PHP:  parent::greet();
来源：http://dali.zhengqikj.top/Article/details/gtojrcmmug.html

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtjyytaggw.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtuvutmvgh.html

Java: super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtszixgzpq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cashguo.top/Article/details/gtvkvhrglt.html

Ruby: super
来源：http://dali.sufxvd.cn/Article/details/gtorxovunr.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gtzzxjjvjb.html

[G08] 静态方法与属性
来源：http://dali.xinyue.icu/Article/details/gtasxunejt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gtkpjdgsbv.html

PHP:  public static function f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtpwussazt.html

JS:   static f() {}
来源：http://dali.tian-w.cn/Article/details/gtxzbphpwm.html

TS:   static f(): void {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpndckty.html

Java: static void f() {}
来源：http://dali.mhx1999.top/Article/details/gtpibkedwh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shangyingyoupin.top/Article/details/gtqgqmxuvf.html

Ruby: def self.f; end
来源：http://dali.zhiwuduotai.top/Article/details/gtmwfvxkti.html

C#:   public static void F() {}
来源：http://dali.zycfv.cn/Article/details/gtxsmsgmri.html

[G09] 接口 / 抽象类
来源：http://dali.pycfn.com/Article/details/gtollcxlza.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkjkbvrt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gtxylklibs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gtipzauzip.html

TS:   interface Shape { area(): number; }
来源：http://dali.ybcxt.top/Article/details/gtpmgtahem.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigufen.top/Article/details/gtwfaglmgn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dianchejie.cn/Article/details/gtxwpoxgfi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gthlyyzdrf.html

C#:   interface IShape { double Area(); }
来源：http://dali.daxiang520.top/Article/details/gtjhrqyvtx.html

[G10] 访问控制
来源：http://dali.sysykeji.top/Article/details/gtfumonahh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yongpay.top/Article/details/gtoyrpktkx.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtyvirykrt.html

JS:   #private 字段；其余公开
来源：http://dali.cheryme.top/Article/details/gtsiqefxiz.html

TS:   public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtqdmtlaun.html

Java: public / protected / private / 默认包级
来源：http://dali.sufxvd.cn/Article/details/gtqxethsas.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlgjvwwd.html

Ruby: public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtzoqmhdnr.html


<!-- 参考信息 -->