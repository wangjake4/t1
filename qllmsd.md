代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.hongshengwenyu.top/Article/details/gtdkqfwzco.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtvrrlobbx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xylfe.cn/Article/details/gtnxhtxdeq.html

JS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtaizphuzb.html

TS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtcbqeupnz.html

Java: String.format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtksvymzzl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtkrwhfdlm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gthvgzigfk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhixingplan.top/Article/details/gtwaecwczc.html

[E11] 反转字符串
来源：http://dali.cashguo.top/Article/details/gtevqfazvs.html

Py:   s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gtnpdkotlo.html

PHP:  strrev($s);
来源：http://dali.xinyue.icu/Article/details/gttddatmzp.html

JS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtpihvahxf.html

TS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtwvkesjyl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xinyue.icu/Article/details/gteaalqxde.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258888.top/Article/details/gtksftdipg.html

Ruby: s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtttlxzudf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gtlicqhizv.html

[E12] 统计某字符出现次数
来源：http://dali.xinyue.icu/Article/details/gtihulhmbd.html

Py:   s.count("a")
来源：http://dali.yongpay.top/Article/details/gtngsejtmm.html

PHP:  substr_count($s, "a");
来源：http://dali.gzhubu.top/Article/details/gtbfhhanov.html

JS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gtgyzmmcjh.html

TS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtseiywypi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.mhx1999.top/Article/details/gtgebnbuea.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258.top/Article/details/gtnkuzqkaw.html

Ruby: s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtmuvwcgro.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cqqwz.cn/Article/details/gtqsjhjxid.html

[E13] 逐字符遍历
来源：http://dali.wangdashe.top/Article/details/gtcuvwlgsl.html

Py:   for ch in s: print(ch)
来源：http://dali.xinyue.icu/Article/details/gtgzrpltmn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkczoeaqt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtznkhnnlp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtynqplvso.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yueranfly.top/Article/details/gtcuieurwg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnwtdhjy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhengqikj.top/Article/details/gtfuisibcm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtgxtwohvd.html

[E14] URL 编码与 Base64
来源：http://dali.andypj.xyz/Article/details/gtctjpjutk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ivvv.top/Article/details/gtoqndievw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yanxiufei.cn/Article/details/gtwvdcynqq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dashuyun.cn/Article/details/gtujnvpkuc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sysykeji.top/Article/details/gtctirqxkg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtfdyfyqwt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxinkj.top/Article/details/gtfmtcxtcf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nwbrower.top/Article/details/gtsvxnjqtt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtxwpctowl.html

[E15] HTML 转义 / 反转义
来源：http://dali.yvedp.cn/Article/details/gtmfmpwrcc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtyludiodk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.birdmap.top/Article/details/gtgsscxrxk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gtjwjiqrug.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shuidangran.top/Article/details/gtbaxcyfmc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.redwolf501.top/Article/details/gtodveldgk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cashguo.top/Article/details/gttuhezins.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.andypj.xyz/Article/details/gtwvxngthr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yanxiufei.cn/Article/details/gtpnnlcwdi.html

[E16] 数字千分位
来源：http://dali.tian-w.cn/Article/details/gthirhcaun.html

Py:   f"{1234567:,}"
来源：http://dali.sxryk.cn/Article/details/gtaytyhcqd.html

PHP:  number_format(1234567);
来源：http://dali.fzhhl.top/Article/details/gtsqaeaqjs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gtvijmafjf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gtfcmaghyo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xinyue.icu/Article/details/gtlstwflrw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuanzx.com/Article/details/gttswqtemk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cdnleiting.top/Article/details/gtvknmmcum.html

C#:   1234567.ToString("N0")
来源：http://dali.sufxvd.cn/Article/details/gtelpqnhlo.html

[E17] 首字母大写
来源：http://dali.zhiwuduotai.top/Article/details/gtpcemtatc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ivvv.top/Article/details/gtttztoxuh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tanke756.top/Article/details/gtywuahuqp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gtoynjirlq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtnoysjwxa.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenzaomai.com/Article/details/gtbuufkrqk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.svipenyu.cn/Article/details/gtdyisojfy.html

Ruby: s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gtlexbsbfd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.havefunace.top/Article/details/gtvxdfbjng.html

[E18] 模板占位符替换
来源：http://dali.0kj1m.cn/Article/details/gtquxgbqiv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xinyue.icu/Article/details/gtusmqhulz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hfpthk.cn/Article/details/gtaajkccqe.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtqofhajpq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtykdxqvfp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtyublxftw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtyihdorif.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pengpengdd.cyou/Article/details/gtlvtatlsy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sxryk.cn/Article/details/gtkeklhbxy.html

[E19] 多行文本按行拆分
来源：http://dali.haohaochexian.top/Article/details/gtzdzszrkg.html

Py:   s.splitlines()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgunmzgk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfbfpnqe.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtotvxopsd.html

TS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gtjewnuxqn.html

Java: s.lines().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtalpkvaym.html

Go:   strings.Split(s, "\n")
来源：http://dali.pycfn.com/Article/details/gtqsmzitpb.html

Ruby: s.lines
来源：http://dali.yvedp.cn/Article/details/gtoirqfbfk.html

C#:   s.Split('\n')
来源：http://dali.shzxlz.cn/Article/details/gtnumfbyzi.html

[E20] 判断字符串是否为空
来源：http://dali.guannengcc.top/Article/details/gtkknupbbt.html

Py:   if not s:
来源：http://dali.hywenlv.cn/Article/details/gtdckhfofm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.c1oappe.top/Article/details/gtszbpwrre.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258888.top/Article/details/gtrhrsundh.html

TS:   if (s === "") {}
来源：http://dali.chenlongwang.top/Article/details/gtystrmlzo.html

Java: if (s.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gtatzldorx.html

Go:   if s == "" {}
来源：http://dali.meibo888.top/Article/details/gtlsadftxj.html

Ruby: if s.empty?
来源：http://dali.yongpay.top/Article/details/gtepkynhpq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hywenlv.cn/Article/details/gtrjzsxuud.html

[E21] 超长截断加省略号
来源：http://dali.316326.xyz/Article/details/gtrguijhly.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hywenlv.cn/Article/details/gtesxuxkmv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtdqaxepus.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtncqsgjjo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtmasoexvg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtjlavzqnb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jyoumei.cn/Article/details/gtoprrhnfu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtpsfpring.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gtsbcnpvrv.html

[E22] 字节长度与字符长度
来源：http://dali.yvedp.cn/Article/details/gtsafrfkwu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fengsongda.top/Article/details/gthzuvardb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtsvqjrval.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtomvhokns.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gtabwtullq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guannengcc.top/Article/details/gtaxnetlvl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.havefunace.top/Article/details/gtspguxxxk.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenlongwang.top/Article/details/gtszrdxeuv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jiagoushi.top/Article/details/gtegjurmff.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtozqgjibn.html

F. 文件与目录
来源：http://dali.wangshuangyany.cn/Article/details/gteurwhttv.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtkjsypqvi.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gtpgbpxggs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tianlin.xyz/Article/details/gtmctiqimb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtgmjdfcrr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fzhhl.top/Article/details/gtcghgtmmh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ivvv.top/Article/details/gtqeodzzur.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gteripeqrw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.iojbl.cn/Article/details/gtlulvmqja.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtammnuoox.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj202588.top/Article/details/gtysfojzhe.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gthvyirfbo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuanzx.com/Article/details/gtiojfjfrn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gogol.net.cn/Article/details/gtngihmpmk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gtwgwzoewr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gtkxnehbvj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtlaogtwbp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.feifeiyinyue.top/Article/details/gtjyuakokh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxuanxn.top/Article/details/gtqozyfkep.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xziqi.cn/Article/details/gtnbxuidhs.html

[F03] 写入文件（覆盖）
来源：http://dali.cucudq.cn/Article/details/gtdtufjrjz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.svipenyu.cn/Article/details/gtsliypfwb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gtqzwmmlxu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gtfwowtgnj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtuclwhflc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hammf.cn/Article/details/gttimwqypp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.kuanghao11.cn/Article/details/gtlmfukcql.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guannengcc.top/Article/details/gtrslruamg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gtzwrgszch.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumyahojl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtdqxmipwl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zdqjudy.top/Article/details/gtczsqcngd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtyjddmshj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtyiabtkmx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shangyingyoupin.top/Article/details/gtruniwewa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xziqi.cn/Article/details/gtdxtkojld.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shangyingyoupin.top/Article/details/gthoblxnsv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuanzhike.top/Article/details/gtafesbagn.html

[F05] 判断文件或目录是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtcnavxyet.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.0kj1m.cn/Article/details/gtrzwnsale.html

PHP:  file_exists("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtzvtlizhm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtkmwcxsih.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtblwzajbr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtntdyunwr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sxryk.cn/Article/details/gtmpzuarcs.html

Ruby: File.exist?("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtibilmsmx.html

C#:   File.Exists("a.txt")
来源：http://dali.havefunace.top/Article/details/gtiavzkrwg.html

[F06] 删除文件
来源：http://dali.mhx1999.top/Article/details/gteivwfofk.html

Py:   os.remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtzzesulyi.html

PHP:  unlink("a.txt");
来源：http://dali.tanke756.top/Article/details/gtvogjaqtc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtwynukwre.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtabbijwvv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtismmvmhc.html

Go:   os.Remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtwtvebqnt.html

Ruby: File.delete("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtvrozmrlq.html

C#:   File.Delete("a.txt");
来源：http://dali.sweek.top/Article/details/gtlgdsznwy.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzsghrsi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgnjacws.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guannengcc.top/Article/details/gtmvaoosqg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gtxrcmjcww.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gtsufrzith.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hfpthk.cn/Article/details/gtsirpdbub.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fengsongda.top/Article/details/gttjranflx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sufxvd.cn/Article/details/gthbvjqbyf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jiagoushi.top/Article/details/gthybxrruw.html

[F08] 遍历目录
来源：http://dali.fengsongda.top/Article/details/gtpkjdyfdw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnssvekz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daxiang520.top/Article/details/gtckhlvfsu.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtjmbzdfbp.html

TS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtgbduewmg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gtyvtofwhx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtagbrvnjr.html

Ruby: Dir.children("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhracoft.html

C#:   Directory.GetFiles("dir")
来源：http://dali.c1oappe.top/Article/details/gtswinsalp.html

[F09] 获取文件大小
来源：http://dali.cucudq.cn/Article/details/gtbpjnhkdp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtapskhqhk.html

PHP:  filesize("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtrexeobux.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gtctwizhwp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtuzyagjun.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzgdgmah.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hywenlv.cn/Article/details/gtelaxetja.html

Ruby: File.size("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtyogsbyfp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aibaodan.cn/Article/details/gtwpazyyyu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fzhhl.top/Article/details/gtuxinbwcf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtsrwwtocq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtiwrybloc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtjhqcttze.html

TS:   path.extname("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtennupefg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gzhubu.top/Article/details/gtpqotwjzx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtvrxazmls.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtyxctywmu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtilzttqgg.html

[F11] 复制与移动文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxkbboqb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtvlkzndqo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.0kj1m.cn/Article/details/gtqxzvfdbj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtbqkiwtuh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtnrwxupff.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shuidangran.top/Article/details/gtknvlznfp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yangfankeji.com/Article/details/gtxycsmhek.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhwctetd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuanzx.com/Article/details/gtuhpprhva.html

[F12] CSV 读写
来源：http://dali.gogol.net.cn/Article/details/gtqworiyki.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.kuanghao11.cn/Article/details/gtiiazbnpo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hongshengwenyu.top/Article/details/gtvwucebgv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sxryk.cn/Article/details/gtbwuldpsk.html

TS:   // 同上
来源：http://dali.kuanghao11.cn/Article/details/gtcmhqjxbg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jianghu66.top/Article/details/gthtuigtjq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigfzy.top/Article/details/gtouhhtder.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.0kj1m.cn/Article/details/gtxjmwpkqu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xziqi.cn/Article/details/gtwjkvmhjo.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtsgwccpdt.html

G. 面向对象
来源：http://dali.hfpthk.cn/Article/details/gtpyxpgvij.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtaffjwych.html

[G01] 定义类
来源：http://dali.zhixingplan.top/Article/details/gtclnkoldy.html

Py:   class User: pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtbihymnsm.html

PHP:  class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtmmvmfyry.html

JS:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gthlwxfeqv.html

TS:   class User { name: string = ""; }
来源：http://dali.xylfe.cn/Article/details/gtnhokcxfx.html

Java: class User {}
来源：http://dali.shuidangran.top/Article/details/gtkzzwxoja.html

Go:   type User struct { Name string }
来源：http://dali.shangyingyoupin.top/Article/details/gtepixuwkm.html

Ruby: class User; end
来源：http://dali.jianghu66.top/Article/details/gtanbxywwz.html

C#:   class User {}
来源：http://dali.cashguo.top/Article/details/gtqkrfetov.html

[G02] 构造函数
来源：http://dali.jinqigufen.top/Article/details/gtotqpfaon.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhixingplan.top/Article/details/gtcifrvjaw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgufenzy.top/Article/details/gtrqacgmui.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gtmimtlqfn.html

TS:   constructor(public name: string) {}
来源：http://dali.yvedp.cn/Article/details/gtmkjxcgec.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfojownbj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guowangkeji.top/Article/details/gtyuggspie.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gtcjvsfope.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtktucaacx.html

[G03] 实例属性
来源：http://dali.chenlongwang.top/Article/details/gtxvuxtgqb.html

Py:   self.name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtcdblpsgk.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gthnlmzsdh.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtzmapodyp.html

TS:   name: string = "x";
来源：http://dali.xziqi.cn/Article/details/gtyogonves.html

Java: private String name;
来源：http://dali.feifeiyinyue.top/Article/details/gtcpwnbtne.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuanzhike.top/Article/details/gtegryuqtm.html

Ruby: @name = "x"
来源：http://dali.aizwys.cn/Article/details/gtlpbdowtg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.c1oappe.top/Article/details/gtapeafjqb.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gtmpcigewe.html

Py:   def greet(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtqurffzqf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gtkinflkda.html

JS:   greet() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtzahvllqa.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqjcxdkq.html

Java: String greet() { return name; }
来源：http://dali.tanke756.top/Article/details/gttajkcush.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtqnphgthh.html

Ruby: def greet; @name; end
来源：http://dali.ydzc1.top/Article/details/gthvkaqrju.html

C#:   public string Greet() => Name;
来源：http://dali.daxiang520.top/Article/details/gtoqlqtvgk.html

[G05] 继承
来源：http://dali.chenlongwang.top/Article/details/gtkjiyqmgo.html

Py:   class Admin(User): pass
来源：http://dali.jianghu66.top/Article/details/gtjtpjcqdg.html

PHP:  class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtymowbhdb.html

JS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtoopgbgdk.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtmdxibgpb.html

Java: class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtpceyhndn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.meibo888.top/Article/details/gtyjuvjofu.html

Ruby: class Admin < User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtftkmvgic.html

C#:   class Admin : User {}
来源：http://dali.birdmap.top/Article/details/gtxqxyuzzc.html

[G06] 重写方法
来源：http://dali.xinyue.icu/Article/details/gthooksthm.html

Py:   def greet(self): return "admin"
来源：http://dali.gotoacloud.top/Article/details/gtogylkflw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtoytkawup.html

JS:   greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtqcbydlam.html

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvcpwwvsh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtqnkwvbop.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yangfankeji.com/Article/details/gtiqkulwwf.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgfzy.top/Article/details/gtnhmfwyqe.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuanzhike.top/Article/details/gtfiaswfue.html

[G07] 调用父类方法
来源：http://dali.hongshengwenyu.top/Article/details/gtveybfacn.html

Py:   super().greet()
来源：http://dali.snrcjt.cn/Article/details/gtlhcxlust.html

PHP:  parent::greet();
来源：http://dali.gzhubu.top/Article/details/gtpqjcktot.html

JS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtuhrojnsl.html

TS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtbtnnffih.html

Java: super.greet();
来源：http://dali.gzhubu.top/Article/details/gtynnqpubf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fengsongda.top/Article/details/gtbzfncauj.html

Ruby: super
来源：http://dali.zhiwuduotai.top/Article/details/gtsauznjkj.html

C#:   base.Greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtslbtszwm.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfusrvgnx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dashuyun.cn/Article/details/gtafzwfcfs.html

PHP:  public static function f() {}
来源：http://dali.fzhhl.top/Article/details/gtattoitpk.html

JS:   static f() {}
来源：http://dali.svipenyu.cn/Article/details/gtothvgydi.html

TS:   static f(): void {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtceycoxyk.html

Java: static void f() {}
来源：http://dali.haohaochexian.top/Article/details/gtrksbairg.html


<!-- 参考信息 -->