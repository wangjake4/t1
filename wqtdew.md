代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuanzhike.top/Article/details/gt2gbdrzppo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2rumirfwj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gaohongyu789.top/Article/details/gt2btvzkphp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yvedp.cn/Article/details/gt2fbyfywlj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xylfe.cn/Article/details/gt2reqyklxw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2nbvduqsm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dashuyun.cn/Article/details/gt2sdsefwnc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yueranfly.top/Article/details/gt2usjkqivy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.kuanghao11.cn/Article/details/gt2sqdkathl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gt2xwqkfogt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.haohaochexian.top/Article/details/gt2jrfcamww.html

JS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gt2bqsedgfq.html

TS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2zswlzsfm.html

Java: String.format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gt2rpqdhfsv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lzlnhxda.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gt2xaqbqdhm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhoulong.xyz/Article/details/gt2qgstwafw.html

[E11] 反转字符串
来源：http://dali.gotoacloud.top/Article/details/gt2dwemddta.html

Py:   s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fpmrtuem.html

PHP:  strrev($s);
来源：http://dali.yj20258.top/Article/details/gt2yotnfgby.html

JS:   [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gt2wgoyfjzy.html

TS:   [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gt2qvcxneou.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ppjwa.cn/Article/details/gt2gohnqbtu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gt2evzkwoah.html

Ruby: s.reverse
来源：http://dali.tanke756.top/Article/details/gt2fydcggrg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangshuangyany.cn/Article/details/gt2jdpcaqoe.html

[E12] 统计某字符出现次数
来源：http://dali.cashguo.top/Article/details/gt2ggaocnko.html

Py:   s.count("a")
来源：http://dali.yongpay.top/Article/details/gt2rhtkqlmg.html

PHP:  substr_count($s, "a");
来源：http://dali.yuanzhike.top/Article/details/gt2evlihdwn.html

JS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gt2uwrrhiao.html

TS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gt2ghbmourz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.9152youxi.cn/Article/details/gt2hihpuaek.html

Go:   strings.Count(s, "a")
来源：http://dali.ppjwa.cn/Article/details/gt2ehgfvwfl.html

Ruby: s.count("a")
来源：http://dali.fzhhl.top/Article/details/gt2uuuztwux.html

C#:   s.Count(c => c == 'a')
来源：http://dali.bjfxy.top/Article/details/gt2euoerbls.html

[E13] 逐字符遍历
来源：http://dali.yj20258.top/Article/details/gt2dqfwnztz.html

Py:   for ch in s: print(ch)
来源：http://dali.ppjwa.cn/Article/details/gt2kybpshqu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.quarkkingdee.top/Article/details/gt2hblnlddi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gt2awjzvjya.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gt2goxzudvm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xziqi.cn/Article/details/gt2zjejxjdw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2odmdyjfv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhixingplan.top/Article/details/gt2scqynhnu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nlmvaopz.html

[E14] URL 编码与 Base64
来源：http://dali.redwolf501.top/Article/details/gt2vbsmfttx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.mhx1999.top/Article/details/gt2kfqfukto.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tanke756.top/Article/details/gt2drovtriv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shzxlz.cn/Article/details/gt2muxwloso.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuanzhike.top/Article/details/gt2xdsdknzn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xinyue.icu/Article/details/gt2atdfomao.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.mhx1999.top/Article/details/gt2eimvevwg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxokbuus.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.aibaodan.cn/Article/details/gt2obzzqfyz.html

[E15] HTML 转义 / 反转义
来源：http://dali.sweek.top/Article/details/gt2rjetcwyd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guowangkeji.top/Article/details/gt2zjhgwuxm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aizwys.cn/Article/details/gt2eehikjnk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cqqwz.cn/Article/details/gt2naokrdhp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2imnxwwjn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hysaishi.cn/Article/details/gt2mpdjieog.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cashguo.top/Article/details/gt2cumamgsy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fhshiuod.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuanzx.com/Article/details/gt2pjjnwhnf.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gt2piqdmgim.html

Py:   f"{1234567:,}"
来源：http://dali.hnxiangtu.top/Article/details/gt2pdvsnjzx.html

PHP:  number_format(1234567);
来源：http://dali.cqqwz.cn/Article/details/gt2lhgahpmo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gt2osibksmd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gt2lyggnwmk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cheryme.top/Article/details/gt2oyljdynq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sysykeji.top/Article/details/gt2pletrlsv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhoulong.xyz/Article/details/gt2wbunzqhz.html

C#:   1234567.ToString("N0")
来源：http://dali.cheryme.top/Article/details/gt2jpjnesys.html

[E17] 首字母大写
来源：http://dali.yongpay.top/Article/details/gt2snjldjue.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhiwuduotai.top/Article/details/gt2dlxspzca.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rsxablsh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gt2mlefsebg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gt2qicnvoib.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yonumen.top/Article/details/gt2gakjmszr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yangfankeji.com/Article/details/gt2imgzpfbb.html

Ruby: s.capitalize
来源：http://dali.haohaochexian.top/Article/details/gt2jycpdlrw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.316326.xyz/Article/details/gt2tmtxhuzr.html

[E18] 模板占位符替换
来源：http://dali.redwolf501.top/Article/details/gt2jzqeppyx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhixingplan.top/Article/details/gt2qcmdcesj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.meibo888.top/Article/details/gt2crwscgnu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gt2cgzbuynj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gt2vouxsocn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gt2kfjpnlqd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jvztstyz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gisqkzth.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.smart0.xyz/Article/details/gt2ssxiaphh.html

[E19] 多行文本按行拆分
来源：http://dali.aibaodan.cn/Article/details/gt2ecnwbhjr.html

Py:   s.splitlines()
来源：http://dali.316326.xyz/Article/details/gt2odutnytg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2clumogcc.html

JS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gt2irsiperc.html

TS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gt2nohcsuaa.html

Java: s.lines().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2gskvkxtn.html

Go:   strings.Split(s, "\n")
来源：http://dali.hammf.cn/Article/details/gt2cqimtmml.html

Ruby: s.lines
来源：http://dali.hammf.cn/Article/details/gt2cmzqudek.html

C#:   s.Split('\n')
来源：http://dali.sufxvd.cn/Article/details/gt2lrbkjuid.html

[E20] 判断字符串是否为空
来源：http://dali.xziqi.cn/Article/details/gt2maxhzpio.html

Py:   if not s:
来源：http://dali.jianghu66.top/Article/details/gt2wzoyjsxt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvgnzqwe.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2uiauuyns.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qerjpzgg.html

Java: if (s.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gt2yzulmenl.html

Go:   if s == "" {}
来源：http://dali.tianlin.xyz/Article/details/gt2gsxjxrrw.html

Ruby: if s.empty?
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bowhxvdi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cdnleiting.top/Article/details/gt2dxjccbhz.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gt2duilaqnk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yonumen.top/Article/details/gt2xmgpjxya.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gt2svfcljiz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gt2eanxllix.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2fgubschr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2pmeyncdp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.0kj1m.cn/Article/details/gt2idgibiqa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sweek.top/Article/details/gt2llxqnnww.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gt2rouwpljk.html

[E22] 字节长度与字符长度
来源：http://dali.hfpthk.cn/Article/details/gt2xrrijivg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hqqmstbv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gt2fwbyyssz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gt2wfkwuxov.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gt2rxladvfr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.birdmap.top/Article/details/gt2cbrmyuix.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tanke756.top/Article/details/gt2zebeywbp.html

Ruby: s.bytesize;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2bayanmyr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gt2xkopopbt.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2jtztijar.html

F. 文件与目录
来源：http://dali.svipenyu.cn/Article/details/gt2ygvepbpl.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2tjghkcpp.html

[F01] 读取整个文件
来源：http://dali.tianlin.xyz/Article/details/gt2atdyvesi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pengpengdd.cyou/Article/details/gt2bmapyhhp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2dnmmyovd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pvllxduq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cashguo.top/Article/details/gt2pjtwwjbn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2yjrhnnvr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fzhhl.top/Article/details/gt2qqioyvmk.html

Ruby: File.read("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2muostqab.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2vfliujng.html

[F02] 逐行读取文件
来源：http://dali.yongpay.top/Article/details/gt2diajitkv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cucudq.cn/Article/details/gt2mjaubexf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhixingplan.top/Article/details/gt2ynlydzch.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2rxidxgmh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gt2omaaayrf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gt2odovyfbp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ppjwa.cn/Article/details/gt2nvgzohai.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jiagoushi.top/Article/details/gt2bekavley.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cqqwz.cn/Article/details/gt2athhpcap.html

[F03] 写入文件（覆盖）
来源：http://dali.chenzaomai.com/Article/details/gt2svudenpo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daria6918.cn/Article/details/gt2nsugwlof.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gt2oucnmiio.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2djufecci.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gt2qoovfuyl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenzaomai.com/Article/details/gt2jqujjavu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ydzc1.top/Article/details/gt2rcyyyfeb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fzhhl.top/Article/details/gt2ntgbhckv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gt2kzhhnopr.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gt2ztviynnt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gzhubu.top/Article/details/gt2wlnzgpiu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258.top/Article/details/gt2ouxerwud.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gt2fcgyjhee.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dyrunvso.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenzaomai.com/Article/details/gt2pkedteqn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgufenzy.top/Article/details/gt2nzmtflsf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aibaodan.cn/Article/details/gt2zstcdzyl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sxryk.cn/Article/details/gt2pfcegkbr.html

[F05] 判断文件或目录是否存在
来源：http://dali.gzhubu.top/Article/details/gt2hgqihddr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenlongwang.top/Article/details/gt2cimfkmle.html

PHP:  file_exists("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2cqtlpdoc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2skvjxwqf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2ubboqcrv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gt2yfzbpvec.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gogol.net.cn/Article/details/gt2fcdlqteg.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2fcjywbwf.html

C#:   File.Exists("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2kcmqhpry.html

[F06] 删除文件
来源：http://dali.guannengcc.top/Article/details/gt2trhjkosr.html

Py:   os.remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2gotqpyoy.html

PHP:  unlink("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2fwkzewdv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2eotvnort.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2venrsxts.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gt2pzmlyzid.html

Go:   os.Remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2nlsxiosv.html

Ruby: File.delete("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2eijwfwvo.html

C#:   File.Delete("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2yumtcteu.html

[F07] 创建目录（含多级）
来源：http://dali.hfpthk.cn/Article/details/gt2ryqkrxhm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gt2dqwlrqah.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenzaomai.com/Article/details/gt2sqaqjzzr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gt2funhosmc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gt2amtzdhnh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.havefunace.top/Article/details/gt2gfzoczmq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pycfn.com/Article/details/gt2hmrglgix.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.haohaochexian.top/Article/details/gt2okjicyrs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aizwys.cn/Article/details/gt2eblwuimi.html

[F08] 遍历目录
来源：http://dali.zycfv.cn/Article/details/gt2qhudaxnz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigufen.top/Article/details/gt2yhzgwcdk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ybcxt.top/Article/details/gt2wyjercqs.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnvtgta.html

TS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gt2ncviordt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gt2ggfauney.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hfbalqvm.html

Ruby: Dir.children("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2zrputjcw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2miqqzgqp.html

[F09] 获取文件大小
来源：http://dali.zhengqikj.top/Article/details/gt2nsiforwx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2zucglpdx.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2meimhhsy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gt2bmztywmv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gt2rrroxsmk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2nhcgankr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdipztxz.html

Ruby: File.size("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2mvhbaddd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qjhoodox.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jianghu66.top/Article/details/gt2qziilluw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2zhupdzhi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2qjpamise.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2pjognvcn.html

TS:   path.extname("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2wshjiaqa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xziqi.cn/Article/details/gt2zvhxbvxt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2iclpkjdb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2nqamorwz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hyvxbatk.html

[F11] 复制与移动文件
来源：http://dali.iojbl.cn/Article/details/gt2xgkimtmb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2ecacnrad.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2pozjwkns.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qygfesik.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2pemknorm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ivvv.top/Article/details/gt2hbvkbkmb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.redwolf501.top/Article/details/gt2denffloy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2vccvaeky.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuxming.cn/Article/details/gt2wvvrhawd.html

[F12] CSV 读写
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ocxuvpnn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yvedp.cn/Article/details/gt2tbveizxl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ydzc1.top/Article/details/gt2lpqnghni.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sysykeji.top/Article/details/gt2ubjupxfg.html

TS:   // 同上
来源：http://dali.ybcxt.top/Article/details/gt2ajphcchy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cheryme.top/Article/details/gt2godbvdws.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gt2nghcftwt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gt2csqiumtg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nwbrower.top/Article/details/gt2apvakskz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2flnnozlq.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gt2qfzjitoz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2uzhkiikp.html

[G01] 定义类
来源：http://dali.jianghu66.top/Article/details/gt2fagzprwk.html

Py:   class User: pass
来源：http://dali.jiagoushi.top/Article/details/gt2uhoglmez.html

PHP:  class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2stjtnqih.html

JS:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2pnfibsvt.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigfzy.top/Article/details/gt2vbcyimem.html

Java: class User {}
来源：http://dali.yuanzhike.top/Article/details/gt2ujerfaos.html

Go:   type User struct { Name string }
来源：http://dali.hammf.cn/Article/details/gt2avgoujxt.html

Ruby: class User; end
来源：http://dali.jqgfzy.top/Article/details/gt2biuevgtq.html

C#:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gt2pmlatxwk.html

[G02] 构造函数
来源：http://dali.chenlongwang.top/Article/details/gt2qdlthfft.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hcvrsiwe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2ualukqng.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cukbuzug.html

TS:   constructor(public name: string) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2wuxdohjp.html

Java: User(String name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gt2yyojinqe.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dbucykii.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mqdqecfw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yvedp.cn/Article/details/gt2gwrbgiwm.html

[G03] 实例属性
来源：http://dali.chenjidiqi.icu/Article/details/gt2chbwmwwv.html

Py:   self.name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gt2sdxvwhbu.html

PHP:  public string $name = "x";
来源：http://dali.sweek.top/Article/details/gt2cgmnozlw.html

JS:   this.name = "x";
来源：http://dali.sxryk.cn/Article/details/gt2lboxxvez.html

TS:   name: string = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2ceyazyqy.html

Java: private String name;
来源：http://dali.xinyue.icu/Article/details/gt2npboxyrw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gt2wuzgrpcv.html

Ruby: @name = "x"
来源：http://dali.pycfn.com/Article/details/gt2jwuzsytj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2mgtdtcra.html

[G04] 定义方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2fmwayegq.html

Py:   def greet(self): return self.name
来源：http://dali.hammf.cn/Article/details/gt2yqtsxbag.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gt2zrtkayon.html

JS:   greet() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gt2gcxdemil.html

TS:   greet(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2glyyvdoq.html

Java: String greet() { return name; }
来源：http://dali.meibo888.top/Article/details/gt2uozivglw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jcitzwpl.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gt2lojvuutc.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2ktbtccbd.html

[G05] 继承
来源：http://dali.cheryme.top/Article/details/gt2dmbtwxkt.html

Py:   class Admin(User): pass
来源：http://dali.kuanghao11.cn/Article/details/gt2luttexod.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2jxnaundf.html

JS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2coyqcvwd.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gt2nymhmtak.html

Java: class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2edvmlsuu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.andypj.xyz/Article/details/gt2zomkkhqq.html

Ruby: class Admin < User; end
来源：http://dali.shuidangran.top/Article/details/gt2hkxjpoev.html

C#:   class Admin : User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2ljnmievc.html

[G06] 重写方法
来源：http://dali.yj20258888.top/Article/details/gt2dzqbqjiz.html

Py:   def greet(self): return "admin"
来源：http://dali.yonumen.top/Article/details/gt2nobrjziu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2wzoonour.html

JS:   greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2fkqxavea.html

TS:   greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2ravpfhjz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gt2trkcozfg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daria6918.cn/Article/details/gt2juldasti.html

Ruby: def greet; "admin"; end
来源：http://dali.quarkkingdee.top/Article/details/gt2nykcyues.html

C#:   public override string Greet() => "admin";
来源：http://dali.hammf.cn/Article/details/gt2utkczdqn.html

[G07] 调用父类方法
来源：http://dali.havefunace.top/Article/details/gt2nbcsmirw.html

Py:   super().greet()
来源：http://dali.xylfe.cn/Article/details/gt2ldsggsac.html

PHP:  parent::greet();
来源：http://dali.fengsongda.top/Article/details/gt2jwnqmvev.html

JS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gt2hpjgcrwq.html

TS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gt2emgqesod.html

Java: super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smundjuv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gt2ovccclbt.html


<!-- 参考信息 -->