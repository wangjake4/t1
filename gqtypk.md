代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gthprsiefj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.havefunace.top/Article/details/gtnelvgvvw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gtiesryuqf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cdnleiting.top/Article/details/gtcippiava.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tanke756.top/Article/details/gtvttxgvlp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cucudq.cn/Article/details/gtylicfyvv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gotoacloud.top/Article/details/gtbqompulh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gtinqphker.html

[E06] 替换子串
来源：http://dali.wangdashe.top/Article/details/gtvmptreup.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cucudq.cn/Article/details/gtsvqquobl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuxming.cn/Article/details/gtxeplvqfd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtnaarpxhl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteujcphzo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtnxwuassu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gthzlhrjxm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtrefwyavo.html

C#:   s.Replace("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtpjmqnjcv.html

[E07] 按分隔符拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbzlvcdt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzginnecq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtnleucerf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hnqzz.top/Article/details/gtgybbnliv.html

TS:   s.split(",")
来源：http://dali.xinyue.icu/Article/details/gtoninpsem.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hywenlv.cn/Article/details/gthtwpqqmv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cheryme.top/Article/details/gttrxnvpcc.html

Ruby: s.split(",");  s.split
来源：http://dali.smart0.xyz/Article/details/gtoagkpemg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdztjesx.html

[E08] 数组按分隔符合并
来源：http://dali.jianghu66.top/Article/details/gtaeggtehc.html

Py:   ",".join(items)
来源：http://dali.zhixingplan.top/Article/details/gtnqhaxjbj.html

PHP:  implode(",", $items);
来源：http://dali.zhengqikj.top/Article/details/gtsffladmg.html

JS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gthekvwojy.html

TS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gtntolakgl.html

Java: String.join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gtvtaloxkr.html

Go:   strings.Join(items, ",")
来源：http://dali.hammf.cn/Article/details/gtdwzbqyyu.html

Ruby: items.join(",")
来源：http://dali.pycfn.com/Article/details/gtcoyqtdqm.html

C#:   string.Join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gtfbyudmbt.html

[E09] 去除所有空白字符
来源：http://dali.chenlongwang.top/Article/details/gtergnvpsf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtglznbjew.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtgfegmunh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gtqodgweme.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gthtqzxvzb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gtwddpixsr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258.top/Article/details/gtevnpoflx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj202588.top/Article/details/gtkumyaxay.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.fzhhl.top/Article/details/gtkoalripu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gzhubu.top/Article/details/gthzeydbeq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtrihmwqmc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cashguo.top/Article/details/gtryotmvsu.html

JS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtwrjsjepu.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtjwbaopxa.html

Java: String.format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtmdpbaavc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gtxnoaspgp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtlkvspqgd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guowangkeji.top/Article/details/gtntuuvigv.html

[E11] 反转字符串
来源：http://dali.shzxlz.cn/Article/details/gtllqfgrgf.html

Py:   s[::-1]
来源：http://dali.daria6918.cn/Article/details/gtimyhntsa.html

PHP:  strrev($s);
来源：http://dali.shuidangran.top/Article/details/gtoysrpcqj.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppfvlelh.html

TS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtczfaednh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.aizwys.cn/Article/details/gtxqzazhtw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtvzullzbj.html

Ruby: s.reverse
来源：http://dali.nanxinkj.top/Article/details/gthonpigxe.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gtidwjxrsk.html

[E12] 统计某字符出现次数
来源：http://dali.316326.xyz/Article/details/gtqdldwrsj.html

Py:   s.count("a")
来源：http://dali.iojbl.cn/Article/details/gtezrrssha.html

PHP:  substr_count($s, "a");
来源：http://dali.yueranfly.top/Article/details/gtfvgfcrtd.html

JS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gtkiitdptf.html

TS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gtyfzokojc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gogol.net.cn/Article/details/gtjjesiyfr.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigufen.top/Article/details/gtkrsjajis.html

Ruby: s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gtmrrjvloh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cucudq.cn/Article/details/gtclycpasl.html

[E13] 逐字符遍历
来源：http://dali.nanxinkj.top/Article/details/gtocaxeirg.html

Py:   for ch in s: print(ch)
来源：http://dali.yanxiufei.cn/Article/details/gtvhypqpfo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyauklypf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtsfzomety.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtevdpdngr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnqzz.top/Article/details/gtfbgxkhbu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aizwys.cn/Article/details/gtbplrwgpi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.daria6918.cn/Article/details/gtqldczkdm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtqrtvvlal.html

[E14] URL 编码与 Base64
来源：http://dali.hysaishi.cn/Article/details/gthnlwnvfn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zycfv.cn/Article/details/gtpqdrxfsv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nwbrower.top/Article/details/gtisfntbig.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.mhx1999.top/Article/details/gtgydnpmjy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.kuanghao11.cn/Article/details/gtzfkejxzn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.redwolf501.top/Article/details/gtjptvxgym.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlorjitkw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cqqwz.cn/Article/details/gtabvlerzg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtwmomvrpo.html

[E15] HTML 转义 / 反转义
来源：http://dali.ehwqpu.com/Article/details/gtazkxlbyn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jlsjyb.cn/Article/details/gtvbvahfto.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nanxinkj.top/Article/details/gtygqolmay.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznkfiqtq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sweek.top/Article/details/gtdecracio.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinghuilouyu.cn/Article/details/gtctgodjte.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zycfv.cn/Article/details/gtxvduaaav.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gtltzzcgwu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtzsqghqrr.html

[E16] 数字千分位
来源：http://dali.snrcjt.cn/Article/details/gtlakerlmc.html

Py:   f"{1234567:,}"
来源：http://dali.nanxinkj.top/Article/details/gteohnozql.html

PHP:  number_format(1234567);
来源：http://dali.redwolf501.top/Article/details/gtzaqivuiy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gtxiodbgce.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyewruhjv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daxiang520.top/Article/details/gtjiczggdi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgfzy.top/Article/details/gttaorvfnt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daria6918.cn/Article/details/gtmeipsztz.html

C#:   1234567.ToString("N0")
来源：http://dali.hysaishi.cn/Article/details/gtsbbdijme.html

[E17] 首字母大写
来源：http://dali.sweek.top/Article/details/gtyxfgkndg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.smart0.xyz/Article/details/gtaitbbyiy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtssmdqoqk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtoxirewiv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzmvpjoy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.316326.xyz/Article/details/gtmianqnza.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtftwvjnnq.html

Ruby: s.capitalize
来源：http://dali.sysykeji.top/Article/details/gtqpeearls.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gogol.net.cn/Article/details/gtwqtbbfqt.html

[E18] 模板占位符替换
来源：http://dali.pengpengdd.cyou/Article/details/gtnhyfqghz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pengpengdd.cyou/Article/details/gtusuewiiu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuetiantiany.cn/Article/details/gtsehxvncc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtbszzygde.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gttwzgfwpq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtjozhcqee.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtvgmfbkes.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigufen.top/Article/details/gtpipuqfeo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sxryk.cn/Article/details/gtbeolyfbl.html

[E19] 多行文本按行拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtsozqvcqn.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gtwfppyrfr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.birdmap.top/Article/details/gtjwldipzc.html

JS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gtjlbwlcot.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtejppxfmj.html

Java: s.lines().toList()
来源：http://dali.nwbrower.top/Article/details/gtnalupnmd.html

Go:   strings.Split(s, "\n")
来源：http://dali.nwbrower.top/Article/details/gtqhybmyiv.html

Ruby: s.lines
来源：http://dali.guowangkeji.top/Article/details/gtefzqoeqf.html

C#:   s.Split('\n')
来源：http://dali.yonumen.top/Article/details/gtspodcwvi.html

[E20] 判断字符串是否为空
来源：http://dali.jqgufenzy.top/Article/details/gtuwnyucmk.html

Py:   if not s:
来源：http://dali.yueranfly.top/Article/details/gtkgcmhoey.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.bjfxy.top/Article/details/gtlrvbyeso.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gaohongyu789.top/Article/details/gtehiddqxc.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gtvagwvzte.html

Java: if (s.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gtrpkowsvo.html

Go:   if s == "" {}
来源：http://dali.dianchejie.cn/Article/details/gttzikzgoc.html

Ruby: if s.empty?
来源：http://dali.xziqi.cn/Article/details/gtmydjfsrw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.9152youxi.cn/Article/details/gtyttnkrbq.html

[E21] 超长截断加省略号
来源：http://dali.kuanghao11.cn/Article/details/gtbrwndyzz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxinkj.top/Article/details/gtaveccjgi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtdxzkaugw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtpjelkxup.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtamxaeniw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtatwuldlz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.haohaochexian.top/Article/details/gtdgsgosrp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtuukbnonz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtqokokrfk.html

[E22] 字节长度与字符长度
来源：http://dali.xziqi.cn/Article/details/gtcswynmbv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258.top/Article/details/gtiqskjokx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtwqzwshpf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtbztrvcsi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtwhkcfsnr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daxiang520.top/Article/details/gtfhmusoxj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnqzz.top/Article/details/gttcqxcztq.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258888.top/Article/details/gtxalcfzgd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrftnwyhn.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtichmcoft.html

F. 文件与目录
来源：http://dali.gogol.net.cn/Article/details/gtlbrwpmyu.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtelidgdtq.html

[F01] 读取整个文件
来源：http://dali.sweek.top/Article/details/gtaoprouvo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zdqjudy.top/Article/details/gtrelbamkm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtwphiwmox.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnxiangtu.top/Article/details/gtvpjzdcwb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtqaynqifp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtemkhjsbu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hysaishi.cn/Article/details/gthluwvvid.html

Ruby: File.read("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtfvuxnjvy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtdnsdzzxl.html

[F02] 逐行读取文件
来源：http://dali.hnqzz.top/Article/details/gthaojbwyh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhixingplan.top/Article/details/gtwyjkkrtw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nwbrower.top/Article/details/gtfbvkpirs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gtkuaubfow.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gtfkpccnzn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gtoaxdhzeq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ivvv.top/Article/details/gtqamhhjhf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jyoumei.cn/Article/details/gtgyqlucvd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hysaishi.cn/Article/details/gtxtanaqoz.html

[F03] 写入文件（覆盖）
来源：http://dali.hnxiangtu.top/Article/details/gtofalyhwz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtyhxpkfmf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gtjiurfkig.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cucudq.cn/Article/details/gthmugafjo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtdewqqycq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aibaodan.cn/Article/details/gttlhyzxkd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tianlin.xyz/Article/details/gtnpqzazzm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yongpay.top/Article/details/gteyqcqyur.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtgnfvzuer.html

[F04] 追加写入文件
来源：http://dali.yj20258.top/Article/details/gtqkysfync.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.smart0.xyz/Article/details/gtyuvyvgsn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.snrcjt.cn/Article/details/gtrxtytimu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gtvipfjkia.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjziorofv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jyoumei.cn/Article/details/gtzlixyvrb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yangfankeji.com/Article/details/gtqkqcqjcj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pengpengdd.cyou/Article/details/gtsqnltunf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hysaishi.cn/Article/details/gtiohteiib.html

[F05] 判断文件或目录是否存在
来源：http://dali.hysaishi.cn/Article/details/gtrzorkaww.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gaohongyu789.top/Article/details/gttgjzunui.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtacfnrhou.html

JS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gturereryc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtkdfkrrai.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtmtersllw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yvedp.cn/Article/details/gtspmqnyta.html

Ruby: File.exist?("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtzztpauir.html

C#:   File.Exists("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtwutptksi.html

[F06] 删除文件
来源：http://dali.quarkkingdee.top/Article/details/gtwnfbwwwg.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtcgccnidw.html

PHP:  unlink("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtfohmhimx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtlwmskwfg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtkyysggue.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gteggyxhrh.html

Go:   os.Remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtiufcacnv.html

Ruby: File.delete("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtbuvxmjwn.html

C#:   File.Delete("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtpcczrlkf.html

[F07] 创建目录（含多级）
来源：http://dali.yongpay.top/Article/details/gtixqeahbn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gtgdiyzwmj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cdnleiting.top/Article/details/gtlwnmdjxt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhxqliaj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuonotzmg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.birdmap.top/Article/details/gteqmhvxmq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hfpthk.cn/Article/details/gtrtilkvdh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnqzz.top/Article/details/gtiuclwkgz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.316326.xyz/Article/details/gtgddnpgiq.html

[F08] 遍历目录
来源：http://dali.fengsongda.top/Article/details/gtmbgwvwqk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.snrcjt.cn/Article/details/gtmyxjtbhq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cheryme.top/Article/details/gtfrazmzoy.html

JS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtvkngmjhh.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtetqjyqsq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gtwwrjthbk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxinkj.top/Article/details/gterralxzm.html

Ruby: Dir.children("dir")
来源：http://dali.cashguo.top/Article/details/gtfnstegqx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guannengcc.top/Article/details/gtpisapcql.html

[F09] 获取文件大小
来源：http://dali.zhixingplan.top/Article/details/gtsgrtbsed.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtvtlhhdsb.html

PHP:  filesize("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtgevywkyx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gtcjtogbss.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gtialiuzwx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtotqhuuhh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnqzz.top/Article/details/gtgefeamxc.html

Ruby: File.size("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtvbkeskrb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cdnleiting.top/Article/details/gtxgcopfvt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cdnleiting.top/Article/details/gtuikrolbi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtvpxkgnjm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtnkndqlrn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtoymkxdmm.html

TS:   path.extname("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtuhvvourp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenjidiqi.icu/Article/details/gtlnagusyf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtutormkyz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtoqxqozlt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgcttqlr.html

[F11] 复制与移动文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuccvvsrv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtjhhtldgb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtqppvhsco.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtfabwazlh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtjkxxgita.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ydzc1.top/Article/details/gtwgcvrnyq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nwbrower.top/Article/details/gtdvstrrdo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtoevcyodq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shuidangran.top/Article/details/gtgwvofgrm.html

[F12] CSV 读写
来源：http://dali.sweek.top/Article/details/gtnpbyayyi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sysykeji.top/Article/details/gtsgmpdwpq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cheryme.top/Article/details/gtptqdnuhy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.kuanghao11.cn/Article/details/gtmufrwqdb.html

TS:   // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gtcuztrtlc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jianghu66.top/Article/details/gtmjswcjgc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xylfe.cn/Article/details/gtwqdxlgez.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hywenlv.cn/Article/details/gtrwrgpalt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yvedp.cn/Article/details/gtbnhalkbv.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtbyuqpgzi.html

G. 面向对象
来源：http://dali.jiagoushi.top/Article/details/gtaxsysxmi.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtmjrgwedx.html

[G01] 定义类
来源：http://dali.jqgufenzy.top/Article/details/gtkvusvztr.html

Py:   class User: pass
来源：http://dali.hnqzz.top/Article/details/gthljbtiwy.html

PHP:  class User {}
来源：http://dali.redwolf501.top/Article/details/gthcrujjlz.html

JS:   class User {}
来源：http://dali.c1oappe.top/Article/details/gtedgvxpfs.html

TS:   class User { name: string = ""; }
来源：http://dali.hnxiangtu.top/Article/details/gtrwalqvba.html

Java: class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtkmzhharn.html

Go:   type User struct { Name string }
来源：http://dali.meibo888.top/Article/details/gtadjnhhbm.html

Ruby: class User; end
来源：http://dali.shuidangran.top/Article/details/gtrduggvks.html

C#:   class User {}
来源：http://dali.zycfv.cn/Article/details/gtfbvubhrv.html

[G02] 构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuikvmzab.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daria6918.cn/Article/details/gtjpvffftj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tian-w.cn/Article/details/gtaskqwgqu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gttbymqkrn.html

TS:   constructor(public name: string) {}
来源：http://dali.tianlin.xyz/Article/details/gtmisptbti.html

Java: User(String name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhanxwum.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cdnleiting.top/Article/details/gtqtqxqxdj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhoulong.xyz/Article/details/gtvuwegfzw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtknijbtmw.html

[G03] 实例属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvjvckii.html

Py:   self.name = "x"
来源：http://dali.hammf.cn/Article/details/gthtwpruto.html

PHP:  public string $name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtbxugdfuq.html

JS:   this.name = "x";
来源：http://dali.xuanzx.com/Article/details/gtawhectwi.html

TS:   name: string = "x";
来源：http://dali.redwolf501.top/Article/details/gtbxejciyh.html

Java: private String name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqzgaemf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xinyue.icu/Article/details/gteahjtpbd.html


<!-- 参考信息 -->