代发 wailian999

[E06] 替换子串
来源：http://dali.xziqi.cn/Article/details/gt2putcmmlf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gt2weecftpz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nhaqnihl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2ajznghhz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gt2kgbonyuk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2jddwfzws.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2elbudqmw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2mzxqmmdj.html

C#:   s.Replace("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2qdwecdyk.html

[E07] 按分隔符拆分
来源：http://dali.jiagoushi.top/Article/details/gt2nbzyvvxj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yongpay.top/Article/details/gt2ucmgxtvp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2iritmgwb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxinkj.top/Article/details/gt2tacitjuy.html

TS:   s.split(",")
来源：http://dali.iojbl.cn/Article/details/gt2gmpooimf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yvedp.cn/Article/details/gt2uokiezqc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daria6918.cn/Article/details/gt2ztrprxhj.html

Ruby: s.split(",");  s.split
来源：http://dali.shangyingyoupin.top/Article/details/gt2gudjfluf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.havefunace.top/Article/details/gt2jdcucopf.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gt2evirsqwk.html

Py:   ",".join(items)
来源：http://dali.zdqjudy.top/Article/details/gt2navusguk.html

PHP:  implode(",", $items);
来源：http://dali.birdmap.top/Article/details/gt2jqdqehmv.html

JS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gt2guvjlxiv.html

TS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gt2oblphaef.html

Java: String.join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gt2zlrjuscf.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zhmzqdvo.html

Ruby: items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gt2ykozfydp.html

C#:   string.Join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gt2xrtiiqxt.html

[E09] 去除所有空白字符
来源：http://dali.fzhhl.top/Article/details/gt2xcqqgoho.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ommkwyzi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2nuwbhzlq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xpfqvxvy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gt2azycjnin.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gt2nynpfwxu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zycfv.cn/Article/details/gt2vmckmagq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.mhx1999.top/Article/details/gt2empnuvae.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sxryk.cn/Article/details/gt2hteywtwm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yueranfly.top/Article/details/gt2fzikzaia.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gt2gmqenaat.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hywenlv.cn/Article/details/gt2lhjgenjh.html

JS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gt2yqwjkbbk.html

TS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gt2gqnwmbue.html

Java: String.format("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gt2kzmirpgy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gt2phewrgvf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gt2twmylejc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ybcxt.top/Article/details/gt2dvwuovsv.html

[E11] 反转字符串
来源：http://dali.yangfankeji.com/Article/details/gt2waaarxrw.html

Py:   s[::-1]
来源：http://dali.ybcxt.top/Article/details/gt2leiojwyy.html

PHP:  strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2vjowotqv.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2checduwk.html

TS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2padwhvql.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tanke756.top/Article/details/gt2zovewqbh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.meibo888.top/Article/details/gt2lpcdovav.html

Ruby: s.reverse
来源：http://dali.birdmap.top/Article/details/gt2mdablhrt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zycfv.cn/Article/details/gt2awatkeab.html

[E12] 统计某字符出现次数
来源：http://dali.andypj.xyz/Article/details/gt2djtfpuin.html

Py:   s.count("a")
来源：http://dali.fzhhl.top/Article/details/gt2afawpjid.html

PHP:  substr_count($s, "a");
来源：http://dali.feifeiyinyue.top/Article/details/gt2yekrbziq.html

JS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gt2bhihlllq.html

TS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gt2hwjnpeld.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shuidangran.top/Article/details/gt2wrtiqcon.html

Go:   strings.Count(s, "a")
来源：http://dali.ydzc1.top/Article/details/gt2gsgxrwsi.html

Ruby: s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gt2oqyndyct.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aizwys.cn/Article/details/gt2ktpybjbm.html

[E13] 逐字符遍历
来源：http://dali.guannengcc.top/Article/details/gt2bxyerger.html

Py:   for ch in s: print(ch)
来源：http://dali.haohaochexian.top/Article/details/gt2ktttmxmh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2awfjmvne.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gt2ibsgknnk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gt2fmowutfd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigufen.top/Article/details/gt2ihhkpgux.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ivvv.top/Article/details/gt2rcbgnbbr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yangfankeji.com/Article/details/gt2onjmjwqm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2wlcjwvuc.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gt2tikltaav.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.andypj.xyz/Article/details/gt2tmebmdqw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2puahqoll.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yvedp.cn/Article/details/gt2ijxosuxr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyuwtel.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xziqi.cn/Article/details/gt2ryubaqzr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jlsjyb.cn/Article/details/gt2plhfcglz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sweek.top/Article/details/gt2ifntedsd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qmqlrpng.html

[E15] HTML 转义 / 反转义
来源：http://dali.9152youxi.cn/Article/details/gt2lixxujvk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ppjwa.cn/Article/details/gt2fvxizaxq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangdashe.top/Article/details/gt2vbsfqvun.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuxming.cn/Article/details/gt2dynbqwbu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pengpengdd.cyou/Article/details/gt2lrrwcwgo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cheryme.top/Article/details/gt2goqeqzif.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.birdmap.top/Article/details/gt2kiufaomt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xylfe.cn/Article/details/gt2jbifikpj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tian-w.cn/Article/details/gt2fdwezasp.html

[E16] 数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gt2qahsvfdn.html

Py:   f"{1234567:,}"
来源：http://dali.daria6918.cn/Article/details/gt2jmoxtnpz.html

PHP:  number_format(1234567);
来源：http://dali.bjfxy.top/Article/details/gt2hwpwssdo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gt2cymmeluq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gt2tidoecfk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yonumen.top/Article/details/gt2aaflzbuz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tian-w.cn/Article/details/gt2pdqzxhsd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xinyue.icu/Article/details/gt2cvramyej.html

C#:   1234567.ToString("N0")
来源：http://dali.hammf.cn/Article/details/gt2effzuysx.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdafbhz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gt2txcwblfv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.bjfxy.top/Article/details/gt2lgmxhjqx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2wipvtrsa.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gt2gjsjobbz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yongpay.top/Article/details/gt2onyqnbfn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.mhx1999.top/Article/details/gt2xxkookps.html

Ruby: s.capitalize
来源：http://dali.yonumen.top/Article/details/gt2qbmkckcv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xllxieru.html

[E18] 模板占位符替换
来源：http://dali.zycfv.cn/Article/details/gt2drpurkrk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shzxlz.cn/Article/details/gt2nrekvyyj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigufen.top/Article/details/gt2mfnekqsu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2myttykpm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gt2hbqzdkih.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gt2ruunakte.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2paugicev.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcedgcbs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2eztwqvkp.html

[E19] 多行文本按行拆分
来源：http://dali.zycfv.cn/Article/details/gt2kjnvlljx.html

Py:   s.splitlines()
来源：http://dali.cheryme.top/Article/details/gt2sqacudkk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2jqiaxsec.html

JS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gt2xzzjafkb.html

TS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gt2itpthjxv.html

Java: s.lines().toList()
来源：http://dali.zdqjudy.top/Article/details/gt2mdsyziib.html

Go:   strings.Split(s, "\n")
来源：http://dali.xinyue.icu/Article/details/gt2rzstnqyb.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfkpotf.html

C#:   s.Split('\n')
来源：http://dali.chenzaomai.com/Article/details/gt2vhfibzhi.html

[E20] 判断字符串是否为空
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dsllhowv.html

Py:   if not s:
来源：http://dali.yuxming.cn/Article/details/gt2rimmdslg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.bjfxy.top/Article/details/gt2kyqnxowt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ivvv.top/Article/details/gt2drsdlnpr.html

TS:   if (s === "") {}
来源：http://dali.vqdsnc.cn/Article/details/gt2amlnrgqr.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ssrrsnkj.html

Go:   if s == "" {}
来源：http://dali.yj20258.top/Article/details/gt2ygjyfseh.html

Ruby: if s.empty?
来源：http://dali.iojbl.cn/Article/details/gt2qngekfor.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.smart0.xyz/Article/details/gt2cezookjx.html

[E21] 超长截断加省略号
来源：http://dali.shangyingyoupin.top/Article/details/gt2ezvjkojb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.bjfxy.top/Article/details/gt2thotbffr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.havefunace.top/Article/details/gt2tpnyjxnm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gt2rwtfhkkm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gt2ittntrbo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2oosdemcj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yonumen.top/Article/details/gt2iphkhzsj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gt2ndjfppsy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2sfhiiiuq.html

[E22] 字节长度与字符长度
来源：http://dali.shzxlz.cn/Article/details/gt2padswnar.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yueranfly.top/Article/details/gt2suxtkkjd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gt2rsjwwlkd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gt2seybjsfc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gt2egcbuyda.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gzhubu.top/Article/details/gt2oifecaqa.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hysaishi.cn/Article/details/gt2syrjywso.html

Ruby: s.bytesize;  s.length
来源：http://dali.aizwys.cn/Article/details/gt2sktnrvhz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gt2wobckcgx.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aunbwdkl.html

F. 文件与目录
来源：http://dali.zhengqikj.top/Article/details/gt2fnlookox.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2homaslxj.html

[F01] 读取整个文件
来源：http://dali.quarkkingdee.top/Article/details/gt2mluzjtvt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ebhqopta.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2olbplazt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgfzy.top/Article/details/gt2mplnstaj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gt2kauwxbzs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gt2oynzfmxf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jlsjyb.cn/Article/details/gt2enziqdub.html

Ruby: File.read("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2yijhoyof.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2fwollnii.html

[F02] 逐行读取文件
来源：http://dali.gotoacloud.top/Article/details/gt2jsiopmpa.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yttcbcgd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yjlncceo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gt2mjisufll.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gt2neqaewis.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gt2kfwxcbhx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gt2dydprwqi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pycfn.com/Article/details/gt2ahhfdlld.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258888.top/Article/details/gt2cqjyouxr.html

[F03] 写入文件（覆盖）
来源：http://dali.cdnleiting.top/Article/details/gt2drgfbebb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tabqymag.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2agclwqsx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gt2xjggfuaa.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gt2dqmcxkxn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.birdmap.top/Article/details/gt2yfenthdo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dianchejie.cn/Article/details/gt2tntkfqxz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigufen.top/Article/details/gt2wuuotucx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gt2gkacrzhu.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mxxdrbvg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gt2xwhwisci.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gaohongyu789.top/Article/details/gt2eefkgwwh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gt2yxkhlolj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gt2vrjxhdsr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yxyziyri.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.snrcjt.cn/Article/details/gt2fzmfrlwd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.vqdsnc.cn/Article/details/gt2pfgzbalj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ppjwa.cn/Article/details/gt2sufzagir.html

[F05] 判断文件或目录是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2twhmkydk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.c1oappe.top/Article/details/gt2dfnjeoib.html

PHP:  file_exists("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2vnnlcbbq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2geyiesgk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2laxlbanq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2mlbxszhr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigufen.top/Article/details/gt2iqdfsgpf.html

Ruby: File.exist?("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2woykexjv.html

C#:   File.Exists("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2cxsmdnpb.html

[F06] 删除文件
来源：http://dali.yj202588.top/Article/details/gt2dffrjqlk.html

Py:   os.remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2wfstkgam.html

PHP:  unlink("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2eqhrxylb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2iojbmtna.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2xanswphv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gt2repkiqqf.html

Go:   os.Remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2xbutmbes.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2hjziptbj.html

C#:   File.Delete("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2eokwimwf.html

[F07] 创建目录（含多级）
来源：http://dali.ppjwa.cn/Article/details/gt2vwxxjnru.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gt2gsyayslo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.vqdsnc.cn/Article/details/gt2iknifsnv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gt2ffuhqvfs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gt2ptvvpfjk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhoulong.xyz/Article/details/gt2wvmxkkmt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hammf.cn/Article/details/gt2lvntwdlo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guowangkeji.top/Article/details/gt2xtgsxeni.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gt2hfpthskn.html

[F08] 遍历目录
来源：http://dali.gzhubu.top/Article/details/gt2ouwlalcz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.andypj.xyz/Article/details/gt2ssnbctpt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxinkj.top/Article/details/gt2wxhqbqzo.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2ppwqjskh.html

TS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gt2huinopat.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gt2vkyfzoav.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2szrdudaf.html

Ruby: Dir.children("dir")
来源：http://dali.bjfxy.top/Article/details/gt2bretsphh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2nubhdmht.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gt2gvopaacg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zvpbrcbe.html

PHP:  filesize("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2mcearohy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gt2ezbosruz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gt2xipkteko.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gt2tqlenbjs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cqqwz.cn/Article/details/gt2kodaexqx.html

Ruby: File.size("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2voxrkchi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuxming.cn/Article/details/gt2uqwdnszc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sysykeji.top/Article/details/gt2yyrcpiah.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2qczbvvtu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2vjugcidd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2xppbnfay.html

TS:   path.extname("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2wfiwlaeh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuxming.cn/Article/details/gt2columvre.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2latjtwtj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2hmajlsuv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2qabiwywi.html

[F11] 复制与移动文件
来源：http://dali.bjfxy.top/Article/details/gt2wciudldg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2cspgwulh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2vevrodjd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2nxvymgvg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2rowysnrn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yyyhrckh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shuidangran.top/Article/details/gt2cdlnooee.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2xhrxmmlp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yanxiufei.cn/Article/details/gt2ojpkqbgc.html

[F12] CSV 读写
来源：http://dali.fengsongda.top/Article/details/gt2ynwuygsx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guannengcc.top/Article/details/gt2nfznmmcw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.kuanghao11.cn/Article/details/gt2jlmesuqe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hfpthk.cn/Article/details/gt2usxltnoo.html

TS:   // 同上
来源：http://dali.hysaishi.cn/Article/details/gt2fknkqmmi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yangfankeji.com/Article/details/gt2tgvhfsfl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dlxvqyrx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tanke756.top/Article/details/gt2eemffonj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ybcxt.top/Article/details/gt2yvzhqllx.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2zgpoaxeo.html

G. 面向对象
来源：http://dali.ydzc1.top/Article/details/gt2savnuymo.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2sqyiawtp.html

[G01] 定义类
来源：http://dali.smart0.xyz/Article/details/gt2kztxglmd.html

Py:   class User: pass
来源：http://dali.jqgfzy.top/Article/details/gt2qbzohobb.html

PHP:  class User {}
来源：http://dali.cqqwz.cn/Article/details/gt2rchtqmeg.html

JS:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2gnqasusf.html

TS:   class User { name: string = ""; }
来源：http://dali.tianlin.xyz/Article/details/gt2omienmvo.html

Java: class User {}
来源：http://dali.ydzc1.top/Article/details/gt2wylbfrfm.html

Go:   type User struct { Name string }
来源：http://dali.xylfe.cn/Article/details/gt2qxyrjggm.html

Ruby: class User; end
来源：http://dali.zdqjudy.top/Article/details/gt2owpjapdf.html

C#:   class User {}
来源：http://dali.xylfe.cn/Article/details/gt2vqtlprqi.html

[G02] 构造函数
来源：http://dali.sufxvd.cn/Article/details/gt2yfloaqxw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.birdmap.top/Article/details/gt2punwhfcm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.smart0.xyz/Article/details/gt2nxounsql.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gt2qcaewjir.html

TS:   constructor(public name: string) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2lptnkrvd.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gt2mhdzpvqm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cdnleiting.top/Article/details/gt2wzafwlul.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sufxvd.cn/Article/details/gt2ebmpkwop.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2byubxlxg.html

[G03] 实例属性
来源：http://dali.snrcjt.cn/Article/details/gt2jglnesto.html

Py:   self.name = "x"
来源：http://dali.dashuyun.cn/Article/details/gt2rfzcuglx.html

PHP:  public string $name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dklqlcrg.html

JS:   this.name = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2gxcpfvvi.html

TS:   name: string = "x";
来源：http://dali.cdnleiting.top/Article/details/gt2gqcmekdg.html

Java: private String name;
来源：http://dali.mhx1999.top/Article/details/gt2jbsgewqo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.0kj1m.cn/Article/details/gt2frwkmzoz.html

Ruby: @name = "x"
来源：http://dali.daria6918.cn/Article/details/gt2prrnhwuv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oynkwlao.html

[G04] 定义方法
来源：http://dali.ehwqpu.com/Article/details/gt2kcvyvhvm.html

Py:   def greet(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gt2bsqensyq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gt2aqiqjmgw.html

JS:   greet() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2kbkakqwj.html

TS:   greet(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bjbmqqfo.html

Java: String greet() { return name; }
来源：http://dali.meibo888.top/Article/details/gt2qizlyrmi.html


<!-- 参考信息 -->