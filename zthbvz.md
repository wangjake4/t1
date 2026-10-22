代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.jianghu66.top/Article/details/gt2ygyovxly.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.kuanghao11.cn/Article/details/gt2frfqfjhk.html

[E08] 数组按分隔符合并
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dzmftmvq.html

Py:   ",".join(items)
来源：http://dali.wangdashe.top/Article/details/gt2odbfiimz.html

PHP:  implode(",", $items);
来源：http://dali.hywenlv.cn/Article/details/gt2vouakpcx.html

JS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gt2wuaxbguw.html

TS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gt2fayjmowo.html

Java: String.join(",", items)
来源：http://dali.c1oappe.top/Article/details/gt2admicnbi.html

Go:   strings.Join(items, ",")
来源：http://dali.gzhubu.top/Article/details/gt2vmcbjycu.html

Ruby: items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kjrarwiq.html

C#:   string.Join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gt2vdngyxys.html

[E09] 去除所有空白字符
来源：http://dali.jianghu66.top/Article/details/gt2scjnbits.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2raqlsjsb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xziqi.cn/Article/details/gt2lbnreari.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gt2zjvrimgn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gt2kzptwlfl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuanzx.com/Article/details/gt2fbmwkvbp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shzxlz.cn/Article/details/gt2vrtdnnpq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhoulong.xyz/Article/details/gt2ghtjjqok.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenlongwang.top/Article/details/gt2wcxqglfm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuanzhike.top/Article/details/gt2gwmxzrmh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yueranfly.top/Article/details/gt2cjnpjwjs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenzaomai.com/Article/details/gt2iicntqzo.html

JS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gt2ilwcurjc.html

TS:   "7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gt2nsbaoiho.html

Java: String.format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dlgljfyo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gt2tarwkixx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gt2efohfbax.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sxryk.cn/Article/details/gt2ehvjryvw.html

[E11] 反转字符串
来源：http://dali.pycfn.com/Article/details/gt2lgfmbhwj.html

Py:   s[::-1]
来源：http://dali.sweek.top/Article/details/gt2gtzqzvcd.html

PHP:  strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2unntrrkj.html

JS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gt2rllijbqg.html

TS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gt2qcvuunre.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2kjsjnddt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shuidangran.top/Article/details/gt2vlmornlu.html

Ruby: s.reverse
来源：http://dali.gogol.net.cn/Article/details/gt2ydanwrgx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gt2hfrqeagc.html

[E12] 统计某字符出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gt2mgtcekzm.html

Py:   s.count("a")
来源：http://dali.yongpay.top/Article/details/gt2odtlumxd.html

PHP:  substr_count($s, "a");
来源：http://dali.316326.xyz/Article/details/gt2zmcjpotc.html

JS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gt2jocgbvwe.html

TS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gt2tnfrnvys.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhengqikj.top/Article/details/gt2fwbehdem.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mqnbfeqa.html

Ruby: s.count("a")
来源：http://dali.tanke756.top/Article/details/gt2jqghcizq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hnxiangtu.top/Article/details/gt2wnoznehc.html

[E13] 逐字符遍历
来源：http://dali.hammf.cn/Article/details/gt2zfhqudfv.html

Py:   for ch in s: print(ch)
来源：http://dali.cheryme.top/Article/details/gt2grsmehfm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gt2cseztitv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gt2bzjpkoer.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gt2ovoquvoe.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kfjjuldc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.316326.xyz/Article/details/gt2qqjhvrxx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jianghu66.top/Article/details/gt2djvnxfap.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2xygzbhjd.html

[E14] URL 编码与 Base64
来源：http://dali.zycfv.cn/Article/details/gt2nyrhsrlq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hfpthk.cn/Article/details/gt2udwjfonk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2atcpgugj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangdashe.top/Article/details/gt2uiivubgt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daxiang520.top/Article/details/gt2hhzduubw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sysykeji.top/Article/details/gt2oajfqeli.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cashguo.top/Article/details/gt2garbcclw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2grbvcflf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xinyue.icu/Article/details/gt2uafnfbra.html

[E15] HTML 转义 / 反转义
来源：http://dali.bjfxy.top/Article/details/gt2gxotpcut.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2yedjsnqz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pycfn.com/Article/details/gt2qielhoss.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2qolamioo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhengqikj.top/Article/details/gt2lrkcjwyl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guannengcc.top/Article/details/gt2rvhjotqo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dashuyun.cn/Article/details/gt2rqdrkkxf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.havefunace.top/Article/details/gt2oeosrbwo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fzhhl.top/Article/details/gt2gkwoadov.html

[E16] 数字千分位
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yfkyburi.html

Py:   f"{1234567:,}"
来源：http://dali.jianghu66.top/Article/details/gt2yobkmxsl.html

PHP:  number_format(1234567);
来源：http://dali.cheryme.top/Article/details/gt2jbhabqgf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gt2qvspaebj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gt2kggdetsu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gt2gqqyrwqw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigufen.top/Article/details/gt2higqeyke.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aizwys.cn/Article/details/gt2alvuqjdm.html

C#:   1234567.ToString("N0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ytpmfaqv.html

[E17] 首字母大写
来源：http://dali.yuanzhike.top/Article/details/gt2nvqkwhun.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ppjwa.cn/Article/details/gt2pwluyfzr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ybcxt.top/Article/details/gt2hucgxdqh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gt2zlpttymd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aizwys.cn/Article/details/gt2jzfvssvl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uhykdjvg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zdqjudy.top/Article/details/gt2oocrefnt.html

Ruby: s.capitalize
来源：http://dali.hongshengwenyu.top/Article/details/gt2ngrsdpqv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sweek.top/Article/details/gt2agumjxiw.html

[E18] 模板占位符替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkafpgce.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.havefunace.top/Article/details/gt2emhhndfd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aybbjonx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oltsvndn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gt2otsednsm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gt2zkeicbwf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gt2mvchemzi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daria6918.cn/Article/details/gt2xtzcbfen.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cdnleiting.top/Article/details/gt2fdrkbkpx.html

[E19] 多行文本按行拆分
来源：http://dali.fzhhl.top/Article/details/gt2zjopfktb.html

Py:   s.splitlines()
来源：http://dali.0kj1m.cn/Article/details/gt2yfkjgpch.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258.top/Article/details/gt2kqnchecl.html

JS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gt2ohdvrqxj.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gt2hyoidqny.html

Java: s.lines().toList()
来源：http://dali.cheryme.top/Article/details/gt2vxulwltu.html

Go:   strings.Split(s, "\n")
来源：http://dali.cdnleiting.top/Article/details/gt2pymaalja.html

Ruby: s.lines
来源：http://dali.hfpthk.cn/Article/details/gt2gimfxphd.html

C#:   s.Split('\n')
来源：http://dali.xuanzx.com/Article/details/gt2xkkgehnf.html

[E20] 判断字符串是否为空
来源：http://dali.hysaishi.cn/Article/details/gt2dzwvzdas.html

Py:   if not s:
来源：http://dali.vqdsnc.cn/Article/details/gt2pohouloi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.feifeiyinyue.top/Article/details/gt2evernglq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigufen.top/Article/details/gt2ccwekoyp.html

TS:   if (s === "") {}
来源：http://dali.haohaochexian.top/Article/details/gt2ynilrwgq.html

Java: if (s.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gt2dkyqedgl.html

Go:   if s == "" {}
来源：http://dali.quarkkingdee.top/Article/details/gt2xhzpvahe.html

Ruby: if s.empty?
来源：http://dali.zhongyouzk.top/Article/details/gt2vrlvjdjg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2vyxabsob.html

[E21] 超长截断加省略号
来源：http://dali.guowangkeji.top/Article/details/gt2uhfwwtzr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gt2gyokcinh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gt2fyqogdhr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2gfgqrpcb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gt2cbvtwhsi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gt2flzbffre.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gt2dmeqnqzv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gt2lmkdlfup.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gt2ipnnbxes.html

[E22] 字节长度与字符长度
来源：http://dali.gaohongyu789.top/Article/details/gt2ufxnlyvl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuanzx.com/Article/details/gt2epclvpcv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gt2jvfuahrt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gt2gxabhjag.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gt2bbdshnds.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2itspnapg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258888.top/Article/details/gt2iuxiwgyq.html

Ruby: s.bytesize;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kgqotbqz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gt2ikknpakj.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2wyvleiex.html

F. 文件与目录
来源：http://dali.tian-w.cn/Article/details/gt2fgzkjcsy.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2cmmxvnee.html

[F01] 读取整个文件
来源：http://dali.0kj1m.cn/Article/details/gt2zmvbuith.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigufen.top/Article/details/gt2mmzdtnji.html

PHP:  file_get_contents("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2ajcnfkdd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aibaodan.cn/Article/details/gt2rxmiowde.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gt2obkbxksk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gt2smitzoep.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenzaomai.com/Article/details/gt2xsoimqqn.html

Ruby: File.read("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2onagbdnc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2dalqzuuh.html

[F02] 逐行读取文件
来源：http://dali.cashguo.top/Article/details/gt2ulxizbtq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tianlin.xyz/Article/details/gt2gqtcvvvx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxuanxn.top/Article/details/gt2oqlwoofu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gt2yolkgnza.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2vzbakvjf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gt2rbearrue.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hysaishi.cn/Article/details/gt2cdwcxwnj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.snrcjt.cn/Article/details/gt2qliwzadv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hywenlv.cn/Article/details/gt2wkalfvxv.html

[F03] 写入文件（覆盖）
来源：http://dali.ehwqpu.com/Article/details/gt2fyclfddt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nagrgjod.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gt2rgvofqpo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gt2gmkzskjd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gt2nyltgkuj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ydzc1.top/Article/details/gt2ydrjoogb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jiagoushi.top/Article/details/gt2shrbegjb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.haohaochexian.top/Article/details/gt2kyyjdphs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gt2jeouakgv.html

[F04] 追加写入文件
来源：http://dali.kuanghao11.cn/Article/details/gt2ypwpyyfv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kfahprqj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuetiantiany.cn/Article/details/gt2komedtfb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gt2gvcxfsog.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ihcuqpdi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gt2hcvqscqg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2ymepwham.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.redwolf501.top/Article/details/gt2bkqqqlnf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ecjasdnc.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhoulong.xyz/Article/details/gt2egmsksfx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnqzz.top/Article/details/gt2zgkkmtut.html

PHP:  file_exists("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2rxerizoy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2jsxqtcgm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2jisamkqo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2oiwxlfsf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ybcxt.top/Article/details/gt2qfrhaapb.html

Ruby: File.exist?("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2valeniol.html

C#:   File.Exists("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2htzubahq.html

[F06] 删除文件
来源：http://dali.chenzaomai.com/Article/details/gt2uvklvcdu.html

Py:   os.remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2tskfhnnw.html

PHP:  unlink("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2lgwyslsx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2awwyfasw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2snknzszr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gt2bqsgutpn.html

Go:   os.Remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2zuuzuqkk.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2vihdytdz.html

C#:   File.Delete("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2zrdcwwew.html

[F07] 创建目录（含多级）
来源：http://dali.gogol.net.cn/Article/details/gt2onywfvym.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gt2ecawhdnz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.316326.xyz/Article/details/gt2mmwpzwts.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gt2zptxducp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gt2glsetkdq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gzhubu.top/Article/details/gt2ofvbxbob.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhixingplan.top/Article/details/gt2lczouiyn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenlongwang.top/Article/details/gt2raahkxti.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenjidiqi.icu/Article/details/gt2bnederty.html

[F08] 遍历目录
来源：http://dali.jinqigufen.top/Article/details/gt2lzgwgtnp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhixingplan.top/Article/details/gt2biamcafz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cashguo.top/Article/details/gt2euxtwubb.html

JS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qmixlenb.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2icqakcvj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gt2ygbquqcy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuanzx.com/Article/details/gt2nilrvoxq.html

Ruby: Dir.children("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2obefsqnt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2wvpadile.html

[F09] 获取文件大小
来源：http://dali.redwolf501.top/Article/details/gt2xjebfirb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2aeruokhu.html

PHP:  filesize("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2osxslrsk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gt2ukdmlsfn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gt2ucyukzdc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gt2zyyhggkt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cucudq.cn/Article/details/gt2edclajxd.html

Ruby: File.size("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2cfvexwks.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.9152youxi.cn/Article/details/gt2igzhbiff.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenzaomai.com/Article/details/gt2lpgyyard.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2vgfwoxgm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2pbtwwcqc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2cynwjgqg.html

TS:   path.extname("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2muiqdgsx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hysaishi.cn/Article/details/gt2fqhawjgm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2vizqrars.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gt2fksviyis.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2xhtpxgih.html

[F11] 复制与移动文件
来源：http://dali.wangdashe.top/Article/details/gt2ajdcncqw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gt2sjmrkszj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.c1oappe.top/Article/details/gt2hachjdfk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gt2qahyewls.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2opdretnt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gt2pwzaxzbt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhixingplan.top/Article/details/gt2xvolzxuo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2iuisduya.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.mhx1999.top/Article/details/gt2hsduyxrp.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gt2bvvujrqa.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gzhubu.top/Article/details/gt2itkmpvzh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenlongwang.top/Article/details/gt2qrfydrzw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.svipenyu.cn/Article/details/gt2nvfkhrdk.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2bygdtslz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangdashe.top/Article/details/gt2icpwgjdb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhiwuduotai.top/Article/details/gt2pybmulic.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxuanxn.top/Article/details/gt2ecozpfvc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhoulong.xyz/Article/details/gt2ezehmncj.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ygzxhyjs.html

G. 面向对象
来源：http://dali.gaohongyu789.top/Article/details/gt2yfsoldoz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2yuopwtdx.html

[G01] 定义类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2akwsfzrk.html

Py:   class User: pass
来源：http://dali.cheryme.top/Article/details/gt2tfliffyj.html

PHP:  class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2zpbivaug.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2hdqzvsji.html

TS:   class User { name: string = ""; }
来源：http://dali.tianlin.xyz/Article/details/gt2iljoelym.html

Java: class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2dgckhbgz.html

Go:   type User struct { Name string }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2syjumdru.html

Ruby: class User; end
来源：http://dali.xuanzx.com/Article/details/gt2whefrqax.html

C#:   class User {}
来源：http://dali.redwolf501.top/Article/details/gt2eszxlwxk.html

[G02] 构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ddgbwzxg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qvwnyiso.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnqzz.top/Article/details/gt2hervvcqu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gt2zzzsouuw.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gt2kuaddfiw.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2dkhugjze.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cdnleiting.top/Article/details/gt2dfljsvxa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nwbrower.top/Article/details/gt2uouadavk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2oytjddml.html

[G03] 实例属性
来源：http://dali.iojbl.cn/Article/details/gt2wtzhqfpl.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gt2pjuickds.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gt2qlwnpmpp.html

JS:   this.name = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2ggmguhix.html

TS:   name: string = "x";
来源：http://dali.zycfv.cn/Article/details/gt2riochdkn.html

Java: private String name;
来源：http://dali.meibo888.top/Article/details/gt2bmfrsijn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258888.top/Article/details/gt2eslwvqxb.html

Ruby: @name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gt2igdmmpcx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxinkj.top/Article/details/gt2qbnvkifl.html

[G04] 定义方法
来源：http://dali.hammf.cn/Article/details/gt2tkzdfvhq.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gt2vmtpnidy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gt2icorjfpd.html

JS:   greet() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gt2ispxvrws.html

TS:   greet(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2bzjefnkp.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2nbklbzzn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2qojsmpds.html

Ruby: def greet; @name; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2wthushfx.html

C#:   public string Greet() => Name;
来源：http://dali.0kj1m.cn/Article/details/gt2rlyvhgzx.html

[G05] 继承
来源：http://dali.meibo888.top/Article/details/gt2ojysuava.html

Py:   class Admin(User): pass
来源：http://dali.jyoumei.cn/Article/details/gt2iebeujzc.html

PHP:  class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2mswtqvmg.html

JS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2zexafuvp.html

TS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2auftzubm.html

Java: class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2bjrkszdj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shuidangran.top/Article/details/gt2vascvato.html

Ruby: class Admin < User; end
来源：http://dali.haohaochexian.top/Article/details/gt2zqnkyxuf.html

C#:   class Admin : User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2kweoikfg.html

[G06] 重写方法
来源：http://dali.zycfv.cn/Article/details/gt2cuyzmuwi.html

Py:   def greet(self): return "admin"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zgafecwy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ethjdvmn.html

JS:   greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2rdtexxgj.html


<!-- 参考信息 -->