代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gt2jydlywiu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhengqikj.top/Article/details/gt2jtmzgczp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guowangkeji.top/Article/details/gt2ngkvunwv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yueranfly.top/Article/details/gt2bqvuosbn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.pycfn.com/Article/details/gt2sagnwfwe.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cghqlkmg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuanzhike.top/Article/details/gt2lygduyth.html

JS:   "7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gt2fkpscykl.html

TS:   "7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gt2bpiwbaos.html

Java: String.format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gt2zsrznrvv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2munzqwnr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gt2ffrydudx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxinkj.top/Article/details/gt2egkibenq.html

[E11] 反转字符串
来源：http://dali.gotoacloud.top/Article/details/gt2edvqovvs.html

Py:   s[::-1]
来源：http://dali.hnqzz.top/Article/details/gt2igstunro.html

PHP:  strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gt2owroivzw.html

JS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2mtwmzdst.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2slykkvla.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2sxtcvety.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnqzz.top/Article/details/gt2rawzfcuz.html

Ruby: s.reverse
来源：http://dali.yj202588.top/Article/details/gt2pgkfscui.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gt2ivzcsgev.html

[E12] 统计某字符出现次数
来源：http://dali.zhixingplan.top/Article/details/gt2xowcltfr.html

Py:   s.count("a")
来源：http://dali.xziqi.cn/Article/details/gt2heoeakko.html

PHP:  substr_count($s, "a");
来源：http://dali.hfpthk.cn/Article/details/gt2mwykhhik.html

JS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gt2xrlgzhrg.html

TS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gt2nuizntta.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258888.top/Article/details/gt2uynvffus.html

Go:   strings.Count(s, "a")
来源：http://dali.cqqwz.cn/Article/details/gt2yzulzhvx.html

Ruby: s.count("a")
来源：http://dali.hfpthk.cn/Article/details/gt2qmorecqo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.vqdsnc.cn/Article/details/gt2zkxwaknj.html

[E13] 逐字符遍历
来源：http://dali.hfpthk.cn/Article/details/gt2yzdgdhew.html

Py:   for ch in s: print(ch)
来源：http://dali.kuanghao11.cn/Article/details/gt2phhaaavv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gogol.net.cn/Article/details/gt2drsxdsaa.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gt2lqrzftid.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gt2ucralwel.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yueranfly.top/Article/details/gt2clxtmwes.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenlongwang.top/Article/details/gt2hdctfclk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenlongwang.top/Article/details/gt2xgqccbya.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sxryk.cn/Article/details/gt2uevrsmml.html

[E14] URL 编码与 Base64
来源：http://dali.hnxiangtu.top/Article/details/gt2jzmjeywr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.feifeiyinyue.top/Article/details/gt2thatmpit.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guannengcc.top/Article/details/gt2ebuqwwwh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yanxiufei.cn/Article/details/gt2gkimksot.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ydzc1.top/Article/details/gt2ukvamgyc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.andypj.xyz/Article/details/gt2gjcvuocs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.iojbl.cn/Article/details/gt2zbbxeklo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.quarkkingdee.top/Article/details/gt2mtzubpti.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jyjylzca.html

[E15] HTML 转义 / 反转义
来源：http://dali.cucudq.cn/Article/details/gt2cmxbagjy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2kxkiifhw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shuidangran.top/Article/details/gt2fuvdrbwb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daria6918.cn/Article/details/gt2jfjzvusa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.haohaochexian.top/Article/details/gt2exeommrc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258.top/Article/details/gt2szrprnwo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnqzz.top/Article/details/gt2npqvlbfa.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xinyue.icu/Article/details/gt2zztogqni.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hkoyrokt.html

[E16] 数字千分位
来源：http://dali.havefunace.top/Article/details/gt2qptmauyc.html

Py:   f"{1234567:,}"
来源：http://dali.sxryk.cn/Article/details/gt2gdiqwisf.html

PHP:  number_format(1234567);
来源：http://dali.bjfxy.top/Article/details/gt2vbmpfrgd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ftehcltj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aryzhirx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yueranfly.top/Article/details/gt2plywghyv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.meibo888.top/Article/details/gt2elpogzpe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hywenlv.cn/Article/details/gt2ukhmnblc.html

C#:   1234567.ToString("N0")
来源：http://dali.dashuyun.cn/Article/details/gt2pjmulpic.html

[E17] 首字母大写
来源：http://dali.hammf.cn/Article/details/gt2uiyathsf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.mhx1999.top/Article/details/gt2xxvjjhyv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.iojbl.cn/Article/details/gt2yjpatfrp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gt2jsrglunh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gt2pfjmvxhx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.andypj.xyz/Article/details/gt2twzvakkr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hammf.cn/Article/details/gt2dgbbxrtf.html

Ruby: s.capitalize
来源：http://dali.cheryme.top/Article/details/gt2heuybkki.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mfiaumuu.html

[E18] 模板占位符替换
来源：http://dali.nanxinkj.top/Article/details/gt2njpybdga.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yueranfly.top/Article/details/gt2gsszodme.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ehwqpu.com/Article/details/gt2rbldymmd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gt2uhltilgv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gt2qoajwffh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gt2evqsxhps.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xylfe.cn/Article/details/gt2gkbcgqep.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zdqjudy.top/Article/details/gt2nhkmrjxp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.mhx1999.top/Article/details/gt2ljczrltc.html

[E19] 多行文本按行拆分
来源：http://dali.yueranfly.top/Article/details/gt2xecmijpi.html

Py:   s.splitlines()
来源：http://dali.sxryk.cn/Article/details/gt2eiejetnx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2lvcfwida.html

JS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gt2kfwgseod.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gt2usnnibfv.html

Java: s.lines().toList()
来源：http://dali.hysaishi.cn/Article/details/gt2oozmobqd.html

Go:   strings.Split(s, "\n")
来源：http://dali.yongpay.top/Article/details/gt2hamdrgot.html

Ruby: s.lines
来源：http://dali.dianchejie.cn/Article/details/gt2ccqlegem.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2kavcmmrx.html

[E20] 判断字符串是否为空
来源：http://dali.chenjidiqi.icu/Article/details/gt2oqalwwjb.html

Py:   if not s:
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wdotixww.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sxryk.cn/Article/details/gt2huemovrz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2mdsxbmqn.html

TS:   if (s === "") {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2xefcwgin.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuanzhike.top/Article/details/gt2arocciyk.html

Go:   if s == "" {}
来源：http://dali.haohaochexian.top/Article/details/gt2jpqzazyk.html

Ruby: if s.empty?
来源：http://dali.birdmap.top/Article/details/gt2luyofsaj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxinkj.top/Article/details/gt2vyieqlzk.html

[E21] 超长截断加省略号
来源：http://dali.xinyue.icu/Article/details/gt2cdhiownu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zycfv.cn/Article/details/gt2swwyedzy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2uctuiszy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2xcezieyl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2anzxfiwi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2snchtmxr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258.top/Article/details/gt2djigsjro.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gt2jspqrcvo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2qsotfrzr.html

[E22] 字节长度与字符长度
来源：http://dali.vqdsnc.cn/Article/details/gt2wmfdlzuq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zycfv.cn/Article/details/gt2heuuibdw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2idqhabkr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gt2lvdydlqp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gt2bnhrqclq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ohpreuyp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kpcgwuxt.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2haemlrbe.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cdnleiting.top/Article/details/gt2ymopcidd.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2tdoazdsq.html

F. 文件与目录
来源：http://dali.cheryme.top/Article/details/gt2drhbwidi.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2tjdcuekc.html

[F01] 读取整个文件
来源：http://dali.dianchejie.cn/Article/details/gt2itnzwplg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zycfv.cn/Article/details/gt2fzaqurve.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2qfyxbwhl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nwbrower.top/Article/details/gt2wqskpbnv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2rbbehcgm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gt2gszvxjmw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.bjfxy.top/Article/details/gt2rpjprhuh.html

Ruby: File.read("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2bkxqbtot.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2ebsjwafg.html

[F02] 逐行读取文件
来源：http://dali.tianlin.xyz/Article/details/gt2azyaztos.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sysykeji.top/Article/details/gt2jpgivpea.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfrkaepx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2utmbwcfo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2qnyrujoa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gt2caxkznnl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eeolrhkw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.havefunace.top/Article/details/gt2ryftbakz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuanzhike.top/Article/details/gt2kvyqksgm.html

[F03] 写入文件（覆盖）
来源：http://dali.quarkkingdee.top/Article/details/gt2qhazkmdf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ybcxt.top/Article/details/gt2fwgdhdxn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gt2dunwllas.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gt2qtnogoeq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.bjfxy.top/Article/details/gt2zjdhvzut.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fjbxeusf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guowangkeji.top/Article/details/gt2zjqadmbg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xziqi.cn/Article/details/gt2raaovpin.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gt2zbupjnpz.html

[F04] 追加写入文件
来源：http://dali.daxiang520.top/Article/details/gt2nulokmqn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jianghu66.top/Article/details/gt2xrqhiurj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.snrcjt.cn/Article/details/gt2rfhzmyqn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gt2hgtnxtyg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gt2dzvzpoak.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aizwys.cn/Article/details/gt2aqtubbsd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hysaishi.cn/Article/details/gt2wthrqycv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fengsongda.top/Article/details/gt2cwdrriym.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shuidangran.top/Article/details/gt2kxbsphlj.html

[F05] 判断文件或目录是否存在
来源：http://dali.guowangkeji.top/Article/details/gt2zigmesxn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdszawbj.html

PHP:  file_exists("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2ekiwptlr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2hovfdgqd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2xtcvshsa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gt2cywmnmru.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhongyouzk.top/Article/details/gt2xdxwynsk.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2fmzqwumt.html

C#:   File.Exists("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2ytknypcg.html

[F06] 删除文件
来源：http://dali.nanxuanxn.top/Article/details/gt2xgwwtsbj.html

Py:   os.remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2abnfqpwq.html

PHP:  unlink("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2txwvvuqi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2vlmhhxfn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ybzxinxr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gt2merzdqju.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2mabjrgdw.html

Ruby: File.delete("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2mhgjdznp.html

C#:   File.Delete("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2rknwfdfa.html

[F07] 创建目录（含多级）
来源：http://dali.gotoacloud.top/Article/details/gt2mdvgbstn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fengsongda.top/Article/details/gt2gycmnaby.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guowangkeji.top/Article/details/gt2kjdsttzt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gt2ulkzucro.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gt2fedijwxs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.snrcjt.cn/Article/details/gt2jdescaky.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yueranfly.top/Article/details/gt2esppenif.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bckbiqmb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shzxlz.cn/Article/details/gt2ejbqzdmd.html

[F08] 遍历目录
来源：http://dali.jyoumei.cn/Article/details/gt2uhgwzunx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnxiangtu.top/Article/details/gt2yjjxlxip.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258888.top/Article/details/gt2awvllyiq.html

JS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gt2rvkcvhun.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2yoanajlx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gt2ptzervxs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbefeqqo.html

Ruby: Dir.children("dir")
来源：http://dali.meibo888.top/Article/details/gt2zwibzmnf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aizwys.cn/Article/details/gt2woeqntdc.html

[F09] 获取文件大小
来源：http://dali.yongpay.top/Article/details/gt2uduhspex.html

Py:   os.path.getsize("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2liiqnbad.html

PHP:  filesize("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ufawwphh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gt2tnnsdvwe.html

TS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gt2yyzospuq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gt2ucmnqwiu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.haohaochexian.top/Article/details/gt2vmxloicy.html

Ruby: File.size("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2sdxkehns.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenlongwang.top/Article/details/gt2jfyzhuig.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.meibo888.top/Article/details/gt2dmscbttz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2gemzjjxs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2ywrdhdkq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2ohaqcmxj.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2mygzwwdn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yueranfly.top/Article/details/gt2oasjvdpu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2ambcsnup.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2sqavwmxv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2bdtxvirb.html

[F11] 复制与移动文件
来源：http://dali.smart0.xyz/Article/details/gt2mfagqjnb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gt2hpyzhdrt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuxming.cn/Article/details/gt2zlkwvztn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2flimmgjx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ljxqzksb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gt2hsxrskyy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.c1oappe.top/Article/details/gt2nwsjrbds.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2silqlbze.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daria6918.cn/Article/details/gt2evefoudt.html

[F12] CSV 读写
来源：http://dali.hnqzz.top/Article/details/gt2ipfvktps.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cheryme.top/Article/details/gt2zsmuivxw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhoulong.xyz/Article/details/gt2smidsgxg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xziqi.cn/Article/details/gt2evyijrks.html

TS:   // 同上
来源：http://dali.fengsongda.top/Article/details/gt2qheicxbe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yvedp.cn/Article/details/gt2kwchaked.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gt2fqnswwqw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigufen.top/Article/details/gt2cjhpecyu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenlongwang.top/Article/details/gt2yntlhcjq.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2dkimolok.html

G. 面向对象
来源：http://dali.zycfv.cn/Article/details/gt2ufryxnso.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2rvdjgrfq.html

[G01] 定义类
来源：http://dali.tian-w.cn/Article/details/gt2wxwoheux.html

Py:   class User: pass
来源：http://dali.xinyue.icu/Article/details/gt2vecksziu.html

PHP:  class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2ylddryub.html

JS:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2mjnfudpe.html

TS:   class User { name: string = ""; }
来源：http://dali.havefunace.top/Article/details/gt2xcezwwyw.html

Java: class User {}
来源：http://dali.xuanzx.com/Article/details/gt2iyepnnbz.html

Go:   type User struct { Name string }
来源：http://dali.yj202588.top/Article/details/gt2gqylfwli.html

Ruby: class User; end
来源：http://dali.gotoacloud.top/Article/details/gt2iacybvkm.html

C#:   class User {}
来源：http://dali.ydzc1.top/Article/details/gt2yhpsfwyd.html

[G02] 构造函数
来源：http://dali.xinyue.icu/Article/details/gt2ocqvcrhq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aibaodan.cn/Article/details/gt2ibgesttc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.smart0.xyz/Article/details/gt2ilpmwqwp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2cucpedjw.html

TS:   constructor(public name: string) {}
来源：http://dali.gotoacloud.top/Article/details/gt2vxiuxgsy.html

Java: User(String name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gt2gofbkmbh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gt2tozcvypc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cucudq.cn/Article/details/gt2mgekfxvw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.9152youxi.cn/Article/details/gt2plwjdpof.html

[G03] 实例属性
来源：http://dali.cashguo.top/Article/details/gt2dmwplkgy.html

Py:   self.name = "x"
来源：http://dali.yueranfly.top/Article/details/gt2pabzpahl.html

PHP:  public string $name = "x";
来源：http://dali.ivvv.top/Article/details/gt2rhcveyhl.html

JS:   this.name = "x";
来源：http://dali.jianghu66.top/Article/details/gt2ovlnnfxn.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gt2anfmnfzk.html

Java: private String name;
来源：http://dali.shangyingyoupin.top/Article/details/gt2rgicnwlw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hysaishi.cn/Article/details/gt2zvasnokx.html

Ruby: @name = "x"
来源：http://dali.guowangkeji.top/Article/details/gt2ifdazfmq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hammf.cn/Article/details/gt2kmfmwepo.html

[G04] 定义方法
来源：http://dali.gzhubu.top/Article/details/gt2wkwgeamz.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gt2jxpgtbcq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ntvbgknx.html

JS:   greet() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gt2oeaitcpo.html

TS:   greet(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gt2emfyxmpz.html

Java: String greet() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2wgaqkcdi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2xrcwbxla.html

Ruby: def greet; @name; end
来源：http://dali.shuidangran.top/Article/details/gt2ukonsvvu.html

C#:   public string Greet() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gt2dtkawedx.html

[G05] 继承
来源：http://dali.bjfxy.top/Article/details/gt2ltbwwldu.html

Py:   class Admin(User): pass
来源：http://dali.kuanghao11.cn/Article/details/gt2ugmnvssp.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2aocqcosl.html

JS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2eqdpstdl.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gt2psxvklqj.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2nfbinxbl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gt2ykeorawp.html

Ruby: class Admin < User; end
来源：http://dali.yj202588.top/Article/details/gt2iatchqcc.html

C#:   class Admin : User {}
来源：http://dali.tanke756.top/Article/details/gt2ucfbtagn.html

[G06] 重写方法
来源：http://dali.chenlongwang.top/Article/details/gt2wynbbdvy.html

Py:   def greet(self): return "admin"
来源：http://dali.chenzaomai.com/Article/details/gt2ztdblzyk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2wqnssqzm.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2jycehgqb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gt2zrnygjwz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nzecmrnu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sweek.top/Article/details/gt2eggvfbcu.html

Ruby: def greet; "admin"; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2widstihs.html

C#:   public override string Greet() => "admin";
来源：http://dali.guannengcc.top/Article/details/gt2ejsqrrqt.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gt2hjzantxs.html

Py:   super().greet()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yvzsggev.html

PHP:  parent::greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zjqfkgdh.html

JS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gt2leerlacx.html

TS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gt2xyowownj.html

Java: super.greet();
来源：http://dali.aizwys.cn/Article/details/gt2rarvoqts.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aibaodan.cn/Article/details/gt2hrkdxiyg.html

Ruby: super
来源：http://dali.gotoacloud.top/Article/details/gt2bqzxxxze.html

C#:   base.Greet();
来源：http://dali.snrcjt.cn/Article/details/gt2xwebxmvs.html

[G08] 静态方法与属性
来源：http://dali.nanxinkj.top/Article/details/gt2attacpns.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fqmpbhhg.html


<!-- 参考信息 -->