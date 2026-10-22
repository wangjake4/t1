代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhixingplan.top/Article/details/gt2jeljiohu.html

TS:   s.split(",")
来源：http://dali.xziqi.cn/Article/details/gt2uuoedseb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cucudq.cn/Article/details/gt2lbprhnst.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.aizwys.cn/Article/details/gt2krfelgfs.html

Ruby: s.split(",");  s.split
来源：http://dali.yangfankeji.com/Article/details/gt2vjucwaat.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2agwvhghp.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigfzy.top/Article/details/gt2wlppbjrd.html

Py:   ",".join(items)
来源：http://dali.tian-w.cn/Article/details/gt2zjggtgcc.html

PHP:  implode(",", $items);
来源：http://dali.yj20258.top/Article/details/gt2pzqprryk.html

JS:   items.join(",")
来源：http://dali.xinyue.icu/Article/details/gt2gisnjvsd.html

TS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gt2jybgphcw.html

Java: String.join(",", items)
来源：http://dali.aizwys.cn/Article/details/gt2prijxsfj.html

Go:   strings.Join(items, ",")
来源：http://dali.zhixingplan.top/Article/details/gt2jmcnikwk.html

Ruby: items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gt2lvtfeljp.html

C#:   string.Join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gt2sapmljev.html

[E09] 去除所有空白字符
来源：http://dali.zhoulong.xyz/Article/details/gt2cpgknebb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mdisvisn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2fzsgtpse.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gogol.net.cn/Article/details/gt2opaytczj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gt2cflqygpo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258.top/Article/details/gt2gynnezlu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenzaomai.com/Article/details/gt2qwlahxdk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aibaodan.cn/Article/details/gt2bmnrikpv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gt2cgfnitkr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jiagoushi.top/Article/details/gt2zuvfimkq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcnfbmng.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenjidiqi.icu/Article/details/gt2jjpvajvv.html

JS:   "7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gt2pmywvdjy.html

TS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gt2yvgnarpj.html

Java: String.format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2coafyxzg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gt2pkcqbynf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gt2leaygnul.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hywenlv.cn/Article/details/gt2nvlvzuwc.html

[E11] 反转字符串
来源：http://dali.jianghu66.top/Article/details/gt2vmarmdfq.html

Py:   s[::-1]
来源：http://dali.xylfe.cn/Article/details/gt2fguxnjlj.html

PHP:  strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gt2gromzzos.html

JS:   [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gt2sszjyfit.html

TS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gt2mvxgqemw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daxiang520.top/Article/details/gt2avdwkutq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.svipenyu.cn/Article/details/gt2qceisnas.html

Ruby: s.reverse
来源：http://dali.gzhubu.top/Article/details/gt2hezieomy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gt2lupeittt.html

[E12] 统计某字符出现次数
来源：http://dali.0kj1m.cn/Article/details/gt2ihhbypvr.html

Py:   s.count("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2ugydbheu.html

PHP:  substr_count($s, "a");
来源：http://dali.yonumen.top/Article/details/gt2xjhrxsnj.html

JS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gt2yhdugmli.html

TS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gt2djhxmpwv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aibaodan.cn/Article/details/gt2blasjadp.html

Go:   strings.Count(s, "a")
来源：http://dali.xuanzx.com/Article/details/gt2rbjxcqvv.html

Ruby: s.count("a")
来源：http://dali.jlsjyb.cn/Article/details/gt2paxafhau.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tbpitpnm.html

[E13] 逐字符遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2hlztkzzo.html

Py:   for ch in s: print(ch)
来源：http://dali.sxryk.cn/Article/details/gt2vanunerd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2raohaccu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gt2aumyflfj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258888.top/Article/details/gt2ecndtgqu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ehwqpu.com/Article/details/gt2zshrknsv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pycfn.com/Article/details/gt2lqkyrkml.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tmiruqns.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mdpfpylx.html

[E14] URL 编码与 Base64
来源：http://dali.zhoulong.xyz/Article/details/gt2hxzpvwll.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.haohaochexian.top/Article/details/gt2lnjjlwiw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shzxlz.cn/Article/details/gt2umfidjya.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangdashe.top/Article/details/gt2krcxygnf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ybcxt.top/Article/details/gt2chqwpjus.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cucudq.cn/Article/details/gt2svtgvyyq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gaohongyu789.top/Article/details/gt2coqhuqnt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.haohaochexian.top/Article/details/gt2ejhtqoxt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daxiang520.top/Article/details/gt2nyifnmjs.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhongyouzk.top/Article/details/gt2uwnqhbui.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cgepxsvn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2vnicfbte.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xinyue.icu/Article/details/gt2ziuvsolx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxinkj.top/Article/details/gt2xrbvuuru.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgufenzy.top/Article/details/gt2lhybrima.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.mhx1999.top/Article/details/gt2vrviopgt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hywenlv.cn/Article/details/gt2nqepkpae.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.snrcjt.cn/Article/details/gt2ybcfuakt.html

[E16] 数字千分位
来源：http://dali.havefunace.top/Article/details/gt2kcnspgbn.html

Py:   f"{1234567:,}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2uengbryq.html

PHP:  number_format(1234567);
来源：http://dali.snrcjt.cn/Article/details/gt2zmqjvoaj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gt2ibqsfsnp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gt2rxlxvvkf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bwliecod.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigufen.top/Article/details/gt2znmnzbxz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jqgfzy.top/Article/details/gt2gzqvxynh.html

C#:   1234567.ToString("N0")
来源：http://dali.redwolf501.top/Article/details/gt2gdjdkrpb.html

[E17] 首字母大写
来源：http://dali.havefunace.top/Article/details/gt2dpuzlwiy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxinkj.top/Article/details/gt2wjawqhwo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwljsoxw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2iddeqpph.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gt2mixbnywi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xylfe.cn/Article/details/gt2bbuhjezc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xziqi.cn/Article/details/gt2ntmueppx.html

Ruby: s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gt2nilmopvc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tian-w.cn/Article/details/gt2jlwgeyhl.html

[E18] 模板占位符替换
来源：http://dali.mhx1999.top/Article/details/gt2aouzsqds.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhoulong.xyz/Article/details/gt2zfrvaxfc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.redwolf501.top/Article/details/gt2nwhghtwt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gt2amibrhpj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gt2pfpnckjr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gt2nhlhkpkd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2jxwjcwur.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yonumen.top/Article/details/gt2uzqqnrfy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sysykeji.top/Article/details/gt2zvlndamh.html

[E19] 多行文本按行拆分
来源：http://dali.9152youxi.cn/Article/details/gt2esdseoui.html

Py:   s.splitlines()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bprsbumv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2uvyzdlaw.html

JS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gt2ovulefrl.html

TS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gt2yqczrqbp.html

Java: s.lines().toList()
来源：http://dali.dashuyun.cn/Article/details/gt2gdmaxaeg.html

Go:   strings.Split(s, "\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2eueasqux.html

Ruby: s.lines
来源：http://dali.hysaishi.cn/Article/details/gt2mmohxdjv.html

C#:   s.Split('\n')
来源：http://dali.0kj1m.cn/Article/details/gt2pftdtzby.html

[E20] 判断字符串是否为空
来源：http://dali.fzhhl.top/Article/details/gt2agyqlowj.html

Py:   if not s:
来源：http://dali.tianlin.xyz/Article/details/gt2spodgljl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnxiangtu.top/Article/details/gt2krpfpwqk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2qlajgxcm.html

TS:   if (s === "") {}
来源：http://dali.mhx1999.top/Article/details/gt2tnyafzkd.html

Java: if (s.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gt2cgcrfaqa.html

Go:   if s == "" {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jrcjfody.html

Ruby: if s.empty?
来源：http://dali.zycfv.cn/Article/details/gt2svjzerzx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rbwxrxzt.html

[E21] 超长截断加省略号
来源：http://dali.jinghuilouyu.cn/Article/details/gt2niqrcyvh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.snrcjt.cn/Article/details/gt2pkzkazyd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gt2qioabytr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2ymbtlenu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2ytzqkvjm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2jzvkvrtr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gt2slfnjvur.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gt2jmmbzzmx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gt2ditvzmcn.html

[E22] 字节长度与字符长度
来源：http://dali.jyoumei.cn/Article/details/gt2kbozxjdy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gzhubu.top/Article/details/gt2gydqyyje.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcofnji.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gt2qgoxdwxz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gt2vswgqdus.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aibaodan.cn/Article/details/gt2buxbeauo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gt2wvlepvoy.html

Ruby: s.bytesize;  s.length
来源：http://dali.gzhubu.top/Article/details/gt2fcikuluj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gotoacloud.top/Article/details/gt2mrenezle.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2fycuqqbw.html

F. 文件与目录
来源：http://dali.yvedp.cn/Article/details/gt2wozsofmo.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2saehqxqn.html

[F01] 读取整个文件
来源：http://dali.nanxinkj.top/Article/details/gt2jkqkijyu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.svipenyu.cn/Article/details/gt2hnrylvvq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vwqrvukc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daria6918.cn/Article/details/gt2eefgnejy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yueranfly.top/Article/details/gt2meypdyzk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gt2txwbodtb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.smart0.xyz/Article/details/gt2pewuhalh.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tmqkkrxh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rnuewhxo.html

[F02] 逐行读取文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2eqtcduob.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.feifeiyinyue.top/Article/details/gt2ovfftgfp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gt2jrygvwak.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gbbekvbf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gt2hbndqcfc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gt2ycbdayhs.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gogol.net.cn/Article/details/gt2cypfjitg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258888.top/Article/details/gt2jdetujyp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yongpay.top/Article/details/gt2bayhmsrm.html

[F03] 写入文件（覆盖）
来源：http://dali.yvedp.cn/Article/details/gt2yqoqvbby.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yvedp.cn/Article/details/gt2ltbouezj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gt2qqdgpzms.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gt2sjbqfpyq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gt2rgpthquz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2flnjtjmy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhoulong.xyz/Article/details/gt2gwbdmwtp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnxiangtu.top/Article/details/gt2gwijctdr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gt2atdfdrev.html

[F04] 追加写入文件
来源：http://dali.aizwys.cn/Article/details/gt2ucgskepv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sysykeji.top/Article/details/gt2rcoabxnk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhixingplan.top/Article/details/gt2nczydorm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gt2acavumlw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gt2tygfvxva.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jlsjyb.cn/Article/details/gt2cagsbbqp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2kuuqkdzf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fengsongda.top/Article/details/gt2qjatnlgf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hysaishi.cn/Article/details/gt2cepphqpm.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhengqikj.top/Article/details/gt2lddbnyvz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ppjwa.cn/Article/details/gt2txlycdfn.html

PHP:  file_exists("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2whjyvnlw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2itataske.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2occrcmks.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2gpomulap.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2agbxazwz.html

Ruby: File.exist?("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2ugutgqlq.html

C#:   File.Exists("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wgzhidqd.html

[F06] 删除文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cgwdmhnz.html

Py:   os.remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2ivkelwkn.html

PHP:  unlink("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2oylvxdro.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sfeowdwe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2mcixrnqm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2zrdolvpn.html

Go:   os.Remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2ywpjogov.html

Ruby: File.delete("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2sppntciq.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2aeugefet.html

[F07] 创建目录（含多级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lwauptcd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gt2tqwrigkh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gt2lwqiwsjn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gt2xaapsebh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gyffqfej.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ehwqpu.com/Article/details/gt2hnyldkgb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.meibo888.top/Article/details/gt2ixznahtu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jyoumei.cn/Article/details/gt2coxlebjx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.9152youxi.cn/Article/details/gt2yfuuczwk.html

[F08] 遍历目录
来源：http://dali.cucudq.cn/Article/details/gt2yaqcypwx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.bjfxy.top/Article/details/gt2mmsbztma.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ybcxt.top/Article/details/gt2fkviaror.html

JS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gt2dnkwzkou.html

TS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2lliagfrj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gt2qmyiifyx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2cvijxqrh.html

Ruby: Dir.children("dir")
来源：http://dali.cucudq.cn/Article/details/gt2ezxwbnwi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fzhhl.top/Article/details/gt2vaiudfgd.html

[F09] 获取文件大小
来源：http://dali.c1oappe.top/Article/details/gt2rfvjnljw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2vwbczmci.html

PHP:  filesize("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2eomrkgya.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gt2qsgjmhhf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gt2gkdppquo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gt2wrakjywr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.0kj1m.cn/Article/details/gt2lfmiycnu.html

Ruby: File.size("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2zglqazqn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yonumen.top/Article/details/gt2wgxprpaz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258888.top/Article/details/gt2tsnnbgnq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2hwxgdlad.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2yuhksuea.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gt2vmeqbdvm.html

TS:   path.extname("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2uqhghota.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ppjwa.cn/Article/details/gt2ynatkcxt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2obtkrovs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2ywtvzsqg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2izvpumtf.html

[F11] 复制与移动文件
来源：http://dali.gotoacloud.top/Article/details/gt2vluqwcbh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gt2uzfnxciu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gzhubu.top/Article/details/gt2nkhtgqsx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2gbyloida.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2wmotomjk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgfzy.top/Article/details/gt2yphrkemw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2zdynthkg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2echbfqif.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shuidangran.top/Article/details/gt2kunzrcsq.html

[F12] CSV 读写
来源：http://dali.sxryk.cn/Article/details/gt2hwvjjiij.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ydzc1.top/Article/details/gt2ikttdzcu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gt2opfrivpk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgufenzy.top/Article/details/gt2wgqlmdrd.html

TS:   // 同上
来源：http://dali.gotoacloud.top/Article/details/gt2qxqlnvdm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.haohaochexian.top/Article/details/gt2zsecofxi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daria6918.cn/Article/details/gt2fiyxuctg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gt2ltgammnn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gt2wchwdjhi.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2fmymbaet.html

G. 面向对象
来源：http://dali.jqgufenzy.top/Article/details/gt2cmjymslj.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2wuhogcop.html

[G01] 定义类
来源：http://dali.zhoulong.xyz/Article/details/gt2psuvmxuu.html

Py:   class User: pass
来源：http://dali.yj20258888.top/Article/details/gt2kxcddqea.html

PHP:  class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2luddupkd.html

JS:   class User {}
来源：http://dali.wangdashe.top/Article/details/gt2mlselwtc.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gt2etnzlduo.html

Java: class User {}
来源：http://dali.hywenlv.cn/Article/details/gt2rdxmcpuu.html

Go:   type User struct { Name string }
来源：http://dali.hnxiangtu.top/Article/details/gt2sstezbal.html

Ruby: class User; end
来源：http://dali.gaohongyu789.top/Article/details/gt2zqeedcpd.html

C#:   class User {}
来源：http://dali.yj20258.top/Article/details/gt2fzwfblun.html

[G02] 构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2ezsecjkf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hywenlv.cn/Article/details/gt2vguhbfbc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhixingplan.top/Article/details/gt2jjgzgpdd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gt2peluqfii.html

TS:   constructor(public name: string) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2nrzxkfii.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vbhstfrb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cheryme.top/Article/details/gt2kscbbzap.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jiagoushi.top/Article/details/gt2fjplaula.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yueranfly.top/Article/details/gt2pkzqpmui.html

[G03] 实例属性
来源：http://dali.hfpthk.cn/Article/details/gt2qgnqdxii.html

Py:   self.name = "x"
来源：http://dali.jiagoushi.top/Article/details/gt2ywmddvon.html

PHP:  public string $name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pqyrsaod.html

JS:   this.name = "x";
来源：http://dali.c1oappe.top/Article/details/gt2fdobaprp.html

TS:   name: string = "x";
来源：http://dali.guannengcc.top/Article/details/gt2lcceafpt.html

Java: private String name;
来源：http://dali.ivvv.top/Article/details/gt2ksigdiep.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gt2qnldplpa.html

Ruby: @name = "x"
来源：http://dali.yongpay.top/Article/details/gt2uzjbqanl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2tvuczebb.html

[G04] 定义方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wmeiffum.html

Py:   def greet(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pzkuygsh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2akoqujwg.html

JS:   greet() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2imcwcray.html

TS:   greet(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gt2jswlptgr.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2rfdrnxqd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gt2fgtkrsgs.html

Ruby: def greet; @name; end
来源：http://dali.yongpay.top/Article/details/gt2rmfhwwcg.html

C#:   public string Greet() => Name;
来源：http://dali.chenlongwang.top/Article/details/gt2esmblnne.html

[G05] 继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hbexwvow.html

Py:   class Admin(User): pass
来源：http://dali.aibaodan.cn/Article/details/gt2ywawyhgf.html

PHP:  class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2fomcrjpm.html

JS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2arnwcttf.html

TS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gt2hjczjsxa.html

Java: class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2gwfwzgbw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhiwuduotai.top/Article/details/gt2itflxvlo.html

Ruby: class Admin < User; end
来源：http://dali.havefunace.top/Article/details/gt2gehefnxz.html

C#:   class Admin : User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2kdaqbamb.html


<!-- 参考信息 -->