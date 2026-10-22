代发 wailian999

TS:   s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtchctudrc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtfyymjjrv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtelshxrcf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gttxzihldz.html

C#:   s.Replace("a", "b")
来源：http://dali.birdmap.top/Article/details/gtotrpcpoq.html

[E07] 按分隔符拆分
来源：http://dali.dianchejie.cn/Article/details/gtbclrtbjd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xziqi.cn/Article/details/gtizrwohox.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtvjndzall.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cheryme.top/Article/details/gtnzqqcjdv.html

TS:   s.split(",")
来源：http://dali.jinqigufen.top/Article/details/gtyhpobzrh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.svipenyu.cn/Article/details/gtizpvfvfv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.fengsongda.top/Article/details/gtkfetalwb.html

Ruby: s.split(",");  s.split
来源：http://dali.sxryk.cn/Article/details/gtaqlzomdy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sysykeji.top/Article/details/gthnfpmzcs.html

[E08] 数组按分隔符合并
来源：http://dali.ppjwa.cn/Article/details/gtlqwaupqg.html

Py:   ",".join(items)
来源：http://dali.yongpay.top/Article/details/gtbmbkellr.html

PHP:  implode(",", $items);
来源：http://dali.svipenyu.cn/Article/details/gtitfldajr.html

JS:   items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtndsquvfy.html

TS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gtzmdxlbxv.html

Java: String.join(",", items)
来源：http://dali.chenzaomai.com/Article/details/gtwcakpuvi.html

Go:   strings.Join(items, ",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhftrgbg.html

Ruby: items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtlbbvfwea.html

C#:   string.Join(",", items)
来源：http://dali.haohaochexian.top/Article/details/gtrzlqwrtr.html

[E09] 去除所有空白字符
来源：http://dali.zhoulong.xyz/Article/details/gtdkufjnys.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.bjfxy.top/Article/details/gtfimgwkog.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtrkmqkmox.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gtxnadycxh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gtcyzcbtge.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tianlin.xyz/Article/details/gtpcwomudx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuetiantiany.cn/Article/details/gtxezsfual.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.havefunace.top/Article/details/gtyfvflazq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gtwdjuhwes.html

[E10] 左侧补零 / 定长填充
来源：http://dali.havefunace.top/Article/details/gtmmvubiid.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmkklekb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ydzc1.top/Article/details/gtihzxsiga.html

JS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gttghzjzvs.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtvlqfwtvd.html

Java: String.format("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsirqxbzl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gthnngibrx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtvxkacktm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gogol.net.cn/Article/details/gthtauwtpv.html

[E11] 反转字符串
来源：http://dali.chenlongwang.top/Article/details/gtmcotfdqo.html

Py:   s[::-1]
来源：http://dali.xziqi.cn/Article/details/gtzqhdktxf.html

PHP:  strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gtgdnzfnar.html

JS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtzzmmkhfl.html

TS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtfxlfihwh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.svipenyu.cn/Article/details/gtinwoikrm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtnnybtawc.html

Ruby: s.reverse
来源：http://dali.dianchejie.cn/Article/details/gtydxdjxix.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gthtubmcbe.html

[E12] 统计某字符出现次数
来源：http://dali.yanxiufei.cn/Article/details/gtpzsbmdkw.html

Py:   s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gtgeqjuebo.html

PHP:  substr_count($s, "a");
来源：http://dali.yj202588.top/Article/details/gtwdzmjwwr.html

JS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtbfulzczw.html

TS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gtsvagpewi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sufxvd.cn/Article/details/gtcdihoftv.html

Go:   strings.Count(s, "a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujvbzbfm.html

Ruby: s.count("a")
来源：http://dali.hnqzz.top/Article/details/gtdsenvehf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gzhubu.top/Article/details/gttfmgbpvv.html

[E13] 逐字符遍历
来源：http://dali.iojbl.cn/Article/details/gtmjedhflh.html

Py:   for ch in s: print(ch)
来源：http://dali.iojbl.cn/Article/details/gtowivazky.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gtskcagoao.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gtojzkfamt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlavpqxsr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daxiang520.top/Article/details/gtytwtihxp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxinkj.top/Article/details/gtmcahabuj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gtnvrchtav.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtdwightwz.html

[E14] URL 编码与 Base64
来源：http://dali.0kj1m.cn/Article/details/gtokshuade.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhongyouzk.top/Article/details/gtuivnpbaq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dashuyun.cn/Article/details/gtktrydmol.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.9152youxi.cn/Article/details/gtvnapuoeu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtnrowzoco.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cashguo.top/Article/details/gtvyvzqddd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cqqwz.cn/Article/details/gtintnjtkb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gtzgxbwalg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtrqscdgwe.html

[E15] HTML 转义 / 反转义
来源：http://dali.snrcjt.cn/Article/details/gteggakfgv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jianghu66.top/Article/details/gtorrzrowz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fzhhl.top/Article/details/gtcyeqrkez.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tianlin.xyz/Article/details/gthbnoluog.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmalrezo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tianlin.xyz/Article/details/gtszofmddv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigufen.top/Article/details/gtfpjoglvt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zycfv.cn/Article/details/gtjzmfjjsl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zdqjudy.top/Article/details/gtnophyyfi.html

[E16] 数字千分位
来源：http://dali.gotoacloud.top/Article/details/gtkmclhoeq.html

Py:   f"{1234567:,}"
来源：http://dali.ivvv.top/Article/details/gtuhsmchio.html

PHP:  number_format(1234567);
来源：http://dali.vqdsnc.cn/Article/details/gtrgpjvvlu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyotrlehn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gthtqutvym.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yanxiufei.cn/Article/details/gtgdkfdwff.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhoulong.xyz/Article/details/gttiwnqdkx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gotoacloud.top/Article/details/gtwsfwcanc.html

C#:   1234567.ToString("N0")
来源：http://dali.fzhhl.top/Article/details/gtdonhcoiy.html

[E17] 首字母大写
来源：http://dali.zhongyouzk.top/Article/details/gtdtqdowhr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hongshengwenyu.top/Article/details/gtytwytpnb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xylfe.cn/Article/details/gtcpueeqaj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gtzgszhtub.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gtpxetngur.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.haohaochexian.top/Article/details/gtfdayfzvd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdinwkbz.html

Ruby: s.capitalize
来源：http://dali.aizwys.cn/Article/details/gtthbryfpz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shangyingyoupin.top/Article/details/gtgmiwogzm.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwyjncbn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.redwolf501.top/Article/details/gtostrcabi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.redwolf501.top/Article/details/gtjpggsnkt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtqfrgjipv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtbecpppqh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtxmowxgni.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtjmjrxzhy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cucudq.cn/Article/details/gthznjkcoz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gzhubu.top/Article/details/gtedffzxva.html

[E19] 多行文本按行拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtwejfgxge.html

Py:   s.splitlines()
来源：http://dali.fengsongda.top/Article/details/gtjgolavnk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtnlpomhov.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlovftqds.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gtemrcbmea.html

Java: s.lines().toList()
来源：http://dali.tian-w.cn/Article/details/gtqwtdkice.html

Go:   strings.Split(s, "\n")
来源：http://dali.sxryk.cn/Article/details/gtgyoihxoh.html

Ruby: s.lines
来源：http://dali.jianghu66.top/Article/details/gtqmixkmdg.html

C#:   s.Split('\n')
来源：http://dali.xuanzx.com/Article/details/gtpalsmlqd.html

[E20] 判断字符串是否为空
来源：http://dali.snrcjt.cn/Article/details/gtlhmcewob.html

Py:   if not s:
来源：http://dali.sufxvd.cn/Article/details/gtykbcvmji.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.c1oappe.top/Article/details/gtvdwlrosb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvuqukhn.html

TS:   if (s === "") {}
来源：http://dali.cdnleiting.top/Article/details/gtmdfdhcno.html

Java: if (s.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gtrpzwbnyy.html

Go:   if s == "" {}
来源：http://dali.yanxiufei.cn/Article/details/gtsfpfbcrx.html

Ruby: if s.empty?
来源：http://dali.jlsjyb.cn/Article/details/gtjbptacxq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daria6918.cn/Article/details/gtehfnnujl.html

[E21] 超长截断加省略号
来源：http://dali.9152youxi.cn/Article/details/gtzyovpqat.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jiagoushi.top/Article/details/gtxublhskr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtaxbjimbt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtkfjlrxtx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtiatkkckp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtmcmmnekm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gteqvphntb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtnyqovqno.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtdbiixydr.html

[E22] 字节长度与字符长度
来源：http://dali.yanxiufei.cn/Article/details/gtqgqbrjrn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pycfn.com/Article/details/gtdzwrxrbu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtbnjnxnzn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gtsibudrxj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtglxqbcbr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guannengcc.top/Article/details/gtfjhpjzcv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tanke756.top/Article/details/gtnalwnjdd.html

Ruby: s.bytesize;  s.length
来源：http://dali.ivvv.top/Article/details/gtvpivmehh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xinyue.icu/Article/details/gtvxqdpzmt.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtywrjijti.html

F. 文件与目录
来源：http://dali.yongpay.top/Article/details/gthuilbldi.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtbigtqofm.html

[F01] 读取整个文件
来源：http://dali.cqqwz.cn/Article/details/gtfsphfwnt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hammf.cn/Article/details/gtybrrvzue.html

PHP:  file_get_contents("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtcibvybjt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhengqikj.top/Article/details/gtsxugltbc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtkqiiypmo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtengkelmn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhongyouzk.top/Article/details/gtewlawolo.html

Ruby: File.read("a.txt")
来源：http://dali.cashguo.top/Article/details/gtvdfvemft.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzkooxdd.html

[F02] 逐行读取文件
来源：http://dali.zhixingplan.top/Article/details/gtnssyxudt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pycfn.com/Article/details/gtmzkukfoe.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daxiang520.top/Article/details/gtetkufshv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtfvpquxed.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gtzcxkuolw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtzmnkkhxc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.0kj1m.cn/Article/details/gtnaujvevz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cheryme.top/Article/details/gtmkmtjyqm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigufen.top/Article/details/gtereptxoq.html

[F03] 写入文件（覆盖）
来源：http://dali.snrcjt.cn/Article/details/gtxupmorka.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zycfv.cn/Article/details/gtkvlmrerv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hnxiangtu.top/Article/details/gtglczkiqp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gtlnyvbesr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtqkzhptur.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tianlin.xyz/Article/details/gtevutlpmd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hfpthk.cn/Article/details/gthhqemhrj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuxming.cn/Article/details/gtenizyyex.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gtwnuyqslz.html

[F04] 追加写入文件
来源：http://dali.yj20258888.top/Article/details/gtxrpkzznh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gtwzjtobod.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigfzy.top/Article/details/gtsmzmdwwf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtnwvffrmg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtqmuaavtv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gaohongyu789.top/Article/details/gtyvgcuxls.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.316326.xyz/Article/details/gtnrbreyzi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daria6918.cn/Article/details/gtbsmdfrdu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hysaishi.cn/Article/details/gtfnachvwp.html

[F05] 判断文件或目录是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkktgredv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gtsuycjbsr.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtmgeuycal.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtllajhkvz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtasoiqgbi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtzvvjgkoc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cashguo.top/Article/details/gtktctoldw.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gttjtfxnqt.html

C#:   File.Exists("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtawnajgbv.html

[F06] 删除文件
来源：http://dali.fzhhl.top/Article/details/gtskefvzyc.html

Py:   os.remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtkmuncyol.html

PHP:  unlink("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtnclpyoka.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtjzcduolt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtksuedmit.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gthizhhybx.html

Go:   os.Remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gttjfuqgoa.html

Ruby: File.delete("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtdbjfannm.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gttfvohjng.html

[F07] 创建目录（含多级）
来源：http://dali.pengpengdd.cyou/Article/details/gtvdegzzog.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sweek.top/Article/details/gtucwvoizu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigfzy.top/Article/details/gtzxfljnpo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gthaphcmyr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gtkzoabxev.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.kuanghao11.cn/Article/details/gtzokaqmdz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyweaggnf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258888.top/Article/details/gtppqzgmxo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnqzz.top/Article/details/gtihwzxqbt.html

[F08] 遍历目录
来源：http://dali.birdmap.top/Article/details/gtzdconhdh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.kuanghao11.cn/Article/details/gtzipxatem.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.haohaochexian.top/Article/details/gtthpyrvnf.html

JS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gtycbsvlee.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gttuyssukq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gtepcpajuk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gogol.net.cn/Article/details/gtoaywbozd.html

Ruby: Dir.children("dir")
来源：http://dali.hywenlv.cn/Article/details/gtrcshvakn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gogol.net.cn/Article/details/gtxylqrzgc.html

[F09] 获取文件大小
来源：http://dali.jinqigufen.top/Article/details/gtrzljgfse.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258.top/Article/details/gtpkoqzupg.html

PHP:  filesize("a.txt");
来源：http://dali.nwbrower.top/Article/details/gttiwffujj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gtmyddjsqv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gtdluyagih.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsybndfd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenzaomai.com/Article/details/gtquealmua.html

Ruby: File.size("a.txt")
来源：http://dali.cashguo.top/Article/details/gtmojviadq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shuidangran.top/Article/details/gtytkyxrsu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zdqjudy.top/Article/details/gtprfbjfsg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gttyedyuui.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtsadksjpw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtufnjssrl.html

TS:   path.extname("a.txt")
来源：http://dali.yonumen.top/Article/details/gtldplgzdx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sweek.top/Article/details/gtyatydvsj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtyrlhmvpq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtkudamzmb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gthcfwgbkp.html

[F11] 复制与移动文件
来源：http://dali.redwolf501.top/Article/details/gtavmblyow.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtbatvvzxw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.mhx1999.top/Article/details/gtdpglpkfs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtgqojvhsv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtosrdmdss.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuanzx.com/Article/details/gtczrmucev.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yongpay.top/Article/details/gteompqukm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtekmzmuae.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yueranfly.top/Article/details/gtaxnhihjq.html

[F12] CSV 读写
来源：http://dali.hysaishi.cn/Article/details/gtalirngpy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj202588.top/Article/details/gtdnuvcgvy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shuidangran.top/Article/details/gtapnosepq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258.top/Article/details/gtbxyfsrrh.html

TS:   // 同上
来源：http://dali.tanke756.top/Article/details/gthixvigkw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ppjwa.cn/Article/details/gtnaptplim.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guannengcc.top/Article/details/gtuftzanay.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hfpthk.cn/Article/details/gtdsqyopvi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jiagoushi.top/Article/details/gtaseichjq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvtrlklc.html

G. 面向对象
来源：http://dali.dianchejie.cn/Article/details/gtczwxkfhu.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gthtlppiqe.html

[G01] 定义类
来源：http://dali.shangyingyoupin.top/Article/details/gtgnvfhgou.html

Py:   class User: pass
来源：http://dali.yj20258888.top/Article/details/gtpqzxnlml.html

PHP:  class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gttyttsgyg.html

JS:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gtofktemod.html

TS:   class User { name: string = ""; }
来源：http://dali.xinyue.icu/Article/details/gtxmbmedgf.html

Java: class User {}
来源：http://dali.yongpay.top/Article/details/gtsgsfgink.html

Go:   type User struct { Name string }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrbhhfje.html

Ruby: class User; end
来源：http://dali.jiagoushi.top/Article/details/gtgfpfkuds.html

C#:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gtqwtxusyb.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gtoijshldh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gtlnejtvfk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtmzdzchqf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtdzdikzmz.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gtqpgclknv.html

Java: User(String name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gtkyznsyhh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangdashe.top/Article/details/gtmesffsqh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenzaomai.com/Article/details/gtileofhlf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zycfv.cn/Article/details/gtarcncraa.html

[G03] 实例属性
来源：http://dali.ydzc1.top/Article/details/gtfahnyfts.html

Py:   self.name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gttavtrxbq.html

PHP:  public string $name = "x";
来源：http://dali.cheryme.top/Article/details/gtszckayom.html

JS:   this.name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtdeuzobfr.html

TS:   name: string = "x";
来源：http://dali.cdnleiting.top/Article/details/gtlumxgmik.html

Java: private String name;
来源：http://dali.jiagoushi.top/Article/details/gtbsyhyaqw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenlongwang.top/Article/details/gtecbrgxzb.html

Ruby: @name = "x"
来源：http://dali.wangdashe.top/Article/details/gthhayddnw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zdqjudy.top/Article/details/gtwktbmpnz.html

[G04] 定义方法
来源：http://dali.tianlin.xyz/Article/details/gtbivijjsw.html

Py:   def greet(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtakhcofay.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtnqhupdxr.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtmwutzhhu.html

TS:   greet(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtocqizzkk.html

Java: String greet() { return name; }
来源：http://dali.cheryme.top/Article/details/gtohplgykg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtcrhkivyj.html

Ruby: def greet; @name; end
来源：http://dali.yj20258888.top/Article/details/gttzvysrry.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258888.top/Article/details/gtdvzbadvl.html

[G05] 继承
来源：http://dali.cucudq.cn/Article/details/gtumuhjtvv.html


<!-- 参考信息 -->