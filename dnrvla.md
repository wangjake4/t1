代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnqzz.top/Article/details/gtamiivugh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xinyue.icu/Article/details/gtvduwstmg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.redwolf501.top/Article/details/gtihloxtzs.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hongshengwenyu.top/Article/details/gttfowdlgl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmarulhsi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.aibaodan.cn/Article/details/gtyynizlha.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yangfankeji.com/Article/details/gtxfjsabvq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gthjlramqe.html

[E06] 替换子串
来源：http://dali.cdnleiting.top/Article/details/gtbxoueylz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gtkdjoroii.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gaohongyu789.top/Article/details/gthveppcpq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtzxnxxheg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtuqpigfut.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtwiusazpd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gtevzhxyzo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tanke756.top/Article/details/gtdgwffxoz.html

C#:   s.Replace("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtenehcsmr.html

[E07] 按分隔符拆分
来源：http://dali.fzhhl.top/Article/details/gtsbbvdjqk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangdashe.top/Article/details/gtamvnycfh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zycfv.cn/Article/details/gtcvjpemhq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258888.top/Article/details/gtzraijqgu.html

TS:   s.split(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjsyttry.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtxnrrec.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.kuanghao11.cn/Article/details/gteytkltis.html

Ruby: s.split(",");  s.split
来源：http://dali.yuxming.cn/Article/details/gtxsaemhkw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.snrcjt.cn/Article/details/gtsknavnrw.html

[E08] 数组按分隔符合并
来源：http://dali.shangyingyoupin.top/Article/details/gtmzghaojl.html

Py:   ",".join(items)
来源：http://dali.sxryk.cn/Article/details/gtmhanfijh.html

PHP:  implode(",", $items);
来源：http://dali.nanxinkj.top/Article/details/gtsaqazrar.html

JS:   items.join(",")
来源：http://dali.xylfe.cn/Article/details/gthxnrhyrh.html

TS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtbjihajyg.html

Java: String.join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gtmnaruuud.html

Go:   strings.Join(items, ",")
来源：http://dali.yueranfly.top/Article/details/gtkuqydeca.html

Ruby: items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtahrucsdb.html

C#:   string.Join(",", items)
来源：http://dali.yj20258888.top/Article/details/gtzreookib.html

[E09] 去除所有空白字符
来源：http://dali.guannengcc.top/Article/details/gtvlzbkjpr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cucudq.cn/Article/details/gthlxhbqgg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hfpthk.cn/Article/details/gtqkweawlz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gtnecxuzji.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gtowodnvsh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ivvv.top/Article/details/gtlqbiprsm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yonumen.top/Article/details/gtttiihkbq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xziqi.cn/Article/details/gtfxzervcf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gtfmkwmigb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jyoumei.cn/Article/details/gtxyhuypzt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtoqnoyudo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxuanxn.top/Article/details/gtcxajpzig.html

JS:   "7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtdkgutjmx.html

TS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtiwnzsqdx.html

Java: String.format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtuekojwjw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gtisankmax.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtdnxqhify.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.c1oappe.top/Article/details/gtrtxobyrm.html

[E11] 反转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtraudnpxp.html

Py:   s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gteosbbuxr.html

PHP:  strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gtrtdhiiyv.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohcxkvhy.html

TS:   [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtsjmlumot.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gtekmorjnw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fengsongda.top/Article/details/gtkixsamwm.html

Ruby: s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtkcmzhswq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gtsshgfxdv.html

[E12] 统计某字符出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gtrxezihev.html

Py:   s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gtpgtuoyzn.html

PHP:  substr_count($s, "a");
来源：http://dali.vqdsnc.cn/Article/details/gtjrtjgilo.html

JS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gtuccqrekc.html

TS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtqakbzsyb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hywenlv.cn/Article/details/gtyaujshix.html

Go:   strings.Count(s, "a")
来源：http://dali.0kj1m.cn/Article/details/gtkhvkbfgn.html

Ruby: s.count("a")
来源：http://dali.fzhhl.top/Article/details/gtkxqukanc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tanke756.top/Article/details/gtkddcqavr.html

[E13] 逐字符遍历
来源：http://dali.nanxinkj.top/Article/details/gtdfedljil.html

Py:   for ch in s: print(ch)
来源：http://dali.xinyue.icu/Article/details/gtnhugnjpd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvqrgztbp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gtlaykisgb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtvugxkvku.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yvedp.cn/Article/details/gtuxydpimj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xziqi.cn/Article/details/gteoldmzsb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpqtntfx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtfpfhdekl.html

[E14] URL 编码与 Base64
来源：http://dali.pycfn.com/Article/details/gtyxmogjvg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangdashe.top/Article/details/gtughtnnbt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.316326.xyz/Article/details/gtbjkciqvh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sxryk.cn/Article/details/gtutltasuf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenzaomai.com/Article/details/gtsakdqqsw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtvcbkufef.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xinyue.icu/Article/details/gtnvjyzkmv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.mhx1999.top/Article/details/gtlxyszpnp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtcvclovdo.html

[E15] HTML 转义 / 反转义
来源：http://dali.c1oappe.top/Article/details/gtfxxutjrg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjafzfss.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnxiangtu.top/Article/details/gteunuesel.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.316326.xyz/Article/details/gtdyypeisn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.andypj.xyz/Article/details/gtirgsqpdd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xylfe.cn/Article/details/gthflnnazy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fengsongda.top/Article/details/gthaulcndy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cqqwz.cn/Article/details/gtgpsbpwmn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yongpay.top/Article/details/gtoeyshlab.html

[E16] 数字千分位
来源：http://dali.yueranfly.top/Article/details/gtxsqrvknu.html

Py:   f"{1234567:,}"
来源：http://dali.tianlin.xyz/Article/details/gtvbwodswd.html

PHP:  number_format(1234567);
来源：http://dali.zhiwuduotai.top/Article/details/gtzotgepfp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtufhukaqb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gtiivkeids.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxinkj.top/Article/details/gtgvnuhcdr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpdcwlvj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yongpay.top/Article/details/gtfspwuzhx.html

C#:   1234567.ToString("N0")
来源：http://dali.zhengqikj.top/Article/details/gtqyboczfw.html

[E17] 首字母大写
来源：http://dali.xinyue.icu/Article/details/gttdzleuvn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj202588.top/Article/details/gttzcqvlok.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gtwxvdksrh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gtsadzljfe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gtwdlpzzzb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrnroran.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shuidangran.top/Article/details/gtnvsaptcu.html

Ruby: s.capitalize
来源：http://dali.yj20258888.top/Article/details/gtfrorgypr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gaohongyu789.top/Article/details/gtdjmvwgho.html

[E18] 模板占位符替换
来源：http://dali.dianchejie.cn/Article/details/gtruoifjrj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthomqvwwl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhixingplan.top/Article/details/gtcfgjfbtr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtrryeqyll.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtiofqpfig.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ivvv.top/Article/details/gtwleovvwk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtvdvwbkhg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fzhhl.top/Article/details/gtngpnhqhj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yanxiufei.cn/Article/details/gtetuqdhbk.html

[E19] 多行文本按行拆分
来源：http://dali.yongpay.top/Article/details/gtbigvmwju.html

Py:   s.splitlines()
来源：http://dali.ydzc1.top/Article/details/gtzkecshhc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuanzx.com/Article/details/gtbqmjvkvo.html

JS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gttgwlkolr.html

TS:   s.split(/\r?\n/)
来源：http://dali.sxryk.cn/Article/details/gtelouxrvs.html

Java: s.lines().toList()
来源：http://dali.guowangkeji.top/Article/details/gtkvbaedbr.html

Go:   strings.Split(s, "\n")
来源：http://dali.zdqjudy.top/Article/details/gtftqspeyq.html

Ruby: s.lines
来源：http://dali.tanke756.top/Article/details/gtscfguvte.html

C#:   s.Split('\n')
来源：http://dali.xziqi.cn/Article/details/gtmyqknucr.html

[E20] 判断字符串是否为空
来源：http://dali.jiagoushi.top/Article/details/gtsdkpbgik.html

Py:   if not s:
来源：http://dali.yueranfly.top/Article/details/gtezdfhasj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shangyingyoupin.top/Article/details/gtqqnthito.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgufenzy.top/Article/details/gtnouksxaa.html

TS:   if (s === "") {}
来源：http://dali.zdqjudy.top/Article/details/gtfvmbsydm.html

Java: if (s.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gtbmdrsajp.html

Go:   if s == "" {}
来源：http://dali.jqgufenzy.top/Article/details/gtjxgljkup.html

Ruby: if s.empty?
来源：http://dali.yvedp.cn/Article/details/gtskkacszo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj202588.top/Article/details/gtptrkhtal.html

[E21] 超长截断加省略号
来源：http://dali.iojbl.cn/Article/details/gtqbgdxirs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258.top/Article/details/gtnzvvjvmf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtdefppgic.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gttczoxtqi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gttkfutqeo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtplxunskf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gogol.net.cn/Article/details/gtfberrsca.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtqpamtdwh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgntfysh.html

[E22] 字节长度与字符长度
来源：http://dali.haohaochexian.top/Article/details/gtwozkiikn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtuqwvrtkc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtqzxhyejj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gtfexexili.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gtoimcqgob.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhhfbdky.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258.top/Article/details/gtgazkeniz.html

Ruby: s.bytesize;  s.length
来源：http://dali.xinyue.icu/Article/details/gtjdsmhuif.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gtmjhduygd.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtolwyqpac.html

F. 文件与目录
来源：http://dali.zhengqikj.top/Article/details/gtkqcwrlgg.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtwcfgjudm.html

[F01] 读取整个文件
来源：http://dali.andypj.xyz/Article/details/gtsiretkdj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aibaodan.cn/Article/details/gtvykczybu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtiasevyjp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.316326.xyz/Article/details/gtlzvwvnjj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtjqmbyodv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtzdpqakcd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guannengcc.top/Article/details/gtpwzrnnrd.html

Ruby: File.read("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtlbhzfdgt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtoiorgmbj.html

[F02] 逐行读取文件
来源：http://dali.havefunace.top/Article/details/gtliimrmkp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhengqikj.top/Article/details/gtmixmhncm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.haohaochexian.top/Article/details/gttiycfrgz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gtjgkkqmoj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gtgmyjtsfr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gtipvbkgxx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shuidangran.top/Article/details/gtdhvfnfjp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sxryk.cn/Article/details/gtcjpvxmbg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxuanxn.top/Article/details/gtmtbueztg.html

[F03] 写入文件（覆盖）
来源：http://dali.xuetiantiany.cn/Article/details/gtscmrqgam.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pycfn.com/Article/details/gtmlwlnevw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gtsoictxll.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtppxerxmq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtxdggbflo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yangfankeji.com/Article/details/gtejuijesh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tian-w.cn/Article/details/gtasafueik.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sufxvd.cn/Article/details/gtubxoyrhn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gtjovpoype.html

[F04] 追加写入文件
来源：http://dali.sysykeji.top/Article/details/gtcttgzjva.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jiagoushi.top/Article/details/gttlnjsqwf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gtzozaygmp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgufenzy.top/Article/details/gtawsupjyp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtzmgftbdo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ybcxt.top/Article/details/gtyjnzmwqe.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtfoifhzho.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.meibo888.top/Article/details/gtckloxplu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gtethpgxij.html

[F05] 判断文件或目录是否存在
来源：http://dali.hywenlv.cn/Article/details/gtbttlwlsi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sysykeji.top/Article/details/gtphtiqjik.html

PHP:  file_exists("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtrcsltldp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtnbabrxhe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtmtmfistv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtilgeywvt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hywenlv.cn/Article/details/gtaxmaboin.html

Ruby: File.exist?("a.txt")
来源：http://dali.xylfe.cn/Article/details/gthxbzljel.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcrlmlwxo.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gtvbhgvmfb.html

Py:   os.remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtgpulcafp.html

PHP:  unlink("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtxlvkhevc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtprdisnmq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gteljcyvei.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtdydhxzjt.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtsxjskfwt.html

Ruby: File.delete("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtldthhavr.html

C#:   File.Delete("a.txt");
来源：http://dali.tanke756.top/Article/details/gtpzqibinb.html

[F07] 创建目录（含多级）
来源：http://dali.tian-w.cn/Article/details/gtapbgmxvk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gtttcycztn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnqzz.top/Article/details/gtwvdmzgat.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gtilennugo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gtsckmdrqp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhoulong.xyz/Article/details/gtmglsuqxz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenzaomai.com/Article/details/gtvuijbcqq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cdnleiting.top/Article/details/gtoxbcmzuu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258888.top/Article/details/gtzjbrdtjs.html

[F08] 遍历目录
来源：http://dali.mhx1999.top/Article/details/gtyicmjhpx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fengsongda.top/Article/details/gtfxktcxnb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.9152youxi.cn/Article/details/gtgoafwqys.html

JS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtlcqgpskr.html

TS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gtmieylvyo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gtzwcrsbaj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtmvghcjoq.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gterhhyukt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daxiang520.top/Article/details/gtbalrpbpg.html

[F09] 获取文件大小
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipznyprq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtwyakmzdm.html

PHP:  filesize("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtajkwykuy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gtuqidfcbm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gtmowsatdc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtnavndxik.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.iojbl.cn/Article/details/gtofgpuxzv.html

Ruby: File.size("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtoxqocjxs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfllndpy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xziqi.cn/Article/details/gtmdmvdbvx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtizhlhnnp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guannengcc.top/Article/details/gtibkoourf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtapwztlva.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtnkwrhmqv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jianghu66.top/Article/details/gtywfalvst.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtvbenshww.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gttxbnsmnx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtiiqmrgxy.html

[F11] 复制与移动文件
来源：http://dali.yueranfly.top/Article/details/gtwwgkjqgi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtoobymrqa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gzhubu.top/Article/details/gtascqtthz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtlzkyoniq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtcxnqqqrg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.havefunace.top/Article/details/gtkilxomlr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuanzx.com/Article/details/gthuuuqqgl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtfljwbdga.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.c1oappe.top/Article/details/gtivmpzfgu.html

[F12] CSV 读写
来源：http://dali.fengsongda.top/Article/details/gtppkuxmea.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xziqi.cn/Article/details/gtpmshhmin.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fzhhl.top/Article/details/gtxdljfscd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.iojbl.cn/Article/details/gtsrqrubhh.html

TS:   // 同上
来源：http://dali.jqgfzy.top/Article/details/gtytsychmb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hysaishi.cn/Article/details/gtgynybgpt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtnolryryf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jianghu66.top/Article/details/gtngtdupaq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.meibo888.top/Article/details/gtobwslgyz.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtfjcjdolr.html

G. 面向对象
来源：http://dali.jqgfzy.top/Article/details/gtcfitaogo.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtvxvjzmyj.html

[G01] 定义类
来源：http://dali.meibo888.top/Article/details/gtemwsgtet.html

Py:   class User: pass
来源：http://dali.gaohongyu789.top/Article/details/gtilrplnoo.html

PHP:  class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtjahdjizx.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtvhuboxdk.html

TS:   class User { name: string = ""; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqvzbukqz.html

Java: class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfpxztom.html

Go:   type User struct { Name string }
来源：http://dali.sxryk.cn/Article/details/gtklclfksw.html

Ruby: class User; end
来源：http://dali.nwbrower.top/Article/details/gtnlkvcslg.html

C#:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gtqtstabxg.html

[G02] 构造函数
来源：http://dali.dianchejie.cn/Article/details/gtquscxfdt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cqqwz.cn/Article/details/gttjdafzep.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.c1oappe.top/Article/details/gtikqodqnt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gthjedhtib.html

TS:   constructor(public name: string) {}
来源：http://dali.nwbrower.top/Article/details/gtnpqhtpsj.html

Java: User(String name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gtxapydrhf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.316326.xyz/Article/details/gtvojsrnrc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ppjwa.cn/Article/details/gtbsnqhheq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtjpivxjbg.html

[G03] 实例属性
来源：http://dali.c1oappe.top/Article/details/gtwrfedpgo.html

Py:   self.name = "x"
来源：http://dali.yueranfly.top/Article/details/gtmxuqfote.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gthuxcnywa.html

JS:   this.name = "x";
来源：http://dali.yongpay.top/Article/details/gtognprwzc.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gtdcpansoz.html

Java: private String name;
来源：http://dali.yj202588.top/Article/details/gtwjznfxlr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tianlin.xyz/Article/details/gtiejqrpsv.html


<!-- 参考信息 -->