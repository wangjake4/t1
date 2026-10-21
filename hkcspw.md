代发 wailian999

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gtplzdgwai.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangshuangyany.cn/Article/details/gtnijtqdtw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.kuanghao11.cn/Article/details/gtpgpxpnbt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtmidayzkc.html

[E06] 替换子串
来源：http://dali.jinqigfzy.top/Article/details/gtyudkotvu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gtmjkiamlt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtxjaotbsz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtudkdgilf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtnbkjccbs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtxqgerjsy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gtvfllhtto.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtwhbwkwgx.html

C#:   s.Replace("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtaqnosmcs.html

[E07] 按分隔符拆分
来源：http://dali.316326.xyz/Article/details/gtvitydsrg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pengpengdd.cyou/Article/details/gtfmiupkzy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.dianchejie.cn/Article/details/gttooydbly.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.bjfxy.top/Article/details/gtoutykwjz.html

TS:   s.split(",")
来源：http://dali.0kj1m.cn/Article/details/gtwlltrkyd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pycfn.com/Article/details/gtuldvetux.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.havefunace.top/Article/details/gtubcenxvh.html

Ruby: s.split(",");  s.split
来源：http://dali.316326.xyz/Article/details/gtmzygufqh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.c1oappe.top/Article/details/gtudkfankj.html

[E08] 数组按分隔符合并
来源：http://dali.jiagoushi.top/Article/details/gtidsivhya.html

Py:   ",".join(items)
来源：http://dali.feifeiyinyue.top/Article/details/gtvnbznbnm.html

PHP:  implode(",", $items);
来源：http://dali.jyoumei.cn/Article/details/gtidglvflf.html

JS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtdpgvrshi.html

TS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtorhhnfjt.html

Java: String.join(",", items)
来源：http://dali.havefunace.top/Article/details/gtodjpsqyw.html

Go:   strings.Join(items, ",")
来源：http://dali.guannengcc.top/Article/details/gtqrvvqmof.html

Ruby: items.join(",")
来源：http://dali.tanke756.top/Article/details/gtczaesbmx.html

C#:   string.Join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gthtunecec.html

[E09] 去除所有空白字符
来源：http://dali.birdmap.top/Article/details/gtrvmzwawd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.andypj.xyz/Article/details/gtruzkaaqx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscwvmurk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gtaphqvxbq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtsnqnissf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ybcxt.top/Article/details/gtejrckvrx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aizwys.cn/Article/details/gtlmzhkuyh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fzhhl.top/Article/details/gtewtdmzle.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gttvdynjjw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhiwuduotai.top/Article/details/gtzbjksmyq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hammf.cn/Article/details/gtnmjsmzss.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yanxiufei.cn/Article/details/gtqmzwynsa.html

JS:   "7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtfamenvqd.html

TS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtacnymdzv.html

Java: String.format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtvkeirmck.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtyaelpplr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtbritdjhr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.andypj.xyz/Article/details/gtvdupjwcn.html

[E11] 反转字符串
来源：http://dali.shuidangran.top/Article/details/gtuzrktjok.html

Py:   s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gtmhviabah.html

PHP:  strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gthecowszu.html

JS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtqmbaszhu.html

TS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtlvgyuuyx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tian-w.cn/Article/details/gtmvkafglf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yueranfly.top/Article/details/gtckrgjccs.html

Ruby: s.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnasuhia.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gtslppeknp.html

[E12] 统计某字符出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gtdqedlrhd.html

Py:   s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtggqqmvuf.html

PHP:  substr_count($s, "a");
来源：http://dali.haohaochexian.top/Article/details/gtbfjiqhjb.html

JS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtuqnhgibo.html

TS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtekcjvyrc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hfpthk.cn/Article/details/gtkpccsqwy.html

Go:   strings.Count(s, "a")
来源：http://dali.guannengcc.top/Article/details/gtbxuheebt.html

Ruby: s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gtgsjrtynh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivrkxxwm.html

[E13] 逐字符遍历
来源：http://dali.daria6918.cn/Article/details/gtrltvvybd.html

Py:   for ch in s: print(ch)
来源：http://dali.jiagoushi.top/Article/details/gteconinuf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gaohongyu789.top/Article/details/gtwvqnglze.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtzinvosgh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gtuemvcepj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtjxdsfqyg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jyoumei.cn/Article/details/gtfiotzbxk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aizwys.cn/Article/details/gtxyjvjpll.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtwpghbgus.html

[E14] URL 编码与 Base64
来源：http://dali.yongpay.top/Article/details/gtdulcdbrz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sufxvd.cn/Article/details/gtovresvrc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ybcxt.top/Article/details/gtcorzjlpe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gzhubu.top/Article/details/gtoozjsfis.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenlongwang.top/Article/details/gtsjkvsonl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gtgdcaqnlw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daxiang520.top/Article/details/gtvygglgts.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jlsjyb.cn/Article/details/gtkkpirprc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtpugrhpiq.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqwmzlbh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fzhhl.top/Article/details/gtwhpfwtie.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenlongwang.top/Article/details/gtrprunmng.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gtzwragwko.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pycfn.com/Article/details/gtjvnapbpf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cdnleiting.top/Article/details/gtnmcgduao.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guowangkeji.top/Article/details/gtodzcwngc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.andypj.xyz/Article/details/gtpjghynvt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yonumen.top/Article/details/gtxdjwznrx.html

[E16] 数字千分位
来源：http://dali.yuanzhike.top/Article/details/gtvdmxxuns.html

Py:   f"{1234567:,}"
来源：http://dali.meibo888.top/Article/details/gtwfgqpnjc.html

PHP:  number_format(1234567);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzftpxgky.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gthlktecmq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gtghfsxriw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cheryme.top/Article/details/gtnaocjanp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zycfv.cn/Article/details/gtzhywptwb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shzxlz.cn/Article/details/gtzauswcuw.html

C#:   1234567.ToString("N0")
来源：http://dali.hnxiangtu.top/Article/details/gtzrxixamk.html

[E17] 首字母大写
来源：http://dali.sweek.top/Article/details/gtdjdzkfuc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cucudq.cn/Article/details/gtluunnwao.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.c1oappe.top/Article/details/gthekuwwkx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.iojbl.cn/Article/details/gtneitvqhl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtqcnfdolz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cucudq.cn/Article/details/gthgqqhvvb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtagzlojru.html

Ruby: s.capitalize
来源：http://dali.chenzaomai.com/Article/details/gtvoqbkpdf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuanzhike.top/Article/details/gtlwkuavph.html

[E18] 模板占位符替换
来源：http://dali.kuanghao11.cn/Article/details/gtuwrbtgay.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.quarkkingdee.top/Article/details/gtmtdxxznw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.dashuyun.cn/Article/details/gtszabucwg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtoukzhmnn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtgktkdrhi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtjlrvcolp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtksfxkvde.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hysaishi.cn/Article/details/gtetnieqmr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hywenlv.cn/Article/details/gtzqkyzzyb.html

[E19] 多行文本按行拆分
来源：http://dali.c1oappe.top/Article/details/gtswifnfsg.html

Py:   s.splitlines()
来源：http://dali.cucudq.cn/Article/details/gtcmxmxbdd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtkrusbpsm.html

JS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gtdqjdjcog.html

TS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtjsyozwvk.html

Java: s.lines().toList()
来源：http://dali.yj202588.top/Article/details/gttgxveckr.html

Go:   strings.Split(s, "\n")
来源：http://dali.hysaishi.cn/Article/details/gttayeetww.html

Ruby: s.lines
来源：http://dali.shzxlz.cn/Article/details/gtvpguhkxn.html

C#:   s.Split('\n')
来源：http://dali.yonumen.top/Article/details/gtifkylctv.html

[E20] 判断字符串是否为空
来源：http://dali.yj202588.top/Article/details/gttzydwikk.html

Py:   if not s:
来源：http://dali.ehwqpu.com/Article/details/gtvmnxvtaq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ydzc1.top/Article/details/gtacborqmw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.birdmap.top/Article/details/gtrnpvmihd.html

TS:   if (s === "") {}
来源：http://dali.aizwys.cn/Article/details/gtukdwwnao.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gtngtgvvoj.html

Go:   if s == "" {}
来源：http://dali.xylfe.cn/Article/details/gtsqmfnzhj.html

Ruby: if s.empty?
来源：http://dali.yuxming.cn/Article/details/gtgaachqrv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fengsongda.top/Article/details/gtoikbvqoi.html

[E21] 超长截断加省略号
来源：http://dali.vqdsnc.cn/Article/details/gtwmtlmqfr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gzhubu.top/Article/details/gtlmxbanya.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtvfpjnexh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtuhehhfvu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gttjykqnwg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtivxwcnze.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbybvusee.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gturcerpiy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtrgkcnpgq.html

[E22] 字节长度与字符长度
来源：http://dali.jyoumei.cn/Article/details/gtywyzylmg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.316326.xyz/Article/details/gtlvuumgat.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gterknccxc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ivvv.top/Article/details/gtkiandgaj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gtyxjyptbu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pycfn.com/Article/details/gtetycfdrd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigufen.top/Article/details/gtxplsusra.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdjaentr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jyoumei.cn/Article/details/gtsyczjppq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtkdmfcars.html

F. 文件与目录
来源：http://dali.guannengcc.top/Article/details/gtrahnbmxq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtepbxltpv.html

[F01] 读取整个文件
来源：http://dali.pycfn.com/Article/details/gtsqqtcjgx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuanzhike.top/Article/details/gtwycpwpyf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtgjagbbgo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.mhx1999.top/Article/details/gtehpnoobw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtjcxdpevc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxwmpyzx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ydzc1.top/Article/details/gtqsphdvas.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtnhzbnyai.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtwipomelg.html

[F02] 逐行读取文件
来源：http://dali.tanke756.top/Article/details/gtjhuiozia.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gtubavatkh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guannengcc.top/Article/details/gtijdpbmxp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gtzpmjsaif.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gtplepeauz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gttqzbuzof.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnoixadvt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xziqi.cn/Article/details/gtjgzlrknf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gtcfmprqne.html

[F03] 写入文件（覆盖）
来源：http://dali.chenlongwang.top/Article/details/gtzdtuagiv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.svipenyu.cn/Article/details/gtsiqvmbzr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gtbkjnqhrw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gtcwogxmxh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtugijudor.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sufxvd.cn/Article/details/gtmvxoaoni.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yvedp.cn/Article/details/gtllqmsnmt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daxiang520.top/Article/details/gtxsdnohzf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gtoulzeywf.html

[F04] 追加写入文件
来源：http://dali.jiagoushi.top/Article/details/gtakeozuyu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtvjzntarm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttaluhtcf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gtagcyzfiq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gtzgxhnmny.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj202588.top/Article/details/gtnsqggvtd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtinwmakwr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ehwqpu.com/Article/details/gtcbuqymfm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guannengcc.top/Article/details/gtevzrmxdt.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuanzhike.top/Article/details/gtoammoncn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hysaishi.cn/Article/details/gtvbqyfyzp.html

PHP:  file_exists("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtgdfzzqga.html

JS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gthpqazmpb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtzuipboib.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtkbznbtqg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258.top/Article/details/gtsquckook.html

Ruby: File.exist?("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtcsrulnbe.html

C#:   File.Exists("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtqubitnfy.html

[F06] 删除文件
来源：http://dali.chenjidiqi.icu/Article/details/gtjnqaknmr.html

Py:   os.remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtvijlcbck.html

PHP:  unlink("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtobxfhmjv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gttuhltbws.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtpgdhbmhz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtrrxuevdd.html

Go:   os.Remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtxokyeome.html

Ruby: File.delete("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtajocamrp.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrhqucce.html

[F07] 创建目录（含多级）
来源：http://dali.jqgufenzy.top/Article/details/gtirujqmor.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.quarkkingdee.top/Article/details/gtqzwpbzga.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gzhubu.top/Article/details/gtzvovegsa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gtqqjokxge.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gtbuywdxng.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ehwqpu.com/Article/details/gtuxlbrqjv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aibaodan.cn/Article/details/gtadzzwxfu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shangyingyoupin.top/Article/details/gtuttcsdbg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gotoacloud.top/Article/details/gtitpxctgl.html

[F08] 遍历目录
来源：http://dali.shangyingyoupin.top/Article/details/gtjpbtsxpg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sysykeji.top/Article/details/gtwwdxrqkq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tianlin.xyz/Article/details/gtkcuwzwfg.html

JS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gtxcnekdyu.html

TS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtuoigaubv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gtrbgenyks.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskivqzmb.html

Ruby: Dir.children("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtrjnbdsre.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxinkj.top/Article/details/gtjxcjiesx.html

[F09] 获取文件大小
来源：http://dali.sweek.top/Article/details/gttdbeifod.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtpxbqrhoc.html

PHP:  filesize("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtjulwtkcj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gtmkadyftb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbvhtvxy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gttdtbtmmd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dashuyun.cn/Article/details/gturatbjyv.html

Ruby: File.size("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtqiqkvlns.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gtxjuynvgv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.haohaochexian.top/Article/details/gtnxyjdzgc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtsegbugzf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtickletca.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtglrmwuga.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtxxjmanfj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hfpthk.cn/Article/details/gtfszorcmx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtwywpfvsn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwelctpwo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrowglgc.html

[F11] 复制与移动文件
来源：http://dali.nanxuanxn.top/Article/details/gtjlrjtwvf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtgsqucoma.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfxmrjje.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtjffylztm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtkncaavgq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yonumen.top/Article/details/gtxtodlauf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gtmmkhwggo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtiwujsaxh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.mhx1999.top/Article/details/gtcqbtyzht.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gtdclbjrfb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cqqwz.cn/Article/details/gtldpytink.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.snrcjt.cn/Article/details/gtpzjrlgpd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aibaodan.cn/Article/details/gtqikxpbwx.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gthebmkbfq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gttatabifz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ivvv.top/Article/details/gtodkemyey.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ppjwa.cn/Article/details/gtvoftghbe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenlongwang.top/Article/details/gtllpkmota.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtoprrrgxi.html

G. 面向对象
来源：http://dali.sysykeji.top/Article/details/gtwvsnjwuj.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtlzjciuwq.html

[G01] 定义类
来源：http://dali.hysaishi.cn/Article/details/gtxnwsguli.html

Py:   class User: pass
来源：http://dali.yonumen.top/Article/details/gtaqihyiaq.html

PHP:  class User {}
来源：http://dali.ehwqpu.com/Article/details/gtwqlkmben.html

JS:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtzmsndtmj.html

TS:   class User { name: string = ""; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjpjaheda.html

Java: class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtohnezfuy.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gtthjbzbki.html

Ruby: class User; end
来源：http://dali.snrcjt.cn/Article/details/gtmympcshd.html

C#:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtkvrovlnz.html

[G02] 构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbioxrjua.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aibaodan.cn/Article/details/gttgiptxws.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ybcxt.top/Article/details/gtmpjxaaic.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gtivtzwetg.html

TS:   constructor(public name: string) {}
来源：http://dali.aibaodan.cn/Article/details/gthfgoqmrg.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqnmwhpj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daria6918.cn/Article/details/gtvmpbdjxh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gtkdmjbdat.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sxryk.cn/Article/details/gtusfsmjzs.html

[G03] 实例属性
来源：http://dali.haohaochexian.top/Article/details/gtlzehxuuf.html

Py:   self.name = "x"
来源：http://dali.wangdashe.top/Article/details/gtaumwclsx.html

PHP:  public string $name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtlwoamuhj.html

JS:   this.name = "x";
来源：http://dali.xziqi.cn/Article/details/gtpmyvugar.html

TS:   name: string = "x";
来源：http://dali.dashuyun.cn/Article/details/gtfowmpwhc.html

Java: private String name;
来源：http://dali.jinqigfzy.top/Article/details/gtwpkimhsp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.quarkkingdee.top/Article/details/gttnmkzyww.html

Ruby: @name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gtqdsaivhk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fzhhl.top/Article/details/gtfhtqptni.html

[G04] 定义方法
来源：http://dali.jyoumei.cn/Article/details/gtqcbmjgvj.html

Py:   def greet(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtkabnovfy.html


<!-- 参考信息 -->