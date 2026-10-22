代发 wailian999

[E06] 替换子串
来源：http://dali.ybcxt.top/Article/details/gtnfroxezs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiltdeejt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ydzc1.top/Article/details/gtxqtnmdrl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtquqsfdde.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtemzmzijg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtbqifwvzo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.9152youxi.cn/Article/details/gtyqufxpzy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtnusqxell.html

C#:   s.Replace("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gthseshtmx.html

[E07] 按分隔符拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbitqsrsw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.quarkkingdee.top/Article/details/gtswexxges.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuxming.cn/Article/details/gtcqzfvsyn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ehwqpu.com/Article/details/gtcadtqcan.html

TS:   s.split(",")
来源：http://dali.chenzaomai.com/Article/details/gthqxflawe.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tanke756.top/Article/details/gthflpxoyj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtvrcypbhq.html

Ruby: s.split(",");  s.split
来源：http://dali.tianlin.xyz/Article/details/gtlfhnszoh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.smart0.xyz/Article/details/gtlhvumigk.html

[E08] 数组按分隔符合并
来源：http://dali.0kj1m.cn/Article/details/gtyxnttioy.html

Py:   ",".join(items)
来源：http://dali.sweek.top/Article/details/gtrebfbewp.html

PHP:  implode(",", $items);
来源：http://dali.xziqi.cn/Article/details/gtbvfoglhw.html

JS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gtzhsbabsw.html

TS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtzifmkobr.html

Java: String.join(",", items)
来源：http://dali.sweek.top/Article/details/gtpgxhrgwp.html

Go:   strings.Join(items, ",")
来源：http://dali.nanxinkj.top/Article/details/gtcotpvbpx.html

Ruby: items.join(",")
来源：http://dali.pycfn.com/Article/details/gtaurefkzx.html

C#:   string.Join(",", items)
来源：http://dali.guannengcc.top/Article/details/gtmqlbglmp.html

[E09] 去除所有空白字符
来源：http://dali.cdnleiting.top/Article/details/gtmlzsongw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenzaomai.com/Article/details/gtohkgfmfh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yongpay.top/Article/details/gtaqsoecvp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gtobeyqjce.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gtsbgfpvto.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.pycfn.com/Article/details/gtelwsoeso.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuanzhike.top/Article/details/gtjpwpkrwi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenzaomai.com/Article/details/gtdvaloyjh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daria6918.cn/Article/details/gtrhulirhy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangdashe.top/Article/details/gthwydtplg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtpyuijtik.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cucudq.cn/Article/details/gtkmpkbyih.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtbjntbizc.html

TS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gtziefzelc.html

Java: String.format("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gtzxufksdb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gthdurkgis.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjberjuez.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hammf.cn/Article/details/gtpnplydkk.html

[E11] 反转字符串
来源：http://dali.xinyue.icu/Article/details/gtntrzwurx.html

Py:   s[::-1]
来源：http://dali.andypj.xyz/Article/details/gtbofxhzpb.html

PHP:  strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtyoyixjqy.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtmrydzuro.html

TS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtppmohijj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxinkj.top/Article/details/gttprxunka.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.iojbl.cn/Article/details/gtsldvorfz.html

Ruby: s.reverse
来源：http://dali.fengsongda.top/Article/details/gttxcpbmiz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gtkbqlkhxh.html

[E12] 统计某字符出现次数
来源：http://dali.fengsongda.top/Article/details/gtgufktklh.html

Py:   s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtfgyrrgoa.html

PHP:  substr_count($s, "a");
来源：http://dali.0kj1m.cn/Article/details/gttccpclxe.html

JS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gtcsaqwdsr.html

TS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gthmhpniux.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cheryme.top/Article/details/gtedlifskz.html

Go:   strings.Count(s, "a")
来源：http://dali.hywenlv.cn/Article/details/gtfdvkijfb.html

Ruby: s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtzernxpsw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxuanxn.top/Article/details/gtmhjbswmj.html

[E13] 逐字符遍历
来源：http://dali.tianlin.xyz/Article/details/gtwyffarww.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258.top/Article/details/gteoqyfmfg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhoulong.xyz/Article/details/gtcjtzzvfz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtehkqprgg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gtrwsgddsc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.birdmap.top/Article/details/gtzimtebux.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtomcquydz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guowangkeji.top/Article/details/gtcyvyixcw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtzmzddiwa.html

[E14] URL 编码与 Base64
来源：http://dali.hysaishi.cn/Article/details/gtxpjwsdcb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aizwys.cn/Article/details/gthekvnsoh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hfpthk.cn/Article/details/gtrnpqupjv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cdnleiting.top/Article/details/gtlehxvpqg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hywenlv.cn/Article/details/gtgrjtrtpl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hysaishi.cn/Article/details/gttyskepbw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpimicjbk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jiagoushi.top/Article/details/gtghivuxjr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.snrcjt.cn/Article/details/gtxbdfjxpr.html

[E15] HTML 转义 / 反转义
来源：http://dali.shzxlz.cn/Article/details/gtcmmnentw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258.top/Article/details/gtmjziwmqf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cashguo.top/Article/details/gtqcrxulsi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnqzz.top/Article/details/gtkzecafgx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cqqwz.cn/Article/details/gtzidyphyw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyfdkbaq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yueranfly.top/Article/details/gtqmkpvfcw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pengpengdd.cyou/Article/details/gttjlmkpas.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sweek.top/Article/details/gtrlnydirl.html

[E16] 数字千分位
来源：http://dali.haohaochexian.top/Article/details/gtenctfspk.html

Py:   f"{1234567:,}"
来源：http://dali.hfpthk.cn/Article/details/gtskvqbkvy.html

PHP:  number_format(1234567);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuuncjiyq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gtobdhvhfl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvuspegkf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gtdrtsakgm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shzxlz.cn/Article/details/gtdoitzhcp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jianghu66.top/Article/details/gtrvvuqlti.html

C#:   1234567.ToString("N0")
来源：http://dali.cdnleiting.top/Article/details/gtqytltbpk.html

[E17] 首字母大写
来源：http://dali.jqgfzy.top/Article/details/gtfrbscehx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcfgefww.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sweek.top/Article/details/gtrxyudrwd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gttiqpbqxk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gtsxhsskea.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xziqi.cn/Article/details/gtzgszhpne.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.vqdsnc.cn/Article/details/gtnrfhsyah.html

Ruby: s.capitalize
来源：http://dali.cheryme.top/Article/details/gtqwkucdty.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnxiangtu.top/Article/details/gtjeurpgnr.html

[E18] 模板占位符替换
来源：http://dali.gzhubu.top/Article/details/gthjkguloy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sysykeji.top/Article/details/gtrkyidtev.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuanzx.com/Article/details/gtcffxufrp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtpgjjzxgb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtrnzhonly.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtgrfkybxl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtalsqitke.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.mhx1999.top/Article/details/gtgsbzqptz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guannengcc.top/Article/details/gteqgjmjwq.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigfzy.top/Article/details/gtzlqtfzrk.html

Py:   s.splitlines()
来源：http://dali.yonumen.top/Article/details/gtsafakmvk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtndjxljkn.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrzocpaw.html

TS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gtbdbwxijo.html

Java: s.lines().toList()
来源：http://dali.sweek.top/Article/details/gtxhbvvmau.html

Go:   strings.Split(s, "\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtdjsfmthg.html

Ruby: s.lines
来源：http://dali.quarkkingdee.top/Article/details/gtuzggpofi.html

C#:   s.Split('\n')
来源：http://dali.vqdsnc.cn/Article/details/gttioxssjp.html

[E20] 判断字符串是否为空
来源：http://dali.sufxvd.cn/Article/details/gtslpivfsr.html

Py:   if not s:
来源：http://dali.vqdsnc.cn/Article/details/gthluycvdb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tianlin.xyz/Article/details/gtkdsqdrtx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj202588.top/Article/details/gtibjvkyuj.html

TS:   if (s === "") {}
来源：http://dali.snrcjt.cn/Article/details/gtenaypyut.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gtwpxifbgz.html

Go:   if s == "" {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtetmswzvm.html

Ruby: if s.empty?
来源：http://dali.feifeiyinyue.top/Article/details/gtfcebwagn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.bjfxy.top/Article/details/gtbqzkizyt.html

[E21] 超长截断加省略号
来源：http://dali.svipenyu.cn/Article/details/gtvwkrwnhw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhengqikj.top/Article/details/gtxtzrjumv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtrggblpti.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtwjjojpzy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtrhtcyjys.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtrispsmed.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxinkj.top/Article/details/gtbgiorevc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtuaymidjr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gttjporjbf.html

[E22] 字节长度与字符长度
来源：http://dali.gaohongyu789.top/Article/details/gtqefbmsyb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yonumen.top/Article/details/gtjdynjmno.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtousfcahg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gtyfjkseto.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gtrzfohsxr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yonumen.top/Article/details/gtdwngxwwz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenzaomai.com/Article/details/gtordnneno.html

Ruby: s.bytesize;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtnkeibdei.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jianghu66.top/Article/details/gtwukjxabp.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gthlbgcjqu.html

F. 文件与目录
来源：http://dali.yj20258.top/Article/details/gtmqwlwvlx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtljtiajks.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gtduktojcy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ppjwa.cn/Article/details/gtvevtylbk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258888.top/Article/details/gttzxupjsv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hywenlv.cn/Article/details/gtpjwbqchu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtfxgrpamd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtplxxbwmw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.316326.xyz/Article/details/gtvsoebxce.html

Ruby: File.read("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtpmzwlvcr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtfljpucds.html

[F02] 逐行读取文件
来源：http://dali.wangdashe.top/Article/details/gtfbpoalkm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxinkj.top/Article/details/gtsqddojry.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.smart0.xyz/Article/details/gtrhwjrbtl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gtqwynxppt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gtgnfeickl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwwffzfz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cashguo.top/Article/details/gtzeptatfy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hammf.cn/Article/details/gtcaawgptx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yvedp.cn/Article/details/gtniwexpbj.html

[F03] 写入文件（覆盖）
来源：http://dali.ybcxt.top/Article/details/gtiuklsfkv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnqzz.top/Article/details/gtohlavyon.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gtkmcdbsaj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtrzqxbycd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gtxknqkvvk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhengqikj.top/Article/details/gtpciztgoh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenjidiqi.icu/Article/details/gtxcxkstfm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnqzz.top/Article/details/gtcryfgjfp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gtfcmtzbya.html

[F04] 追加写入文件
来源：http://dali.sweek.top/Article/details/gtaiqymfkn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nwbrower.top/Article/details/gtbwicuxdr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.9152youxi.cn/Article/details/gthncbcuuk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gthkgrvyek.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtzkwjdkri.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrytcmttt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtkvdezbdt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dashuyun.cn/Article/details/gtvxtwelln.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sxryk.cn/Article/details/gtolkhwpgf.html

[F05] 判断文件或目录是否存在
来源：http://dali.cucudq.cn/Article/details/gtdeafertj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxinkj.top/Article/details/gtwscpfrbn.html

PHP:  file_exists("a.txt");
来源：http://dali.cheryme.top/Article/details/gtoyhmryud.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtfsntxwjw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gttelahale.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtltifzpcl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ppjwa.cn/Article/details/gtbqwulguj.html

Ruby: File.exist?("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtzesswnuq.html

C#:   File.Exists("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzloprmjr.html

[F06] 删除文件
来源：http://dali.dianchejie.cn/Article/details/gtfzfkgbdt.html

Py:   os.remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtcaaobnis.html

PHP:  unlink("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtgxjzabxo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtytugeegu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtxknmpqlb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtkgbjhqnw.html

Go:   os.Remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtltlrtrsh.html

Ruby: File.delete("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtzahqxhzd.html

C#:   File.Delete("a.txt");
来源：http://dali.tanke756.top/Article/details/gtlcdlygmr.html

[F07] 创建目录（含多级）
来源：http://dali.ehwqpu.com/Article/details/gtzomkxdiq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.316326.xyz/Article/details/gthtiawarq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.svipenyu.cn/Article/details/gtavlcmoaw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtnvvzczhb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gtbfuuxyet.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gtiorfheti.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyuhctvjg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.feifeiyinyue.top/Article/details/gtigcuydhs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangdashe.top/Article/details/gtmqyajgda.html

[F08] 遍历目录
来源：http://dali.tanke756.top/Article/details/gtkspmhwsk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gtriixxgpb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aizwys.cn/Article/details/gtornhpjgn.html

JS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gttygesenk.html

TS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gtvugtxwnf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gtzxwnrgek.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jianghu66.top/Article/details/gtcswdglgo.html

Ruby: Dir.children("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtxpwcggjj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sxryk.cn/Article/details/gtymwlnbzv.html

[F09] 获取文件大小
来源：http://dali.ppjwa.cn/Article/details/gtowpkzjwp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtnkumpupa.html

PHP:  filesize("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtaxuywnbz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtueucpwgu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gtjlmbomix.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtbdppmbqe.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.haohaochexian.top/Article/details/gtawtrldgl.html

Ruby: File.size("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtklolzkac.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenlongwang.top/Article/details/gtxblsefmw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.316326.xyz/Article/details/gttymfunas.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtjitovhep.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtqojvmtuk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtcytnlrbd.html

TS:   path.extname("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtupxpqfkz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.feifeiyinyue.top/Article/details/gtorzilyve.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtkivgdula.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtigqsmecu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtwvowdetn.html

[F11] 复制与移动文件
来源：http://dali.tianlin.xyz/Article/details/gtqznrfpfc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtvossbtqt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenlongwang.top/Article/details/gtcvsfulgp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtdtgpywoi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtjwdbndfn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sxryk.cn/Article/details/gtwmrftpnd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gteeotfxfx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtzzttqycx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.c1oappe.top/Article/details/gtwdxoekxw.html

[F12] CSV 读写
来源：http://dali.hfpthk.cn/Article/details/gtxxardpen.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.9152youxi.cn/Article/details/gtcrtbjdlj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sxryk.cn/Article/details/gtolbfqyir.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhongyouzk.top/Article/details/gtbqdjdxki.html

TS:   // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gtgsiqxyvl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hammf.cn/Article/details/gtfzhmefdq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.mhx1999.top/Article/details/gteodnieiq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gtkliuoeug.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangshuangyany.cn/Article/details/gtnendcdkm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtrsuqnlxa.html

G. 面向对象
来源：http://dali.nwbrower.top/Article/details/gtwlfeaudo.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtcgxjdemc.html

[G01] 定义类
来源：http://dali.jlsjyb.cn/Article/details/gtkravvpjx.html

Py:   class User: pass
来源：http://dali.gogol.net.cn/Article/details/gtpkwjcrwq.html

PHP:  class User {}
来源：http://dali.hnqzz.top/Article/details/gtwyfjwolm.html

JS:   class User {}
来源：http://dali.sweek.top/Article/details/gtzdlakvpc.html

TS:   class User { name: string = ""; }
来源：http://dali.xuanzx.com/Article/details/gtvpkhazey.html

Java: class User {}
来源：http://dali.chenzaomai.com/Article/details/gttqbbuesy.html

Go:   type User struct { Name string }
来源：http://dali.yangfankeji.com/Article/details/gtogizzkwk.html

Ruby: class User; end
来源：http://dali.jlsjyb.cn/Article/details/gttaaytmql.html

C#:   class User {}
来源：http://dali.hnqzz.top/Article/details/gtoaniydoo.html

[G02] 构造函数
来源：http://dali.zhixingplan.top/Article/details/gtaizsmdeg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gotoacloud.top/Article/details/gtjgdoxmmx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtielceslf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtcsjbnxpx.html

TS:   constructor(public name: string) {}
来源：http://dali.gzhubu.top/Article/details/gtuixlokbn.html

Java: User(String name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtihyzptdj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cdnleiting.top/Article/details/gtmzjfqkee.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tanke756.top/Article/details/gtmtwgywxf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtcvvdzokj.html

[G03] 实例属性
来源：http://dali.xuetiantiany.cn/Article/details/gtmsnfnsmk.html

Py:   self.name = "x"
来源：http://dali.guannengcc.top/Article/details/gtpddacbbc.html

PHP:  public string $name = "x";
来源：http://dali.gotoacloud.top/Article/details/gttifwhdve.html

JS:   this.name = "x";
来源：http://dali.nanxinkj.top/Article/details/gtajiasoft.html

TS:   name: string = "x";
来源：http://dali.yuxming.cn/Article/details/gtxqtgwzeu.html

Java: private String name;
来源：http://dali.nwbrower.top/Article/details/gtdhfspidx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dashuyun.cn/Article/details/gteerfhoaz.html

Ruby: @name = "x"
来源：http://dali.xziqi.cn/Article/details/gtujjeswdc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuanzx.com/Article/details/gthtnnkjyt.html

[G04] 定义方法
来源：http://dali.cucudq.cn/Article/details/gtklobayri.html

Py:   def greet(self): return self.name
来源：http://dali.sweek.top/Article/details/gtdxyukgof.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtgevcxjun.html

JS:   greet() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtpagdsdjp.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtkwbdgslv.html

Java: String greet() { return name; }
来源：http://dali.cashguo.top/Article/details/gthiddhoma.html


<!-- 参考信息 -->