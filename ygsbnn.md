代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xgwyrbsd.html

[E07] 按分隔符拆分
来源：http://dali.jyoumei.cn/Article/details/gt2ipvvwncu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mhhcfplo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2oxhouart.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2sunanqcx.html

TS:   s.split(",")
来源：http://dali.smart0.xyz/Article/details/gt2enctbhim.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yonumen.top/Article/details/gt2gxujppiv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.smart0.xyz/Article/details/gt2zmgzmzhi.html

Ruby: s.split(",");  s.split
来源：http://dali.yueranfly.top/Article/details/gt2iioxwlbs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.andypj.xyz/Article/details/gt2qfmdsbxw.html

[E08] 数组按分隔符合并
来源：http://dali.yvedp.cn/Article/details/gt2uphjwvhn.html

Py:   ",".join(items)
来源：http://dali.dashuyun.cn/Article/details/gt2bzzzjmxg.html

PHP:  implode(",", $items);
来源：http://dali.mhx1999.top/Article/details/gt2mnjonhhm.html

JS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gt2bsndmeqj.html

TS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gt2iazcleky.html

Java: String.join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zercccdm.html

Go:   strings.Join(items, ",")
来源：http://dali.ehwqpu.com/Article/details/gt2ymnlomva.html

Ruby: items.join(",")
来源：http://dali.c1oappe.top/Article/details/gt2vywigmgx.html

C#:   string.Join(",", items)
来源：http://dali.guannengcc.top/Article/details/gt2ydwwweyk.html

[E09] 去除所有空白字符
来源：http://dali.guannengcc.top/Article/details/gt2ojmbdixb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj202588.top/Article/details/gt2wnkblhjv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.birdmap.top/Article/details/gt2simfqmtm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gt2uuikoqcm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gt2vgpzjlrp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gt2gvumiwmy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.vqdsnc.cn/Article/details/gt2bqwsrdyw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.quarkkingdee.top/Article/details/gt2cbwjqirb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gt2rxedxsvd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.c1oappe.top/Article/details/gt2krcgktsk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gt2vrppiems.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dianchejie.cn/Article/details/gt2xfjitfcd.html

JS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gt2dobffwxy.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2nfqwnhar.html

Java: String.format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gt2qpoiwfmc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sweek.top/Article/details/gt2yeexkxpj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gt2jccxwmht.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj202588.top/Article/details/gt2bmlamdua.html

[E11] 反转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wwnymdgy.html

Py:   s[::-1]
来源：http://dali.fzhhl.top/Article/details/gt2iooitvdl.html

PHP:  strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gt2trfuyxnv.html

JS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gt2gilfjcbg.html

TS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gt2vdbxquyj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guannengcc.top/Article/details/gt2qdsejjgf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dashuyun.cn/Article/details/gt2uapgohfi.html

Ruby: s.reverse
来源：http://dali.yj20258.top/Article/details/gt2nyhcocey.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zycfv.cn/Article/details/gt2lvxejwci.html

[E12] 统计某字符出现次数
来源：http://dali.meibo888.top/Article/details/gt2vupxyuvm.html

Py:   s.count("a")
来源：http://dali.yuxming.cn/Article/details/gt2hewxlafu.html

PHP:  substr_count($s, "a");
来源：http://dali.gaohongyu789.top/Article/details/gt2rvtnvajm.html

JS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gt2gzxlipwz.html

TS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gt2kzlwpvqw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guannengcc.top/Article/details/gt2odfuuits.html

Go:   strings.Count(s, "a")
来源：http://dali.sufxvd.cn/Article/details/gt2lgdptwoi.html

Ruby: s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2rzackcqk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhixingplan.top/Article/details/gt2ljmiudpx.html

[E13] 逐字符遍历
来源：http://dali.chenzaomai.com/Article/details/gt2prtyazih.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258888.top/Article/details/gt2eclcjslb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.bjfxy.top/Article/details/gt2vwtzzsku.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gt2xqddyoif.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2qpylbxdn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.haohaochexian.top/Article/details/gt2tlcazxtu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ybcxt.top/Article/details/gt2opgpimoe.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ehwqpu.com/Article/details/gt2sltdxrrz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2sgbzcrwn.html

[E14] URL 编码与 Base64
来源：http://dali.yj202588.top/Article/details/gt2rrsefdpe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2doukvpxf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fengsongda.top/Article/details/gt2ckozifek.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shangyingyoupin.top/Article/details/gt2anxigplf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ppjwa.cn/Article/details/gt2yagvnvny.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.c1oappe.top/Article/details/gt2qpvmbydr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ccngbbck.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yangfankeji.com/Article/details/gt2xrrtgkzq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.0kj1m.cn/Article/details/gt2nvvubhwb.html

[E15] HTML 转义 / 反转义
来源：http://dali.hywenlv.cn/Article/details/gt2hdadegwj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.birdmap.top/Article/details/gt2eaoaboxn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bjzvyudm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangdashe.top/Article/details/gt2jpkswoxy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.vqdsnc.cn/Article/details/gt2hnevrblt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.redwolf501.top/Article/details/gt2njwwttfn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.bjfxy.top/Article/details/gt2uncofkkw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hammf.cn/Article/details/gt2wyewprvv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nwbrower.top/Article/details/gt2qbvcfrsj.html

[E16] 数字千分位
来源：http://dali.smart0.xyz/Article/details/gt2fqtdhrrb.html

Py:   f"{1234567:,}"
来源：http://dali.daxiang520.top/Article/details/gt2bkectgla.html

PHP:  number_format(1234567);
来源：http://dali.zhiwuduotai.top/Article/details/gt2auhepkcd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gt2sobfoxvl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gt2ipriikyn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fzhhl.top/Article/details/gt2drlozblw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuanzx.com/Article/details/gt2khfxlpgm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.mhx1999.top/Article/details/gt2gndxbpud.html

C#:   1234567.ToString("N0")
来源：http://dali.xylfe.cn/Article/details/gt2jzgewcsu.html

[E17] 首字母大写
来源：http://dali.cheryme.top/Article/details/gt2epywizje.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gt2mgiduuzz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2ewrtljkc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gt2ipvppmzi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gt2abpgwbgq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.meibo888.top/Article/details/gt2wfpaugkn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ydzc1.top/Article/details/gt2decqdybx.html

Ruby: s.capitalize
来源：http://dali.0kj1m.cn/Article/details/gt2uwloyaja.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fraqoptn.html

[E18] 模板占位符替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2eadfxfil.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuanzx.com/Article/details/gt2nmmaubqt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hfpthk.cn/Article/details/gt2widvhalr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gt2checekab.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gt2wrgznvax.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gt2rqihwmon.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guannengcc.top/Article/details/gt2snwtddsh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tianlin.xyz/Article/details/gt2zjwlcqsk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.haohaochexian.top/Article/details/gt2hecsfklh.html

[E19] 多行文本按行拆分
来源：http://dali.iojbl.cn/Article/details/gt2qyxhaowz.html

Py:   s.splitlines()
来源：http://dali.cucudq.cn/Article/details/gt2nqwmoqpi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2rzterned.html

JS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gt2fdwqdpkd.html

TS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gt2ntxzsbhx.html

Java: s.lines().toList()
来源：http://dali.shuidangran.top/Article/details/gt2bxxshukd.html

Go:   strings.Split(s, "\n")
来源：http://dali.aibaodan.cn/Article/details/gt2pamfkstc.html

Ruby: s.lines
来源：http://dali.xuanzx.com/Article/details/gt2bkzqrjni.html

C#:   s.Split('\n')
来源：http://dali.quarkkingdee.top/Article/details/gt2hjcspgfb.html

[E20] 判断字符串是否为空
来源：http://dali.shuidangran.top/Article/details/gt2gmvzbzsb.html

Py:   if not s:
来源：http://dali.yuanzhike.top/Article/details/gt2sdktopkv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shangyingyoupin.top/Article/details/gt2ssiauhqs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.mhx1999.top/Article/details/gt2igfhamlp.html

TS:   if (s === "") {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2ygxjjbqf.html

Java: if (s.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gt2flkadvgb.html

Go:   if s == "" {}
来源：http://dali.jqgfzy.top/Article/details/gt2hlrmkyme.html

Ruby: if s.empty?
来源：http://dali.dianchejie.cn/Article/details/gt2ikpggxco.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fpibkwvh.html

[E21] 超长截断加省略号
来源：http://dali.quarkkingdee.top/Article/details/gt2thjsyded.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nwbrower.top/Article/details/gt2uapoccvy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gt2bykzkufd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2dyfwhyld.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2qlpcvtlx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2wpsbeguj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yongpay.top/Article/details/gt2aqsuvpvo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ydzc1.top/Article/details/gt2zkjmausw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gt2fizncafq.html

[E22] 字节长度与字符长度
来源：http://dali.jyoumei.cn/Article/details/gt2axphsqfk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hammf.cn/Article/details/gt2gkozcltv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gt2ovdgdhfm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gt2hpmwaoyg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2nkfpfzrk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vctkbtmw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.smart0.xyz/Article/details/gt2wujeawpz.html

Ruby: s.bytesize;  s.length
来源：http://dali.andypj.xyz/Article/details/gt2cwuhgpvz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwmqmzuf.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2smltldcr.html

F. 文件与目录
来源：http://dali.tian-w.cn/Article/details/gt2lcgfvsgd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2ueywgnau.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mczvxztl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xyctrxyp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2fmkosecv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangtech.top/Article/details/gt2slhwhrdw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gt2thtlnlqd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gt2kxsvxpeq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zycfv.cn/Article/details/gt2planbjku.html

Ruby: File.read("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2twjojghe.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2kwrltsmi.html

[F02] 逐行读取文件
来源：http://dali.yvedp.cn/Article/details/gt2qodtonoi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yueranfly.top/Article/details/gt2edugbali.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ydzc1.top/Article/details/gt2arsrbxws.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gt2cnbvnrra.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2ywsvizbl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gt2lcreepcx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ivvv.top/Article/details/gt2czcofzuj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yvedp.cn/Article/details/gt2fcglsvcg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258888.top/Article/details/gt2pafzifuz.html

[F03] 写入文件（覆盖）
来源：http://dali.sxryk.cn/Article/details/gt2cxdvafgr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.vqdsnc.cn/Article/details/gt2qesmdxsu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gt2wmafugmj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gt2mmnilgoy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gt2iifnibbt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dashuyun.cn/Article/details/gt2mvcjkmzk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ukhibhjd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yonumen.top/Article/details/gt2akhyfmng.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gt2dncecfps.html

[F04] 追加写入文件
来源：http://dali.jyoumei.cn/Article/details/gt2kmduzpag.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aizwys.cn/Article/details/gt2nxjizqdq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgfzy.top/Article/details/gt2kizmunqr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gt2hekdkwhi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gt2tpfdcikx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gotoacloud.top/Article/details/gt2xumcnmtc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2adilrqea.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ppjwa.cn/Article/details/gt2brbnlyei.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tanke756.top/Article/details/gt2izuhnnlv.html

[F05] 判断文件或目录是否存在
来源：http://dali.ehwqpu.com/Article/details/gt2ylfpsyia.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.0kj1m.cn/Article/details/gt2dzxhppku.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2ischhqej.html

JS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2qcocnwtr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2vktlsdqt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gt2yqgpzlrp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fengsongda.top/Article/details/gt2lrvyjvyb.html

Ruby: File.exist?("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2wmrgdqsn.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2lswwturj.html

[F06] 删除文件
来源：http://dali.316326.xyz/Article/details/gt2aitsezyz.html

Py:   os.remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2cyoqlqtk.html

PHP:  unlink("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wkydjzqe.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2edeujrec.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2qmjckrev.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gt2dsnlouch.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2bqxdopkv.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2iqqpexin.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2oyfpjfsi.html

[F07] 创建目录（含多级）
来源：http://dali.redwolf501.top/Article/details/gt2smhccjxt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gt2smvksnms.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.birdmap.top/Article/details/gt2ojqimdoa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gt2xsmapqfb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oyudbjyr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnqzz.top/Article/details/gt2mxwshwyl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gt2npynsatq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gotoacloud.top/Article/details/gt2zlwtjmvu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ivvv.top/Article/details/gt2iwpebscv.html

[F08] 遍历目录
来源：http://dali.sxryk.cn/Article/details/gt2nuwqrisc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjtkvpwg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenlongwang.top/Article/details/gt2cuankkmw.html

JS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gt2trmzguth.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2rqrqdbay.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gt2ttexzzzv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nwbrower.top/Article/details/gt2okbbnobn.html

Ruby: Dir.children("dir")
来源：http://dali.gogol.net.cn/Article/details/gt2syctcpci.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258.top/Article/details/gt2jfnvnxfp.html

[F09] 获取文件大小
来源：http://dali.jinghuilouyu.cn/Article/details/gt2riomgscu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qamphqmq.html

PHP:  filesize("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2iiymutmj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gt2fzffjdhr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gt2xupuqwvc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gt2fvdtbvxs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhoulong.xyz/Article/details/gt2rxlzjnrr.html

Ruby: File.size("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2velxoksz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dashuyun.cn/Article/details/gt2gijxmkmz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gotoacloud.top/Article/details/gt2enfnpifn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2rxogwcre.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2frmhzdyi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2trbluhrk.html

TS:   path.extname("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2daaefhbu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.iojbl.cn/Article/details/gt2oacusisx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2wzztinxu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2wshfojns.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2ybxujbaw.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gt2xdvabozj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2skpmdglx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.c1oappe.top/Article/details/gt2henaszdf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2eujrcqmv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gt2cqpvmbnf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cdnleiting.top/Article/details/gt2vegvgyga.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigufen.top/Article/details/gt2cjlfzckv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2srccqdgw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnxiangtu.top/Article/details/gt2mqjklttl.html

[F12] CSV 读写
来源：http://dali.haohaochexian.top/Article/details/gt2cmeabhig.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.quarkkingdee.top/Article/details/gt2bchmbxhn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hysaishi.cn/Article/details/gt2esyakiqj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gt2ymtmbdqi.html

TS:   // 同上
来源：http://dali.ydzc1.top/Article/details/gt2drfffgmh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hongshengwenyu.top/Article/details/gt2lgryiwbc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ehwqpu.com/Article/details/gt2bvrvutmw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258888.top/Article/details/gt2fzducguh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gt2frqmywex.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2iycnjjfg.html

G. 面向对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2qdmpakce.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2vsjgbnmj.html

[G01] 定义类
来源：http://dali.hnxiangtu.top/Article/details/gt2zyqsaejh.html

Py:   class User: pass
来源：http://dali.ybcxt.top/Article/details/gt2zmdpewcq.html

PHP:  class User {}
来源：http://dali.tanke756.top/Article/details/gt2ztikpqxk.html

JS:   class User {}
来源：http://dali.daria6918.cn/Article/details/gt2fwvwpuyd.html

TS:   class User { name: string = ""; }
来源：http://dali.gzhubu.top/Article/details/gt2kwqqbzkf.html

Java: class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2tjugqaoi.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gt2grdyukco.html

Ruby: class User; end
来源：http://dali.yongpay.top/Article/details/gt2vfnhmyqo.html

C#:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ivtrhynq.html

[G02] 构造函数
来源：http://dali.shuidangran.top/Article/details/gt2aisfbvch.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgufenzy.top/Article/details/gt2dcxrjmlc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dianchejie.cn/Article/details/gt2ncndkkeu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gt2iiysilto.html

TS:   constructor(public name: string) {}
来源：http://dali.ppjwa.cn/Article/details/gt2dpkactti.html

Java: User(String name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gt2dxqgktkr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.vqdsnc.cn/Article/details/gt2siljudbe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dashuyun.cn/Article/details/gt2fchlsptz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2xwogyxhy.html

[G03] 实例属性
来源：http://dali.zhongyouzk.top/Article/details/gt2oojegyla.html

Py:   self.name = "x"
来源：http://dali.xuanzx.com/Article/details/gt2cauexlgx.html

PHP:  public string $name = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2gsdyjhun.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gt2ckuhijhn.html

TS:   name: string = "x";
来源：http://dali.shuidangran.top/Article/details/gt2ruvoousv.html

Java: private String name;
来源：http://dali.shzxlz.cn/Article/details/gt2bbgcvzju.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gt2uzvngvfh.html

Ruby: @name = "x"
来源：http://dali.chenlongwang.top/Article/details/gt2tdcgucpj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenlongwang.top/Article/details/gt2eqygrptu.html

[G04] 定义方法
来源：http://dali.fzhhl.top/Article/details/gt2wqhmdcwp.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258.top/Article/details/gt2ytxfebvv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gt2sdopkrbj.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2xlldogci.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2frinnaei.html

Java: String greet() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yysczlaa.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gt2yundqynu.html

Ruby: def greet; @name; end
来源：http://dali.sweek.top/Article/details/gt2goijawmu.html

C#:   public string Greet() => Name;
来源：http://dali.pycfn.com/Article/details/gt2qgpnhtnv.html

[G05] 继承
来源：http://dali.ehwqpu.com/Article/details/gt2dtweqvch.html

Py:   class Admin(User): pass
来源：http://dali.tanke756.top/Article/details/gt2iletejpx.html

PHP:  class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gt2xnosetfc.html

JS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2ljnmynaj.html

TS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gt2xvdzktgq.html


<!-- 参考信息 -->