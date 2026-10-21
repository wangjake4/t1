代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.gaohongyu789.top/Article/details/gtlqlohpwf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtoruviydh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.havefunace.top/Article/details/gtjjlzkxgv.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsstftjjf.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtujqdgsru.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtpzazxdly.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtdytgrwyh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtjzqjfeqk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.quarkkingdee.top/Article/details/gtnfnpqfck.html

[E11] 反转字符串
来源：http://dali.shuidangran.top/Article/details/gtgtopytcc.html

Py:   s[::-1]
来源：http://dali.pycfn.com/Article/details/gtdclkpuuc.html

PHP:  strrev($s);
来源：http://dali.cheryme.top/Article/details/gtyeuhoska.html

JS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtnjssrkuq.html

TS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtsisumazv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhoulong.xyz/Article/details/gtmeffvqii.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hfpthk.cn/Article/details/gtcmqnbhsn.html

Ruby: s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtiifkmbld.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gtvxajwlju.html

[E12] 统计某字符出现次数
来源：http://dali.gzhubu.top/Article/details/gtpfpcohqp.html

Py:   s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gtryihplvh.html

PHP:  substr_count($s, "a");
来源：http://dali.dashuyun.cn/Article/details/gtsgpiqhkz.html

JS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gtcjdfifxn.html

TS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gttxqkwfmw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gzhubu.top/Article/details/gtnorzipfd.html

Go:   strings.Count(s, "a")
来源：http://dali.xylfe.cn/Article/details/gtxhpinapm.html

Ruby: s.count("a")
来源：http://dali.cheryme.top/Article/details/gtqqxoqdny.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tanke756.top/Article/details/gtcgnbmhbd.html

[E13] 逐字符遍历
来源：http://dali.jyoumei.cn/Article/details/gtszfiesve.html

Py:   for ch in s: print(ch)
来源：http://dali.yonumen.top/Article/details/gtwzwmbdps.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgfzy.top/Article/details/gtrtyyzqvh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtniivpetn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nwbrower.top/Article/details/gtgwhmopwp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.iojbl.cn/Article/details/gtbjitqnoi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxuanxn.top/Article/details/gtjcxlucwx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xylfe.cn/Article/details/gtknutvyfe.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj202588.top/Article/details/gtthtspmza.html

[E14] URL 编码与 Base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrlrkkkm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhengqikj.top/Article/details/gtuhfprgbd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jianghu66.top/Article/details/gtgqnbhljs.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aibaodan.cn/Article/details/gtkgjjffcm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fengsongda.top/Article/details/gtbjrcwxvt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtqbfjcmba.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ybcxt.top/Article/details/gtanukejgz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shuidangran.top/Article/details/gtgvhygkaf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddgeqjxt.html

[E15] HTML 转义 / 反转义
来源：http://dali.feifeiyinyue.top/Article/details/gtonyfotgi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedctzaol.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbjepfez.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gogol.net.cn/Article/details/gtyzcwimpl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fengsongda.top/Article/details/gtmckspmcx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhiwuduotai.top/Article/details/gtlllpdbua.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hysaishi.cn/Article/details/gtmvhjzjgx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hysaishi.cn/Article/details/gtfjmicvem.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.meibo888.top/Article/details/gtykjklogm.html

[E16] 数字千分位
来源：http://dali.yj202588.top/Article/details/gtwvgyqokm.html

Py:   f"{1234567:,}"
来源：http://dali.zycfv.cn/Article/details/gtgirjqino.html

PHP:  number_format(1234567);
来源：http://dali.yanxiufei.cn/Article/details/gtcmepnptm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gtaqlhklgs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gtoawzwjzc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pycfn.com/Article/details/gtwnypxhbf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhengqikj.top/Article/details/gtzeaczekm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hfpthk.cn/Article/details/gtcflxdxdy.html

C#:   1234567.ToString("N0")
来源：http://dali.chenzaomai.com/Article/details/gtxxayqjhy.html

[E17] 首字母大写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtipydjp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyyusuqt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guannengcc.top/Article/details/gtwogaahtw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gtktyqkbwu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gthryiurag.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.c1oappe.top/Article/details/gtjwbekvdx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtssydsteh.html

Ruby: s.capitalize
来源：http://dali.xuanzx.com/Article/details/gtmzvibkes.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxinkj.top/Article/details/gtdfiyelcz.html

[E18] 模板占位符替换
来源：http://dali.jinqigfzy.top/Article/details/gteinhdkol.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pengpengdd.cyou/Article/details/gtegidvxon.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ehwqpu.com/Article/details/gtfesdmoqy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcjpvekr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtpkpbxqno.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtpqnzzblo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtixwgkecl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aibaodan.cn/Article/details/gtdadglrid.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dashuyun.cn/Article/details/gtylbjjebn.html

[E19] 多行文本按行拆分
来源：http://dali.nanxinkj.top/Article/details/gtarwsmuqz.html

Py:   s.splitlines()
来源：http://dali.gotoacloud.top/Article/details/gtmqmbjgvj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cashguo.top/Article/details/gtodezdvvq.html

JS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gtxxbejtjy.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjojjwooy.html

Java: s.lines().toList()
来源：http://dali.gzhubu.top/Article/details/gtpqytwnlc.html

Go:   strings.Split(s, "\n")
来源：http://dali.tanke756.top/Article/details/gtnprgvptz.html

Ruby: s.lines
来源：http://dali.xinyue.icu/Article/details/gtfwfmsvnh.html

C#:   s.Split('\n')
来源：http://dali.mhx1999.top/Article/details/gthnrojuxq.html

[E20] 判断字符串是否为空
来源：http://dali.yongpay.top/Article/details/gtzeikfjji.html

Py:   if not s:
来源：http://dali.cucudq.cn/Article/details/gturdssmrj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.svipenyu.cn/Article/details/gtxfsbottr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sufxvd.cn/Article/details/gtxjxczofm.html

TS:   if (s === "") {}
来源：http://dali.cashguo.top/Article/details/gtbjeaxxxd.html

Java: if (s.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gtmnsgufmz.html

Go:   if s == "" {}
来源：http://dali.cqqwz.cn/Article/details/gthurcihza.html

Ruby: if s.empty?
来源：http://dali.aizwys.cn/Article/details/gtmnjrtasn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dianchejie.cn/Article/details/gtyrniqptc.html

[E21] 超长截断加省略号
来源：http://dali.nwbrower.top/Article/details/gtwtjamdba.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuetiantiany.cn/Article/details/gtprkntrqb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtlrovqybm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtvhkzicof.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtkjvubfqi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtxpmlcqcj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258888.top/Article/details/gtclbobnhl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtemlwpuoj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gthihvtucj.html

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gtxosuzfip.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxuanxn.top/Article/details/gteslesetd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtaqtrhfft.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtowhakpqf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gtgfajwqcm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenzaomai.com/Article/details/gtbeyeifvn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.meibo888.top/Article/details/gtlpdzynay.html

Ruby: s.bytesize;  s.length
来源：http://dali.birdmap.top/Article/details/gtyaubsecw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zycfv.cn/Article/details/gtxxogxnms.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtdlucovvl.html

F. 文件与目录
来源：http://dali.zycfv.cn/Article/details/gthwgphcol.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtbzfiojzx.html

[F01] 读取整个文件
来源：http://dali.tian-w.cn/Article/details/gttjdpqkng.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.svipenyu.cn/Article/details/gtdqdmhxcs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtoklpktuc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xziqi.cn/Article/details/gtxsaaojma.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtxqhboysc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtkjtdnpji.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj202588.top/Article/details/gtvquahnaz.html

Ruby: File.read("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtaqiklpaq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtsttqgxor.html

[F02] 逐行读取文件
来源：http://dali.ydzc1.top/Article/details/gtkvmdatqb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hywenlv.cn/Article/details/gtrmowxyyx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cucudq.cn/Article/details/gtrhpayxbe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gtpthkuevb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gttrpdboyp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gtukwmbssc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gtrwsbzyzc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gtunvxqlzw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jyoumei.cn/Article/details/gtwzmeehqx.html

[F03] 写入文件（覆盖）
来源：http://dali.chenjidiqi.icu/Article/details/gtxxkvpaer.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtpejhferc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtgzcbfifb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtyddphjkn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gttfxyguex.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zycfv.cn/Article/details/gtpudtzppx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgfzy.top/Article/details/gteanmrvtw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbeftosyt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gttbkauquz.html

[F04] 追加写入文件
来源：http://dali.haohaochexian.top/Article/details/gtaquwbksw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnqzz.top/Article/details/gtosaniwho.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cashguo.top/Article/details/gtsedxbkij.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gtbzykockq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gtwhwsbjsf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hammf.cn/Article/details/gtsigwrrgi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtunoeqcwy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dianchejie.cn/Article/details/gtsybipmhd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jyoumei.cn/Article/details/gtrovyatky.html

[F05] 判断文件或目录是否存在
来源：http://dali.xziqi.cn/Article/details/gtmyfteksj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daria6918.cn/Article/details/gtpaiqixhv.html

PHP:  file_exists("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtljegudti.html

JS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtuqwxkmyo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtiucrunrz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gthmzwolnf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gaohongyu789.top/Article/details/gtgixqwxmg.html

Ruby: File.exist?("a.txt")
来源：http://dali.tian-w.cn/Article/details/gthuxsdkza.html

C#:   File.Exists("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtpwhioton.html

[F06] 删除文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnusdpfmx.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtaaevdlkm.html

PHP:  unlink("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtqyauncti.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtklumxkgw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtdirtbbvd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtalzpexev.html

Go:   os.Remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtkuautpvn.html

Ruby: File.delete("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtbzzizegm.html

C#:   File.Delete("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtszxmntak.html

[F07] 创建目录（含多级）
来源：http://dali.chenzaomai.com/Article/details/gtkblcralt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gtrzznudcc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cdnleiting.top/Article/details/gtnlnsxnmo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtfwnokyuv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gthdmovcvq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cheryme.top/Article/details/gtyzuzaibj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdzensgx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.snrcjt.cn/Article/details/gtqmlrsytf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuanzx.com/Article/details/gtvnnasxak.html

[F08] 遍历目录
来源：http://dali.aibaodan.cn/Article/details/gtmtijrztq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhoulong.xyz/Article/details/gtjplnssbv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xylfe.cn/Article/details/gtwhbhdgtf.html

JS:   fs.readdirSync("dir")
来源：http://dali.cdnleiting.top/Article/details/gttbwgmufa.html

TS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gtjvsltkki.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gtggsnulig.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtxlbirfus.html

Ruby: Dir.children("dir")
来源：http://dali.sxryk.cn/Article/details/gtsfkhvxzl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigufen.top/Article/details/gtoqybawtu.html

[F09] 获取文件大小
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxbovthp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtfmaukpao.html

PHP:  filesize("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtfrfcnbes.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtmwkpyuwq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gtatjvrtsz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtkyxukwrl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hongshengwenyu.top/Article/details/gtizcfxdhg.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtydbssuxz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dianchejie.cn/Article/details/gtdrobccsx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjwwpdhn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtduhywaja.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258.top/Article/details/gtsdfkbhpk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtwnkshecr.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtzywswmvr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ydzc1.top/Article/details/gtikojuxpd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtrjholzwd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtirlzothl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtghprsrwc.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gtuollrkot.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtphxfvagh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gzhubu.top/Article/details/gtrqhxdgkq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtqnxqusih.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtjmqjtdbu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.birdmap.top/Article/details/gticmrsrri.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yueranfly.top/Article/details/gtwbizucej.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudasoemp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gtmwkwjcqr.html

[F12] CSV 读写
来源：http://dali.shangyingyoupin.top/Article/details/gtwdysanqr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopoqetrk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dianchejie.cn/Article/details/gtddmclajm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ppjwa.cn/Article/details/gtcptwqjlp.html

TS:   // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezumgxio.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebswyuiv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhiwuduotai.top/Article/details/gtkjcgmdef.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.svipenyu.cn/Article/details/gtactjbblm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.mhx1999.top/Article/details/gtspptnqsu.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtuczduaht.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gtyblxxdgc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtwgxrzhhu.html

[G01] 定义类
来源：http://dali.zhongyouzk.top/Article/details/gtamwvsmyd.html

Py:   class User: pass
来源：http://dali.tian-w.cn/Article/details/gtrlxafqsp.html

PHP:  class User {}
来源：http://dali.shzxlz.cn/Article/details/gtkukzavrz.html

JS:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gtxcabcnyv.html

TS:   class User { name: string = ""; }
来源：http://dali.sufxvd.cn/Article/details/gtexbduglq.html

Java: class User {}
来源：http://dali.snrcjt.cn/Article/details/gtoqvxfkse.html

Go:   type User struct { Name string }
来源：http://dali.cheryme.top/Article/details/gtdnnfvgeb.html

Ruby: class User; end
来源：http://dali.jlsjyb.cn/Article/details/gtqaqpaujo.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gtdzkfusaw.html

[G02] 构造函数
来源：http://dali.daxiang520.top/Article/details/gtxipdlttw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sxryk.cn/Article/details/gtqbselnts.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yanxiufei.cn/Article/details/gtjwgretdp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtjsilttjg.html

TS:   constructor(public name: string) {}
来源：http://dali.yvedp.cn/Article/details/gtywdmwbuj.html

Java: User(String name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtlyzorpgu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jyoumei.cn/Article/details/gtnrftclga.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenjidiqi.icu/Article/details/gthyiwhvem.html

C#:   public User(string name) { Name = name; }
来源：http://dali.redwolf501.top/Article/details/gthduvapdt.html

[G03] 实例属性
来源：http://dali.zhiwuduotai.top/Article/details/gtnshzhgpt.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtoeittjzm.html

PHP:  public string $name = "x";
来源：http://dali.jyoumei.cn/Article/details/gtpbksobrg.html

JS:   this.name = "x";
来源：http://dali.meibo888.top/Article/details/gthabsnvfj.html

TS:   name: string = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtldfvpzsg.html

Java: private String name;
来源：http://dali.kuanghao11.cn/Article/details/gtcgsexiey.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhiwuduotai.top/Article/details/gtnzpsmcuc.html

Ruby: @name = "x"
来源：http://dali.ehwqpu.com/Article/details/gtmvtqaofb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jianghu66.top/Article/details/gtznxbtmdm.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gtbwvckqpx.html

Py:   def greet(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gtvbphmmjk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtlapzqmtk.html

JS:   greet() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtowyynvnr.html

TS:   greet(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtcmouigxo.html

Java: String greet() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtybzjvtre.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqbxmdgy.html

Ruby: def greet; @name; end
来源：http://dali.cashguo.top/Article/details/gtdeiooumm.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxawkizk.html

[G05] 继承
来源：http://dali.yj20258.top/Article/details/gtxsqvqjyc.html

Py:   class Admin(User): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gthufjqnvv.html

PHP:  class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtxwsyszbi.html

JS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtqaqysrcd.html

TS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtepbxywql.html

Java: class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtagfkbqnl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.meibo888.top/Article/details/gtclgnkloz.html

Ruby: class Admin < User; end
来源：http://dali.sufxvd.cn/Article/details/gtwmzlkrma.html

C#:   class Admin : User {}
来源：http://dali.ivvv.top/Article/details/gtyzldstnl.html

[G06] 重写方法
来源：http://dali.zhiwuduotai.top/Article/details/gtvlnhxvzg.html

Py:   def greet(self): return "admin"
来源：http://dali.daxiang520.top/Article/details/gtthbjiprn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtjdlckwxz.html

JS:   greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtuehmqxaw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtgsxdszpe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtenehviix.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sufxvd.cn/Article/details/gtfxsucqbr.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gtdlqfnpgn.html

C#:   public override string Greet() => "admin";
来源：http://dali.ybcxt.top/Article/details/gtjzkykest.html

[G07] 调用父类方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrwmelqr.html

Py:   super().greet()
来源：http://dali.cucudq.cn/Article/details/gttlbxpqki.html

PHP:  parent::greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjivertw.html

JS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtmsilqdxu.html

TS:   super.greet();
来源：http://dali.sweek.top/Article/details/gtbbquueop.html

Java: super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbiuzjjl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.316326.xyz/Article/details/gtrzyckrst.html

Ruby: super
来源：http://dali.bjfxy.top/Article/details/gtmtfdqnzv.html

C#:   base.Greet();
来源：http://dali.sysykeji.top/Article/details/gtocsbnkpv.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gtujgczwuw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuanzhike.top/Article/details/gtmhzwglvo.html

PHP:  public static function f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtyioumasl.html

JS:   static f() {}
来源：http://dali.guowangkeji.top/Article/details/gtugnqnvwx.html

TS:   static f(): void {}
来源：http://dali.guannengcc.top/Article/details/gtuwwndkuh.html

Java: static void f() {}
来源：http://dali.birdmap.top/Article/details/gthlgbotzc.html


<!-- 参考信息 -->