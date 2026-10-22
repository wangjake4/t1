代发 wailian999

TS:   s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2bskmyqlf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qsqrrfxl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.birdmap.top/Article/details/gt2khbshzyh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.c1oappe.top/Article/details/gt2oetgokee.html

C#:   s.Replace("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2zkgqpodk.html

[E07] 按分隔符拆分
来源：http://dali.yongpay.top/Article/details/gt2olgcxinv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dashuyun.cn/Article/details/gt2inryxbdp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2xfihyksf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.havefunace.top/Article/details/gt2kwyhwboy.html

TS:   s.split(",")
来源：http://dali.yj202588.top/Article/details/gt2zwvlppdl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sweek.top/Article/details/gt2gbzfpujz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shzxlz.cn/Article/details/gt2prczcsfl.html

Ruby: s.split(",");  s.split
来源：http://dali.quarkkingdee.top/Article/details/gt2cptemnmi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigufen.top/Article/details/gt2iuhyhtck.html

[E08] 数组按分隔符合并
来源：http://dali.cdnleiting.top/Article/details/gt2itfisgpy.html

Py:   ",".join(items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bwywmclc.html

PHP:  implode(",", $items);
来源：http://dali.aizwys.cn/Article/details/gt2dbksaonm.html

JS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gt2lsteryid.html

TS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gt2zadeecuq.html

Java: String.join(",", items)
来源：http://dali.fzhhl.top/Article/details/gt2lwwlblyu.html

Go:   strings.Join(items, ",")
来源：http://dali.tianlin.xyz/Article/details/gt2nbrxexpp.html

Ruby: items.join(",")
来源：http://dali.cashguo.top/Article/details/gt2tlbzggzm.html

C#:   string.Join(",", items)
来源：http://dali.hammf.cn/Article/details/gt2tjjijrmw.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gt2fnnvsnda.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ybcxt.top/Article/details/gt2wtlgkztc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2qanmgbce.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gt2gjyilxpk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gt2mihxfedg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gt2kxtsumzc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zmaerols.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.haohaochexian.top/Article/details/gt2usxdqvvv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gt2craoetar.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gzhubu.top/Article/details/gt2upohetqk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.redwolf501.top/Article/details/gt2whiksynj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jlsjyb.cn/Article/details/gt2kagearig.html

JS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gt2tyvoxmay.html

TS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gt2yltsepqx.html

Java: String.format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gt2pieokrsp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gt2idettvkd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gt2hhxuzggq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gt2hvnwtuox.html

[E11] 反转字符串
来源：http://dali.xuanzx.com/Article/details/gt2xfsskmac.html

Py:   s[::-1]
来源：http://dali.daxiang520.top/Article/details/gt2erviigvc.html

PHP:  strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gt2ssuxjozs.html

JS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gt2shjvfseb.html

TS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2enjeiwsx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dashuyun.cn/Article/details/gt2ibhltudk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sysykeji.top/Article/details/gt2wcqucfen.html

Ruby: s.reverse
来源：http://dali.zycfv.cn/Article/details/gt2gvkklgaf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gt2jyzzvxiz.html

[E12] 统计某字符出现次数
来源：http://dali.hywenlv.cn/Article/details/gt2yvthodwe.html

Py:   s.count("a")
来源：http://dali.fzhhl.top/Article/details/gt2vhngaxay.html

PHP:  substr_count($s, "a");
来源：http://dali.jiagoushi.top/Article/details/gt2iwwfxxmr.html

JS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gt2guqvuqve.html

TS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gt2shtcmdfr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hysaishi.cn/Article/details/gt2qqphbdwk.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vtalkkzk.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2tteduthz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuetiantiany.cn/Article/details/gt2yliapetx.html

[E13] 逐字符遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2ypzkejrr.html

Py:   for ch in s: print(ch)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2amdcntqx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zycfv.cn/Article/details/gt2myentcec.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gt2rllhcvph.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gt2zbjyyyld.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tianlin.xyz/Article/details/gt2xygsnikd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2ftappifs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hammf.cn/Article/details/gt2ugkmaoww.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tianlin.xyz/Article/details/gt2jamncogd.html

[E14] URL 编码与 Base64
来源：http://dali.gaohongyu789.top/Article/details/gt2pdfldozk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuxming.cn/Article/details/gt2szoxpnld.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ybcxt.top/Article/details/gt2ibbwpgrt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guowangkeji.top/Article/details/gt2fuursnfz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yonumen.top/Article/details/gt2nzokfypj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.c1oappe.top/Article/details/gt2bgxkoazg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shzxlz.cn/Article/details/gt2rlccmeiz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yonumen.top/Article/details/gt2axjguweg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tianlin.xyz/Article/details/gt2sdkwultk.html

[E15] HTML 转义 / 反转义
来源：http://dali.gogol.net.cn/Article/details/gt2sasfegxc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.birdmap.top/Article/details/gt2zhfgmxis.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yangfankeji.com/Article/details/gt2ayhmnojg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2vkithyuu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.316326.xyz/Article/details/gt2bnqrzvxn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.c1oappe.top/Article/details/gt2jkgtyeao.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nnbgeqoz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fzhhl.top/Article/details/gt2ffrcnrxq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.pycfn.com/Article/details/gt2tqmhevrd.html

[E16] 数字千分位
来源：http://dali.chenlongwang.top/Article/details/gt2ppbtpxoa.html

Py:   f"{1234567:,}"
来源：http://dali.xziqi.cn/Article/details/gt2ujsgxmtn.html

PHP:  number_format(1234567);
来源：http://dali.shzxlz.cn/Article/details/gt2iuzxjhmg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gt2eouxwfmy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gt2ehheipbq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gt2nextramn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shuidangran.top/Article/details/gt2yjcqewqy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ehwqpu.com/Article/details/gt2ggbvqwgc.html

C#:   1234567.ToString("N0")
来源：http://dali.iojbl.cn/Article/details/gt2lkzgsdbt.html

[E17] 首字母大写
来源：http://dali.wangshuangyany.cn/Article/details/gt2ztmqbsew.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yuanzhike.top/Article/details/gt2navthvcu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aizwys.cn/Article/details/gt2ngnlkgmm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gt2mizeyuhn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gt2pzgjwqbr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj202588.top/Article/details/gt2cxmfshss.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tianlin.xyz/Article/details/gt2wxldwmcq.html

Ruby: s.capitalize
来源：http://dali.yj20258.top/Article/details/gt2tteyxuio.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tanke756.top/Article/details/gt2mtepkttu.html

[E18] 模板占位符替换
来源：http://dali.gzhubu.top/Article/details/gt2lvztvctj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tian-w.cn/Article/details/gt2ekhrexzb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tian-w.cn/Article/details/gt2mgazyuws.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gt2lrvkdsiz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gt2kukaeaio.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2lgwqykuy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2ygfzoaqs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ivvv.top/Article/details/gt2kwtejuoa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258.top/Article/details/gt2zghadwmy.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gt2psjsthka.html

Py:   s.splitlines()
来源：http://dali.andypj.xyz/Article/details/gt2jxwexxhl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.316326.xyz/Article/details/gt2hcccedan.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gt2njpdczyj.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gt2mxohrdwc.html

Java: s.lines().toList()
来源：http://dali.jyoumei.cn/Article/details/gt2wdnicylh.html

Go:   strings.Split(s, "\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2yzchoynw.html

Ruby: s.lines
来源：http://dali.wangdashe.top/Article/details/gt2gqisdopk.html

C#:   s.Split('\n')
来源：http://dali.nanxuanxn.top/Article/details/gt2wrmgxgfd.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxrrxtt.html

Py:   if not s:
来源：http://dali.jinqigfzy.top/Article/details/gt2bljglksm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenlongwang.top/Article/details/gt2gswvmpwl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jianghu66.top/Article/details/gt2wlqbbpfp.html

TS:   if (s === "") {}
来源：http://dali.yangfankeji.com/Article/details/gt2ivfxhamc.html

Java: if (s.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gt2zmgwxtdg.html

Go:   if s == "" {}
来源：http://dali.tian-w.cn/Article/details/gt2xjkfwxhj.html

Ruby: if s.empty?
来源：http://dali.jinqigfzy.top/Article/details/gt2sxalklhw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nwbrower.top/Article/details/gt2btbrhynq.html

[E21] 超长截断加省略号
来源：http://dali.xinyue.icu/Article/details/gt2absrgzyo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ytzekwsi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gt2ihaxahuu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2plroavxh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gt2ucsmcgii.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2cvfpvyjd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aibaodan.cn/Article/details/gt2qrsckfwg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gt2mxkdvbig.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2dmmnhicq.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2djxjhggd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aizwys.cn/Article/details/gt2umixxlwg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2nvcinkgx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gt2bzmqldzf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.snrcjt.cn/Article/details/gt2zuqkbdnm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guowangkeji.top/Article/details/gt2gskciavo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cucudq.cn/Article/details/gt2ttcyiagv.html

Ruby: s.bytesize;  s.length
来源：http://dali.zycfv.cn/Article/details/gt2rpbsrbsq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gt2xyolynnh.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ikzpifrq.html

F. 文件与目录
来源：http://dali.jyoumei.cn/Article/details/gt2zcambnjn.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2msdqxike.html

[F01] 读取整个文件
来源：http://dali.jqgufenzy.top/Article/details/gt2lcqxwpjq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.snrcjt.cn/Article/details/gt2xyjcthwn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2dxoiuztp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shzxlz.cn/Article/details/gt2buonvlrg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gt2ymtxbmky.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2gxrkfoeg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2huosdkwu.html

Ruby: File.read("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2pbxbhyoy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2tpjlscfm.html

[F02] 逐行读取文件
来源：http://dali.fzhhl.top/Article/details/gt2qjpotzcn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.meibo888.top/Article/details/gt2oecenjjp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.bjfxy.top/Article/details/gt2edhywhda.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gt2xhmpqsvo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gt2vtyvdpzy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ezxsjbnc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kdjoadqj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tanke756.top/Article/details/gt2zglqabgg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hywenlv.cn/Article/details/gt2drvfufly.html

[F03] 写入文件（覆盖）
来源：http://dali.cucudq.cn/Article/details/gt2utfndmbr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vwxycydk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gt2foaenrjk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gt2wgvrmeaa.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gt2aftcauua.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aibaodan.cn/Article/details/gt2mmebsajh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zdqjudy.top/Article/details/gt2ofqvutaw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuxming.cn/Article/details/gt2fmmoeuou.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gt2abivqmky.html

[F04] 追加写入文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2qrbpzdra.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2rzactzws.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dashuyun.cn/Article/details/gt2gfseldht.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gt2palsywta.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gt2hdwyfrtu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.kuanghao11.cn/Article/details/gt2hyujuxus.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2dvdzistg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gt2kyimmlnq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuetiantiany.cn/Article/details/gt2kwdssorp.html

[F05] 判断文件或目录是否存在
来源：http://dali.fengsongda.top/Article/details/gt2uoirkpwz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnxiangtu.top/Article/details/gt2pjgpovsd.html

PHP:  file_exists("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2degitwep.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hthlklrz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2arjqyttj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2znatdfyl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dashuyun.cn/Article/details/gt2owovsnnw.html

Ruby: File.exist?("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2wsjnteyj.html

C#:   File.Exists("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2srrepqgv.html

[F06] 删除文件
来源：http://dali.yonumen.top/Article/details/gt2wzgyoyzt.html

Py:   os.remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2wyngcpdt.html

PHP:  unlink("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2hwguiwns.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2gzzzipxu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2pdekhakb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2erpbvbjz.html

Go:   os.Remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2ztatjjmo.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2kusayopo.html

C#:   File.Delete("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2sohteyel.html

[F07] 创建目录（含多级）
来源：http://dali.yongpay.top/Article/details/gt2mmumfghu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ivvv.top/Article/details/gt2ajxgmkmn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hfpthk.cn/Article/details/gt2ezcplxiu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gt2hgspilkg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tsfqohdi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hywenlv.cn/Article/details/gt2wyutuiyu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aizwys.cn/Article/details/gt2gjkmsurd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ydzc1.top/Article/details/gt2rlfhmrex.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ppjwa.cn/Article/details/gt2yquplsto.html

[F08] 遍历目录
来源：http://dali.xylfe.cn/Article/details/gt2dvaxehwe.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2eyofrtqk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ppjwa.cn/Article/details/gt2omeaxmet.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2gwdafdcd.html

TS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2awtjnwwo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gt2xjjcqogp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yvedp.cn/Article/details/gt2dieuilmv.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2woaxruei.html

C#:   Directory.GetFiles("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mvkavobq.html

[F09] 获取文件大小
来源：http://dali.jinqigufen.top/Article/details/gt2wjgdlkkh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2lihgvygg.html

PHP:  filesize("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2ykkumpny.html

JS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gt2dbwrkjgp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jdztczrq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gt2cznlcfis.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenjidiqi.icu/Article/details/gt2rlnlymfj.html

Ruby: File.size("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2zmwbnahx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cashguo.top/Article/details/gt2dciugdva.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aizwys.cn/Article/details/gt2yvccmekq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2iounlveg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2ycgdyjov.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2uqwhyzok.html

TS:   path.extname("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2yianjywi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.9152youxi.cn/Article/details/gt2ycqimare.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2yzemonlq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2qwpbseak.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kyuaknoq.html

[F11] 复制与移动文件
来源：http://dali.jyoumei.cn/Article/details/gt2vjlvzkid.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2llfheyjx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ybcxt.top/Article/details/gt2ytnyqmvj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gt2nowcntnc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2jxcxetdy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gt2rjgelvfv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dianchejie.cn/Article/details/gt2cintxrqe.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2gimwtozr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.c1oappe.top/Article/details/gt2javvqrna.html

[F12] CSV 读写
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pruipzjq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zycfv.cn/Article/details/gt2buubtoes.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cucudq.cn/Article/details/gt2usdvkuuy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.0kj1m.cn/Article/details/gt2bgdhskkx.html

TS:   // 同上
来源：http://dali.hnxiangtu.top/Article/details/gt2ghoamciu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gt2ovgklhmc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yueranfly.top/Article/details/gt2ufhwnwjw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.havefunace.top/Article/details/gt2cyzqacgz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gzhubu.top/Article/details/gt2awujivtw.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2glpbrqul.html

G. 面向对象
来源：http://dali.smart0.xyz/Article/details/gt2vogqfvxk.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2apssofoq.html

[G01] 定义类
来源：http://dali.zhongyouzk.top/Article/details/gt2akrnmerd.html

Py:   class User: pass
来源：http://dali.gzhubu.top/Article/details/gt2tzupyeip.html

PHP:  class User {}
来源：http://dali.fengsongda.top/Article/details/gt2ovqiimyo.html

JS:   class User {}
来源：http://dali.guannengcc.top/Article/details/gt2sdorcwvf.html

TS:   class User { name: string = ""; }
来源：http://dali.zycfv.cn/Article/details/gt2cyifudtu.html

Java: class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2oqbmfuyv.html

Go:   type User struct { Name string }
来源：http://dali.jinqigfzy.top/Article/details/gt2pzbiaxms.html

Ruby: class User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2atrjlgty.html

C#:   class User {}
来源：http://dali.yj20258888.top/Article/details/gt2anftywpf.html

[G02] 构造函数
来源：http://dali.xziqi.cn/Article/details/gt2osxvlsge.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.birdmap.top/Article/details/gt2iiejohiy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhixingplan.top/Article/details/gt2nkbkspne.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gt2efciqsog.html

TS:   constructor(public name: string) {}
来源：http://dali.zdqjudy.top/Article/details/gt2jelntfka.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2rjruqhbr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dianchejie.cn/Article/details/gt2gizqocyx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sweek.top/Article/details/gt2nfedtzhz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cdnleiting.top/Article/details/gt2sciyrzgo.html

[G03] 实例属性
来源：http://dali.jqgfzy.top/Article/details/gt2esvrezmv.html

Py:   self.name = "x"
来源：http://dali.fengsongda.top/Article/details/gt2amqslhpp.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gt2optpxpzg.html

JS:   this.name = "x";
来源：http://dali.dianchejie.cn/Article/details/gt2uibqhjxq.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mnbhhvdw.html

Java: private String name;
来源：http://dali.meibo888.top/Article/details/gt2pfuavdwt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gt2ofbfytcc.html

Ruby: @name = "x"
来源：http://dali.bjfxy.top/Article/details/gt2nkcdhoir.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenlongwang.top/Article/details/gt2kutsbowr.html

[G04] 定义方法
来源：http://dali.hnqzz.top/Article/details/gt2dejaxdeo.html

Py:   def greet(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gt2knadhbfx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gt2pqcshxfp.html

JS:   greet() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2cyhyhrhx.html

TS:   greet(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2hupljpuw.html

Java: String greet() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2eylmgexm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gt2rqxkkfvl.html

Ruby: def greet; @name; end
来源：http://dali.hammf.cn/Article/details/gt2hlbxysrs.html

C#:   public string Greet() => Name;
来源：http://dali.xylfe.cn/Article/details/gt2ghkhlbgx.html

[G05] 继承
来源：http://dali.xinyue.icu/Article/details/gt2rhrnoqpz.html


<!-- 参考信息 -->