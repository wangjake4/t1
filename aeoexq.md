代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gotoacloud.top/Article/details/gt2wjibcfnz.html

TS:   s.split(",")
来源：http://dali.havefunace.top/Article/details/gt2hthnyjsv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xinyue.icu/Article/details/gt2zzxzbcys.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yongpay.top/Article/details/gt2rdyqszom.html

Ruby: s.split(",");  s.split
来源：http://dali.cashguo.top/Article/details/gt2qgawdyfg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sufxvd.cn/Article/details/gt2dzbumire.html

[E08] 数组按分隔符合并
来源：http://dali.zycfv.cn/Article/details/gt2abfzhpic.html

Py:   ",".join(items)
来源：http://dali.tianlin.xyz/Article/details/gt2ybtmaxvr.html

PHP:  implode(",", $items);
来源：http://dali.iojbl.cn/Article/details/gt2hmstrpvh.html

JS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gt2zevdwaut.html

TS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gt2cwrlhnex.html

Java: String.join(",", items)
来源：http://dali.daxiang520.top/Article/details/gt2pgbszwbr.html

Go:   strings.Join(items, ",")
来源：http://dali.sufxvd.cn/Article/details/gt2nfatgxcp.html

Ruby: items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gt2boeucgbs.html

C#:   string.Join(",", items)
来源：http://dali.sweek.top/Article/details/gt2oxpxpmtc.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2drjwjlaj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sweek.top/Article/details/gt2iieymvof.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2tyqxeqnv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gt2esdbaccx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gt2gvvmelyl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gt2xijpzpqj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daxiang520.top/Article/details/gt2efnedxib.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.quarkkingdee.top/Article/details/gt2mrrpwufx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258888.top/Article/details/gt2sdqrgfyv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xylfe.cn/Article/details/gt2duoqtcqh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gt2bvlwpxaa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gogol.net.cn/Article/details/gt2sxxyhpsd.html

JS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gt2wzlzhdmy.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gt2fygvdatw.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bkxnnfnz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gt2ywhbteft.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gt2hhbttbia.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jianghu66.top/Article/details/gt2kppqpbpu.html

[E11] 反转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jhwobloj.html

Py:   s[::-1]
来源：http://dali.gzhubu.top/Article/details/gt2ekjlasuh.html

PHP:  strrev($s);
来源：http://dali.ybcxt.top/Article/details/gt2xrjgboaf.html

JS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gt2izlkmvpi.html

TS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gt2bqwezwdc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenzaomai.com/Article/details/gt2lfyxmiqr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.birdmap.top/Article/details/gt2sbxjbxre.html

Ruby: s.reverse
来源：http://dali.zdqjudy.top/Article/details/gt2kmnzwynr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gt2kzfiddbh.html

[E12] 统计某字符出现次数
来源：http://dali.cheryme.top/Article/details/gt2unhcxasf.html

Py:   s.count("a")
来源：http://dali.mhx1999.top/Article/details/gt2lsxbfppp.html

PHP:  substr_count($s, "a");
来源：http://dali.tanke756.top/Article/details/gt2nxvcoiwf.html

JS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gt2dnahjvws.html

TS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gt2iejlayvw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dianchejie.cn/Article/details/gt2udkctqdl.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxinkj.top/Article/details/gt2bulvaoys.html

Ruby: s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2anababdf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.haohaochexian.top/Article/details/gt2soxctjec.html

[E13] 逐字符遍历
来源：http://dali.yonumen.top/Article/details/gt2hodoqvwi.html

Py:   for ch in s: print(ch)
来源：http://dali.sweek.top/Article/details/gt2jautftcl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgfzy.top/Article/details/gt2fqaoxvek.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.c1oappe.top/Article/details/gt2eidctvdy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gt2ubdlypom.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hsgfnwbz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qeevdsxs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cqqwz.cn/Article/details/gt2sgmstwju.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yujbleft.html

[E14] URL 编码与 Base64
来源：http://dali.guannengcc.top/Article/details/gt2khdfdtqf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yangfankeji.com/Article/details/gt2zlguwqqs.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hysaishi.cn/Article/details/gt2kgjwnzhl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.bjfxy.top/Article/details/gt2acuofyry.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2fbwrkyys.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dianchejie.cn/Article/details/gt2fbobdpey.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cheryme.top/Article/details/gt2ldzzpnjb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zdqjudy.top/Article/details/gt2ddrizpog.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gt2sqtkrkpt.html

[E15] HTML 转义 / 反转义
来源：http://dali.havefunace.top/Article/details/gt2ppbdpael.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cdnleiting.top/Article/details/gt2htihuave.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.havefunace.top/Article/details/gt2dihbwnsf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aizwys.cn/Article/details/gt2fbfnexfz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hysaishi.cn/Article/details/gt2cwdwbtrv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgufenzy.top/Article/details/gt2jfacxfqj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fengsongda.top/Article/details/gt2wtjduuiq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nblwprtu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.birdmap.top/Article/details/gt2npymuzut.html

[E16] 数字千分位
来源：http://dali.shzxlz.cn/Article/details/gt2obddahok.html

Py:   f"{1234567:,}"
来源：http://dali.xziqi.cn/Article/details/gt2dkzdoivv.html

PHP:  number_format(1234567);
来源：http://dali.ydzc1.top/Article/details/gt2usiagpot.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gt2vjfndomh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gt2pvxwisxr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tianlin.xyz/Article/details/gt2saficzki.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rwojtqzv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.andypj.xyz/Article/details/gt2hbxlhfgh.html

C#:   1234567.ToString("N0")
来源：http://dali.ydzc1.top/Article/details/gt2ypoppffc.html

[E17] 首字母大写
来源：http://dali.jqgfzy.top/Article/details/gt2rflpwohi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.316326.xyz/Article/details/gt2liwjloba.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2anppaadh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gt2cywxxrui.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gt2frshamrf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cheryme.top/Article/details/gt2zeoiqgji.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gt2gmoyjcvp.html

Ruby: s.capitalize
来源：http://dali.yj20258.top/Article/details/gt2vjweisxj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yangfankeji.com/Article/details/gt2oxpegxso.html

[E18] 模板占位符替换
来源：http://dali.zhixingplan.top/Article/details/gt2dmzcajgb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.meibo888.top/Article/details/gt2xklyokcm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ivvv.top/Article/details/gt2jubbttnu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gt2ilyiqcdb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gt2watfbnik.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gt2sojjmccp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2eavnkhmq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jianghu66.top/Article/details/gt2xfwgluww.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sufxvd.cn/Article/details/gt2idynlahr.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bmsgnfwy.html

Py:   s.splitlines()
来源：http://dali.hnqzz.top/Article/details/gt2zimuxlkt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2bafnappl.html

JS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gt2iotmkozs.html

TS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gt2wkgfdakh.html

Java: s.lines().toList()
来源：http://dali.jiagoushi.top/Article/details/gt2pysqrjxu.html

Go:   strings.Split(s, "\n")
来源：http://dali.jyoumei.cn/Article/details/gt2naeiscpa.html

Ruby: s.lines
来源：http://dali.wangshuangyany.cn/Article/details/gt2txqasbzk.html

C#:   s.Split('\n')
来源：http://dali.meibo888.top/Article/details/gt2uemgwxow.html

[E20] 判断字符串是否为空
来源：http://dali.yuanzhike.top/Article/details/gt2adbdxyur.html

Py:   if not s:
来源：http://dali.hfpthk.cn/Article/details/gt2fuofnmdo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tanke756.top/Article/details/gt2caxstjyn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2gmzzgmpe.html

TS:   if (s === "") {}
来源：http://dali.guowangkeji.top/Article/details/gt2xogajkcu.html

Java: if (s.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gt2mebueqnl.html

Go:   if s == "" {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vvxaqiiw.html

Ruby: if s.empty?
来源：http://dali.yj20258.top/Article/details/gt2eryruxos.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rjyypual.html

[E21] 超长截断加省略号
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fefrfjjd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cheryme.top/Article/details/gt2snsjqify.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yongpay.top/Article/details/gt2dmihedsl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2zrtbziby.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gt2ctimmovs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gt2dhirnvaz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2faicatmy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2wscwfzrk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2jvxfbzre.html

[E22] 字节长度与字符长度
来源：http://dali.jyoumei.cn/Article/details/gt2wjqbxuyv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cqqwz.cn/Article/details/gt2euysdrog.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gt2cwbprgmm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gt2hyrtzmpv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gt2wlbcsnti.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.havefunace.top/Article/details/gt2ncymgdlv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.smart0.xyz/Article/details/gt2alzhmyzw.html

Ruby: s.bytesize;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xmruucdg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258.top/Article/details/gt2wxvrilbr.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2yewwsejn.html

F. 文件与目录
来源：http://dali.fzhhl.top/Article/details/gt2sbkulvqv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2kkysvldk.html

[F01] 读取整个文件
来源：http://dali.cdnleiting.top/Article/details/gt2yxkhlrva.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xziqi.cn/Article/details/gt2uugtpdph.html

PHP:  file_get_contents("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2wqddksbg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daria6918.cn/Article/details/gt2xcvphznx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gt2ffonrouz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gt2bafnavoo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yonumen.top/Article/details/gt2jmuqaqrv.html

Ruby: File.read("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2fciafpyd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2kyealfgg.html

[F02] 逐行读取文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vzvfsfcl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.mhx1999.top/Article/details/gt2bfjgevuc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.dianchejie.cn/Article/details/gt2jxbatquo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2iisptxfi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gt2sxizmdsl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gt2mvenudii.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xziqi.cn/Article/details/gt2mmntozhh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guannengcc.top/Article/details/gt2tdlkmnyg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.9152youxi.cn/Article/details/gt2fouopzdy.html

[F03] 写入文件（覆盖）
来源：http://dali.316326.xyz/Article/details/gt2qhezbkbd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hongshengwenyu.top/Article/details/gt2eexgthpc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gt2xkryzymq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gt2hsosspoz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lylgztwa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gt2mriwfcbp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangdashe.top/Article/details/gt2pywrqhyt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.smart0.xyz/Article/details/gt2fvrehncj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cgjbkfdk.html

[F04] 追加写入文件
来源：http://dali.yueranfly.top/Article/details/gt2jnxbvtad.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2pcnkbuji.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258.top/Article/details/gt2wipzqvqc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gt2rhkhjqof.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mxzkzrjz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.snrcjt.cn/Article/details/gt2snufolap.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhixingplan.top/Article/details/gt2yybsnjcl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.birdmap.top/Article/details/gt2vwvjylar.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.316326.xyz/Article/details/gt2ubuzzdau.html

[F05] 判断文件或目录是否存在
来源：http://dali.gaohongyu789.top/Article/details/gt2dtxoavri.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhiwuduotai.top/Article/details/gt2jujouosr.html

PHP:  file_exists("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2jsvidbyi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2tcpmtecb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2trlgnmts.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2qxqvhccg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258.top/Article/details/gt2eidwibwp.html

Ruby: File.exist?("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2rozjxmyp.html

C#:   File.Exists("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2cuedfwiq.html

[F06] 删除文件
来源：http://dali.pycfn.com/Article/details/gt2wncrecsf.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2tycxkmrl.html

PHP:  unlink("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2qjvxjcbw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2klufmdku.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2jrlkzara.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2coofujuv.html

Go:   os.Remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2fhifklmh.html

Ruby: File.delete("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2zvkdzpsl.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2kkgfjjge.html

[F07] 创建目录（含多级）
来源：http://dali.aibaodan.cn/Article/details/gt2tslguhcg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gt2xmvvqksg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258.top/Article/details/gt2remcihka.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gt2vocjgcmo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gt2qtyugmuh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xinyue.icu/Article/details/gt2eldytbvm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zxzwmujg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tanke756.top/Article/details/gt2bjzniryf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hfpthk.cn/Article/details/gt2pljgxziy.html

[F08] 遍历目录
来源：http://dali.ybcxt.top/Article/details/gt2pcxpkfqb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sxryk.cn/Article/details/gt2lfgvdzdv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.birdmap.top/Article/details/gt2jylmdhko.html

JS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2fforfsew.html

TS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2wnwvepjt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gt2kcyldbbt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sweek.top/Article/details/gt2kgyjsxym.html

Ruby: Dir.children("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2jphsbnnv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.svipenyu.cn/Article/details/gt2zkkscujr.html

[F09] 获取文件大小
来源：http://dali.hnqzz.top/Article/details/gt2gtribjhh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2zuubnuwk.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zwbymfyd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2amxblpha.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gt2rjhkbvsq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2jwktqzlz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pengpengdd.cyou/Article/details/gt2pgxntgxt.html

Ruby: File.size("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2vqggsajx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj20258888.top/Article/details/gt2byzxzcma.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.9152youxi.cn/Article/details/gt2xjhyadpt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2hznqqken.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2oneuwuza.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2vqwvlwdo.html

TS:   path.extname("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2mrmqiczy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yanxiufei.cn/Article/details/gt2bdvgcecw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ohlkcewn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2qigpnqln.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2blqoctdp.html

[F11] 复制与移动文件
来源：http://dali.jiagoushi.top/Article/details/gt2daljbzob.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2landybdm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nwbrower.top/Article/details/gt2dwzxnqxh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gt2hivztrvl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2imuykkcs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tianlin.xyz/Article/details/gt2caihklru.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gt2gptaobgz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2mqxhqzof.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cdnleiting.top/Article/details/gt2nreqquzo.html

[F12] CSV 读写
来源：http://dali.sufxvd.cn/Article/details/gt2rnpacnsc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sxryk.cn/Article/details/gt2kbhrodah.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sysykeji.top/Article/details/gt2bozzyukd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dianchejie.cn/Article/details/gt2oyczdhso.html

TS:   // 同上
来源：http://dali.hfpthk.cn/Article/details/gt2fevmtyhw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gzhubu.top/Article/details/gt2qcudyqxz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gfvfdvwy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhongyouzk.top/Article/details/gt2lfwaazpj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ppjwa.cn/Article/details/gt2rhvdtdoy.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2ffzmwkar.html

G. 面向对象
来源：http://dali.mhx1999.top/Article/details/gt2gxyhzwdh.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gdgpseqo.html

[G01] 定义类
来源：http://dali.guowangkeji.top/Article/details/gt2bgdhkice.html

Py:   class User: pass
来源：http://dali.sysykeji.top/Article/details/gt2wnfeppos.html

PHP:  class User {}
来源：http://dali.sweek.top/Article/details/gt2agkauqvp.html

JS:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2mmcltkjm.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258888.top/Article/details/gt2cbdhxpws.html

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2ninnenvl.html

Go:   type User struct { Name string }
来源：http://dali.cucudq.cn/Article/details/gt2feazzhoy.html

Ruby: class User; end
来源：http://dali.guowangkeji.top/Article/details/gt2puorukef.html

C#:   class User {}
来源：http://dali.daxiang520.top/Article/details/gt2jgowmipz.html

[G02] 构造函数
来源：http://dali.cheryme.top/Article/details/gt2qklwxfeq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangshuangyany.cn/Article/details/gt2soxprzni.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2mlmdbkiq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dseweket.html

TS:   constructor(public name: string) {}
来源：http://dali.hywenlv.cn/Article/details/gt2lceiqunv.html

Java: User(String name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gt2lttmtbgc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenlongwang.top/Article/details/gt2qyrqwgce.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangdashe.top/Article/details/gt2qgeviipv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tanke756.top/Article/details/gt2wffkbvhm.html

[G03] 实例属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2htpjtkfi.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gt2wsbxiogn.html

PHP:  public string $name = "x";
来源：http://dali.havefunace.top/Article/details/gt2aaexyxnq.html

JS:   this.name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gt2hpwgstqr.html

TS:   name: string = "x";
来源：http://dali.zhixingplan.top/Article/details/gt2ulenzsqm.html

Java: private String name;
来源：http://dali.daria6918.cn/Article/details/gt2beaqhtkk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.meibo888.top/Article/details/gt2qlvrjlsq.html

Ruby: @name = "x"
来源：http://dali.snrcjt.cn/Article/details/gt2bhmkxjvu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jianghu66.top/Article/details/gt2uzlvkfok.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gt2rsirlggq.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258.top/Article/details/gt2zmsxammh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gt2xefaflli.html

JS:   greet() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2reachskq.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gt2yygtzkpy.html

Java: String greet() { return name; }
来源：http://dali.yj202588.top/Article/details/gt2mwmyeyng.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gt2zoibgklo.html

Ruby: def greet; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gt2bafleino.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258888.top/Article/details/gt2uwyvpbse.html

[G05] 继承
来源：http://dali.ivvv.top/Article/details/gt2mrpiwgow.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gt2lavixaet.html

PHP:  class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2blefilts.html

JS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2sdezhgud.html

TS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2txowpcks.html

Java: class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2olqhirdf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pycfn.com/Article/details/gt2tvoarpye.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gt2awuyvlwm.html

C#:   class Admin : User {}
来源：http://dali.tianlin.xyz/Article/details/gt2wlcaehyg.html


<!-- 参考信息 -->