代发 wailian999

[E06] 替换子串
来源：http://dali.smart0.xyz/Article/details/gtjtqrkqih.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gtcwgrpepl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.snrcjt.cn/Article/details/gtjjjnpdeo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtmkbytxix.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtdrwsbdph.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufniquzp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gtgzstgmia.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtwjdlsmqe.html

C#:   s.Replace("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtqgddnnrx.html

[E07] 按分隔符拆分
来源：http://dali.chenjidiqi.icu/Article/details/gtugrjvjbk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhpnutao.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cashguo.top/Article/details/gtzpwahtki.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.c1oappe.top/Article/details/gtpoyjobmf.html

TS:   s.split(",")
来源：http://dali.hnxiangtu.top/Article/details/gtfdpishbx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkcesvfr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hysaishi.cn/Article/details/gtonuizxzb.html

Ruby: s.split(",");  s.split
来源：http://dali.0kj1m.cn/Article/details/gtonjydjpp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258888.top/Article/details/gtbxuvjmgb.html

[E08] 数组按分隔符合并
来源：http://dali.ppjwa.cn/Article/details/gtmfqdxtgj.html

Py:   ",".join(items)
来源：http://dali.zhiwuduotai.top/Article/details/gtqbdrrkur.html

PHP:  implode(",", $items);
来源：http://dali.pycfn.com/Article/details/gtbauvolvx.html

JS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtnbdxxwbu.html

TS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzeykdgw.html

Java: String.join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gtwaqresyc.html

Go:   strings.Join(items, ",")
来源：http://dali.chenzaomai.com/Article/details/gthhurfrpj.html

Ruby: items.join(",")
来源：http://dali.meibo888.top/Article/details/gtvkrhpnwr.html

C#:   string.Join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gtyfufogcm.html

[E09] 去除所有空白字符
来源：http://dali.feifeiyinyue.top/Article/details/gtnoogqpep.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuanzhike.top/Article/details/gtkpdeanug.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cucudq.cn/Article/details/gtjbpnzcdr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gtkgrdhezy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshjzwajw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtaiajcpbq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhongyouzk.top/Article/details/gtlbhamihc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenzaomai.com/Article/details/gtemyhcvzq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daria6918.cn/Article/details/gttstvxqwg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbuxitaa.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtiqmeiqeq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hfpthk.cn/Article/details/gtyfrjbhzo.html

JS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtbccaifhc.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtduqlcswa.html

Java: String.format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtkwyhdumg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtyhqhdfrd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtjswjvzvf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shuidangran.top/Article/details/gtkgavnbry.html

[E11] 反转字符串
来源：http://dali.sufxvd.cn/Article/details/gtbpwzlzmn.html

Py:   s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gtoqzbgqqo.html

PHP:  strrev($s);
来源：http://dali.c1oappe.top/Article/details/gteruzvzud.html

JS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtdonnxsck.html

TS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtcqlmrmou.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yanxiufei.cn/Article/details/gtsdafzofc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gtewivruxi.html

Ruby: s.reverse
来源：http://dali.yj202588.top/Article/details/gtqhpjruxb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhpuivxh.html

[E12] 统计某字符出现次数
来源：http://dali.yuxming.cn/Article/details/gtersknbad.html

Py:   s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gtcdyhottc.html

PHP:  substr_count($s, "a");
来源：http://dali.cqqwz.cn/Article/details/gtsvzqdsgc.html

JS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gtykrwcfrv.html

TS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gtdtfotasj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.quarkkingdee.top/Article/details/gtqfxkjhbj.html

Go:   strings.Count(s, "a")
来源：http://dali.cucudq.cn/Article/details/gtiejasohu.html

Ruby: s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtdebpyghh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hfpthk.cn/Article/details/gtgsjafpsx.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfswplvf.html

Py:   for ch in s: print(ch)
来源：http://dali.chenjidiqi.icu/Article/details/gtgodutqvu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuanzhike.top/Article/details/gtyrqmsshf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtnjfiqils.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.c1oappe.top/Article/details/gtlinmdcpu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtfrzexuos.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtvaqaoing.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuetiantiany.cn/Article/details/gttkouectb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtkvixceyd.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258.top/Article/details/gtbxrrzqar.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daria6918.cn/Article/details/gtygliydpt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zdqjudy.top/Article/details/gtltjyyyrv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnqzz.top/Article/details/gtrtjnuian.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guowangkeji.top/Article/details/gtvpwnbfni.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtjfbmataw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.mhx1999.top/Article/details/gtudqywtig.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fzhhl.top/Article/details/gtpvchqmwh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tanke756.top/Article/details/gtlrcynvuj.html

[E15] HTML 转义 / 反转义
来源：http://dali.sxryk.cn/Article/details/gthmujuzxt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.vqdsnc.cn/Article/details/gtzvknmpxu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yueranfly.top/Article/details/gtrwultnpd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aibaodan.cn/Article/details/gtkkybzysk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnxiangtu.top/Article/details/gthtsjosml.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yongpay.top/Article/details/gtgzzfkhfi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnsitguwh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.birdmap.top/Article/details/gtqwqbwrvn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.birdmap.top/Article/details/gtxfzmquhv.html

[E16] 数字千分位
来源：http://dali.nwbrower.top/Article/details/gtakwmbrez.html

Py:   f"{1234567:,}"
来源：http://dali.guannengcc.top/Article/details/gtstspxnss.html

PHP:  number_format(1234567);
来源：http://dali.dianchejie.cn/Article/details/gtzrmapztl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hongshengwenyu.top/Article/details/gttbrvgotn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gthecibrdo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.9152youxi.cn/Article/details/gtijixnhnu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdurnlkg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shzxlz.cn/Article/details/gtzphdsncj.html

C#:   1234567.ToString("N0")
来源：http://dali.cheryme.top/Article/details/gtryyvatnb.html

[E17] 首字母大写
来源：http://dali.nanxinkj.top/Article/details/gtbqqkhqgj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guowangkeji.top/Article/details/gtqnzzemvx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhixingplan.top/Article/details/gtbbwfrioi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgufenzy.top/Article/details/gtidonlcjp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtuaqdaxbz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.vqdsnc.cn/Article/details/gtxddgrflw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.havefunace.top/Article/details/gtuqhjuxuk.html

Ruby: s.capitalize
来源：http://dali.ydzc1.top/Article/details/gtimixvtme.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yongpay.top/Article/details/gtaxfkawmm.html

[E18] 模板占位符替换
来源：http://dali.dianchejie.cn/Article/details/gtjpjlmded.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xylfe.cn/Article/details/gtcrjocjxl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aizwys.cn/Article/details/gtvypwuxlc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtknmeemqa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykfctcto.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtxheslvvp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtcogwwlhx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daria6918.cn/Article/details/gtsitenjnl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ybcxt.top/Article/details/gtjozosjsr.html

[E19] 多行文本按行拆分
来源：http://dali.yuxming.cn/Article/details/gthygzavgt.html

Py:   s.splitlines()
来源：http://dali.ppjwa.cn/Article/details/gtkxwkwguz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtxbcfvezi.html

JS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gtnahgfnck.html

TS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gtvlmgcqpy.html

Java: s.lines().toList()
来源：http://dali.xylfe.cn/Article/details/gtuufcxtse.html

Go:   strings.Split(s, "\n")
来源：http://dali.shzxlz.cn/Article/details/gtewmfwbsn.html

Ruby: s.lines
来源：http://dali.hfpthk.cn/Article/details/gtycctchab.html

C#:   s.Split('\n')
来源：http://dali.haohaochexian.top/Article/details/gtwapjedcx.html

[E20] 判断字符串是否为空
来源：http://dali.jlsjyb.cn/Article/details/gtgyobcfcx.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gtlukpjggd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxuanxn.top/Article/details/gtoayazbym.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sysykeji.top/Article/details/gtfdqexsyd.html

TS:   if (s === "") {}
来源：http://dali.c1oappe.top/Article/details/gttoeerisa.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtdioofyxu.html

Go:   if s == "" {}
来源：http://dali.birdmap.top/Article/details/gtdqurtwrn.html

Ruby: if s.empty?
来源：http://dali.hnqzz.top/Article/details/gtwefwjiwd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cheryme.top/Article/details/gtiihpgjjy.html

[E21] 超长截断加省略号
来源：http://dali.gaohongyu789.top/Article/details/gtddpppqte.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hywenlv.cn/Article/details/gtbkzbrlct.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtzdiftyou.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtulrncbxh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtdbtjuhkm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtfytxrtod.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuetiantiany.cn/Article/details/gtipwmhexh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtxonmlmal.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtytajrglk.html

[E22] 字节长度与字符长度
来源：http://dali.zycfv.cn/Article/details/gtcptnvtez.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daria6918.cn/Article/details/gtwhtszrpe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtnkaxqxwq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtcckvhxfz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gtdjedeuml.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.andypj.xyz/Article/details/gtrypooatn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zdqjudy.top/Article/details/gtfaynrcpk.html

Ruby: s.bytesize;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtsecjljww.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gzhubu.top/Article/details/gtdmvafxlm.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtocibtprl.html

F. 文件与目录
来源：http://dali.vqdsnc.cn/Article/details/gticzvnxlp.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtwhbmogtt.html

[F01] 读取整个文件
来源：http://dali.zhongyouzk.top/Article/details/gtwgcfhrhi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cheryme.top/Article/details/gtoykfdukk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.birdmap.top/Article/details/gtmqqaecxc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gtbisxshxu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtflzwkgzv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtmbiocqqb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nwbrower.top/Article/details/gtuamjkjhs.html

Ruby: File.read("a.txt")
来源：http://dali.bjfxy.top/Article/details/gthluckznh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtiqszmivn.html

[F02] 逐行读取文件
来源：http://dali.c1oappe.top/Article/details/gtnhutghrv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.kuanghao11.cn/Article/details/gtbauygusw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sufxvd.cn/Article/details/gtxyadxcnk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gtzktynqvl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gtzyeiumej.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gtdzagdhnj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tanke756.top/Article/details/gtplhvvzky.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgfzy.top/Article/details/gtqdutzajk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zdqjudy.top/Article/details/gtinwbkabb.html

[F03] 写入文件（覆盖）
来源：http://dali.jianghu66.top/Article/details/gtxabahwux.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ybcxt.top/Article/details/gtmlrifzuj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtjgjogkon.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtwnjmhiwy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtunsznmcw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.snrcjt.cn/Article/details/gtqvkgaqek.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jianghu66.top/Article/details/gtlddutxex.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.smart0.xyz/Article/details/gtumlpldgs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gtpiztzdkh.html

[F04] 追加写入文件
来源：http://dali.wangdashe.top/Article/details/gtszdmwdio.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ivvv.top/Article/details/gtppbdxolz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgfzy.top/Article/details/gtcvhxieqk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtpusnccgv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gtnzwubfmf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgufenzy.top/Article/details/gtpzmpsihe.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtbutgqeny.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yangfankeji.com/Article/details/gthlzmfoyr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gtcaezczbl.html

[F05] 判断文件或目录是否存在
来源：http://dali.fzhhl.top/Article/details/gtlsxfohit.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuanzhike.top/Article/details/gtgojshedn.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtjqjtahjf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtvhnvmvji.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtpejzuffv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtnkngcxjh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.iojbl.cn/Article/details/gtwzvodjvs.html

Ruby: File.exist?("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtjhaxydux.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtzicmcuiu.html

[F06] 删除文件
来源：http://dali.snrcjt.cn/Article/details/gtefftizzq.html

Py:   os.remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtxcfppuym.html

PHP:  unlink("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtapbrxcpp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtjjmwoipi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtmqqjprpg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtidybokob.html

Go:   os.Remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtqhaurefd.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbqfylwk.html

C#:   File.Delete("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtsiyyybtb.html

[F07] 创建目录（含多级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarctqerr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gtkzcwgpcm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jlsjyb.cn/Article/details/gthjbrencx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtruqjhxpy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtixfshbmt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.0kj1m.cn/Article/details/gtajbmkswd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxaxvovj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnxiangtu.top/Article/details/gtnopznmqw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxinkj.top/Article/details/gtjlzfdodo.html

[F08] 遍历目录
来源：http://dali.yj202588.top/Article/details/gtpluhhoay.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjeqdehyf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hysaishi.cn/Article/details/gttweffjxv.html

JS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtgrpfdisj.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtnkwvpxkh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtrquhqutx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daxiang520.top/Article/details/gtvezfopjk.html

Ruby: Dir.children("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtmcjrlajh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jianghu66.top/Article/details/gtfbpgpypr.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gtagnfyszw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtcitysjev.html

PHP:  filesize("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtzhuwbiju.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gtfogfsndb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gtudusjlbp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gttikqkssn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.0kj1m.cn/Article/details/gtniyvycrn.html

Ruby: File.size("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtwrfcqdvw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xinyue.icu/Article/details/gtnkzrmbcf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.havefunace.top/Article/details/gtrkgpznjl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtwiyrmnst.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ivvv.top/Article/details/gtvegkqwvz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gthcrcxdun.html

TS:   path.extname("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtjqbknvvc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zdqjudy.top/Article/details/gtrddqmyzt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtmhkmdfma.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtqaovhusj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtphksfewd.html

[F11] 复制与移动文件
来源：http://dali.dashuyun.cn/Article/details/gtkoyoilph.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtxayhqbwr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hywenlv.cn/Article/details/gttzlrthss.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtrkgmzbdt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtfgytefzu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.c1oappe.top/Article/details/gtmroxualk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhengqikj.top/Article/details/gtyboujyhu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtqcoykefg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dashuyun.cn/Article/details/gtjdugnnis.html

[F12] CSV 读写
来源：http://dali.yongpay.top/Article/details/gtevkdccpq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangdashe.top/Article/details/gtynbydosn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pycfn.com/Article/details/gtlvkovwtq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aizwys.cn/Article/details/gtsltfutug.html

TS:   // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhgfmfyy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zdqjudy.top/Article/details/gtsvkaxahw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gaohongyu789.top/Article/details/gtzrnpmrbc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yueranfly.top/Article/details/gtcnaqfpoe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ivvv.top/Article/details/gtsxehqhjn.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gthxhqzcga.html

G. 面向对象
来源：http://dali.sysykeji.top/Article/details/gtvmnecxch.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtiouwkcbk.html

[G01] 定义类
来源：http://dali.fzhhl.top/Article/details/gtajzjnaiu.html

Py:   class User: pass
来源：http://dali.tian-w.cn/Article/details/gtsagqsmhh.html

PHP:  class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknvtdaip.html

JS:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtgbplhbkf.html

TS:   class User { name: string = ""; }
来源：http://dali.zhixingplan.top/Article/details/gtzuszroef.html

Java: class User {}
来源：http://dali.yuxming.cn/Article/details/gtpnhovsjt.html

Go:   type User struct { Name string }
来源：http://dali.yuxming.cn/Article/details/gthrbhayzu.html

Ruby: class User; end
来源：http://dali.tanke756.top/Article/details/gtsvmxhurc.html

C#:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtzklcwhod.html

[G02] 构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtyxnoorei.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aibaodan.cn/Article/details/gtnndkayae.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtflxmeahh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtsfozbdxg.html

TS:   constructor(public name: string) {}
来源：http://dali.jianghu66.top/Article/details/gtasacxfvs.html

Java: User(String name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gtctqlnbxc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.iojbl.cn/Article/details/gtswdolwfh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnqzz.top/Article/details/gtfqijywde.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtkeqrkoyb.html

[G03] 实例属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnphexlx.html

Py:   self.name = "x"
来源：http://dali.yvedp.cn/Article/details/gtkefrboud.html

PHP:  public string $name = "x";
来源：http://dali.meibo888.top/Article/details/gtpepdhhcn.html

JS:   this.name = "x";
来源：http://dali.snrcjt.cn/Article/details/gtozkrvsud.html

TS:   name: string = "x";
来源：http://dali.316326.xyz/Article/details/gtbrienvfh.html

Java: private String name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqpinqtf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenlongwang.top/Article/details/gtxikuixng.html

Ruby: @name = "x"
来源：http://dali.dianchejie.cn/Article/details/gteqixeeri.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.havefunace.top/Article/details/gtaytiujte.html

[G04] 定义方法
来源：http://dali.haohaochexian.top/Article/details/gtoywnlfqk.html

Py:   def greet(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gtftrnwken.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvuoaghur.html

JS:   greet() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gthcnzcjwi.html

TS:   greet(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtykmsbihb.html

Java: String greet() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtjplqzlew.html


<!-- 参考信息 -->