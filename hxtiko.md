代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.meibo888.top/Article/details/gt2allevhky.html

JS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gt2tfykummb.html

TS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gt2vetduflp.html

Java: String.join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gt2wcrmnlxi.html

Go:   strings.Join(items, ",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nkxmvatz.html

Ruby: items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gt2neonvmfq.html

C#:   string.Join(",", items)
来源：http://dali.hnqzz.top/Article/details/gt2iylhhihm.html

[E09] 去除所有空白字符
来源：http://dali.zycfv.cn/Article/details/gt2hhnrcqjh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zdqjudy.top/Article/details/gt2qzgkhsvc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2jsumfano.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mrmzsnqy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gt2whuiuewv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gt2xmtlojfw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cashguo.top/Article/details/gt2ywdecpdm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yvedp.cn/Article/details/gt2upkxmnal.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yongpay.top/Article/details/gt2xqpwbjka.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuetiantiany.cn/Article/details/gt2fvggugvu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2jtaxjjib.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj202588.top/Article/details/gt2hmpcywjn.html

JS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gt2vwtdxdik.html

TS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gt2lnxjedet.html

Java: String.format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ewtjeauy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gt2gopkzguu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gt2hlxmasbz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gaohongyu789.top/Article/details/gt2vtddaohw.html

[E11] 反转字符串
来源：http://dali.birdmap.top/Article/details/gt2lizhmwpd.html

Py:   s[::-1]
来源：http://dali.cucudq.cn/Article/details/gt2coicgwie.html

PHP:  strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ailalkpt.html

JS:   [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ifmpsobd.html

TS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2vmbrwxkg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hfpthk.cn/Article/details/gt2fzpwpwvy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258888.top/Article/details/gt2mrjitmtb.html

Ruby: s.reverse
来源：http://dali.zhengqikj.top/Article/details/gt2vrkmecta.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gt2jfzrtjrr.html

[E12] 统计某字符出现次数
来源：http://dali.0kj1m.cn/Article/details/gt2owzcuulf.html

Py:   s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gt2czxfrqap.html

PHP:  substr_count($s, "a");
来源：http://dali.xuetiantiany.cn/Article/details/gt2ntdqjntq.html

JS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gt2ubgvaegg.html

TS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gt2onjpdxnu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hammf.cn/Article/details/gt2xgzhghza.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxqnuuu.html

Ruby: s.count("a")
来源：http://dali.jianghu66.top/Article/details/gt2llcazpmr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.haohaochexian.top/Article/details/gt2wqjrljhi.html

[E13] 逐字符遍历
来源：http://dali.yj20258.top/Article/details/gt2jvlklzcr.html

Py:   for ch in s: print(ch)
来源：http://dali.hywenlv.cn/Article/details/gt2tzcqfbmt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gaohongyu789.top/Article/details/gt2pbuvepry.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gt2fmogfpvr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gt2ecbyhiax.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aizwys.cn/Article/details/gt2eovvwacy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zycfv.cn/Article/details/gt2unjodvmv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yanxiufei.cn/Article/details/gt2dnftezda.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hfpthk.cn/Article/details/gt2ccnsaics.html

[E14] URL 编码与 Base64
来源：http://dali.jiagoushi.top/Article/details/gt2rnnboudj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ppjwa.cn/Article/details/gt2oknmvszu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ynxivvqf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jiagoushi.top/Article/details/gt2idtcvhhc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2evjokkgk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hfpthk.cn/Article/details/gt2ifthymdy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pycfn.com/Article/details/gt2vawsaykf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sufxvd.cn/Article/details/gt2jwwbcpge.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzqmixgg.html

[E15] HTML 转义 / 反转义
来源：http://dali.yongpay.top/Article/details/gt2ojvmusgn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2osxxyrvb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.bjfxy.top/Article/details/gt2gronqhwq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cashguo.top/Article/details/gt2svyqgbpb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pengpengdd.cyou/Article/details/gt2rjmzfnxk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgufenzy.top/Article/details/gt2mbfzxfoj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.bjfxy.top/Article/details/gt2tpcqijfn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2ygfcohgj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2bvedkanu.html

[E16] 数字千分位
来源：http://dali.jyoumei.cn/Article/details/gt2rlwjhksz.html

Py:   f"{1234567:,}"
来源：http://dali.vqdsnc.cn/Article/details/gt2aeoltown.html

PHP:  number_format(1234567);
来源：http://dali.fengsongda.top/Article/details/gt2esajceaf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vuhmuuiq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gt2tgcaliml.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gt2gbluqoco.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jdwpgjzu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sxryk.cn/Article/details/gt2miaacvfs.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigfzy.top/Article/details/gt2rkqcggyx.html

[E17] 首字母大写
来源：http://dali.xuetiantiany.cn/Article/details/gt2joquskca.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhongyouzk.top/Article/details/gt2dpfuamgh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jyoumei.cn/Article/details/gt2hegoamuq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2jadfztxq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gt2fquqksgb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zycfv.cn/Article/details/gt2ecxnchvr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.birdmap.top/Article/details/gt2bupntgwi.html

Ruby: s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gt2gvjmeqno.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhengqikj.top/Article/details/gt2zlgpljps.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kgwadwuk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.c1oappe.top/Article/details/gt2kppfxydd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mbnairvl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2etluwqoo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gt2spxshjhz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gt2qddcjhdu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wmpgtqpl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guowangkeji.top/Article/details/gt2pezduhwx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yvedp.cn/Article/details/gt2hafbgowv.html

[E19] 多行文本按行拆分
来源：http://dali.ydzc1.top/Article/details/gt2qulcwdgo.html

Py:   s.splitlines()
来源：http://dali.kuanghao11.cn/Article/details/gt2hvegxnfw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2figsqhvj.html

JS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gt2fbqfrqgd.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2moaowclm.html

Java: s.lines().toList()
来源：http://dali.cucudq.cn/Article/details/gt2jrjjdavf.html

Go:   strings.Split(s, "\n")
来源：http://dali.ehwqpu.com/Article/details/gt2gkhsaece.html

Ruby: s.lines
来源：http://dali.chenzaomai.com/Article/details/gt2tjcgascs.html

C#:   s.Split('\n')
来源：http://dali.gaohongyu789.top/Article/details/gt2joigugjq.html

[E20] 判断字符串是否为空
来源：http://dali.hfpthk.cn/Article/details/gt2flvmffty.html

Py:   if not s:
来源：http://dali.chenzaomai.com/Article/details/gt2hdygdrgf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ppjwa.cn/Article/details/gt2bnnzszuq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gotoacloud.top/Article/details/gt2wfdejevv.html

TS:   if (s === "") {}
来源：http://dali.yj202588.top/Article/details/gt2frrsgeup.html

Java: if (s.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gt2fmokoflo.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uswsgoxe.html

Ruby: if s.empty?
来源：http://dali.zhongyouzk.top/Article/details/gt2mmlvlofg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.iojbl.cn/Article/details/gt2xtncaiox.html

[E21] 超长截断加省略号
来源：http://dali.smart0.xyz/Article/details/gt2iunyhsfe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cucudq.cn/Article/details/gt2wzawzrcm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ohzxzash.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2llkyxcoc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bsblkyio.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2qysjbspt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dashuyun.cn/Article/details/gt2volqwldd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2ysmppsfj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2cohyjswp.html

[E22] 字节长度与字符长度
来源：http://dali.zhengqikj.top/Article/details/gt2cbknnxia.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2vxxyjfcf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gt2qokkmtyx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gogol.net.cn/Article/details/gt2aokkftbm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gt2kztkcqcz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuanzhike.top/Article/details/gt2fqlejeld.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xylfe.cn/Article/details/gt2ughcbxhf.html

Ruby: s.bytesize;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2xwsklliv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gt2zzrymqzc.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2zdpyvsql.html

F. 文件与目录
来源：http://dali.snrcjt.cn/Article/details/gt2lavhcihj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2eumkzkqr.html

[F01] 读取整个文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2rldcoqgn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.snrcjt.cn/Article/details/gt2soyflacx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2tbmjduzv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xylfe.cn/Article/details/gt2ccfeuees.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daxiang520.top/Article/details/gt2hnztijdv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xegkwgtr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangdashe.top/Article/details/gt2tggpllkt.html

Ruby: File.read("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2phetgexb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2ykeypekc.html

[F02] 逐行读取文件
来源：http://dali.xylfe.cn/Article/details/gt2jgbcmzmc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuxming.cn/Article/details/gt2bqdvkhzp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ijyiobdr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gt2tphayenm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pglycwng.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gt2oixdksps.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.9152youxi.cn/Article/details/gt2xcdflpzr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.c1oappe.top/Article/details/gt2baatggur.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj202588.top/Article/details/gt2nvehznmk.html

[F03] 写入文件（覆盖）
来源：http://dali.kuanghao11.cn/Article/details/gt2wppfwgpx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuetiantiany.cn/Article/details/gt2chzdmxlt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fengsongda.top/Article/details/gt2dqlzinwm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2trypxeaf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gt2ugaqtsdg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mdgneadc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuetiantiany.cn/Article/details/gt2izabylre.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zdqjudy.top/Article/details/gt2bbefxsso.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2qwdfufrt.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gt2rqixhpdu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.9152youxi.cn/Article/details/gt2gxdorneg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258888.top/Article/details/gt2dndfclbf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2zlmgmisl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2paepiopw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ivvv.top/Article/details/gt2viidvigu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fzhhl.top/Article/details/gt2dythoaiw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxehkan.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.iojbl.cn/Article/details/gt2jtewkvzt.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gt2jqfswezq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ybcxt.top/Article/details/gt2etwiixjx.html

PHP:  file_exists("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2lezxwytr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2ftllgjol.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2zjaxautd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2baooytpw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gzhubu.top/Article/details/gt2imcotzgz.html

Ruby: File.exist?("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2ueckvtpx.html

C#:   File.Exists("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2pblmujgt.html

[F06] 删除文件
来源：http://dali.andypj.xyz/Article/details/gt2oawpawhe.html

Py:   os.remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2tnwsvssj.html

PHP:  unlink("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2mbcwbguv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2hnjbuolx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2eihdakrz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2qolnlwys.html

Go:   os.Remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2afgpsfru.html

Ruby: File.delete("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2bujykwoz.html

C#:   File.Delete("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2frnpdbyk.html

[F07] 创建目录（含多级）
来源：http://dali.chenjidiqi.icu/Article/details/gt2aazwpefd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.mhx1999.top/Article/details/gt2bkhmqqcw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gt2eelgmdkg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gt2ubuzhdbj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.havefunace.top/Article/details/gt2fqyghpmr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.smart0.xyz/Article/details/gt2ppkrktmx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.9152youxi.cn/Article/details/gt2ixlslzxx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yongpay.top/Article/details/gt2wbrrrchf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2myguipwp.html

[F08] 遍历目录
来源：http://dali.xuanzx.com/Article/details/gt2wepqowks.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pszarlay.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangdashe.top/Article/details/gt2wfvtzckn.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2jlbsthfs.html

TS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2vhpbgpys.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gt2epbykkce.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2dtlogwdp.html

Ruby: Dir.children("dir")
来源：http://dali.fzhhl.top/Article/details/gt2aftvqmwp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2cmeegrgv.html

[F09] 获取文件大小
来源：http://dali.aizwys.cn/Article/details/gt2muhtgpro.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sihmfiau.html

PHP:  filesize("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2feriitci.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gt2ogsfrkci.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gt2lhgkhmfc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gt2qdpszmvn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gogol.net.cn/Article/details/gt2hsoxiovx.html

Ruby: File.size("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2vupkxbuj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.smart0.xyz/Article/details/gt2ghxyuesx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xinyue.icu/Article/details/gt2bauhuhss.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2gridlytc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2dknpukgt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tevzjzue.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2brzkfuiz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fzhhl.top/Article/details/gt2zonncvvj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2ybjbbkrg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2cugykevr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2dapgsiqp.html

[F11] 复制与移动文件
来源：http://dali.tian-w.cn/Article/details/gt2yibmbddd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2ibisydar.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2chqyrqca.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gt2wgwnttkz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gt2ihtibelr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gt2pqijmdmv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daria6918.cn/Article/details/gt2hxlvrirs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2iewhmzzs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guowangkeji.top/Article/details/gt2jtuebejv.html

[F12] CSV 读写
来源：http://dali.ehwqpu.com/Article/details/gt2inxjkclv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sziqsgko.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangdashe.top/Article/details/gt2neixnuur.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgufenzy.top/Article/details/gt2kkbtrqph.html

TS:   // 同上
来源：http://dali.yuxming.cn/Article/details/gt2fqdvvxhc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gt2qxiojpqh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgufenzy.top/Article/details/gt2vishmnag.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gt2urrqdjek.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gzhubu.top/Article/details/gt2pwsnnggq.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2yjwvzgkb.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gt2jersblbs.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2yasjyrrk.html

[G01] 定义类
来源：http://dali.gogol.net.cn/Article/details/gt2ckphxwkz.html

Py:   class User: pass
来源：http://dali.nanxuanxn.top/Article/details/gt2mkvvieru.html

PHP:  class User {}
来源：http://dali.zycfv.cn/Article/details/gt2odlbquhx.html

JS:   class User {}
来源：http://dali.c1oappe.top/Article/details/gt2yldggvnd.html

TS:   class User { name: string = ""; }
来源：http://dali.daria6918.cn/Article/details/gt2yaxqjepa.html

Java: class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2fqqwbizn.html

Go:   type User struct { Name string }
来源：http://dali.cucudq.cn/Article/details/gt2dkedwndt.html

Ruby: class User; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2agaidlzh.html

C#:   class User {}
来源：http://dali.havefunace.top/Article/details/gt2tqlulwaj.html

[G02] 构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2wedljwon.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aizwys.cn/Article/details/gt2lbixfrmh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aizwys.cn/Article/details/gt2gugnkrry.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gt2ifaqfytk.html

TS:   constructor(public name: string) {}
来源：http://dali.316326.xyz/Article/details/gt2qhnzhnkg.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swxstxiq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.birdmap.top/Article/details/gt2ygurutmr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.bjfxy.top/Article/details/gt2irlhkvwm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2jjjmfowx.html

[G03] 实例属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bupzvymd.html

Py:   self.name = "x"
来源：http://dali.guowangkeji.top/Article/details/gt2yhhbgvjw.html

PHP:  public string $name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gt2hhephsmk.html

JS:   this.name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2wpbvvumx.html

TS:   name: string = "x";
来源：http://dali.shzxlz.cn/Article/details/gt2xvfrdcqk.html

Java: private String name;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ordsyiil.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.svipenyu.cn/Article/details/gt2ujextvyi.html

Ruby: @name = "x"
来源：http://dali.tianlin.xyz/Article/details/gt2byiedwli.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.redwolf501.top/Article/details/gt2kdhufwyr.html

[G04] 定义方法
来源：http://dali.nwbrower.top/Article/details/gt2mquecyud.html

Py:   def greet(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gt2qnqpzbvy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gt2dlqclgdd.html

JS:   greet() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2zpjnuzrs.html

TS:   greet(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2cchadhpq.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2udryxifh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gt2qvammxtn.html

Ruby: def greet; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gt2qecyolha.html

C#:   public string Greet() => Name;
来源：http://dali.pycfn.com/Article/details/gt2raexclme.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gt2ppgghaka.html

Py:   class Admin(User): pass
来源：http://dali.yueranfly.top/Article/details/gt2btyijfgt.html

PHP:  class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gt2icgzyfpv.html

JS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gt2ieteqocd.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gt2kkwhkhfg.html

Java: class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2gjxcxnby.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tian-w.cn/Article/details/gt2nlvleqkc.html

Ruby: class Admin < User; end
来源：http://dali.cashguo.top/Article/details/gt2hcdvfonp.html

C#:   class Admin : User {}
来源：http://dali.ehwqpu.com/Article/details/gt2mybkxhlr.html

[G06] 重写方法
来源：http://dali.zhengqikj.top/Article/details/gt2dauqbjzo.html

Py:   def greet(self): return "admin"
来源：http://dali.sufxvd.cn/Article/details/gt2noqqonvz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2guwabtoj.html

JS:   greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gt2pvhochgr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gt2fevtpylg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2veacuafc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.bjfxy.top/Article/details/gt2mbskzcxh.html

Ruby: def greet; "admin"; end
来源：http://dali.zycfv.cn/Article/details/gt2yjelmpre.html


<!-- 参考信息 -->