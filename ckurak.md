代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.jianghu66.top/Article/details/gtqmekozgt.html

JS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtypzlxkxb.html

TS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyytcmljs.html

Java: String.join(",", items)
来源：http://dali.cheryme.top/Article/details/gtqihoinwu.html

Go:   strings.Join(items, ",")
来源：http://dali.chenlongwang.top/Article/details/gtxenjvonl.html

Ruby: items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtbnqooupu.html

C#:   string.Join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gthibkjcsl.html

[E09] 去除所有空白字符
来源：http://dali.birdmap.top/Article/details/gthqjorych.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aibaodan.cn/Article/details/gtfrsyvadp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.meibo888.top/Article/details/gtdlpyzjxa.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtjokylxpk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gthsxgmqwr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gtjlixiqoo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhiwuduotai.top/Article/details/gtbenssciz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.316326.xyz/Article/details/gtaiigipcj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shuidangran.top/Article/details/gtxrgwujqx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenzaomai.com/Article/details/gtidvdtxau.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtgynuztyj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xinyue.icu/Article/details/gthbdxcaql.html

JS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtbywmsmbm.html

TS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonspofwg.html

Java: String.format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtuargqfjb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtciepnftf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtprizgqqe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gtuqmsgwbx.html

[E11] 反转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtgahhazks.html

Py:   s[::-1]
来源：http://dali.yueranfly.top/Article/details/gtwvgjrwed.html

PHP:  strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gtdbbwcssl.html

JS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtpujbbktg.html

TS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpustczyh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.bjfxy.top/Article/details/gtwyqczuaa.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daria6918.cn/Article/details/gtronpmxyx.html

Ruby: s.reverse
来源：http://dali.redwolf501.top/Article/details/gtvqinzwge.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gtmyvwhhic.html

[E12] 统计某字符出现次数
来源：http://dali.jyoumei.cn/Article/details/gtpkflitrl.html

Py:   s.count("a")
来源：http://dali.fengsongda.top/Article/details/gtezkjymun.html

PHP:  substr_count($s, "a");
来源：http://dali.chenzaomai.com/Article/details/gtqymypsma.html

JS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gtvcdrldnf.html

TS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gtrtetckjx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigufen.top/Article/details/gtqdaufhts.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxuanxn.top/Article/details/gtmziuvxxv.html

Ruby: s.count("a")
来源：http://dali.xziqi.cn/Article/details/gtoltuawnz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zycfv.cn/Article/details/gtxenrwgey.html

[E13] 逐字符遍历
来源：http://dali.xziqi.cn/Article/details/gtkqhffuzz.html

Py:   for ch in s: print(ch)
来源：http://dali.smart0.xyz/Article/details/gtvndfsers.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuxming.cn/Article/details/gtujblnasl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gtymvubzsj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtaiihuglu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yongpay.top/Article/details/gtmakmiyrd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zycfv.cn/Article/details/gtopvftvaf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hfpthk.cn/Article/details/gtdnnhpilr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cheryme.top/Article/details/gtkyffyrjf.html

[E14] URL 编码与 Base64
来源：http://dali.feifeiyinyue.top/Article/details/gtxzsqbvtd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ivvv.top/Article/details/gtdcxdkwjt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdmzbkqy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.snrcjt.cn/Article/details/gtlwhjxtyp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gtpnasdomh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj202588.top/Article/details/gtcmmobagq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yangfankeji.com/Article/details/gtgxtldboc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sysykeji.top/Article/details/gtsskmpqle.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtxoeoxxun.html

[E15] HTML 转义 / 反转义
来源：http://dali.tanke756.top/Article/details/gtdsznkqps.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gthhkkibfl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ppjwa.cn/Article/details/gtiuouxxmr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cheryme.top/Article/details/gtueixscxd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hammf.cn/Article/details/gtnvlaxjej.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzbnyggy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daria6918.cn/Article/details/gtozvshlcw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cheryme.top/Article/details/gtdvwwkeig.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnxiangtu.top/Article/details/gtxtdsdold.html

[E16] 数字千分位
来源：http://dali.mhx1999.top/Article/details/gthfehjdpk.html

Py:   f"{1234567:,}"
来源：http://dali.hammf.cn/Article/details/gtqfixjvki.html

PHP:  number_format(1234567);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiulacxpv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gtfsbkhfyu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gtlhmpttky.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gtfwvvlzeg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.havefunace.top/Article/details/gtgvhepqzj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.smart0.xyz/Article/details/gtidcqlslb.html

C#:   1234567.ToString("N0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxnckvvn.html

[E17] 首字母大写
来源：http://dali.sysykeji.top/Article/details/gtdauycama.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.smart0.xyz/Article/details/gtrsqayyjz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shzxlz.cn/Article/details/gtvpzsizlm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtnftfpnuj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtrtgrtnze.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yonumen.top/Article/details/gtlgclntcw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xylfe.cn/Article/details/gtuwkbowxg.html

Ruby: s.capitalize
来源：http://dali.daxiang520.top/Article/details/gtfwkmjzzo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenjidiqi.icu/Article/details/gtuvtpdtka.html

[E18] 模板占位符替换
来源：http://dali.jyoumei.cn/Article/details/gtsmncssda.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xylfe.cn/Article/details/gtecxyxpud.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guowangkeji.top/Article/details/gthfipjurb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtcpxgemzs.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtrlyxzpyy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtjcvyppkr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtlxzziofq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yongpay.top/Article/details/gtzvxyzpya.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj202588.top/Article/details/gtlqirqekl.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258.top/Article/details/gtyowipnvx.html

Py:   s.splitlines()
来源：http://dali.hongshengwenyu.top/Article/details/gtbterhetl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sxryk.cn/Article/details/gtwvetmgzq.html

JS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gtcebokfrq.html

TS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gtnefjhozg.html

Java: s.lines().toList()
来源：http://dali.nanxinkj.top/Article/details/gtxtfsbqrb.html

Go:   strings.Split(s, "\n")
来源：http://dali.ydzc1.top/Article/details/gtnvdkkfjx.html

Ruby: s.lines
来源：http://dali.dianchejie.cn/Article/details/gtywqmaepm.html

C#:   s.Split('\n')
来源：http://dali.xuanzx.com/Article/details/gtvbxrvjxm.html

[E20] 判断字符串是否为空
来源：http://dali.yongpay.top/Article/details/gtzbnvtvgk.html

Py:   if not s:
来源：http://dali.tanke756.top/Article/details/gtkpfoajax.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhixingplan.top/Article/details/gtoohgjdbv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuxming.cn/Article/details/gtxglmkfge.html

TS:   if (s === "") {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjngvhsto.html

Java: if (s.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gthmnzfsdj.html

Go:   if s == "" {}
来源：http://dali.hfpthk.cn/Article/details/gtcnfwywks.html

Ruby: if s.empty?
来源：http://dali.9152youxi.cn/Article/details/gtpfmvskpb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yvedp.cn/Article/details/gtjiaotouy.html

[E21] 超长截断加省略号
来源：http://dali.yuxming.cn/Article/details/gtikrgqmda.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxuanxn.top/Article/details/gtjyyftaqg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtwmlvaoqb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtxryatwxc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtfbululoj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtqakyqjcg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhengqikj.top/Article/details/gtdzhjtkyy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtdvcqcqqw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gttymnbwtv.html

[E22] 字节长度与字符长度
来源：http://dali.gotoacloud.top/Article/details/gttanuneyc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtnpbeyeiz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtmrknpthu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtgbrwpeqe.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtccwxcptu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhengqikj.top/Article/details/gtraqgxqbj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangdashe.top/Article/details/gthmdoqtlo.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj202588.top/Article/details/gtbpokydnv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yangfankeji.com/Article/details/gtvdinkopm.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtideqrotd.html

F. 文件与目录
来源：http://dali.sweek.top/Article/details/gtvoiudqbl.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtatzdzyih.html

[F01] 读取整个文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzbtpqqu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxuanxn.top/Article/details/gtktxsizmh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtbpxfszdv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zycfv.cn/Article/details/gtbgcbhrlh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtspwlzxjf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtrbyutvkd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hongshengwenyu.top/Article/details/gtavemscor.html

Ruby: File.read("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtggxwdjtv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gttmsbljjn.html

[F02] 逐行读取文件
来源：http://dali.pycfn.com/Article/details/gtwngxyqec.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sxryk.cn/Article/details/gtxgroflaa.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yvedp.cn/Article/details/gtzvdcdfdr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtzzgyvziq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gtmyctpvdu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gtmnoiojcu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yueranfly.top/Article/details/gtobhmddls.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenjidiqi.icu/Article/details/gtbcvkhrts.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.andypj.xyz/Article/details/gtctoevaol.html

[F03] 写入文件（覆盖）
来源：http://dali.9152youxi.cn/Article/details/gthjynudmt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgufenzy.top/Article/details/gtymrshizq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gtwbxytipl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gthhnbyqcc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtjizneguk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xinyue.icu/Article/details/gttbiqjmho.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj202588.top/Article/details/gtnejrcjld.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gaohongyu789.top/Article/details/gtrdyzbijb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtinzafmok.html

[F04] 追加写入文件
来源：http://dali.zhixingplan.top/Article/details/gtykqftgcf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtrnevtrpp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenjidiqi.icu/Article/details/gtotfcmkxh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gtgthzkecb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gtjliermhu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shzxlz.cn/Article/details/gtiocqbmdl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yvedp.cn/Article/details/gthtgddgbm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.snrcjt.cn/Article/details/gtwcavchof.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwdohwmq.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj202588.top/Article/details/gtxobgezbq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hysaishi.cn/Article/details/gtryisepab.html

PHP:  file_exists("a.txt");
来源：http://dali.cashguo.top/Article/details/gtoxesupqa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtveoqotjx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtjoqybpkv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gttnqhjncu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ybcxt.top/Article/details/gtttnkteyq.html

Ruby: File.exist?("a.txt")
来源：http://dali.tanke756.top/Article/details/gteqxkhbbl.html

C#:   File.Exists("a.txt")
来源：http://dali.yj202588.top/Article/details/gtkiskqaiy.html

[F06] 删除文件
来源：http://dali.feifeiyinyue.top/Article/details/gtxvpqgtfi.html

Py:   os.remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtsjcrdmks.html

PHP:  unlink("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtvqzeojus.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtmkmqzhvh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtpyaziuyw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtvixuyfno.html

Go:   os.Remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gthvacmzjp.html

Ruby: File.delete("a.txt")
来源：http://dali.hammf.cn/Article/details/gtvgjfihkv.html

C#:   File.Delete("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtqmdeavsa.html

[F07] 创建目录（含多级）
来源：http://dali.9152youxi.cn/Article/details/gthruynlcr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gtuolpdhfj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gzhubu.top/Article/details/gtonwcejfs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gtvnnpcodd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gtlwcrehgm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cashguo.top/Article/details/gtclceaddy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yangfankeji.com/Article/details/gtrqnejrla.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nwbrower.top/Article/details/gtlmjbzyar.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hywenlv.cn/Article/details/gtuftcvrcf.html

[F08] 遍历目录
来源：http://dali.zhixingplan.top/Article/details/gtftxycwow.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.smart0.xyz/Article/details/gthmhdtaqa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgfzy.top/Article/details/gtegubjguo.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gterzrfznz.html

TS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtwpcnxwul.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtmincptgj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.redwolf501.top/Article/details/gtnelwicqp.html

Ruby: Dir.children("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtdxwcvtyz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aibaodan.cn/Article/details/gtwwmxivti.html

[F09] 获取文件大小
来源：http://dali.jlsjyb.cn/Article/details/gtwjzopxrb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258.top/Article/details/gtkklrbnck.html

PHP:  filesize("a.txt");
来源：http://dali.ivvv.top/Article/details/gtqhvqctyn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gttieommkl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtaxtladyv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtenlyifjo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fzhhl.top/Article/details/gtjseztupw.html

Ruby: File.size("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtmsjcvkvx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.316326.xyz/Article/details/gthdhfauvi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zdqjudy.top/Article/details/gtfowidmao.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtwkhwkzft.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtxmgyaegg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtwiofnbbe.html

TS:   path.extname("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtrkmdmqcc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnqzz.top/Article/details/gtwcdvkzmw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gttoiewvkd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtwbhwavft.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtmqynctph.html

[F11] 复制与移动文件
来源：http://dali.yanxiufei.cn/Article/details/gtwquzwfhq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gttzjldfoq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.meibo888.top/Article/details/gtygdgealf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtpjvcxcqb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtqvlomynz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yueranfly.top/Article/details/gtiygbqpen.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xziqi.cn/Article/details/gtjpucsqtq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtwsdnvqwt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xylfe.cn/Article/details/gtsjrsrhrs.html

[F12] CSV 读写
来源：http://dali.chenzaomai.com/Article/details/gtbhzcdreu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xziqi.cn/Article/details/gtelintwoe.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yongpay.top/Article/details/gtczexbvac.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenjidiqi.icu/Article/details/gtfyvepnld.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gtrrvvdhml.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.iojbl.cn/Article/details/gtwgeyjemo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tian-w.cn/Article/details/gtfyolpyiy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.mhx1999.top/Article/details/gtmesdstez.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ybcxt.top/Article/details/gtciejgjpl.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtahysqadf.html

G. 面向对象
来源：http://dali.pengpengdd.cyou/Article/details/gtcibfofqp.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtrqofriop.html

[G01] 定义类
来源：http://dali.zhiwuduotai.top/Article/details/gtmiknggga.html

Py:   class User: pass
来源：http://dali.c1oappe.top/Article/details/gtgkmswqij.html

PHP:  class User {}
来源：http://dali.snrcjt.cn/Article/details/gtsqnmmkzn.html

JS:   class User {}
来源：http://dali.fengsongda.top/Article/details/gthuefotdm.html

TS:   class User { name: string = ""; }
来源：http://dali.yueranfly.top/Article/details/gtcflslyvb.html

Java: class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gthzaylwrw.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gtkuuljfbw.html

Ruby: class User; end
来源：http://dali.pengpengdd.cyou/Article/details/gtykfqlphx.html

C#:   class User {}
来源：http://dali.ydzc1.top/Article/details/gtndgjvggs.html

[G02] 构造函数
来源：http://dali.zhengqikj.top/Article/details/gtypdmbpcd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daria6918.cn/Article/details/gtuwhvbhvg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dianchejie.cn/Article/details/gtlwsxtidt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtjmdaomkl.html

TS:   constructor(public name: string) {}
来源：http://dali.aizwys.cn/Article/details/gtugzeqmpe.html

Java: User(String name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtrxlhatxj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cucudq.cn/Article/details/gtbxgwwbjf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuxming.cn/Article/details/gtavaonyrd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtvxwpjvig.html

[G03] 实例属性
来源：http://dali.ydzc1.top/Article/details/gtyrfyhgjh.html

Py:   self.name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtnxjkjnuu.html

PHP:  public string $name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtoncdhqxp.html

JS:   this.name = "x";
来源：http://dali.zdqjudy.top/Article/details/gtuetrldok.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtrccmstwj.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gtclsssrgh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.svipenyu.cn/Article/details/gtyqahathw.html

Ruby: @name = "x"
来源：http://dali.shzxlz.cn/Article/details/gtxedmcghs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yueranfly.top/Article/details/gtpnffjata.html

[G04] 定义方法
来源：http://dali.smart0.xyz/Article/details/gtcnzfloeh.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtwnhtejym.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtruismisu.html

JS:   greet() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtxsfkljqi.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtdrzqbtkp.html

Java: String greet() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtakzpeere.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtvuyomfhr.html

Ruby: def greet; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtiqwjdzed.html

C#:   public string Greet() => Name;
来源：http://dali.aizwys.cn/Article/details/gtbbelnnwg.html

[G05] 继承
来源：http://dali.meibo888.top/Article/details/gtzdoonkfq.html

Py:   class Admin(User): pass
来源：http://dali.jlsjyb.cn/Article/details/gtcrtoneox.html

PHP:  class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtflzifpfr.html

JS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtzznikmrt.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtkhohvkgo.html

Java: class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtojbhjcbu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuanzx.com/Article/details/gtxuewhcvx.html

Ruby: class Admin < User; end
来源：http://dali.havefunace.top/Article/details/gtscnpnqkq.html

C#:   class Admin : User {}
来源：http://dali.jianghu66.top/Article/details/gtqqehxoeh.html

[G06] 重写方法
来源：http://dali.cdnleiting.top/Article/details/gtxqtoxsxg.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgufenzy.top/Article/details/gtknkwrkux.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtgtymysph.html

JS:   greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtbofqoean.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtngacshky.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtakwtflme.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.c1oappe.top/Article/details/gtqimrgjrs.html

Ruby: def greet; "admin"; end
来源：http://dali.svipenyu.cn/Article/details/gtyuvihfrz.html


<!-- 参考信息 -->