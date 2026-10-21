代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.ppjwa.cn/Article/details/gtpgtoikxv.html

JS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gtlknkmuzi.html

TS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gtkjpnsnde.html

Java: String.join(",", items)
来源：http://dali.xuanzx.com/Article/details/gtbmyqpmcy.html

Go:   strings.Join(items, ",")
来源：http://dali.dianchejie.cn/Article/details/gtzaxiepnj.html

Ruby: items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtcvswmnzi.html

C#:   string.Join(",", items)
来源：http://dali.xuetiantiany.cn/Article/details/gtefteccpx.html

[E09] 去除所有空白字符
来源：http://dali.gotoacloud.top/Article/details/gtiyvcmurc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.meibo888.top/Article/details/gtvpdvwgbn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.0kj1m.cn/Article/details/gtgtwptvud.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gtuxvdwgtu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gtoprniqlp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj202588.top/Article/details/gtlhctclvv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jiagoushi.top/Article/details/gtfkwtfuoq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.vqdsnc.cn/Article/details/gtfzeydnvy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gtzjgrhdqq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jyoumei.cn/Article/details/gtpliskyts.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtbwehybzd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhongyouzk.top/Article/details/gtijbveffi.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtkkmgijpe.html

TS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtczhoedyp.html

Java: String.format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtmvdkaglg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtqiqurruz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtdztbrlkm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xinyue.icu/Article/details/gtgxsgzehq.html

[E11] 反转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtpiverwdi.html

Py:   s[::-1]
来源：http://dali.ivvv.top/Article/details/gtagracgke.html

PHP:  strrev($s);
来源：http://dali.yj20258.top/Article/details/gtkkncjnzr.html

JS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtwqkfgsyi.html

TS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtbpiyvfye.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sysykeji.top/Article/details/gtxkpnzxwk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xziqi.cn/Article/details/gtvzcrqeqs.html

Ruby: s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gtlvwhaugj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gtshigopjo.html

[E12] 统计某字符出现次数
来源：http://dali.nanxuanxn.top/Article/details/gtmndzvzkj.html

Py:   s.count("a")
来源：http://dali.yueranfly.top/Article/details/gtokznifoy.html

PHP:  substr_count($s, "a");
来源：http://dali.dashuyun.cn/Article/details/gtxmmbavxc.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxanltqt.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gtfgfjixaz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pycfn.com/Article/details/gtacrtfvvo.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgfzy.top/Article/details/gtmdfjkvdy.html

Ruby: s.count("a")
来源：http://dali.ydzc1.top/Article/details/gtvlklmjgo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hfpthk.cn/Article/details/gtiewhxlbq.html

[E13] 逐字符遍历
来源：http://dali.gaohongyu789.top/Article/details/gtwqmwloun.html

Py:   for ch in s: print(ch)
来源：http://dali.hongshengwenyu.top/Article/details/gtyjzzaipk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gtdohinbww.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gtzqbgrcst.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gtknegkvgo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.bjfxy.top/Article/details/gtxvpxplvr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxinkj.top/Article/details/gtiofqycgv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xylfe.cn/Article/details/gtulwtitab.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtegxbazuh.html

[E14] URL 编码与 Base64
来源：http://dali.hywenlv.cn/Article/details/gtweepoyjm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hfpthk.cn/Article/details/gteymzqxkz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.quarkkingdee.top/Article/details/gtchuqvoox.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.kuanghao11.cn/Article/details/gtisfutoub.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.snrcjt.cn/Article/details/gtwifbeivf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtaqkmluak.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbmabyxa.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hammf.cn/Article/details/gtsxwsuulp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtthwsfpvf.html

[E15] HTML 转义 / 反转义
来源：http://dali.vqdsnc.cn/Article/details/gteafcwkmd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sxryk.cn/Article/details/gtjgmnnlqm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xylfe.cn/Article/details/gtavopisvk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtlkrupvbz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgfzy.top/Article/details/gtcycyuvbe.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfiglyigw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gzhubu.top/Article/details/gtfwhsyqyl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zycfv.cn/Article/details/gtusfbdcyu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fzhhl.top/Article/details/gtzmzypmkn.html

[E16] 数字千分位
来源：http://dali.c1oappe.top/Article/details/gtmfmdlzff.html

Py:   f"{1234567:,}"
来源：http://dali.zdqjudy.top/Article/details/gtfrbthyvl.html

PHP:  number_format(1234567);
来源：http://dali.sweek.top/Article/details/gthhmlibkn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gtonlncptu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gtuipwejyi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jiagoushi.top/Article/details/gtmpbcaezn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guannengcc.top/Article/details/gtbrfjktml.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhixingplan.top/Article/details/gtjgmagxja.html

C#:   1234567.ToString("N0")
来源：http://dali.pycfn.com/Article/details/gtrflkbhac.html

[E17] 首字母大写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucduixpx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzbjkvtf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.316326.xyz/Article/details/gtdfvudywt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtmceleffb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gtbczksfta.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgfzy.top/Article/details/gtcbqglzbn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gtqvthnjxx.html

Ruby: s.capitalize
来源：http://dali.jinqigfzy.top/Article/details/gticimkyvh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.0kj1m.cn/Article/details/gtzbfnuesh.html

[E18] 模板占位符替换
来源：http://dali.xziqi.cn/Article/details/gtlajfyyks.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yvedp.cn/Article/details/gtbaqlgvcz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.andypj.xyz/Article/details/gtliyazisn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtvxibhaqe.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gttxzxqimk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtuulmyjyh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ivvv.top/Article/details/gtkwlzthwr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dashuyun.cn/Article/details/gtzfvixcph.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cdnleiting.top/Article/details/gtucmqvopo.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258.top/Article/details/gtphumgmcs.html

Py:   s.splitlines()
来源：http://dali.pycfn.com/Article/details/gttjkunvvb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtmovccuma.html

JS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gttjqzcmrs.html

TS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gtflzeqjih.html

Java: s.lines().toList()
来源：http://dali.cheryme.top/Article/details/gtptvioqwf.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuxming.cn/Article/details/gtmsehhvkz.html

Ruby: s.lines
来源：http://dali.cucudq.cn/Article/details/gtqepriyup.html

C#:   s.Split('\n')
来源：http://dali.yj20258888.top/Article/details/gtmvrtsdxs.html

[E20] 判断字符串是否为空
来源：http://dali.jqgufenzy.top/Article/details/gtueinapfe.html

Py:   if not s:
来源：http://dali.pengpengdd.cyou/Article/details/gtqidwnsof.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zycfv.cn/Article/details/gtrwqbsdgr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.meibo888.top/Article/details/gtwoopvjrw.html

TS:   if (s === "") {}
来源：http://dali.yj20258.top/Article/details/gtgjhagehm.html

Java: if (s.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gtsfgswgsv.html

Go:   if s == "" {}
来源：http://dali.hnqzz.top/Article/details/gtcslfzdbp.html

Ruby: if s.empty?
来源：http://dali.dianchejie.cn/Article/details/gtmmabtxpq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvytfhifx.html

[E21] 超长截断加省略号
来源：http://dali.shangyingyoupin.top/Article/details/gttcmzyzqj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangshuangyany.cn/Article/details/gtkfxqqtjl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtkonxirne.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtufqocesl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtosrlwhqe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtxcxvlcmx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhixingplan.top/Article/details/gtjibncvjk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtnssbtmzq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtruykailz.html

[E22] 字节长度与字符长度
来源：http://dali.tian-w.cn/Article/details/gtbcxuvlsa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenzaomai.com/Article/details/gtjdmnptsx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtzfmhvktl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtegcybqjy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gtbtrejmbq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnqzz.top/Article/details/gttwnavytb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cheryme.top/Article/details/gtiztudbqc.html

Ruby: s.bytesize;  s.length
来源：http://dali.ybcxt.top/Article/details/gtefegtekg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shzxlz.cn/Article/details/gthrhdqrju.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtgmmohnzh.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gtaqgddhut.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtouoksjjz.html

[F01] 读取整个文件
来源：http://dali.jinqigfzy.top/Article/details/gthqcpdclw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqkbhrfj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258.top/Article/details/gtjhpepyvd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tian-w.cn/Article/details/gtiihcowla.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtmgqrjyfn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtkmxsmysz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangshuangyany.cn/Article/details/gtkuorrrtj.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258888.top/Article/details/gttndipxyq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtyvjtpbyr.html

[F02] 逐行读取文件
来源：http://dali.yongpay.top/Article/details/gtcxcufedr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guowangkeji.top/Article/details/gtowvvhjfw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenlongwang.top/Article/details/gteemcayjz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gtyyehjbxi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtscwzvwtw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gtylhubqvs.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.0kj1m.cn/Article/details/gtcqmmwubb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangshuangyany.cn/Article/details/gtkusyvyxe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.svipenyu.cn/Article/details/gtkhiivoqw.html

[F03] 写入文件（覆盖）
来源：http://dali.yj202588.top/Article/details/gtnobhqzbf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbuntrrq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gttmopgxuk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtzdeqygbl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gthpckjchu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ybcxt.top/Article/details/gtckdwoiag.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jyoumei.cn/Article/details/gtikmyavab.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yonumen.top/Article/details/gtytklexcf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gtmlctmjyq.html

[F04] 追加写入文件
来源：http://dali.zhengqikj.top/Article/details/gtclbkondo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gtmqvcfwpa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yongpay.top/Article/details/gtabclmkjh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gtjlwulwlp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtqbecpqtd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zdqjudy.top/Article/details/gtvdbriykq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sweek.top/Article/details/gtqgleloxz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gzhubu.top/Article/details/gtbonkiaep.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.smart0.xyz/Article/details/gtgtsjnrmz.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gtnpovpqxa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphuitdxx.html

PHP:  file_exists("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtyurvvgen.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtczrlnrba.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtwzedshdp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtyofylzer.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinghuilouyu.cn/Article/details/gteeogjhdo.html

Ruby: File.exist?("a.txt")
来源：http://dali.yongpay.top/Article/details/gtiqdcikic.html

C#:   File.Exists("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtpomedjdf.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gtnvjfcdkx.html

Py:   os.remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtavxaqlpa.html

PHP:  unlink("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtnesrpswx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtewlxmkcp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtxqqtjumx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtylfrocvk.html

Go:   os.Remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtmetenwhe.html

Ruby: File.delete("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtssbotoby.html

C#:   File.Delete("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtlologkly.html

[F07] 创建目录（含多级）
来源：http://dali.yangfankeji.com/Article/details/gttzevmqun.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwnmomdh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxinkj.top/Article/details/gtrlhmtuji.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gtnleldbev.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gtvyndxewg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhiwuduotai.top/Article/details/gtzxikxxgx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daria6918.cn/Article/details/gtwctucrwt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gtyucnbmoq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.redwolf501.top/Article/details/gtstfbubio.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gtsoagkour.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgfzy.top/Article/details/gtqmtafxtv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.meibo888.top/Article/details/gtivxqskqw.html

JS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtajkvctov.html

TS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gtcvuyxpcn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gtumxvlgay.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtsvuvsucb.html

Ruby: Dir.children("dir")
来源：http://dali.jqgfzy.top/Article/details/gtbppsxpzh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aibaodan.cn/Article/details/gtghusjmdl.html

[F09] 获取文件大小
来源：http://dali.nwbrower.top/Article/details/gtgzhrygcd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtjbsxoyte.html

PHP:  filesize("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtpofrnroo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gttrzsedhj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gtqdmjrymp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gthezowxrf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gtfoqpaigw.html

Ruby: File.size("a.txt")
来源：http://dali.cashguo.top/Article/details/gtuhyyajcj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tian-w.cn/Article/details/gttghfclba.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tianlin.xyz/Article/details/gtngjjaadn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtaqwsmprs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jianghu66.top/Article/details/gtadrddjaz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtnbueucpb.html

TS:   path.extname("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gthmkbjowb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jianghu66.top/Article/details/gtcfpgixfu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtrwvcnbfg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtsrfontfl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtdmvktuia.html

[F11] 复制与移动文件
来源：http://dali.redwolf501.top/Article/details/gtlsdxsgss.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gttjorudie.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gotoacloud.top/Article/details/gtzhzraicd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtecdvuzxv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtmhrnamkz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtixllfksz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.vqdsnc.cn/Article/details/gtbkkpfeey.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtncukfalv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhixingplan.top/Article/details/gtyqbpytap.html

[F12] CSV 读写
来源：http://dali.jinqigfzy.top/Article/details/gtoxfmkdfl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shzxlz.cn/Article/details/gtkswaevts.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.316326.xyz/Article/details/gtduzstpjx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.316326.xyz/Article/details/gtmvpdbfwn.html

TS:   // 同上
来源：http://dali.hywenlv.cn/Article/details/gtdlntrexd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpvqpiro.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgufenzy.top/Article/details/gtxrydiqpp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jyoumei.cn/Article/details/gtbblkkgqj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj202588.top/Article/details/gtrjxhvnxj.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtxrjodnpc.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gtmjrpwwqk.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtwssliriw.html

[G01] 定义类
来源：http://dali.tianlin.xyz/Article/details/gtduwwgaym.html

Py:   class User: pass
来源：http://dali.jqgufenzy.top/Article/details/gtsbuzhddz.html

PHP:  class User {}
来源：http://dali.andypj.xyz/Article/details/gtmimlwadc.html

JS:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gtghwbxpma.html

TS:   class User { name: string = ""; }
来源：http://dali.tanke756.top/Article/details/gtempxummx.html

Java: class User {}
来源：http://dali.pycfn.com/Article/details/gtntlqwgki.html

Go:   type User struct { Name string }
来源：http://dali.jinqigfzy.top/Article/details/gtkvxyclfv.html

Ruby: class User; end
来源：http://dali.cdnleiting.top/Article/details/gtuqxuppug.html

C#:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gtuykjoezk.html

[G02] 构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtmpqouiys.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuxming.cn/Article/details/gtewbnyokt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gtexxhwgfb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtvntocush.html

TS:   constructor(public name: string) {}
来源：http://dali.yueranfly.top/Article/details/gtpolpskzs.html

Java: User(String name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvmtfvdj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shuidangran.top/Article/details/gtrvjlfrif.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gtzvwbamyc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtnerehdfl.html

[G03] 实例属性
来源：http://dali.sweek.top/Article/details/gtjzduehme.html

Py:   self.name = "x"
来源：http://dali.zycfv.cn/Article/details/gtgjhonvcx.html

PHP:  public string $name = "x";
来源：http://dali.hysaishi.cn/Article/details/gtonqvvjlb.html

JS:   this.name = "x";
来源：http://dali.zycfv.cn/Article/details/gtmrbbqqdv.html

TS:   name: string = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtbcpccxwg.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gtolcxbrpq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgufenzy.top/Article/details/gtztfbssdd.html

Ruby: @name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtztpqsblr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gtipvzkkox.html

[G04] 定义方法
来源：http://dali.iojbl.cn/Article/details/gtewuzrozx.html

Py:   def greet(self): return self.name
来源：http://dali.yonumen.top/Article/details/gtuddxvwdu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmdpfhroe.html

JS:   greet() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbqdypuu.html

TS:   greet(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtjqgantlz.html

Java: String greet() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtdudzffkr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtxkmbrzjb.html

Ruby: def greet; @name; end
来源：http://dali.yj202588.top/Article/details/gtqpwhagkh.html

C#:   public string Greet() => Name;
来源：http://dali.jqgfzy.top/Article/details/gtahvilkui.html

[G05] 继承
来源：http://dali.cdnleiting.top/Article/details/gtyodlbytp.html

Py:   class Admin(User): pass
来源：http://dali.hnxiangtu.top/Article/details/gtswmkcmeb.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtbavgwrtp.html

JS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtmgnlotgo.html

TS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtojgwldxv.html

Java: class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwfthxqo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbygkgixq.html

Ruby: class Admin < User; end
来源：http://dali.c1oappe.top/Article/details/gtqlwbghqj.html

C#:   class Admin : User {}
来源：http://dali.jlsjyb.cn/Article/details/gtklqpmuzn.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmzvsdlz.html

Py:   def greet(self): return "admin"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdxyegzg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtuazrgmxy.html

JS:   greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtlvkootvz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtghlmcdjb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtffnqxvbz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.iojbl.cn/Article/details/gtiqjyyrjv.html

Ruby: def greet; "admin"; end
来源：http://dali.cashguo.top/Article/details/gtijqubzib.html


<!-- 参考信息 -->