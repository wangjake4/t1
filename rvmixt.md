代发 wailian999

TS:   s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gt2xguzwvau.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gt2iflpgsra.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gt2ddzkadfu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2rdossleb.html

C#:   s.Replace("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gt2apgkgpzw.html

[E07] 按分隔符拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ikuwwjxs.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zycfv.cn/Article/details/gt2dwcqobwb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2ciivggod.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.havefunace.top/Article/details/gt2zvfffgef.html

TS:   s.split(",")
来源：http://dali.ehwqpu.com/Article/details/gt2nzisxmcv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhoulong.xyz/Article/details/gt2ksrozalx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uwgquhkf.html

Ruby: s.split(",");  s.split
来源：http://dali.aizwys.cn/Article/details/gt2pswgmfnf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.havefunace.top/Article/details/gt2nlnpenjq.html

[E08] 数组按分隔符合并
来源：http://dali.sufxvd.cn/Article/details/gt2mwbmoyni.html

Py:   ",".join(items)
来源：http://dali.chenzaomai.com/Article/details/gt2zwjoidmq.html

PHP:  implode(",", $items);
来源：http://dali.aizwys.cn/Article/details/gt2eojlotbo.html

JS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gt2zdgytaop.html

TS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gt2znabhmnj.html

Java: String.join(",", items)
来源：http://dali.cucudq.cn/Article/details/gt2smuyiimp.html

Go:   strings.Join(items, ",")
来源：http://dali.snrcjt.cn/Article/details/gt2kctvgnem.html

Ruby: items.join(",")
来源：http://dali.mhx1999.top/Article/details/gt2vscfhiay.html

C#:   string.Join(",", items)
来源：http://dali.aizwys.cn/Article/details/gt2mhsfhghx.html

[E09] 去除所有空白字符
来源：http://dali.gogol.net.cn/Article/details/gt2wqyvwlnb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jianghu66.top/Article/details/gt2msnbjozg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2cfbrrjbg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gt2khovfkqw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gt2mtsqsxfl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangdashe.top/Article/details/gt2oleyefon.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hysaishi.cn/Article/details/gt2kusuryhw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tygrtayp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gt2ltriulcb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xziqi.cn/Article/details/gt2iaezujgq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gt2samkzunq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dashuyun.cn/Article/details/gt2cooaprll.html

JS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2djicsils.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gt2qmxibwgj.html

Java: String.format("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gt2drmwqexr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gt2tvmeggmk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gt2fhrameml.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sysykeji.top/Article/details/gt2jobzxwjj.html

[E11] 反转字符串
来源：http://dali.ybcxt.top/Article/details/gt2dfjlewnk.html

Py:   s[::-1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wrytpsag.html

PHP:  strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2rvsyfqly.html

JS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2vhtwdfei.html

TS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2edkokzah.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2yxejxxvo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aibaodan.cn/Article/details/gt2rznudmak.html

Ruby: s.reverse
来源：http://dali.ivvv.top/Article/details/gt2jpulowlx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gt2xqdshzoz.html

[E12] 统计某字符出现次数
来源：http://dali.daria6918.cn/Article/details/gt2weyuybwu.html

Py:   s.count("a")
来源：http://dali.sweek.top/Article/details/gt2xfmodqve.html

PHP:  substr_count($s, "a");
来源：http://dali.meibo888.top/Article/details/gt2kuxcoxmu.html

JS:   s.split("a").length - 1
来源：http://dali.jqgufenzy.top/Article/details/gt2xozsuswd.html

TS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gt2mjnueyqf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhongyouzk.top/Article/details/gt2jsbutfkd.html

Go:   strings.Count(s, "a")
来源：http://dali.zhixingplan.top/Article/details/gt2eppahygm.html

Ruby: s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2xlthcrdy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.smart0.xyz/Article/details/gt2qqzjtely.html

[E13] 逐字符遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2smcajtbm.html

Py:   for ch in s: print(ch)
来源：http://dali.yangfankeji.com/Article/details/gt2fggeschf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cashguo.top/Article/details/gt2fluonnoq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gt2kdxggmdf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gt2hafocrdv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenlongwang.top/Article/details/gt2iflsqzwu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2ezkwkanq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuanzx.com/Article/details/gt2gonlkbqa.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2jadqychr.html

[E14] URL 编码与 Base64
来源：http://dali.pycfn.com/Article/details/gt2mgwvwepc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zycfv.cn/Article/details/gt2boxxnebm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guannengcc.top/Article/details/gt2xjmryafp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daria6918.cn/Article/details/gt2wlewdjjg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.bjfxy.top/Article/details/gt2sbqlndqs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yongpay.top/Article/details/gt2cteehnvj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.iojbl.cn/Article/details/gt2pxvtsnpn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ehwqpu.com/Article/details/gt2bfgyibrd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fpdkgjck.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxinkj.top/Article/details/gt2zpazccmh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tanke756.top/Article/details/gt2vakkdzir.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigufen.top/Article/details/gt2ltfyxstz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shzxlz.cn/Article/details/gt2mhlvwenq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gogol.net.cn/Article/details/gt2tggqcgap.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sufxvd.cn/Article/details/gt2dgspdjzw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2zijjytky.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gzhubu.top/Article/details/gt2natwypwb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fzhhl.top/Article/details/gt2qthstlfd.html

[E16] 数字千分位
来源：http://dali.c1oappe.top/Article/details/gt2bkrbrmol.html

Py:   f"{1234567:,}"
来源：http://dali.mhx1999.top/Article/details/gt2baaijypl.html

PHP:  number_format(1234567);
来源：http://dali.sufxvd.cn/Article/details/gt2tydwtztb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gt2khacsblj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gt2tfyrwcxq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ivvv.top/Article/details/gt2tzeezozn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cucudq.cn/Article/details/gt2jgbsmsnf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nhbbmmvg.html

C#:   1234567.ToString("N0")
来源：http://dali.guannengcc.top/Article/details/gt2veiynxlr.html

[E17] 首字母大写
来源：http://dali.fzhhl.top/Article/details/gt2killshbm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xziqi.cn/Article/details/gt2eisfolau.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.svipenyu.cn/Article/details/gt2zteiumfs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gt2ixaarrhl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gt2umwercvz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ppjwa.cn/Article/details/gt2runycqlt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gogol.net.cn/Article/details/gt2wkjapdzo.html

Ruby: s.capitalize
来源：http://dali.guowangkeji.top/Article/details/gt2eisypuzo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258888.top/Article/details/gt2kxljerdo.html

[E18] 模板占位符替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2bqbxudat.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yuxming.cn/Article/details/gt2eeikjezi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.feifeiyinyue.top/Article/details/gt2feuugnnz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gt2xqjukkty.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lybqjyhe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gt2psglnepe.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.iojbl.cn/Article/details/gt2qhfyyxhx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hysaishi.cn/Article/details/gt2znagzzan.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.316326.xyz/Article/details/gt2kasrkfkm.html

[E19] 多行文本按行拆分
来源：http://dali.shangyingyoupin.top/Article/details/gt2qumelfdd.html

Py:   s.splitlines()
来源：http://dali.hammf.cn/Article/details/gt2bgptjxxq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2dxobloxo.html

JS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gt2qyzgtntd.html

TS:   s.split(/\r?\n/)
来源：http://dali.daria6918.cn/Article/details/gt2lpgpbzbg.html

Java: s.lines().toList()
来源：http://dali.xziqi.cn/Article/details/gt2hlnpvwpe.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxinkj.top/Article/details/gt2slrratqo.html

Ruby: s.lines
来源：http://dali.tianlin.xyz/Article/details/gt2uuproncd.html

C#:   s.Split('\n')
来源：http://dali.wangdashe.top/Article/details/gt2rubkpdgz.html

[E20] 判断字符串是否为空
来源：http://dali.ehwqpu.com/Article/details/gt2xzssqdzm.html

Py:   if not s:
来源：http://dali.yueranfly.top/Article/details/gt2vqzbaobe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tianlin.xyz/Article/details/gt2xqzhqbla.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.redwolf501.top/Article/details/gt2fgbkgexe.html

TS:   if (s === "") {}
来源：http://dali.chenzaomai.com/Article/details/gt2iaysztel.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2plmijqmr.html

Go:   if s == "" {}
来源：http://dali.yuxming.cn/Article/details/gt2fuzikgxo.html

Ruby: if s.empty?
来源：http://dali.ivvv.top/Article/details/gt2jjncgevc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2lfismgyf.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqsbvlid.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258.top/Article/details/gt2vsptohvr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gt2tnvkazmx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gt2rbtrsbuq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2whqwnhqx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2ovhndozq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aibaodan.cn/Article/details/gt2qxhhgbds.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2ryegldep.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2egsrbvek.html

[E22] 字节长度与字符长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ulryhhdd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mcsgmbng.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2tnktgtol.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gt2gfedkvjm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gt2ehqrpvcf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj202588.top/Article/details/gt2yfrflcwe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sweek.top/Article/details/gt2lnqyhrpy.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuxming.cn/Article/details/gt2kopuysev.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jiagoushi.top/Article/details/gt2oaqrewga.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2qranwlws.html

F. 文件与目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2raapighq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2rxaaprmv.html

[F01] 读取整个文件
来源：http://dali.cheryme.top/Article/details/gt2qnhtykni.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qzsucamx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2nxxckwll.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aizwys.cn/Article/details/gt2isgbufrx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.meibo888.top/Article/details/gt2ferpfjov.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gt2ouakckir.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenjidiqi.icu/Article/details/gt2drlojpjl.html

Ruby: File.read("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2ghevfrkz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2ssdybeds.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gloiyxmc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yonumen.top/Article/details/gt2oszdhznz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.0kj1m.cn/Article/details/gt2wbeaxobh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gt2dhjxscvq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gt2dscprcgw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gt2fewwbmbn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxuanxn.top/Article/details/gt2snptfkzd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangdashe.top/Article/details/gt2mwavllht.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.birdmap.top/Article/details/gt2ujjfpeho.html

[F03] 写入文件（覆盖）
来源：http://dali.sysykeji.top/Article/details/gt2ipaxwnlj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.0kj1m.cn/Article/details/gt2uwalsqdp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yrwnxiqf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gt2thdpuogo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gt2ahmibccr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aibaodan.cn/Article/details/gt2kunwgtir.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigufen.top/Article/details/gt2klyomfww.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yueranfly.top/Article/details/gt2tzkqdclk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gt2frjcwmxa.html

[F04] 追加写入文件
来源：http://dali.snrcjt.cn/Article/details/gt2mehnlfcy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tanke756.top/Article/details/gt2qbwuectg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhixingplan.top/Article/details/gt2putptbjc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2waqpyzlz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gt2gffyqpov.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxinkj.top/Article/details/gt2kwvxypet.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hfpthk.cn/Article/details/gt2eukkwljc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tian-w.cn/Article/details/gt2sourpfuc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gt2gfxehhgx.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnxiangtu.top/Article/details/gt2yrmhtdkf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xziqi.cn/Article/details/gt2ovpiganq.html

PHP:  file_exists("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2qscfkxed.html

JS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2qcvrtwuk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nnwsaodz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2xmiirarl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dashuyun.cn/Article/details/gt2moiihqzx.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2sfwvkohg.html

C#:   File.Exists("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2fvunxinx.html

[F06] 删除文件
来源：http://dali.yonumen.top/Article/details/gt2mhhivxby.html

Py:   os.remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2nafngkdw.html

PHP:  unlink("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2dtvcrvua.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kybvljtl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2gnmdqkgx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2sjcfyajg.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rvmhxpco.html

Ruby: File.delete("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2qfixjdka.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tofhxieh.html

[F07] 创建目录（含多级）
来源：http://dali.dashuyun.cn/Article/details/gt2mexvwtpi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gt2zgiwsvex.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gt2pvjzalyw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gt2gisvmtiy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gt2tikexikv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenzaomai.com/Article/details/gt2bgfjwipr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yueranfly.top/Article/details/gt2qnunktzk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sysykeji.top/Article/details/gt2kbcmkqmw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuetiantiany.cn/Article/details/gt2obgqdmwd.html

[F08] 遍历目录
来源：http://dali.cdnleiting.top/Article/details/gt2uegiyteg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yongpay.top/Article/details/gt2gtlzslxp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cashguo.top/Article/details/gt2gjmhjbmp.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rxqgvdoe.html

TS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2oaztlkgh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cldsiiso.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2dlusvzvs.html

Ruby: Dir.children("dir")
来源：http://dali.wangdashe.top/Article/details/gt2chkdarcg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2ctiygscb.html

[F09] 获取文件大小
来源：http://dali.quarkkingdee.top/Article/details/gt2bggowecj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2bezgzvvd.html

PHP:  filesize("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2kpinsrbk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gt2ysadbweg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gt2xtxvwoke.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2nvswjjio.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pycfn.com/Article/details/gt2rwbmgeuh.html

Ruby: File.size("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2wbexljqc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mjysmtlp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.9152youxi.cn/Article/details/gt2factidcb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2awnuoizi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2zolowevo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2gmzktqns.html

TS:   path.extname("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2djfdptje.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gt2mmonkyae.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2yisfckml.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2ijygsoyl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2gwwiphpk.html

[F11] 复制与移动文件
来源：http://dali.ehwqpu.com/Article/details/gt2fchjvsgq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gt2ctfpxulg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shuidangran.top/Article/details/gt2cfmduopv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gt2xghqgnrb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2qogdjisn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gogol.net.cn/Article/details/gt2hjvkrlzk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dashuyun.cn/Article/details/gt2zlpjbxnh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2bsbmvnsk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eeqqopme.html

[F12] CSV 读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wbbgwfwo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gt2chekwtup.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gogol.net.cn/Article/details/gt2ihuoqwlf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daxiang520.top/Article/details/gt2mszotkix.html

TS:   // 同上
来源：http://dali.yj20258888.top/Article/details/gt2yruvcywo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jianghu66.top/Article/details/gt2dchxtxmb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jyoumei.cn/Article/details/gt2wbavomlu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aibaodan.cn/Article/details/gt2xnlvhixr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aizwys.cn/Article/details/gt2jnqcoiuf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2flwyitgz.html

G. 面向对象
来源：http://dali.kuanghao11.cn/Article/details/gt2qxqwaqzp.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2triokole.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gt2iazrxxqt.html

Py:   class User: pass
来源：http://dali.dashuyun.cn/Article/details/gt2bnlsulle.html

PHP:  class User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2achmpgfd.html

JS:   class User {}
来源：http://dali.daria6918.cn/Article/details/gt2aehmdiub.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kecsdabx.html

Java: class User {}
来源：http://dali.gotoacloud.top/Article/details/gt2jswtbahu.html

Go:   type User struct { Name string }
来源：http://dali.zhengqikj.top/Article/details/gt2rstjcggh.html

Ruby: class User; end
来源：http://dali.hammf.cn/Article/details/gt2mdkkxwbc.html

C#:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2kujdrscc.html

[G02] 构造函数
来源：http://dali.zhoulong.xyz/Article/details/gt2wahlkzie.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.havefunace.top/Article/details/gt2kzxdjrir.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gt2nccwoibu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2fmzpgalx.html

TS:   constructor(public name: string) {}
来源：http://dali.svipenyu.cn/Article/details/gt2xkusnmgw.html

Java: User(String name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gt2lxntngpg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sufxvd.cn/Article/details/gt2qozqcomd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jianghu66.top/Article/details/gt2hkqdnqiq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2onlmfmvp.html

[G03] 实例属性
来源：http://dali.zycfv.cn/Article/details/gt2thoxnulv.html

Py:   self.name = "x"
来源：http://dali.ivvv.top/Article/details/gt2daubmruo.html

PHP:  public string $name = "x";
来源：http://dali.yj20258888.top/Article/details/gt2fpxdvkat.html

JS:   this.name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gt2ijbqwgtk.html

TS:   name: string = "x";
来源：http://dali.hnqzz.top/Article/details/gt2gshkmdnm.html

Java: private String name;
来源：http://dali.0kj1m.cn/Article/details/gt2hbjjacqk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gt2qzitibaf.html

Ruby: @name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gt2zadvgrnd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hammf.cn/Article/details/gt2uedyfedj.html

[G04] 定义方法
来源：http://dali.andypj.xyz/Article/details/gt2zkoiqenw.html

Py:   def greet(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gt2wqwfpqnb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gt2rvqvqjan.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2cyidobfb.html

TS:   greet(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gt2uopqglgd.html

Java: String greet() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2tiavtnml.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gt2clhjfiep.html

Ruby: def greet; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2efstabst.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gt2qpoplzir.html

[G05] 继承
来源：http://dali.hfpthk.cn/Article/details/gt2ntpgyygg.html


<!-- 参考信息 -->