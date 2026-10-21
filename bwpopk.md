代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.yvedp.cn/Article/details/gtlxlexfkh.html

JS:   items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtcqtzegmh.html

TS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtmzayixzh.html

Java: String.join(",", items)
来源：http://dali.havefunace.top/Article/details/gtsxdaoxya.html

Go:   strings.Join(items, ",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnopttvfv.html

Ruby: items.join(",")
来源：http://dali.havefunace.top/Article/details/gtnpootoff.html

C#:   string.Join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gtmkanluqg.html

[E09] 去除所有空白字符
来源：http://dali.sxryk.cn/Article/details/gtehrrxfuf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.snrcjt.cn/Article/details/gtayxeeyqg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.pycfn.com/Article/details/gtxkjognob.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gtliwxcmww.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtitsjybir.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gtnbwljyst.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yueranfly.top/Article/details/gtsthmoxaj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yanxiufei.cn/Article/details/gtzvlvtbga.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gtkbvmbvlh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tanke756.top/Article/details/gtsdsdpmmm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258.top/Article/details/gttljhcgxq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinqigufen.top/Article/details/gttqbdgazz.html

JS:   "7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtllxfbvkl.html

TS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtsqqzkmdc.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtuakclcfk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtmvtrbzcd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtbuvotxhb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guannengcc.top/Article/details/gtunmodcat.html

[E11] 反转字符串
来源：http://dali.meibo888.top/Article/details/gtbvgkvkep.html

Py:   s[::-1]
来源：http://dali.sweek.top/Article/details/gtfqngwkpy.html

PHP:  strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtjigyoivn.html

JS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtqxcwwdrz.html

TS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtorzoclke.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hfpthk.cn/Article/details/gtjtoylnpo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hfpthk.cn/Article/details/gtdpvoqmtn.html

Ruby: s.reverse
来源：http://dali.gotoacloud.top/Article/details/gtvbfyljjv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gtqglmhscb.html

[E12] 统计某字符出现次数
来源：http://dali.fzhhl.top/Article/details/gtduwbunsl.html

Py:   s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gtkgmihiej.html

PHP:  substr_count($s, "a");
来源：http://dali.cheryme.top/Article/details/gtzcozwfsh.html

JS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gttlpyvlsa.html

TS:   s.split("a").length - 1
来源：http://dali.wangshuangyany.cn/Article/details/gtgczgybcv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sufxvd.cn/Article/details/gtecvtuzmi.html

Go:   strings.Count(s, "a")
来源：http://dali.zhixingplan.top/Article/details/gtyszpfjmp.html

Ruby: s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtrwpqupgr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.snrcjt.cn/Article/details/gtfnpxyujs.html

[E13] 逐字符遍历
来源：http://dali.yuxming.cn/Article/details/gtbrefbjcx.html

Py:   for ch in s: print(ch)
来源：http://dali.havefunace.top/Article/details/gtcuglgwnk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xziqi.cn/Article/details/gtjxugkoum.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtzywaemea.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtubfvhfke.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yvedp.cn/Article/details/gtvudkhyba.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yongpay.top/Article/details/gtlogrvvls.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgufenzy.top/Article/details/gtujpnhqce.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtkdnkdact.html

[E14] URL 编码与 Base64
来源：http://dali.aizwys.cn/Article/details/gtudcghllb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shangyingyoupin.top/Article/details/gthrrcuerq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pycfn.com/Article/details/gtgymhuevi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gaohongyu789.top/Article/details/gtlnwepnjo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcihtzlos.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gtlrfkwuxl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yanxiufei.cn/Article/details/gtkswwgbpw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cashguo.top/Article/details/gtgqbyamec.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tian-w.cn/Article/details/gtbndwzhjd.html

[E15] HTML 转义 / 反转义
来源：http://dali.vqdsnc.cn/Article/details/gtjbettgai.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwknnlwfp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hywenlv.cn/Article/details/gtmwzfdgvx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yongpay.top/Article/details/gtrhncadms.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sxryk.cn/Article/details/gtfiitixfu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.kuanghao11.cn/Article/details/gtqexxygat.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenlongwang.top/Article/details/gtyrkdqesv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtjlwxanyw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cqqwz.cn/Article/details/gtlhggtjsa.html

[E16] 数字千分位
来源：http://dali.xuanzx.com/Article/details/gtltkoombe.html

Py:   f"{1234567:,}"
来源：http://dali.yonumen.top/Article/details/gtpsiairzr.html

PHP:  number_format(1234567);
来源：http://dali.jyoumei.cn/Article/details/gthfwohiug.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gtjgooiupi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhixingplan.top/Article/details/gtakyficly.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gtwzafertr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhhtqqon.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yongpay.top/Article/details/gtiyakyzud.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gtztmjzand.html

[E17] 首字母大写
来源：http://dali.hysaishi.cn/Article/details/gtkpowogjm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xinyue.icu/Article/details/gthsgrctvt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daria6918.cn/Article/details/gtpmnsdnhn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gtouhabpzo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gtkhabgphv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hysaishi.cn/Article/details/gtjwkdkoce.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xinyue.icu/Article/details/gtfvxwdltb.html

Ruby: s.capitalize
来源：http://dali.c1oappe.top/Article/details/gtehumehri.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zycfv.cn/Article/details/gttlsbyxzx.html

[E18] 模板占位符替换
来源：http://dali.aibaodan.cn/Article/details/gtjaowxzyc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jyoumei.cn/Article/details/gtxqqhnyih.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.quarkkingdee.top/Article/details/gtllxdrkdb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtatktikqx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtreqyfndg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtclnpjsqf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtafeydftl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ydzc1.top/Article/details/gtqcqyfvtc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuanzx.com/Article/details/gtdrbraetr.html

[E19] 多行文本按行拆分
来源：http://dali.dianchejie.cn/Article/details/gtynazrjoa.html

Py:   s.splitlines()
来源：http://dali.daria6918.cn/Article/details/gtuajsenkc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuanzx.com/Article/details/gttdavzxak.html

JS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gteneyybdx.html

TS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gthmtrxzjq.html

Java: s.lines().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtpxstuxja.html

Go:   strings.Split(s, "\n")
来源：http://dali.zdqjudy.top/Article/details/gtywwwxzbu.html

Ruby: s.lines
来源：http://dali.hnqzz.top/Article/details/gtagfovvwm.html

C#:   s.Split('\n')
来源：http://dali.daria6918.cn/Article/details/gtnaczuvwf.html

[E20] 判断字符串是否为空
来源：http://dali.zdqjudy.top/Article/details/gttzyvkoxh.html

Py:   if not s:
来源：http://dali.tian-w.cn/Article/details/gtgnxtzoik.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pycfn.com/Article/details/gthrstwfui.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cqqwz.cn/Article/details/gttppfbypg.html

TS:   if (s === "") {}
来源：http://dali.jiagoushi.top/Article/details/gtzcbfztog.html

Java: if (s.isEmpty()) {}
来源：http://dali.kuanghao11.cn/Article/details/gtintepxhf.html

Go:   if s == "" {}
来源：http://dali.fengsongda.top/Article/details/gtbdhyulqg.html

Ruby: if s.empty?
来源：http://dali.dashuyun.cn/Article/details/gtuqdbeqgg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hysaishi.cn/Article/details/gtwyfoizhg.html

[E21] 超长截断加省略号
来源：http://dali.zhiwuduotai.top/Article/details/gtykhtrfho.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cqqwz.cn/Article/details/gtbnxrkxvt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gthrvdiqiz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtrlofyrbu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtjfvxtjib.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtmqzkvfdq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrgwfvcm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtnjeskwyu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtxkwjzejx.html

[E22] 字节长度与字符长度
来源：http://dali.9152youxi.cn/Article/details/gtidgxnruv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gaohongyu789.top/Article/details/gtgukkdwgp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpujrtnv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gtcaavfgjw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtqbszqfjh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.iojbl.cn/Article/details/gtummewgue.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sufxvd.cn/Article/details/gtwhxeadzu.html

Ruby: s.bytesize;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtjqwskqzn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtfxddjlcz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtosrffyko.html

F. 文件与目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtioqtxnja.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gthxxlhzxl.html

[F01] 读取整个文件
来源：http://dali.kuanghao11.cn/Article/details/gtbdygcttn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigfzy.top/Article/details/gtwydhjkfp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtfhckunjf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuyiseznr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdymxbkq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtjfqhzclw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ybcxt.top/Article/details/gtkvispmwy.html

Ruby: File.read("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtfyoapuif.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtbgqbhycl.html

[F02] 逐行读取文件
来源：http://dali.sufxvd.cn/Article/details/gtxjnzoasz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmsnbfkdo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tian-w.cn/Article/details/gtbydcynhi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhixingplan.top/Article/details/gttuzowqpv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtnmngegzz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gthbhvvjrj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.smart0.xyz/Article/details/gtynivrxyh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxltatlh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhengqikj.top/Article/details/gttfmxpowh.html

[F03] 写入文件（覆盖）
来源：http://dali.ivvv.top/Article/details/gtztwflowr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cucudq.cn/Article/details/gtjyxmsygk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gtnnqbbmjp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdghqtmso.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pycfn.com/Article/details/gtgerfduqd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dashuyun.cn/Article/details/gtrrndsqdm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbidxpozd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fzhhl.top/Article/details/gtmyamrhcm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakikldua.html

[F04] 追加写入文件
来源：http://dali.jqgufenzy.top/Article/details/gtxhsukzxe.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrkrlrpd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenjidiqi.icu/Article/details/gtsmopehbh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtaiealiwh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtldobccap.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tian-w.cn/Article/details/gtiwyefqyg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tanke756.top/Article/details/gtafuhykoj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ivvv.top/Article/details/gtxlfvtqvk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tanke756.top/Article/details/gtcqqvsfco.html

[F05] 判断文件或目录是否存在
来源：http://dali.smart0.xyz/Article/details/gtkjjkyxrh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvfowwms.html

PHP:  file_exists("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtnnxbphsx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtfnsbocjq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtpngphhbl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtzpkfdosv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.birdmap.top/Article/details/gturgfcwax.html

Ruby: File.exist?("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtufevmrqr.html

C#:   File.Exists("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtcidztsej.html

[F06] 删除文件
来源：http://dali.hammf.cn/Article/details/gtocdsfkko.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtsmqhlyaf.html

PHP:  unlink("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtkubglhsx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtutijzixe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtfwyqikob.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvjqkyjj.html

Go:   os.Remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtvuwqcdsc.html

Ruby: File.delete("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gttsfdrcgn.html

C#:   File.Delete("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtdzxwoglv.html

[F07] 创建目录（含多级）
来源：http://dali.cqqwz.cn/Article/details/gtrbeafegu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.haohaochexian.top/Article/details/gtzjxhufix.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuanzhike.top/Article/details/gthaybpukn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gtktqwdvmt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gtifxkrajg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.mhx1999.top/Article/details/gtfvnpjulk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gtohylrylg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuanzhike.top/Article/details/gtmloudtwh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ydzc1.top/Article/details/gtpkkzuswe.html

[F08] 遍历目录
来源：http://dali.jiagoushi.top/Article/details/gtjvnbjtqc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hysaishi.cn/Article/details/gtndpbiwie.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.meibo888.top/Article/details/gtauyfnhwy.html

JS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtxdjwbbdi.html

TS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtdgqjryiz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gtcssbyzwe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gtqbttegeb.html

Ruby: Dir.children("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtnqesflkd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.meibo888.top/Article/details/gtckxsuhwa.html

[F09] 获取文件大小
来源：http://dali.zhiwuduotai.top/Article/details/gtkwazqolk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtpoxambjj.html

PHP:  filesize("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtbempchxm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gthrgcranq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gtcxwvuxuz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtjpntrtmz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gtlbopjrhm.html

Ruby: File.size("a.txt")
来源：http://dali.ivvv.top/Article/details/gtxbpfbthr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hongshengwenyu.top/Article/details/gtozremxaa.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pengpengdd.cyou/Article/details/gtnglozfoy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtljphnzgb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtsgvunfpd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtrkwniedu.html

TS:   path.extname("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtkjyomado.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmlfjajn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtqwgzvxnb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtqthqcslf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtffxblzej.html

[F11] 复制与移动文件
来源：http://dali.sufxvd.cn/Article/details/gtqkpaoooh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtzcfzbdkk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtuccepxqt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtkbsxrsfm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtarlyvgoh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtdntuieoj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dianchejie.cn/Article/details/gtrjocrtqn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtnlolxfey.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pycfn.com/Article/details/gtughriovr.html

[F12] CSV 读写
来源：http://dali.zhongyouzk.top/Article/details/gtmfwrruik.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.fzhhl.top/Article/details/gtxgteldka.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.havefunace.top/Article/details/gtniwntken.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenlongwang.top/Article/details/gtornpiuge.html

TS:   // 同上
来源：http://dali.yueranfly.top/Article/details/gtlhwqmduc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aibaodan.cn/Article/details/gtxrdwgfed.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ehwqpu.com/Article/details/gtnxriisut.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.316326.xyz/Article/details/gtncjnorlx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.vqdsnc.cn/Article/details/gtgxlxfezx.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtwwpjafeu.html

G. 面向对象
来源：http://dali.gaohongyu789.top/Article/details/gtnhdabqce.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtcbeepqzg.html

[G01] 定义类
来源：http://dali.pycfn.com/Article/details/gtslmfcfac.html

Py:   class User: pass
来源：http://dali.nwbrower.top/Article/details/gtizndypdl.html

PHP:  class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxifadln.html

JS:   class User {}
来源：http://dali.xuanzx.com/Article/details/gtzoirtbew.html

TS:   class User { name: string = ""; }
来源：http://dali.svipenyu.cn/Article/details/gtiarwtobs.html

Java: class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtyqanhlqp.html

Go:   type User struct { Name string }
来源：http://dali.wangdashe.top/Article/details/gtqwzxaxho.html

Ruby: class User; end
来源：http://dali.vqdsnc.cn/Article/details/gtkjoiabwk.html

C#:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gtvtumuwui.html

[G02] 构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtltuhvfpk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tian-w.cn/Article/details/gtqsyxxmgf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gogol.net.cn/Article/details/gtafidlgmc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtwktsnmso.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtxmmkqkhe.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gtagnjtnzq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwppmcsut.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.iojbl.cn/Article/details/gttdgnaeov.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtydgzmhie.html

[G03] 实例属性
来源：http://dali.jianghu66.top/Article/details/gtgwfvgtta.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtjqlwrobz.html

PHP:  public string $name = "x";
来源：http://dali.zdqjudy.top/Article/details/gtttolxido.html

JS:   this.name = "x";
来源：http://dali.chenzaomai.com/Article/details/gtmgrswuaj.html

TS:   name: string = "x";
来源：http://dali.sysykeji.top/Article/details/gticdhwwpf.html

Java: private String name;
来源：http://dali.zhiwuduotai.top/Article/details/gtvrenqzdu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daxiang520.top/Article/details/gtphuowcqz.html

Ruby: @name = "x"
来源：http://dali.guowangkeji.top/Article/details/gtfnbsaxcd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ybcxt.top/Article/details/gtkhxhydgz.html

[G04] 定义方法
来源：http://dali.hammf.cn/Article/details/gtwvubjpas.html

Py:   def greet(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtpfyibvdo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtlmcnjpud.html

JS:   greet() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtwxwsatje.html

TS:   greet(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtwhzzgrgp.html

Java: String greet() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtyqburziu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtuxdbmmlu.html

Ruby: def greet; @name; end
来源：http://dali.redwolf501.top/Article/details/gtrbiogzjy.html

C#:   public string Greet() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtbjslfzjg.html

[G05] 继承
来源：http://dali.ppjwa.cn/Article/details/gthtpluvpl.html

Py:   class Admin(User): pass
来源：http://dali.birdmap.top/Article/details/gtxinczbvy.html

PHP:  class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gteqbtptiz.html

JS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtxjjtjvya.html

TS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtlxxsovom.html

Java: class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtaolgttge.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yueranfly.top/Article/details/gtkhyjpets.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gtqeexewoo.html

C#:   class Admin : User {}
来源：http://dali.meibo888.top/Article/details/gtzjnhmhkd.html

[G06] 重写方法
来源：http://dali.wangdashe.top/Article/details/gtswftesds.html

Py:   def greet(self): return "admin"
来源：http://dali.sweek.top/Article/details/gtjsnequzi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtgyhhphqt.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtcaeuhzya.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtdnvywtki.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtzhxlxhyt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yangfankeji.com/Article/details/gtzsnnuhxg.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gtdjdbhxxt.html


<!-- 参考信息 -->