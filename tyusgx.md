代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenlongwang.top/Article/details/gtjjtnnuau.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbfypgsu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gthcbqtydt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.316326.xyz/Article/details/gtcsrpfmea.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gtxhqljbnt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.havefunace.top/Article/details/gtjkqosrjo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xziqi.cn/Article/details/gtkkpxmzdv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gtutkwufyy.html

[E06] 替换子串
来源：http://dali.gzhubu.top/Article/details/gttjdkiojz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinqigufen.top/Article/details/gtpauccpdk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ppjwa.cn/Article/details/gtajxwkefj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtutbhissj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtazskwlwt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gtqkzbkmns.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gtvukgxbtb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pycfn.com/Article/details/gtynkczcma.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtiaajfafr.html

[E07] 按分隔符拆分
来源：http://dali.gogol.net.cn/Article/details/gtphuzkxyx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yuanzhike.top/Article/details/gtejedwbgx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjkyshal.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.bjfxy.top/Article/details/gtwlapiufi.html

TS:   s.split(",")
来源：http://dali.meibo888.top/Article/details/gtbhkietra.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hysaishi.cn/Article/details/gtpkjwmeib.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtqekdyugu.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangtech.top/Article/details/gtygbvigyo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj202588.top/Article/details/gtqprsxcvh.html

[E08] 数组按分隔符合并
来源：http://dali.andypj.xyz/Article/details/gtffioqtzj.html

Py:   ",".join(items)
来源：http://dali.shuidangran.top/Article/details/gtybhmjyzy.html

PHP:  implode(",", $items);
来源：http://dali.ybcxt.top/Article/details/gtpzpcpiby.html

JS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtxcrgxwhy.html

TS:   items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gthyycackw.html

Java: String.join(",", items)
来源：http://dali.guannengcc.top/Article/details/gtxgfpjini.html

Go:   strings.Join(items, ",")
来源：http://dali.zhoulong.xyz/Article/details/gtepxgkqrp.html

Ruby: items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdpkoybo.html

C#:   string.Join(",", items)
来源：http://dali.sxryk.cn/Article/details/gtdprlshib.html

[E09] 去除所有空白字符
来源：http://dali.bjfxy.top/Article/details/gtbboicvyw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuanzhike.top/Article/details/gtzhspbdyc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.birdmap.top/Article/details/gtybxfrfkf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtxfbxllys.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gtpyhdfitn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gtucytzwie.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnxiangtu.top/Article/details/gtiuzdnwsj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.birdmap.top/Article/details/gtadysqylj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gtkhzpfnwg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gotoacloud.top/Article/details/gtsfasguyo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtcmvpviir.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gogol.net.cn/Article/details/gtrrcaznbf.html

JS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtbcmweidb.html

TS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtpgdgsrya.html

Java: String.format("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gtjfwytkom.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gtockwnpft.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gthmhbfhky.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenlongwang.top/Article/details/gtubumqjho.html

[E11] 反转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgkmfjyu.html

Py:   s[::-1]
来源：http://dali.hnxiangtu.top/Article/details/gtilxlvldm.html

PHP:  strrev($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtkutrahyg.html

JS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtuuiwoeda.html

TS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtqkhbdxyv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sysykeji.top/Article/details/gtvorawdcg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtzztimxac.html

Ruby: s.reverse
来源：http://dali.xinyue.icu/Article/details/gtonjdhfct.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gtwinqjzzc.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258.top/Article/details/gtsbvavqoh.html

Py:   s.count("a")
来源：http://dali.hfpthk.cn/Article/details/gtvcrsucon.html

PHP:  substr_count($s, "a");
来源：http://dali.sweek.top/Article/details/gtoulggjsd.html

JS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gtchbgcpww.html

TS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gttzbllrqn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhengqikj.top/Article/details/gtqhcmimiu.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258.top/Article/details/gtpjhgdjdr.html

Ruby: s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gtugeideog.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuetiantiany.cn/Article/details/gtocyukdhh.html

[E13] 逐字符遍历
来源：http://dali.kuanghao11.cn/Article/details/gtkxerkfhh.html

Py:   for ch in s: print(ch)
来源：http://dali.birdmap.top/Article/details/gtbnskcchx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhongyouzk.top/Article/details/gtqeqhscfp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtvdbdvxya.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtmrkilttq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxinkj.top/Article/details/gttztttaqg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.316326.xyz/Article/details/gtbszqmvuo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zycfv.cn/Article/details/gttphsfhab.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangdashe.top/Article/details/gtteehxrgx.html

[E14] URL 编码与 Base64
来源：http://dali.yj202588.top/Article/details/gtcbynuhho.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhixingplan.top/Article/details/gtrwwctior.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtuxmewsez.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangdashe.top/Article/details/gtozhuxwjg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtokmquaug.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtbqzvhfjx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sxryk.cn/Article/details/gtriltkndh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.kuanghao11.cn/Article/details/gtqehexceg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nwbrower.top/Article/details/gtlbmelkqo.html

[E15] HTML 转义 / 反转义
来源：http://dali.jiagoushi.top/Article/details/gtmcvnujoi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guowangkeji.top/Article/details/gtfgvmscez.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.svipenyu.cn/Article/details/gtfqbtrwlf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnxiangtu.top/Article/details/gtvoxszfxl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigfzy.top/Article/details/gtsqvzwlxt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.c1oappe.top/Article/details/gtnaoezzdb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhengqikj.top/Article/details/gtwggmbozb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sxryk.cn/Article/details/gtnrugctwl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hammf.cn/Article/details/gtltpyphbb.html

[E16] 数字千分位
来源：http://dali.iojbl.cn/Article/details/gthpqfyjsi.html

Py:   f"{1234567:,}"
来源：http://dali.yueranfly.top/Article/details/gtekbfjaux.html

PHP:  number_format(1234567);
来源：http://dali.cucudq.cn/Article/details/gtpxmrbbzo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gtqigropiw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gthdomsgpz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ivvv.top/Article/details/gtysgazboe.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zycfv.cn/Article/details/gtkbeamonk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jqgufenzy.top/Article/details/gtucqrhmja.html

C#:   1234567.ToString("N0")
来源：http://dali.gzhubu.top/Article/details/gtihppctld.html

[E17] 首字母大写
来源：http://dali.hongshengwenyu.top/Article/details/gtphoeharz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gtdlkrzgmw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtanyxaqxw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gtomuyolym.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gtedldspmw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjnsnwnu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.316326.xyz/Article/details/gtrbaxwujj.html

Ruby: s.capitalize
来源：http://dali.havefunace.top/Article/details/gtnyxvwcnn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxuanxn.top/Article/details/gtxrdqiyyl.html

[E18] 模板占位符替换
来源：http://dali.yj202588.top/Article/details/gtcqvpwomm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhengqikj.top/Article/details/gtqprcykum.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.andypj.xyz/Article/details/gtfrqnwezl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtgafmirmp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gtboeuwkna.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gthtxozrnk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtfuacyprs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tanke756.top/Article/details/gteomkafdq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnxiangtu.top/Article/details/gtgtnanxcj.html

[E19] 多行文本按行拆分
来源：http://dali.jianghu66.top/Article/details/gtyfuwlabb.html

Py:   s.splitlines()
来源：http://dali.pycfn.com/Article/details/gtplbofgpa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtlefrdvbn.html

JS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gtzxmlepnu.html

TS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gtlgeozanp.html

Java: s.lines().toList()
来源：http://dali.birdmap.top/Article/details/gtgdtpwhdl.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtqspyhjxt.html

Ruby: s.lines
来源：http://dali.zhixingplan.top/Article/details/gtayagxywh.html

C#:   s.Split('\n')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiazaglbg.html

[E20] 判断字符串是否为空
来源：http://dali.hfpthk.cn/Article/details/gtvlxvywcb.html

Py:   if not s:
来源：http://dali.bjfxy.top/Article/details/gtabebfzjy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hysaishi.cn/Article/details/gtssgvmnol.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cdnleiting.top/Article/details/gtknnjyayr.html

TS:   if (s === "") {}
来源：http://dali.yj20258888.top/Article/details/gtjpumpskz.html

Java: if (s.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gtvtzalthm.html

Go:   if s == "" {}
来源：http://dali.pycfn.com/Article/details/gtsmyjdkhs.html

Ruby: if s.empty?
来源：http://dali.pengpengdd.cyou/Article/details/gtboxdbynk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtmvwoelxm.html

[E21] 超长截断加省略号
来源：http://dali.haohaochexian.top/Article/details/gtdaifzjsa.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hfpthk.cn/Article/details/gtmkfqmunx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtwxyuxnde.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtciufqtpb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtsvzyvjof.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtucbytgsw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sufxvd.cn/Article/details/gtqnbqhdnl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtnxpqppbl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtmhgnlkii.html

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gtslisznzb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cdnleiting.top/Article/details/gtjrdbkdaf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtyzqkawmo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gtgpevsuhe.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gtzqruzcrm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gtylcxddgj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cqqwz.cn/Article/details/gtqyhhvzey.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gtfxfxczix.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhengqikj.top/Article/details/gtorsqrfxc.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtnbejbmke.html

F. 文件与目录
来源：http://dali.zdqjudy.top/Article/details/gthfuhkayy.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtpwrlflcp.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gtxnwokagk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuetiantiany.cn/Article/details/gteuyqtiuj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtzzvytisb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hammf.cn/Article/details/gttdvzvfsx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtixvqjfdd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtoiobygeb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shuidangran.top/Article/details/gtotknwsxm.html

Ruby: File.read("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtcnkpbuao.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yongpay.top/Article/details/gtwfaydzxs.html

[F02] 逐行读取文件
来源：http://dali.fzhhl.top/Article/details/gtpzskbtzn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ydzc1.top/Article/details/gtkkojbble.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.dianchejie.cn/Article/details/gtzoaesnbg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gtgonhzgmc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zycfv.cn/Article/details/gtwormvene.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gtslnodljo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hysaishi.cn/Article/details/gtfjxzragj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuxming.cn/Article/details/gtolrdvwxv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.birdmap.top/Article/details/gtxrurqiko.html

[F03] 写入文件（覆盖）
来源：http://dali.sufxvd.cn/Article/details/gtjojzkzqc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxinkj.top/Article/details/gtgpnexabr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gtskbdgagf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtcudrrknb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtqwqknopj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gtpcctibgw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gaohongyu789.top/Article/details/gtoowfoqbx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tianlin.xyz/Article/details/gtfeeckeua.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtidzcmwgl.html

[F04] 追加写入文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanwpdilt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.smart0.xyz/Article/details/gtzmfzwimr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangshuangyany.cn/Article/details/gtayhkxqdb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gtdpnvahuf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtyxurudkg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgfzy.top/Article/details/gtibstzkyb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtkrxjbxqy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.havefunace.top/Article/details/gteflxvwla.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tian-w.cn/Article/details/gtholriheh.html

[F05] 判断文件或目录是否存在
来源：http://dali.dianchejie.cn/Article/details/gtuzmazfkh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xziqi.cn/Article/details/gtzvivuvzo.html

PHP:  file_exists("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtnlsgoohu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtquhoxewb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtjldzabbi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtglzfizqq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenjidiqi.icu/Article/details/gtswqyklye.html

Ruby: File.exist?("a.txt")
来源：http://dali.cashguo.top/Article/details/gtphhqhmnq.html

C#:   File.Exists("a.txt")
来源：http://dali.316326.xyz/Article/details/gtnwshsukb.html

[F06] 删除文件
来源：http://dali.sufxvd.cn/Article/details/gtyotpyrae.html

Py:   os.remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtdjpwcxix.html

PHP:  unlink("a.txt");
来源：http://dali.pycfn.com/Article/details/gtiketszth.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtzqgklybg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtqvmtfuzb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtrjlldoyw.html

Go:   os.Remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtsjvhhbio.html

Ruby: File.delete("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtezexncew.html

C#:   File.Delete("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtjrzplolw.html

[F07] 创建目录（含多级）
来源：http://dali.fengsongda.top/Article/details/gtcgnhhlrp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gtgnsxsqgf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigufen.top/Article/details/gtrrnshudc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gtprxptkmm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtlvlirpnz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gtmziaywnr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yonumen.top/Article/details/gtvajkerie.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tian-w.cn/Article/details/gtzcmujtes.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shangyingyoupin.top/Article/details/gtplephxdo.html

[F08] 遍历目录
来源：http://dali.zhiwuduotai.top/Article/details/gtghfrnnua.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hywenlv.cn/Article/details/gtbixqrnku.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgeathuwt.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtxgmzzwky.html

TS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gthmcopcwq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtiwdgtmbn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hammf.cn/Article/details/gtqotpvjdw.html

Ruby: Dir.children("dir")
来源：http://dali.cucudq.cn/Article/details/gteskwrwsz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtwcjidqwr.html

[F09] 获取文件大小
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfovjemwh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ivvv.top/Article/details/gtxhxbcilg.html

PHP:  filesize("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtkcluefuk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gtewcxdfbq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gtieyzctqq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtnbemalmm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sysykeji.top/Article/details/gtzktvsqgp.html

Ruby: File.size("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtucfmkqyh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.snrcjt.cn/Article/details/gtawtspsck.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhoulong.xyz/Article/details/gtuljzyloh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtjsnimlcs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtuzbcuiil.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gthbahetdc.html

TS:   path.extname("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtasawmkkx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskacfynr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtseoxvmda.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtbspswqjq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtliwixlvk.html

[F11] 复制与移动文件
来源：http://dali.ppjwa.cn/Article/details/gtamppdufv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtxieayvey.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxuanxn.top/Article/details/gttpcwksoo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtoubvnerq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtsrueliid.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sxryk.cn/Article/details/gtzobmqisx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigufen.top/Article/details/gtlezoqnbl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtoevnzeer.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yongpay.top/Article/details/gthzrbwmue.html

[F12] CSV 读写
来源：http://dali.yuanzhike.top/Article/details/gttcskhqtz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.smart0.xyz/Article/details/gtpfiermjd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jianghu66.top/Article/details/gtmvnelfwe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.mhx1999.top/Article/details/gtzeuvbkae.html

TS:   // 同上
来源：http://dali.zdqjudy.top/Article/details/gtdzmwfdcg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnxiangtu.top/Article/details/gtptjbyydb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yangfankeji.com/Article/details/gtzuwiehaz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj202588.top/Article/details/gtshqxrene.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ivvv.top/Article/details/gtrelyeaqc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtzrptzngp.html

G. 面向对象
来源：http://dali.redwolf501.top/Article/details/gtdumrvvmg.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtrvpsmfxv.html

[G01] 定义类
来源：http://dali.zycfv.cn/Article/details/gtdkackmue.html

Py:   class User: pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigxkonta.html

PHP:  class User {}
来源：http://dali.redwolf501.top/Article/details/gtghtuygag.html

JS:   class User {}
来源：http://dali.fzhhl.top/Article/details/gtmgswfkzs.html

TS:   class User { name: string = ""; }
来源：http://dali.yongpay.top/Article/details/gtwjlsxdsx.html

Java: class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtkrofvnap.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gtlsvsahnx.html

Ruby: class User; end
来源：http://dali.cqqwz.cn/Article/details/gtdrrsihcr.html

C#:   class User {}
来源：http://dali.tian-w.cn/Article/details/gtklvavqim.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gtuhmzfvbb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjggotbyv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sxryk.cn/Article/details/gtjprhntrg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtnrjdpfsx.html

TS:   constructor(public name: string) {}
来源：http://dali.gotoacloud.top/Article/details/gtgwilzzqg.html

Java: User(String name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gtwvjdkjcw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gtjrbcekdq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gtnstcdqwt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtxclxllau.html

[G03] 实例属性
来源：http://dali.zhengqikj.top/Article/details/gturcoqqeh.html

Py:   self.name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtebfobctq.html

PHP:  public string $name = "x";
来源：http://dali.tian-w.cn/Article/details/gtoxhhmjqw.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjiluotzp.html

TS:   name: string = "x";
来源：http://dali.guannengcc.top/Article/details/gtwhjsfflf.html

Java: private String name;
来源：http://dali.quarkkingdee.top/Article/details/gttgeiwvgl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ydzc1.top/Article/details/gtirvuetua.html


<!-- 参考信息 -->