代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.tianlin.xyz/Article/details/gt2bhmgxmvc.html

Ruby: items.join(",")
来源：http://dali.iojbl.cn/Article/details/gt2usfdjnor.html

C#:   string.Join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vedholon.html

[E09] 去除所有空白字符
来源：http://dali.quarkkingdee.top/Article/details/gt2nijoygpy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.316326.xyz/Article/details/gt2cmhllliv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2zllbaemz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ivvv.top/Article/details/gt2mpcehrnp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gt2ttjnmnig.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.andypj.xyz/Article/details/gt2oxdsjkdw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tian-w.cn/Article/details/gt2drauaned.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zycfv.cn/Article/details/gt2qryttcvf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daria6918.cn/Article/details/gt2blfijjvv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sxryk.cn/Article/details/gt2yqsnfhni.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.havefunace.top/Article/details/gt2wdantdsw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xwlwwufk.html

JS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gt2xhdtfyoc.html

TS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gt2ydqvzylm.html

Java: String.format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gt2gjkgphlo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gt2bnoodehb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gt2twjbpbtj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.meibo888.top/Article/details/gt2binobwqo.html

[E11] 反转字符串
来源：http://dali.yuxming.cn/Article/details/gt2ckyqtpbt.html

Py:   s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gt2yfvrlial.html

PHP:  strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iwwlxvjg.html

JS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gt2eqnqhfve.html

TS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2brorfysg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258888.top/Article/details/gt2megqpbhd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jiagoushi.top/Article/details/gt2rdajptdm.html

Ruby: s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2spbvslre.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gt2hikgtofs.html

[E12] 统计某字符出现次数
来源：http://dali.chenlongwang.top/Article/details/gt2lrahqacv.html

Py:   s.count("a")
来源：http://dali.yj202588.top/Article/details/gt2shvjfrmr.html

PHP:  substr_count($s, "a");
来源：http://dali.xuetiantiany.cn/Article/details/gt2qspunjhf.html

JS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gt2gtafmkgu.html

TS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gt2xqrfqhcz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ppjwa.cn/Article/details/gt2istyhxom.html

Go:   strings.Count(s, "a")
来源：http://dali.birdmap.top/Article/details/gt2zfuubezf.html

Ruby: s.count("a")
来源：http://dali.xylfe.cn/Article/details/gt2rslykvow.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nwbrower.top/Article/details/gt2fefdzdmp.html

[E13] 逐字符遍历
来源：http://dali.ppjwa.cn/Article/details/gt2ikhlqmnb.html

Py:   for ch in s: print(ch)
来源：http://dali.gotoacloud.top/Article/details/gt2kecnksbn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lrwgphfm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwlnlda.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pwdembws.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xylfe.cn/Article/details/gt2wszfcijj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guowangkeji.top/Article/details/gt2rmaozckp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yonumen.top/Article/details/gt2cimlbmat.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gt2vrjgwflt.html

[E14] URL 编码与 Base64
来源：http://dali.mhx1999.top/Article/details/gt2ulzgsjkx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuanzhike.top/Article/details/gt2nezxzcst.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ydzc1.top/Article/details/gt2brrnozas.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yvedp.cn/Article/details/gt2wrmtxuvz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cqqwz.cn/Article/details/gt2qproioqq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuxming.cn/Article/details/gt2obzynlzj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tianlin.xyz/Article/details/gt2ioeueayd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.mhx1999.top/Article/details/gt2sahyzrcm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.316326.xyz/Article/details/gt2ztfvuvcm.html

[E15] HTML 转义 / 反转义
来源：http://dali.havefunace.top/Article/details/gt2wzeshiyg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shzxlz.cn/Article/details/gt2rpgicfrm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uzvmtdyn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxinkj.top/Article/details/gt2ianldgvc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ygbpbzdd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhixingplan.top/Article/details/gt2mirkjkvf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eawirrxa.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sdrirlxy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guowangkeji.top/Article/details/gt2cezvfptq.html

[E16] 数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gt2mwyubpmw.html

Py:   f"{1234567:,}"
来源：http://dali.hnxiangtu.top/Article/details/gt2oczmiweh.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wnhtlhjg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gt2kfldwxfq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gt2ivucnioz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dianchejie.cn/Article/details/gt2hybqgyml.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgufenzy.top/Article/details/gt2waamgdrn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yangfankeji.com/Article/details/gt2vuuxiera.html

C#:   1234567.ToString("N0")
来源：http://dali.redwolf501.top/Article/details/gt2sqjunxyz.html

[E17] 首字母大写
来源：http://dali.zhongyouzk.top/Article/details/gt2neleldoh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cdnleiting.top/Article/details/gt2ltqtfnbl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.haohaochexian.top/Article/details/gt2bbzdjcfy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gt2abprkvjx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2gefguajh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2sfugzmlk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yangfankeji.com/Article/details/gt2mwyketyv.html

Ruby: s.capitalize
来源：http://dali.yanxiufei.cn/Article/details/gt2tqtuyvak.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guowangkeji.top/Article/details/gt2pkcatlyu.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbpcyqo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jlsjyb.cn/Article/details/gt2hxdhggsz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aizwys.cn/Article/details/gt2hustevca.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rozqzdyy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gt2apcurkms.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cheryme.top/Article/details/gt2xoeyfkee.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gt2ehtyfich.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jyoumei.cn/Article/details/gt2fknqssmg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xziqi.cn/Article/details/gt2acsinvhv.html

[E19] 多行文本按行拆分
来源：http://dali.xinyue.icu/Article/details/gt2hzcfgjzi.html

Py:   s.splitlines()
来源：http://dali.xylfe.cn/Article/details/gt2yxpszxkq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2sfmymmzh.html

JS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gt2gqzzqzct.html

TS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gt2vvbmhijn.html

Java: s.lines().toList()
来源：http://dali.hfpthk.cn/Article/details/gt2ichuphla.html

Go:   strings.Split(s, "\n")
来源：http://dali.mhx1999.top/Article/details/gt2zxkjyfdf.html

Ruby: s.lines
来源：http://dali.xinyue.icu/Article/details/gt2pfbnvkql.html

C#:   s.Split('\n')
来源：http://dali.wangshuangyany.cn/Article/details/gt2jisjozqb.html

[E20] 判断字符串是否为空
来源：http://dali.nwbrower.top/Article/details/gt2homaquqq.html

Py:   if not s:
来源：http://dali.yanxiufei.cn/Article/details/gt2crndyrnl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jlsjyb.cn/Article/details/gt2ftizpwvp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hywenlv.cn/Article/details/gt2fivgtufz.html

TS:   if (s === "") {}
来源：http://dali.sufxvd.cn/Article/details/gt2mcyakrvt.html

Java: if (s.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gt2svqitbdx.html

Go:   if s == "" {}
来源：http://dali.yj20258888.top/Article/details/gt2apitfhnc.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gt2ehcgjrnl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dianchejie.cn/Article/details/gt2nubxqnmf.html

[E21] 超长截断加省略号
来源：http://dali.iojbl.cn/Article/details/gt2uvkqzlhs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gt2fgmpzjiy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2yeourjhw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2srpdxuqr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2pjznqjgg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2eqmuirfx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gotoacloud.top/Article/details/gt2wfeiufjr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2xqtkesvo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2lvspgjkr.html

[E22] 字节长度与字符长度
来源：http://dali.hammf.cn/Article/details/gt2tngpxpbs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.316326.xyz/Article/details/gt2cuceafwt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqokwbn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gt2ydxsavhb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gt2gipfzpir.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zycfv.cn/Article/details/gt2fhsekyic.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.havefunace.top/Article/details/gt2crvpmbzx.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnqzz.top/Article/details/gt2jvszvpqd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gt2qfkygbbl.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2yuxmfckc.html

F. 文件与目录
来源：http://dali.xziqi.cn/Article/details/gt2anqqngwd.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2xzfrcjjd.html

[F01] 读取整个文件
来源：http://dali.havefunace.top/Article/details/gt2bfacymno.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sigvabvj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2sucntkdt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sxryk.cn/Article/details/gt2dfedpbmq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangdashe.top/Article/details/gt2pjixbyei.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2ejzpqpci.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuanzx.com/Article/details/gt2sdgrpntz.html

Ruby: File.read("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2uilihrot.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2wrlxgvxj.html

[F02] 逐行读取文件
来源：http://dali.smart0.xyz/Article/details/gt2pyqjjite.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuetiantiany.cn/Article/details/gt2addahdid.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ivvv.top/Article/details/gt2jqbxjfla.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gt2imrypcov.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gt2qofypsdy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gt2byhbwrod.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gzhubu.top/Article/details/gt2yscmpmxa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jlsjyb.cn/Article/details/gt2quqkglkb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxinkj.top/Article/details/gt2gvpwjesb.html

[F03] 写入文件（覆盖）
来源：http://dali.ehwqpu.com/Article/details/gt2dniyufps.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigfzy.top/Article/details/gt2yzrovlda.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gt2hkfhllhl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gt2eqdwdlng.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gt2deedzqxo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dianchejie.cn/Article/details/gt2vwmftbur.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guannengcc.top/Article/details/gt2yxyqcmtp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nwbrower.top/Article/details/gt2mfnewdra.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gt2mxcecxql.html

[F04] 追加写入文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2ttoeutlh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.9152youxi.cn/Article/details/gt2ubxhfpoi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cheryme.top/Article/details/gt2nlnkwqrr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gt2nqvqznnl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gt2ycuqwmnh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pycfn.com/Article/details/gt2wtzgflby.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2aqkdzkrm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aibaodan.cn/Article/details/gt2bjgwhrph.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yonumen.top/Article/details/gt2utwjdcnt.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gt2jpllepln.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.vqdsnc.cn/Article/details/gt2dsxscubb.html

PHP:  file_exists("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2aiyqxylc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2ickcezvl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2wgbfebze.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pzajyrqo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuanzhike.top/Article/details/gt2hjvkddrc.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2kizrioyh.html

C#:   File.Exists("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2ebdkxpyo.html

[F06] 删除文件
来源：http://dali.fzhhl.top/Article/details/gt2ffvocbkz.html

Py:   os.remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2ovyhyqeq.html

PHP:  unlink("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2rcwlblio.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2phcqykhh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2amajwihq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gt2oyvnitph.html

Go:   os.Remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2xtrhntqb.html

Ruby: File.delete("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2urlzoliu.html

C#:   File.Delete("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2apawpzhq.html

[F07] 创建目录（含多级）
来源：http://dali.xinyue.icu/Article/details/gt2hgrsfudl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.meibo888.top/Article/details/gt2vifwguvx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ivvv.top/Article/details/gt2sqbrlifm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tlghkncc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gt2epjxcnrh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ycruzoun.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pycfn.com/Article/details/gt2qzanrbwk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxinkj.top/Article/details/gt2xmbkeqca.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guannengcc.top/Article/details/gt2xjefhvwv.html

[F08] 遍历目录
来源：http://dali.yonumen.top/Article/details/gt2qwisezvo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gaohongyu789.top/Article/details/gt2rlrpvhjv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.316326.xyz/Article/details/gt2twsaytvz.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gt2svqoxxxb.html

TS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gt2hzespxvv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gt2smykjddh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.316326.xyz/Article/details/gt2tigwcfyd.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2wystlpcj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2zytutrlx.html

[F09] 获取文件大小
来源：http://dali.tianlin.xyz/Article/details/gt2yjngafke.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2acodofep.html

PHP:  filesize("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2tfgeotaj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gt2gbtizwlz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gt2yhefjqgy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2zbdrdgxf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gt2vdrfxzch.html

Ruby: File.size("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2ghuatyeg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulluxjtx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shangyingyoupin.top/Article/details/gt2txxcdaaq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2qolteadw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2nilclqbz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewjipfvb.html

TS:   path.extname("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2wmztxpop.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yonumen.top/Article/details/gt2fmuujfnf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2gysghehj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2jssqjzhj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2tefeayvo.html

[F11] 复制与移动文件
来源：http://dali.redwolf501.top/Article/details/gt2tnuvbfto.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2kmwrvsau.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2tkmdymmd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wdfssyol.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tdbcutjp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zycfv.cn/Article/details/gt2fqecjicj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhiwuduotai.top/Article/details/gt2eomeudmd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gt2rjnwqrkt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jotmlswc.html

[F12] CSV 读写
来源：http://dali.sufxvd.cn/Article/details/gt2fmjnzfod.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cqqwz.cn/Article/details/gt2lmbcfibu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.redwolf501.top/Article/details/gt2oshsvbfv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.mhx1999.top/Article/details/gt2leltllvg.html

TS:   // 同上
来源：http://dali.fzhhl.top/Article/details/gt2zkqlzevg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.snrcjt.cn/Article/details/gt2duyivrol.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daxiang520.top/Article/details/gt2yviflvne.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cqqwz.cn/Article/details/gt2ncvflrri.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shangyingyoupin.top/Article/details/gt2zmnsicbc.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2rnxaimtc.html

G. 面向对象
来源：http://dali.jianghu66.top/Article/details/gt2ftndotyx.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2pzyuvake.html

[G01] 定义类
来源：http://dali.yueranfly.top/Article/details/gt2fhvmfuce.html

Py:   class User: pass
来源：http://dali.316326.xyz/Article/details/gt2lowyazzb.html

PHP:  class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mzfsckce.html

JS:   class User {}
来源：http://dali.cucudq.cn/Article/details/gt2eqytnttx.html

TS:   class User { name: string = ""; }
来源：http://dali.jianghu66.top/Article/details/gt2ztuqkfak.html

Java: class User {}
来源：http://dali.gzhubu.top/Article/details/gt2auhyvudf.html

Go:   type User struct { Name string }
来源：http://dali.xziqi.cn/Article/details/gt2nidddrww.html

Ruby: class User; end
来源：http://dali.zhoulong.xyz/Article/details/gt2fgkcxafh.html

C#:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2rfzqmgcm.html

[G02] 构造函数
来源：http://dali.smart0.xyz/Article/details/gt2hchkfuxc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jianghu66.top/Article/details/gt2cohcoeko.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangdashe.top/Article/details/gt2fucbcrnz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ptzujdwx.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2mhjhhrzx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wrborhjv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.bjfxy.top/Article/details/gt2xdglgxem.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.kuanghao11.cn/Article/details/gt2rmesjoat.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sysykeji.top/Article/details/gt2whifxxye.html

[G03] 实例属性
来源：http://dali.316326.xyz/Article/details/gt2mzffdrjk.html

Py:   self.name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gt2vtldraaa.html

PHP:  public string $name = "x";
来源：http://dali.chenzaomai.com/Article/details/gt2voumvxte.html

JS:   this.name = "x";
来源：http://dali.haohaochexian.top/Article/details/gt2epsqaxwk.html

TS:   name: string = "x";
来源：http://dali.haohaochexian.top/Article/details/gt2dmunxcmz.html

Java: private String name;
来源：http://dali.chenlongwang.top/Article/details/gt2nltcppij.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sweek.top/Article/details/gt2qwylfrse.html

Ruby: @name = "x"
来源：http://dali.ydzc1.top/Article/details/gt2qejbvwng.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.bjfxy.top/Article/details/gt2ptfydenx.html

[G04] 定义方法
来源：http://dali.zhixingplan.top/Article/details/gt2vgpygkyu.html

Py:   def greet(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gt2thgvmnit.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2ddsvipnl.html

JS:   greet() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gt2wphzgxrw.html

TS:   greet(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gt2ayddumiu.html

Java: String greet() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tnexjfgy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cqjxjeak.html

Ruby: def greet; @name; end
来源：http://dali.nanxinkj.top/Article/details/gt2dqrkieie.html

C#:   public string Greet() => Name;
来源：http://dali.hywenlv.cn/Article/details/gt2ugrguelw.html

[G05] 继承
来源：http://dali.yvedp.cn/Article/details/gt2kijezgda.html

Py:   class Admin(User): pass
来源：http://dali.ybcxt.top/Article/details/gt2evjetvbv.html

PHP:  class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gt2rkzbxcyg.html

JS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2vufdjufw.html

TS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2kshnsoov.html

Java: class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gt2zcggcebk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yongpay.top/Article/details/gt2etdsffja.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gt2gasvsxjw.html

C#:   class Admin : User {}
来源：http://dali.cucudq.cn/Article/details/gt2cgbeoppt.html

[G06] 重写方法
来源：http://dali.cashguo.top/Article/details/gt2fvxlzedg.html

Py:   def greet(self): return "admin"
来源：http://dali.yueranfly.top/Article/details/gt2owkkfjaf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gt2vztuwsvk.html

JS:   greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mawsjvfb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gt2jgmftcsi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2kllaehtj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sxryk.cn/Article/details/gt2czmezfgy.html

Ruby: def greet; "admin"; end
来源：http://dali.mhx1999.top/Article/details/gt2nwwqrqqi.html

C#:   public override string Greet() => "admin";
来源：http://dali.hongshengwenyu.top/Article/details/gt2ebdadpop.html

[G07] 调用父类方法
来源：http://dali.jinqigufen.top/Article/details/gt2lloswftx.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gt2zueqjsel.html

PHP:  parent::greet();
来源：http://dali.sysykeji.top/Article/details/gt2fnmterek.html


<!-- 参考信息 -->