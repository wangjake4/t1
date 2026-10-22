代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cucudq.cn/Article/details/gt2evqybace.html

TS:   s.split(",")
来源：http://dali.vqdsnc.cn/Article/details/gt2sxbqhlln.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.bjfxy.top/Article/details/gt2mkvyqkne.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2gryrjfjc.html

Ruby: s.split(",");  s.split
来源：http://dali.cqqwz.cn/Article/details/gt2ehqqmnnz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gt2zeimxppt.html

[E08] 数组按分隔符合并
来源：http://dali.yongpay.top/Article/details/gt2vlobrjbj.html

Py:   ",".join(items)
来源：http://dali.ydzc1.top/Article/details/gt2xujkvczn.html

PHP:  implode(",", $items);
来源：http://dali.ydzc1.top/Article/details/gt2sgtlgypy.html

JS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gt2fkwajfte.html

TS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gt2vrptkryb.html

Java: String.join(",", items)
来源：http://dali.daxiang520.top/Article/details/gt2skbvmtxx.html

Go:   strings.Join(items, ",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qmcjlffm.html

Ruby: items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gt2cjtzknxr.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ieftswii.html

[E09] 去除所有空白字符
来源：http://dali.wangshuangyany.cn/Article/details/gt2hjcuzqxm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zdqjudy.top/Article/details/gt2hplgswpm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2upagycsg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gt2zimrtzbi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gt2xoecnjym.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gt2nzhohrzx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.andypj.xyz/Article/details/gt2peghlyim.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aizwys.cn/Article/details/gt2xwuhhaep.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xziqi.cn/Article/details/gt2fggbbewg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aibaodan.cn/Article/details/gt2pzprmbwr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gt2pncaspll.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2omgjxxez.html

JS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gt2qlpohijr.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gt2smknfthu.html

Java: String.format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gt2lzxzbtxn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ujvdmwrw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gt2fmshbzjl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuanzhike.top/Article/details/gt2mhwdvncc.html

[E11] 反转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2nvpxxuxt.html

Py:   s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gt2cachzscp.html

PHP:  strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gt2xfuemtjw.html

JS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gt2evvjzlaa.html

TS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gt2okgvhoas.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ttqdzcon.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gt2sbipipee.html

Ruby: s.reverse
来源：http://dali.meibo888.top/Article/details/gt2dfyqpatt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gt2ycmliibc.html

[E12] 统计某字符出现次数
来源：http://dali.xuetiantiany.cn/Article/details/gt2mrdjwsyd.html

Py:   s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2krxolnea.html

PHP:  substr_count($s, "a");
来源：http://dali.sufxvd.cn/Article/details/gt2gkhvqcdp.html

JS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2njfsztec.html

TS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2witjagfx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aibaodan.cn/Article/details/gt2ekradhxo.html

Go:   strings.Count(s, "a")
来源：http://dali.zhengqikj.top/Article/details/gt2uyxzzlbb.html

Ruby: s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gt2pvfvihja.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pengpengdd.cyou/Article/details/gt2kmqsrvzc.html

[E13] 逐字符遍历
来源：http://dali.redwolf501.top/Article/details/gt2dwwjmprw.html

Py:   for ch in s: print(ch)
来源：http://dali.c1oappe.top/Article/details/gt2fmqjlwke.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gt2xyddahgq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nwbrower.top/Article/details/gt2fpsyding.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdjcohc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj202588.top/Article/details/gt2kovdpmyc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2ygtaepwq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gaohongyu789.top/Article/details/gt2mgolnbjb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sysykeji.top/Article/details/gt2eiiukrfc.html

[E14] URL 编码与 Base64
来源：http://dali.yonumen.top/Article/details/gt2ehxficsi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgfzy.top/Article/details/gt2ldzqaxep.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenzaomai.com/Article/details/gt2fcvhvezs.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuxming.cn/Article/details/gt2hapllhut.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2cnilmghy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuanzhike.top/Article/details/gt2twkioila.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hammf.cn/Article/details/gt2trbjvpsk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zdqjudy.top/Article/details/gt2dcsvxmem.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gt2acgwaqwi.html

[E15] HTML 转义 / 反转义
来源：http://dali.zycfv.cn/Article/details/gt2lphobwwa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2rkitxgft.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2twdkijvw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.316326.xyz/Article/details/gt2zshawubg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigfzy.top/Article/details/gt2htlpatlk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.quarkkingdee.top/Article/details/gt2itqrllvn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guannengcc.top/Article/details/gt2onqibgnt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258888.top/Article/details/gt2iporsaky.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jiagoushi.top/Article/details/gt2whkdlnnt.html

[E16] 数字千分位
来源：http://dali.guowangkeji.top/Article/details/gt2kxklczqm.html

Py:   f"{1234567:,}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2iyckxihc.html

PHP:  number_format(1234567);
来源：http://dali.guowangkeji.top/Article/details/gt2ktmzepka.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gt2cgngczet.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gt2uzgqavff.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pdlydgji.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sxryk.cn/Article/details/gt2yvxyyqve.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shuidangran.top/Article/details/gt2ywwdqyun.html

C#:   1234567.ToString("N0")
来源：http://dali.xinyue.icu/Article/details/gt2etsctdrl.html

[E17] 首字母大写
来源：http://dali.tian-w.cn/Article/details/gt2zgphlymj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.fengsongda.top/Article/details/gt2pvhmengg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2jfkryyny.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gt2dokhvmii.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gt2tomtmzsr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gogol.net.cn/Article/details/gt2hzakyaam.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sxryk.cn/Article/details/gt2ocjojefz.html

Ruby: s.capitalize
来源：http://dali.xuetiantiany.cn/Article/details/gt2lcavojkf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.redwolf501.top/Article/details/gt2cpijnxfn.html

[E18] 模板占位符替换
来源：http://dali.jinqigufen.top/Article/details/gt2ymwgshga.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangshuangyany.cn/Article/details/gt2cqkepqzg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.haohaochexian.top/Article/details/gt2fuzdpznu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gt2wfiqxhvo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2ceajlupb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gt2llxnujxq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gt2gwwyydkk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnqzz.top/Article/details/gt2eshpqape.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2iqyfxpke.html

[E19] 多行文本按行拆分
来源：http://dali.jlsjyb.cn/Article/details/gt2faphpadu.html

Py:   s.splitlines()
来源：http://dali.daxiang520.top/Article/details/gt2hvptfjaq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gosrugmm.html

JS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gt2mqkpghlk.html

TS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gt2scyfitdr.html

Java: s.lines().toList()
来源：http://dali.snrcjt.cn/Article/details/gt2rgkdfdbf.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenlongwang.top/Article/details/gt2idmihchk.html

Ruby: s.lines
来源：http://dali.nanxinkj.top/Article/details/gt2gyeunpxl.html

C#:   s.Split('\n')
来源：http://dali.hysaishi.cn/Article/details/gt2ferraspx.html

[E20] 判断字符串是否为空
来源：http://dali.zdqjudy.top/Article/details/gt2rvovzbif.html

Py:   if not s:
来源：http://dali.hnqzz.top/Article/details/gt2hwxuzcih.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhongyouzk.top/Article/details/gt2sjnieyfm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mukvrzut.html

TS:   if (s === "") {}
来源：http://dali.yangfankeji.com/Article/details/gt2qkawhkgu.html

Java: if (s.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gt2osxckxwz.html

Go:   if s == "" {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2ablqcsbv.html

Ruby: if s.empty?
来源：http://dali.snrcjt.cn/Article/details/gt2xfjyzhqt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxinkj.top/Article/details/gt2mwugiknm.html

[E21] 超长截断加省略号
来源：http://dali.quarkkingdee.top/Article/details/gt2ugthjala.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.bjfxy.top/Article/details/gt2vhdrxtgr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2rppeopbo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2gtjhziir.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2ddzewwrk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2nmsiamvz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.birdmap.top/Article/details/gt2rhzfxrdt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2bqglftwx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2mvqyzhoy.html

[E22] 字节长度与字符长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2jjtmsghl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nwbrower.top/Article/details/gt2fegfjzqb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2dcumjhpr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gt2gyduksyo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gt2memtkvuv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.c1oappe.top/Article/details/gt2vynvcpkj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sweek.top/Article/details/gt2dxbmmrpt.html

Ruby: s.bytesize;  s.length
来源：http://dali.hysaishi.cn/Article/details/gt2nghbjylr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2blllaaca.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2dfbzsazh.html

F. 文件与目录
来源：http://dali.xuanzx.com/Article/details/gt2npcorvrv.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2tgxfusgf.html

[F01] 读取整个文件
来源：http://dali.vqdsnc.cn/Article/details/gt2nxhknuyg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yoqkqflb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2cqiocpfl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daxiang520.top/Article/details/gt2jmwnbcal.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuanzx.com/Article/details/gt2nqvrtlmm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2fbsdfjun.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sweek.top/Article/details/gt2nwlsriju.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2uplpnuiu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2mvlwiazc.html

[F02] 逐行读取文件
来源：http://dali.jyoumei.cn/Article/details/gt2wksalezw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hongshengwenyu.top/Article/details/gt2bilywora.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.vqdsnc.cn/Article/details/gt2bcmtxqal.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gt2tdskdios.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2rsfoxrwt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gt2uosxblsw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fengsongda.top/Article/details/gt2vfphigew.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gt2hmpkjmdt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258.top/Article/details/gt2lkmodlhv.html

[F03] 写入文件（覆盖）
来源：http://dali.zdqjudy.top/Article/details/gt2wnwfxrqg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnxiangtu.top/Article/details/gt2joicbnwr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gt2yqxjiepn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gt2bozwnbnv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gt2mrbxgfre.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.quarkkingdee.top/Article/details/gt2xbcterkc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenlongwang.top/Article/details/gt2rtzuzgvt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cqqwz.cn/Article/details/gt2atvwzqzj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gt2dbgrhpcw.html

[F04] 追加写入文件
来源：http://dali.cqqwz.cn/Article/details/gt2oexbtywi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2feslrzhw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.bjfxy.top/Article/details/gt2dgjfatic.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2gjbhqobw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gt2lnhwkdvt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zdqjudy.top/Article/details/gt2gcgqtsvn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xziqi.cn/Article/details/gt2bxiclnqd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jyoumei.cn/Article/details/gt2lvrlpiqw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sxryk.cn/Article/details/gt2hlktvqob.html

[F05] 判断文件或目录是否存在
来源：http://dali.yvedp.cn/Article/details/gt2byhbkpxk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dashuyun.cn/Article/details/gt2cvtrltdc.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yykscxei.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2hfzruqlp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2fhuzofms.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gt2yydslxcn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daria6918.cn/Article/details/gt2wdazjsby.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vpovhenv.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rciyjdso.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gt2rcizaxut.html

Py:   os.remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2poexymos.html

PHP:  unlink("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xvpzzbqr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2bndclqmx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2nsmxclay.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gt2gexsbnyy.html

Go:   os.Remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2uxedauib.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2vpggjflk.html

C#:   File.Delete("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2unflujvg.html

[F07] 创建目录（含多级）
来源：http://dali.yuxming.cn/Article/details/gt2vygxhwxu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gt2wvguyrvp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qmhmxiuk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gt2hsucsunc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gt2jpewwdse.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gt2qpyxzbvk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ttkckmun.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jiagoushi.top/Article/details/gt2cownrsow.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yueranfly.top/Article/details/gt2vnhpjkuk.html

[F08] 遍历目录
来源：http://dali.hnqzz.top/Article/details/gt2lptheijv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258.top/Article/details/gt2rsqidwkw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhixingplan.top/Article/details/gt2ldfcmxri.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2nqspcgop.html

TS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gt2xljdaxkf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gt2kcaeupfo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2jrknapdo.html

Ruby: Dir.children("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2mkrwqsod.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xylfe.cn/Article/details/gt2nukxojee.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gt2fouxxvqy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2aiwzffsu.html

PHP:  filesize("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2odzvxbyz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gt2kolwwwgt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gt2oquvemik.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gt2nfhkcsjy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuanzx.com/Article/details/gt2urlrlxtt.html

Ruby: File.size("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2syejrqfa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yvedp.cn/Article/details/gt2uxvsqcaq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxinkj.top/Article/details/gt2cpfgqzkm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2khxedmew.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2jsxuskhp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2iofemxzu.html

TS:   path.extname("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2hbnevnty.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fengsongda.top/Article/details/gt2ypjzaetk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2lkbpvoem.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2yhcvozjz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2qwkiszfo.html

[F11] 复制与移动文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2seyxeinh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2cspcvdho.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daria6918.cn/Article/details/gt2grvtypeb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2rhuvxcyx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2buitmjzl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gt2qbbfcgpk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guowangkeji.top/Article/details/gt2snhuvesq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hyypokld.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuanzx.com/Article/details/gt2xzwflmbd.html

[F12] CSV 读写
来源：http://dali.shzxlz.cn/Article/details/gt2fggfdsqi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.9152youxi.cn/Article/details/gt2oszoqlgl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yonumen.top/Article/details/gt2lxuuibks.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj202588.top/Article/details/gt2lkojural.html

TS:   // 同上
来源：http://dali.yonumen.top/Article/details/gt2tjnpabzp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigufen.top/Article/details/gt2ejjrrozv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhongyouzk.top/Article/details/gt2snfpxguf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gt2vvkrhifa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yvedp.cn/Article/details/gt2lttpqdyt.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2xzvijxbp.html

G. 面向对象
来源：http://dali.daxiang520.top/Article/details/gt2txthghvm.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2vttrdjim.html

[G01] 定义类
来源：http://dali.ivvv.top/Article/details/gt2rbijeqsk.html

Py:   class User: pass
来源：http://dali.pengpengdd.cyou/Article/details/gt2pbtqskuf.html

PHP:  class User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2pkvukbax.html

JS:   class User {}
来源：http://dali.316326.xyz/Article/details/gt2fhkllzvj.html

TS:   class User { name: string = ""; }
来源：http://dali.ybcxt.top/Article/details/gt2requoigq.html

Java: class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2rtzfpwvd.html

Go:   type User struct { Name string }
来源：http://dali.c1oappe.top/Article/details/gt2xulsdcbu.html

Ruby: class User; end
来源：http://dali.hfpthk.cn/Article/details/gt2wnptebmb.html

C#:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2qwgrucki.html

[G02] 构造函数
来源：http://dali.xylfe.cn/Article/details/gt2oplpauuu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.vqdsnc.cn/Article/details/gt2smggmoax.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.smart0.xyz/Article/details/gt2tshquhya.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gt2mwbdwhxe.html

TS:   constructor(public name: string) {}
来源：http://dali.316326.xyz/Article/details/gt2ujgxzpwj.html

Java: User(String name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gt2hhonbwkb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.9152youxi.cn/Article/details/gt2htjktqpy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hammf.cn/Article/details/gt2xvjffcax.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sysykeji.top/Article/details/gt2sqmhnrdu.html

[G03] 实例属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2egubmymm.html

Py:   self.name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qqktnlfs.html

PHP:  public string $name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gt2uhyuewcu.html

JS:   this.name = "x";
来源：http://dali.ydzc1.top/Article/details/gt2objkwljg.html

TS:   name: string = "x";
来源：http://dali.dianchejie.cn/Article/details/gt2ubbwsqvk.html

Java: private String name;
来源：http://dali.xinyue.icu/Article/details/gt2jbybqicz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gt2ydrypvkq.html

Ruby: @name = "x"
来源：http://dali.xinyue.icu/Article/details/gt2hydxcfev.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2fntimkzf.html

[G04] 定义方法
来源：http://dali.fengsongda.top/Article/details/gt2mmzxlntp.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gt2utesqzrk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gt2shtluckl.html

JS:   greet() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gt2cwbernvw.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2lcvvvqmh.html

Java: String greet() { return name; }
来源：http://dali.cheryme.top/Article/details/gt2vipvtgrz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gt2mzkxpnzb.html

Ruby: def greet; @name; end
来源：http://dali.daria6918.cn/Article/details/gt2herpciyv.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ngqzhmyv.html

[G05] 继承
来源：http://dali.wangdashe.top/Article/details/gt2xzrkbabu.html

Py:   class Admin(User): pass
来源：http://dali.daria6918.cn/Article/details/gt2jjtxwzxk.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2slewwnoe.html

JS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gt2oapjwzcw.html

TS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gt2kzhyhjnk.html

Java: class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2wdcqxqfz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jyoumei.cn/Article/details/gt2asdmpats.html

Ruby: class Admin < User; end
来源：http://dali.cucudq.cn/Article/details/gt2woiymtep.html

C#:   class Admin : User {}
来源：http://dali.cucudq.cn/Article/details/gt2adgdwqra.html


<!-- 参考信息 -->