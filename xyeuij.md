代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtjocfyvmt.html

Java: String.format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtrgdseqxx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtpagvywof.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtbidbaqnb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hongshengwenyu.top/Article/details/gtgppawryz.html

[E11] 反转字符串
来源：http://dali.dashuyun.cn/Article/details/gtifjkdviq.html

Py:   s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gtilbxgivq.html

PHP:  strrev($s);
来源：http://dali.316326.xyz/Article/details/gtzaocznda.html

JS:   [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtuhjkiyqd.html

TS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjupuqnt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnqzz.top/Article/details/gtkgfthtet.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gogol.net.cn/Article/details/gtoakoklvv.html

Ruby: s.reverse
来源：http://dali.yj20258.top/Article/details/gtagyrfcsm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gtzbryctcb.html

[E12] 统计某字符出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gtsobellsk.html

Py:   s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtojxaeujm.html

PHP:  substr_count($s, "a");
来源：http://dali.hysaishi.cn/Article/details/gtywionhmh.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwwowskf.html

TS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gtheldsjca.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuanzhike.top/Article/details/gtdlzvdtnj.html

Go:   strings.Count(s, "a")
来源：http://dali.cucudq.cn/Article/details/gtstvxxaxt.html

Ruby: s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gtstqivbid.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daria6918.cn/Article/details/gtjcliuyez.html

[E13] 逐字符遍历
来源：http://dali.guowangkeji.top/Article/details/gtgbgxlhkk.html

Py:   for ch in s: print(ch)
来源：http://dali.haohaochexian.top/Article/details/gtgczhbsgv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gtswhtydnw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gtxbiuwtov.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtzrulimsi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pycfn.com/Article/details/gttorcxrir.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cqqwz.cn/Article/details/gtivsdmefh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.c1oappe.top/Article/details/gtolcfcqpg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtpszxdpzf.html

[E14] URL 编码与 Base64
来源：http://dali.redwolf501.top/Article/details/gtyzadsmpm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hammf.cn/Article/details/gtkcdlwafx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigfzy.top/Article/details/gteeqxfrny.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnqzz.top/Article/details/gtvoadkqtd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtqpcgdcbb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gtyxlxpalm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cqqwz.cn/Article/details/gtthuxpnco.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cdnleiting.top/Article/details/gtpeihtnby.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guannengcc.top/Article/details/gtawcdxonk.html

[E15] HTML 转义 / 反转义
来源：http://dali.sufxvd.cn/Article/details/gtduyvgidp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fzhhl.top/Article/details/gteecjnoft.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ydzc1.top/Article/details/gtwxiazrmm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xziqi.cn/Article/details/gtfyfonrmj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtdjdadfms.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.svipenyu.cn/Article/details/gtlubbnuda.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yvedp.cn/Article/details/gtjdqwtudu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdzcayzt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgufenzy.top/Article/details/gtjbomrgzc.html

[E16] 数字千分位
来源：http://dali.yanxiufei.cn/Article/details/gtzbdtkbqu.html

Py:   f"{1234567:,}"
来源：http://dali.svipenyu.cn/Article/details/gtfutzvrka.html

PHP:  number_format(1234567);
来源：http://dali.nanxuanxn.top/Article/details/gtjjuolplg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gtgqhrnpsw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenjidiqi.icu/Article/details/gtuczddpje.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gtzunjeajr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.snrcjt.cn/Article/details/gtwxihiybk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sxryk.cn/Article/details/gtxkhfdybm.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258.top/Article/details/gtqdjniccj.html

[E17] 首字母大写
来源：http://dali.ivvv.top/Article/details/gtfshfrwbo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jyoumei.cn/Article/details/gttwsqxydw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpirrxiy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gthsebfvwg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtkaonkzds.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuxming.cn/Article/details/gtuhbamwek.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtjbjlilaz.html

Ruby: s.capitalize
来源：http://dali.yonumen.top/Article/details/gtufbwuafr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shzxlz.cn/Article/details/gtugocrpki.html

[E18] 模板占位符替换
来源：http://dali.c1oappe.top/Article/details/gtevkxsega.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangdashe.top/Article/details/gtatvmygmp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxuanxn.top/Article/details/gtphtbpitp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtstzppxfr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtdydzwuqd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbwjjupl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtcezyrklo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxuanxn.top/Article/details/gtblfeoigp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpjudqdn.html

[E19] 多行文本按行拆分
来源：http://dali.jqgfzy.top/Article/details/gtwnxyants.html

Py:   s.splitlines()
来源：http://dali.jlsjyb.cn/Article/details/gtcfwvcpve.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpumfprks.html

JS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gtgfyjxxmk.html

TS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gtipyvgoqm.html

Java: s.lines().toList()
来源：http://dali.aizwys.cn/Article/details/gtkhkujkqz.html

Go:   strings.Split(s, "\n")
来源：http://dali.yongpay.top/Article/details/gttfqxqlaz.html

Ruby: s.lines
来源：http://dali.cucudq.cn/Article/details/gtasriqhet.html

C#:   s.Split('\n')
来源：http://dali.feifeiyinyue.top/Article/details/gtzldwoyfl.html

[E20] 判断字符串是否为空
来源：http://dali.tanke756.top/Article/details/gtusjecnbu.html

Py:   if not s:
来源：http://dali.haohaochexian.top/Article/details/gtbatkagkz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gogol.net.cn/Article/details/gtyovxivqv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hongshengwenyu.top/Article/details/gttxiyuybp.html

TS:   if (s === "") {}
来源：http://dali.vqdsnc.cn/Article/details/gtmgsjljbl.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gtprwxuabq.html

Go:   if s == "" {}
来源：http://dali.shuidangran.top/Article/details/gtifbpfdaw.html

Ruby: if s.empty?
来源：http://dali.yuxming.cn/Article/details/gtagovdlai.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hfpthk.cn/Article/details/gtqmefknkk.html

[E21] 超长截断加省略号
来源：http://dali.vqdsnc.cn/Article/details/gtarygobix.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cashguo.top/Article/details/gtmbjgknro.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtqnotacax.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gttjplarep.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtslvrpxhy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtevhshbxd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuanzhike.top/Article/details/gtjsvycalm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtzeooskjo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtsxnbvhbw.html

[E22] 字节长度与字符长度
来源：http://dali.shangyingyoupin.top/Article/details/gtaixjxycn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cheryme.top/Article/details/gtlcwrvqjh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtyherfinq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gttnyxeqbj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtaxjldaxb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xylfe.cn/Article/details/gtvnduyaqe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hysaishi.cn/Article/details/gtmnbxagpu.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gtlujsprxf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gaohongyu789.top/Article/details/gtrisljegl.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtdwvzbiew.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gtmhbelycc.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtxzsqtbhg.html

[F01] 读取整个文件
来源：http://dali.snrcjt.cn/Article/details/gtcepcdxkw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daxiang520.top/Article/details/gtwbngxzha.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtnkakrwmq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yonumen.top/Article/details/gtuutgisqm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gthdbufuni.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtymmgtjvo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgfzy.top/Article/details/gttyngqtnn.html

Ruby: File.read("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtdslvnxcr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtetqxmmqg.html

[F02] 逐行读取文件
来源：http://dali.aizwys.cn/Article/details/gtsgvnbqbl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuetiantiany.cn/Article/details/gtcyvbyxpt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmzrxcvm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gtfzcgzidy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gtztzpccul.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gtwzixuwxr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gtslpeqysd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrsxnpqbt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.smart0.xyz/Article/details/gttgauvifz.html

[F03] 写入文件（覆盖）
来源：http://dali.aibaodan.cn/Article/details/gtbkzhoflm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tianlin.xyz/Article/details/gtpvfatwfh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gtnpdlhiyw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtxmwrgbfx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtholjtgsf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgufenzy.top/Article/details/gtzauwtmwx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gtvjlrqoso.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhoulong.xyz/Article/details/gtfkulrkms.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gteraelfhi.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuuokwvyo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tanke756.top/Article/details/gtaqhgmyeq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tian-w.cn/Article/details/gtxtuphirg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gtfhaeqbpp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gthpgenopf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.svipenyu.cn/Article/details/gteoibzfhx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guannengcc.top/Article/details/gtduidyuit.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.0kj1m.cn/Article/details/gthlmkecrs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.feifeiyinyue.top/Article/details/gtnsypjbvm.html

[F05] 判断文件或目录是否存在
来源：http://dali.c1oappe.top/Article/details/gttgfascis.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dashuyun.cn/Article/details/gtpdxwfukq.html

PHP:  file_exists("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtrlptvcex.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtvrvcdtlu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gthcrtfhlm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtoaaqcbnj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cqqwz.cn/Article/details/gtgyawyjem.html

Ruby: File.exist?("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtclloulmq.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gttqmtnqjy.html

[F06] 删除文件
来源：http://dali.jyoumei.cn/Article/details/gtyxrbwmmk.html

Py:   os.remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtayzicjos.html

PHP:  unlink("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtapfsiafs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gteeywzxdo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtmhamabqu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gttpspbjgh.html

Go:   os.Remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtwrpiapvb.html

Ruby: File.delete("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtsvyunlia.html

C#:   File.Delete("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtavbwjdcp.html

[F07] 创建目录（含多级）
来源：http://dali.quarkkingdee.top/Article/details/gtsymodpjr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gtroldtwcc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.316326.xyz/Article/details/gtkkeprbdj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtsfvsaves.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gtcckhedoq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cqqwz.cn/Article/details/gtzaqlbtsr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sufxvd.cn/Article/details/gteliiqjhi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenlongwang.top/Article/details/gttkvtndju.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.quarkkingdee.top/Article/details/gtwilegdhb.html

[F08] 遍历目录
来源：http://dali.tianlin.xyz/Article/details/gtwcixxwal.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.feifeiyinyue.top/Article/details/gtbxuxipho.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gzhubu.top/Article/details/gtxvtrbblo.html

JS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gtxavvntyb.html

TS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtwwbdykmm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtcnfkoxoc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ivvv.top/Article/details/gtbgmaukmx.html

Ruby: Dir.children("dir")
来源：http://dali.shzxlz.cn/Article/details/gtpgjwolfr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.mhx1999.top/Article/details/gtjmfpoupj.html

[F09] 获取文件大小
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbrhqibh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.meibo888.top/Article/details/gtbctwmlgs.html

PHP:  filesize("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtkdhuspbn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gtxgghecgl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gtfickhguz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtwdmoehgw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hysaishi.cn/Article/details/gtoevtchaw.html

Ruby: File.size("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtdchjrijw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwsjvofv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhengqikj.top/Article/details/gtnzbhgedr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtbthlyavh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yongpay.top/Article/details/gttqdxgqqz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtqvwftidh.html

TS:   path.extname("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtolhhwvdf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnqzz.top/Article/details/gtxgwjiwsb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtdhrmkfru.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gttvfnunxn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtztvdcqzk.html

[F11] 复制与移动文件
来源：http://dali.jiagoushi.top/Article/details/gtpuouaxan.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtfaqonelx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sysykeji.top/Article/details/gtqqcqxqht.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtcjvjguij.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gttboygxdy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.316326.xyz/Article/details/gtvousuusd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnqzz.top/Article/details/gtztkxxlya.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtuqwamxir.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yvedp.cn/Article/details/gtawmyzqqa.html

[F12] CSV 读写
来源：http://dali.jqgufenzy.top/Article/details/gtmljppknz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sysykeji.top/Article/details/gteansfyeu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fengsongda.top/Article/details/gtzprlruex.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yongpay.top/Article/details/gthhihljmn.html

TS:   // 同上
来源：http://dali.jqgufenzy.top/Article/details/gtbdzszfma.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.haohaochexian.top/Article/details/gtovdqiqsj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cucudq.cn/Article/details/gtqttptwrr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.iojbl.cn/Article/details/gtbvlyxeod.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgfzy.top/Article/details/gtbjmzccsq.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtxnfpivtl.html

G. 面向对象
来源：http://dali.havefunace.top/Article/details/gtemzjmrrn.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtcxpzyrad.html

[G01] 定义类
来源：http://dali.daria6918.cn/Article/details/gtegbeasnb.html

Py:   class User: pass
来源：http://dali.c1oappe.top/Article/details/gtcffrzsse.html

PHP:  class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtjufhvsfp.html

JS:   class User {}
来源：http://dali.jianghu66.top/Article/details/gtzxkzmvec.html

TS:   class User { name: string = ""; }
来源：http://dali.gzhubu.top/Article/details/gttgdkpmrl.html

Java: class User {}
来源：http://dali.xziqi.cn/Article/details/gtrqadhaue.html

Go:   type User struct { Name string }
来源：http://dali.c1oappe.top/Article/details/gtxdkurimt.html

Ruby: class User; end
来源：http://dali.iojbl.cn/Article/details/gtyagurwgf.html

C#:   class User {}
来源：http://dali.xinyue.icu/Article/details/gtglzyamuw.html

[G02] 构造函数
来源：http://dali.sufxvd.cn/Article/details/gttnlgduzq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj202588.top/Article/details/gtqubqcwvo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fzhhl.top/Article/details/gtqwtnjegx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtqckyjipk.html

TS:   constructor(public name: string) {}
来源：http://dali.andypj.xyz/Article/details/gtwjdlgqgs.html

Java: User(String name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gttjhkfxzx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gtwsinbgjn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnxiangtu.top/Article/details/gtozimekwf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258888.top/Article/details/gtvdpgnxep.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gtpblvnrsc.html

Py:   self.name = "x"
来源：http://dali.pycfn.com/Article/details/gtzrcxvqsj.html

PHP:  public string $name = "x";
来源：http://dali.xinyue.icu/Article/details/gtnklbtbgf.html

JS:   this.name = "x";
来源：http://dali.smart0.xyz/Article/details/gtkwzzyftx.html

TS:   name: string = "x";
来源：http://dali.dashuyun.cn/Article/details/gtbggrofhp.html

Java: private String name;
来源：http://dali.cashguo.top/Article/details/gtbagytvga.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.316326.xyz/Article/details/gtcwqlviei.html

Ruby: @name = "x"
来源：http://dali.0kj1m.cn/Article/details/gtwhqeevue.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dianchejie.cn/Article/details/gtzsqsppnp.html

[G04] 定义方法
来源：http://dali.dashuyun.cn/Article/details/gtuvkgjbbs.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlotppwx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtqgpiicmd.html

JS:   greet() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtjtafhhmo.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtqktwxyjm.html

Java: String greet() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtdmdjsfsm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtpmrpwyet.html

Ruby: def greet; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gtywqakvrh.html

C#:   public string Greet() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gtpebutfkq.html

[G05] 继承
来源：http://dali.hnqzz.top/Article/details/gtubuhwhjl.html

Py:   class Admin(User): pass
来源：http://dali.bjfxy.top/Article/details/gtnwhhkeqv.html

PHP:  class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtqotzcopg.html

JS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtfkzvautx.html

TS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gteqndghho.html

Java: class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtvytchzyn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gzhubu.top/Article/details/gtnrspqkdt.html

Ruby: class Admin < User; end
来源：http://dali.xylfe.cn/Article/details/gtssnpbvbb.html

C#:   class Admin : User {}
来源：http://dali.xuanzx.com/Article/details/gtrjrmanwy.html

[G06] 重写方法
来源：http://dali.fengsongda.top/Article/details/gttcfmakff.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gtjcnzumuu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtskjklijg.html

JS:   greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtuhlhvqko.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtujxdzane.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtpnkpxhco.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xziqi.cn/Article/details/gtmpwctcts.html

Ruby: def greet; "admin"; end
来源：http://dali.gotoacloud.top/Article/details/gtsrfzaaay.html

C#:   public override string Greet() => "admin";
来源：http://dali.ehwqpu.com/Article/details/gthaowhdkz.html

[G07] 调用父类方法
来源：http://dali.shangyingyoupin.top/Article/details/gtsthhzpek.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gtqbgfgfle.html

PHP:  parent::greet();
来源：http://dali.hammf.cn/Article/details/gtatbsksle.html

JS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtewlpxhko.html

TS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtbszntdug.html

Java: super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtsdcgcsvh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hywenlv.cn/Article/details/gtykqnyjcp.html

Ruby: super
来源：http://dali.zhiwuduotai.top/Article/details/gtqodjdvev.html

C#:   base.Greet();
来源：http://dali.cheryme.top/Article/details/gtygcfxxkr.html

[G08] 静态方法与属性
来源：http://dali.xuanzx.com/Article/details/gtykxcxgbh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sxryk.cn/Article/details/gtwcyxugvt.html

PHP:  public static function f() {}
来源：http://dali.hammf.cn/Article/details/gtqbwqovtl.html

JS:   static f() {}
来源：http://dali.0kj1m.cn/Article/details/gtrwxndpwt.html

TS:   static f(): void {}
来源：http://dali.pengpengdd.cyou/Article/details/gtshwirfsc.html

Java: static void f() {}
来源：http://dali.cucudq.cn/Article/details/gttacicsjm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hfpthk.cn/Article/details/gtqhyibjma.html

Ruby: def self.f; end
来源：http://dali.svipenyu.cn/Article/details/gtunvrhyky.html

C#:   public static void F() {}
来源：http://dali.cucudq.cn/Article/details/gtcuoxhbyt.html

[G09] 接口 / 抽象类
来源：http://dali.hywenlv.cn/Article/details/gtqcavypnf.html


<!-- 参考信息 -->