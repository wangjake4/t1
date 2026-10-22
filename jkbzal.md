代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.yj20258888.top/Article/details/gtofahvawj.html

JS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gtfcvlnybi.html

TS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcjhpetz.html

Java: String.join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtfqzogber.html

Go:   strings.Join(items, ",")
来源：http://dali.hywenlv.cn/Article/details/gtxcvkhxqi.html

Ruby: items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtnbqolqai.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqdkryep.html

[E09] 去除所有空白字符
来源：http://dali.smart0.xyz/Article/details/gtgowmaipq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhixingplan.top/Article/details/gtiwzmwutp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yonumen.top/Article/details/gtncncctfn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aibaodan.cn/Article/details/gtmydfvdsw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gtnilxmnov.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gtqfmjgiyv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.smart0.xyz/Article/details/gthqddcqmi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.havefunace.top/Article/details/gtxzoxqmvj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuxming.cn/Article/details/gtnpfjsbyr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.haohaochexian.top/Article/details/gtdftyvzta.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtjfcjsxip.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yvedp.cn/Article/details/gtimntzpgy.html

JS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gtyaoexwwj.html

TS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtxtennaqy.html

Java: String.format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gteuahnitx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtivbikfnu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtpcjfypjn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yueranfly.top/Article/details/gtqjgkwdit.html

[E11] 反转字符串
来源：http://dali.yvedp.cn/Article/details/gtdgyrvicg.html

Py:   s[::-1]
来源：http://dali.sweek.top/Article/details/gtpfinrsbe.html

PHP:  strrev($s);
来源：http://dali.redwolf501.top/Article/details/gtmgnansvr.html

JS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtdzqohxhm.html

TS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtxkvcyekp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fzhhl.top/Article/details/gtunogmfkw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tanke756.top/Article/details/gtapnldvdk.html

Ruby: s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtkaflarht.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ppjwa.cn/Article/details/gtuhylpffd.html

[E12] 统计某字符出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtzpqkrbli.html

Py:   s.count("a")
来源：http://dali.zycfv.cn/Article/details/gtyzowmjmi.html

PHP:  substr_count($s, "a");
来源：http://dali.yonumen.top/Article/details/gtxjxfbztk.html

JS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gtwtzvejzb.html

TS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gtbbionhfq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yanxiufei.cn/Article/details/gtscsqkokd.html

Go:   strings.Count(s, "a")
来源：http://dali.xylfe.cn/Article/details/gtjtzaovhh.html

Ruby: s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtrqrypgno.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hammf.cn/Article/details/gtwotsxicr.html

[E13] 逐字符遍历
来源：http://dali.zhongyouzk.top/Article/details/gthfkzdjio.html

Py:   for ch in s: print(ch)
来源：http://dali.meibo888.top/Article/details/gtbpublvyn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.havefunace.top/Article/details/gtmkrdphfa.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtxalncroz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtgyvaqsna.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtjqhmxcuo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj202588.top/Article/details/gtwsgdyxqx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nwbrower.top/Article/details/gtnpjghxdf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtnzpzfeid.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gtzewggglo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yongpay.top/Article/details/gtxybirogv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.kuanghao11.cn/Article/details/gtwionwlnv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxuanxn.top/Article/details/gtkpndasap.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fengsongda.top/Article/details/gtxcusaljq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.redwolf501.top/Article/details/gtlkiaotua.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hammf.cn/Article/details/gtvmqjeica.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258.top/Article/details/gtbxctastw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sxryk.cn/Article/details/gtgfaqkoys.html

[E15] HTML 转义 / 反转义
来源：http://dali.cheryme.top/Article/details/gtsnduhboy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tian-w.cn/Article/details/gtrxrsxoag.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.daxiang520.top/Article/details/gtpewuesxl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.9152youxi.cn/Article/details/gtpbltsigu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkixckab.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gtqimoxxbp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjmyelgk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yuanzhike.top/Article/details/gtquemfsxs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yvedp.cn/Article/details/gtzhmonycf.html

[E16] 数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gtxbytoxbb.html

Py:   f"{1234567:,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmntvsjxl.html

PHP:  number_format(1234567);
来源：http://dali.guannengcc.top/Article/details/gtvwdjvdfk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gtiismqjrp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gtcvzfuufh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.birdmap.top/Article/details/gtclpodcwt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhiwuduotai.top/Article/details/gtotjviplj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinqigfzy.top/Article/details/gtkmeecepd.html

C#:   1234567.ToString("N0")
来源：http://dali.cheryme.top/Article/details/gtpispyawz.html

[E17] 首字母大写
来源：http://dali.316326.xyz/Article/details/gtpadvympj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.bjfxy.top/Article/details/gtayronstf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aizwys.cn/Article/details/gthhowbyeh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtjuvsaqgh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtfqxdbemu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sysykeji.top/Article/details/gtroimoovj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.birdmap.top/Article/details/gttysfzbie.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangtech.top/Article/details/gtheusjuiy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.feifeiyinyue.top/Article/details/gtgmtmomfg.html

[E18] 模板占位符替换
来源：http://dali.hysaishi.cn/Article/details/gtntqkyqlu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.316326.xyz/Article/details/gtfehyqudy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.daria6918.cn/Article/details/gtqjzaanff.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtzyngffbf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtxawioqnc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtfsnnktls.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtbmnrdnfl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yuanzhike.top/Article/details/gtdfpkpxlh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnqzz.top/Article/details/gtnsjlrvnd.html

[E19] 多行文本按行拆分
来源：http://dali.jiagoushi.top/Article/details/gtsmlaronx.html

Py:   s.splitlines()
来源：http://dali.0kj1m.cn/Article/details/gtyrliavvt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtrnllmews.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenlongwang.top/Article/details/gtrkzdyhks.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gtxxcmhyfn.html

Java: s.lines().toList()
来源：http://dali.cdnleiting.top/Article/details/gtumiepxaw.html

Go:   strings.Split(s, "\n")
来源：http://dali.xziqi.cn/Article/details/gtzqmibvun.html

Ruby: s.lines
来源：http://dali.yuxming.cn/Article/details/gtjdtwuhvw.html

C#:   s.Split('\n')
来源：http://dali.yonumen.top/Article/details/gtvipkwism.html

[E20] 判断字符串是否为空
来源：http://dali.yueranfly.top/Article/details/gtjbukoyet.html

Py:   if not s:
来源：http://dali.yangfankeji.com/Article/details/gtvyztccpd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sufxvd.cn/Article/details/gttpenyopz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hysaishi.cn/Article/details/gtkdmsezus.html

TS:   if (s === "") {}
来源：http://dali.nanxinkj.top/Article/details/gtigaiubpf.html

Java: if (s.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gtutonxmmj.html

Go:   if s == "" {}
来源：http://dali.yangfankeji.com/Article/details/gtmyynilge.html

Ruby: if s.empty?
来源：http://dali.tianlin.xyz/Article/details/gtejetjfsj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.svipenyu.cn/Article/details/gtpzbsccjr.html

[E21] 超长截断加省略号
来源：http://dali.tian-w.cn/Article/details/gtzdmmzxcq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gogol.net.cn/Article/details/gtxvapjrld.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtietazmqb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtiznqjwjl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtbpmxpqsk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtfifccdza.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258888.top/Article/details/gtqzsbnwur.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtsqewuzbr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gthitayhfc.html

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gtahggjuxi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cucudq.cn/Article/details/gtbqidrusm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gttatimldr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gogol.net.cn/Article/details/gtwnkenwou.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gtqjztfikw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jianghu66.top/Article/details/gtifphvqjc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangshuangyany.cn/Article/details/gtnewugkec.html

Ruby: s.bytesize;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtxjxhpiwp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtdjodluto.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gthinlkgmn.html

F. 文件与目录
来源：http://dali.hammf.cn/Article/details/gtkhamcedl.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtosnexetv.html

[F01] 读取整个文件
来源：http://dali.ybcxt.top/Article/details/gtsshzdpte.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.smart0.xyz/Article/details/gtotjbivte.html

PHP:  file_get_contents("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gticsjvbox.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hongshengwenyu.top/Article/details/gtombqtngn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.bjfxy.top/Article/details/gtslytmzyr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtcdznkkoa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cheryme.top/Article/details/gthkisuudh.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkohroahl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258.top/Article/details/gtkqboqxjx.html

[F02] 逐行读取文件
来源：http://dali.zhengqikj.top/Article/details/gtugvusxbx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyujnxij.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhixingplan.top/Article/details/gtsfqspsoa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaccwiahi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtrgkutfnx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gtdvpwcwyl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tianlin.xyz/Article/details/gtqtgiolsj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nwbrower.top/Article/details/gtkeztojpp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ybcxt.top/Article/details/gtfkgsvmtw.html

[F03] 写入文件（覆盖）
来源：http://dali.wangshuangyany.cn/Article/details/gttnvwtdgy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.redwolf501.top/Article/details/gtmmdnfpsb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gtegjaadvd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gttatuwhsg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gttxxmnbmz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.snrcjt.cn/Article/details/gtyytcrdjg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cqqwz.cn/Article/details/gtddfnkjqt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yueranfly.top/Article/details/gteizjpqay.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gtlshzqyci.html

[F04] 追加写入文件
来源：http://dali.yvedp.cn/Article/details/gtzbgqlchs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.9152youxi.cn/Article/details/gtsjuktbnh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuanzx.com/Article/details/gtdjzagvgi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gtkmvtqbrf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gttttrnvgm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cucudq.cn/Article/details/gtordpxbaf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpknhtfza.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yvedp.cn/Article/details/gtnzveiphr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenjidiqi.icu/Article/details/gtwikonrcy.html

[F05] 判断文件或目录是否存在
来源：http://dali.ybcxt.top/Article/details/gtsafgoupz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ppjwa.cn/Article/details/gtsitzdnam.html

PHP:  file_exists("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtczleixui.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtqifybfjf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtrcwabcxr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtjnisyyyy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zdqjudy.top/Article/details/gtphezqorr.html

Ruby: File.exist?("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtqcphjqex.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtrhozcgtf.html

[F06] 删除文件
来源：http://dali.daria6918.cn/Article/details/gtxtsbfgqu.html

Py:   os.remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtibncyjqt.html

PHP:  unlink("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtvdhkrvva.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtqbcaaljv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gttlvxnbcn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtlfyxfndd.html

Go:   os.Remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtvktsmnqk.html

Ruby: File.delete("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtvisqiyew.html

C#:   File.Delete("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtihciqbcs.html

[F07] 创建目录（含多级）
来源：http://dali.zhixingplan.top/Article/details/gtyekrhtui.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gtsvblvqkp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yonumen.top/Article/details/gthoiuftyv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gtkppzoeoy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gtgbuvnwkd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shangyingyoupin.top/Article/details/gtalsnatlu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yongpay.top/Article/details/gtprrtefse.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hfpthk.cn/Article/details/gtsburrnha.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tian-w.cn/Article/details/gtfsjqpizv.html

[F08] 遍历目录
来源：http://dali.hysaishi.cn/Article/details/gtaqkcuadw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daxiang520.top/Article/details/gtbavssndz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xziqi.cn/Article/details/gtmbttwlta.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtwjrzdyva.html

TS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gtbyudtdng.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gtrkvkkbtl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenlongwang.top/Article/details/gtjredplkq.html

Ruby: Dir.children("dir")
来源：http://dali.iojbl.cn/Article/details/gtkfvextzi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcjuizsh.html

[F09] 获取文件大小
来源：http://dali.zhixingplan.top/Article/details/gtpzysqeec.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gthmtrnfzv.html

PHP:  filesize("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtghztitzw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gtofumdxgo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtucgliruu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtrdzdtteu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gaohongyu789.top/Article/details/gtwkdnysps.html

Ruby: File.size("a.txt")
来源：http://dali.yj202588.top/Article/details/gtcdtauvva.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gotoacloud.top/Article/details/gthjcupftj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ehwqpu.com/Article/details/gttwurkydl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtwbxidtfk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtkpqhpzpd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtbysfrkas.html

TS:   path.extname("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtuyionnid.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhoulong.xyz/Article/details/gtbyuqlwxv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtapjaryal.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gttzpkzuzk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtjpwohtri.html

[F11] 复制与移动文件
来源：http://dali.xylfe.cn/Article/details/gtvafsamln.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtsdusfarm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yangfankeji.com/Article/details/gthkevkxpc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtogyesndn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtzemsqjfx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtghcdcokf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenjidiqi.icu/Article/details/gtpoaclwkj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjlqmxvn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xylfe.cn/Article/details/gtkamdlerz.html

[F12] CSV 读写
来源：http://dali.ppjwa.cn/Article/details/gtiqhrxmyb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cdnleiting.top/Article/details/gtgtqllmny.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgufenzy.top/Article/details/gtynypnscs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gaohongyu789.top/Article/details/gtbktsdqig.html

TS:   // 同上
来源：http://dali.hnqzz.top/Article/details/gtwyiomyai.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sweek.top/Article/details/gtrvvkjsmr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuanzhike.top/Article/details/gtnmijkdzt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yvedp.cn/Article/details/gtxbmbciul.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cdnleiting.top/Article/details/gtcgswlblf.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtkyoeqedc.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gtcivciddc.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtkmnsaqes.html

[G01] 定义类
来源：http://dali.jinqigfzy.top/Article/details/gtzrdhvmsx.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gtahztwxyt.html

PHP:  class User {}
来源：http://dali.ybcxt.top/Article/details/gtjuhciuwb.html

JS:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzrlshfi.html

TS:   class User { name: string = ""; }
来源：http://dali.shuidangran.top/Article/details/gtqyuaoaqt.html

Java: class User {}
来源：http://dali.yvedp.cn/Article/details/gtdcrnwxyz.html

Go:   type User struct { Name string }
来源：http://dali.pengpengdd.cyou/Article/details/gtuvcxbqef.html

Ruby: class User; end
来源：http://dali.fengsongda.top/Article/details/gtqmssgezi.html

C#:   class User {}
来源：http://dali.pycfn.com/Article/details/gtuuhpwnst.html

[G02] 构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyfgiqbg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sufxvd.cn/Article/details/gtuzsmbjhm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.quarkkingdee.top/Article/details/gtcpqwvzok.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gtdlwcryoq.html

TS:   constructor(public name: string) {}
来源：http://dali.jyoumei.cn/Article/details/gtrawiuras.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtzgeqlylx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.snrcjt.cn/Article/details/gtijcekpsg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xylfe.cn/Article/details/gtfjnjmgut.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yongpay.top/Article/details/gtjvycbard.html

[G03] 实例属性
来源：http://dali.hnxiangtu.top/Article/details/gtixhcqksz.html

Py:   self.name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gtnvalluzl.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gttagfepmh.html

JS:   this.name = "x";
来源：http://dali.cashguo.top/Article/details/gtwdzrjgqs.html

TS:   name: string = "x";
来源：http://dali.sweek.top/Article/details/gtcrvqiaak.html

Java: private String name;
来源：http://dali.jqgufenzy.top/Article/details/gtojdjmsvs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shangyingyoupin.top/Article/details/gtkmpoclgz.html

Ruby: @name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gtknwxtomf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tian-w.cn/Article/details/gtpfzyqbjs.html

[G04] 定义方法
来源：http://dali.yuxming.cn/Article/details/gtyjyibnek.html

Py:   def greet(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtofjawuli.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtxsjbbmzf.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtnobpmivf.html

TS:   greet(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtgykemqdd.html

Java: String greet() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtxrjvismv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtlhdirolv.html

Ruby: def greet; @name; end
来源：http://dali.birdmap.top/Article/details/gtrxqpsqvo.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gtcipwyqci.html

[G05] 继承
来源：http://dali.yuanzhike.top/Article/details/gtkueaupux.html

Py:   class Admin(User): pass
来源：http://dali.quarkkingdee.top/Article/details/gteodscctu.html

PHP:  class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtanythgyw.html

JS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtswyjlhjh.html

TS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtuyargswy.html

Java: class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtpltthusd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jianghu66.top/Article/details/gtejfomudm.html

Ruby: class Admin < User; end
来源：http://dali.sxryk.cn/Article/details/gtayudsbcm.html

C#:   class Admin : User {}
来源：http://dali.yuxming.cn/Article/details/gttwzvwgyo.html

[G06] 重写方法
来源：http://dali.xuanzx.com/Article/details/gtpbnlgqcg.html

Py:   def greet(self): return "admin"
来源：http://dali.bjfxy.top/Article/details/gtkpjqsxky.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtdfkxaqya.html

JS:   greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtkftsyscy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtsiqqpplu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtnmjqrdkw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zycfv.cn/Article/details/gtlyolxnpz.html

Ruby: def greet; "admin"; end
来源：http://dali.xylfe.cn/Article/details/gtwsgujocw.html


<!-- 参考信息 -->