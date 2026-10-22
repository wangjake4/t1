代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shzxlz.cn/Article/details/gtexoqenmi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yanxiufei.cn/Article/details/gtrkfonbay.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gtcwidhqnm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ybcxt.top/Article/details/gtkgqfkljq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtiswycgqp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shzxlz.cn/Article/details/gtmjajbjek.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pycfn.com/Article/details/gtvarqgwti.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtqcytgbls.html

[E06] 替换子串
来源：http://dali.yvedp.cn/Article/details/gtuzzqcmig.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gtwnnnxars.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xziqi.cn/Article/details/gtokpmtoqh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtmoodzaaw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtcouhurep.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtjpxkxyux.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gtlhjcrogf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.316326.xyz/Article/details/gtslgjrdlz.html

C#:   s.Replace("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcanrfds.html

[E07] 按分隔符拆分
来源：http://dali.svipenyu.cn/Article/details/gtjzkazzhz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shangyingyoupin.top/Article/details/gtczgjbrad.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtuhzezxjn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gzhubu.top/Article/details/gtzhffzfex.html

TS:   s.split(",")
来源：http://dali.jqgufenzy.top/Article/details/gtftqvjqpx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.birdmap.top/Article/details/gtkyuvfuhe.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtsdlewnnn.html

Ruby: s.split(",");  s.split
来源：http://dali.chenjidiqi.icu/Article/details/gtnyildmvy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.havefunace.top/Article/details/gtabphkrof.html

[E08] 数组按分隔符合并
来源：http://dali.vqdsnc.cn/Article/details/gtotkyobtu.html

Py:   ",".join(items)
来源：http://dali.jianghu66.top/Article/details/gtzdxuasjs.html

PHP:  implode(",", $items);
来源：http://dali.yvedp.cn/Article/details/gtqjnbeida.html

JS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtkrhtkmip.html

TS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtzkcrpwbj.html

Java: String.join(",", items)
来源：http://dali.feifeiyinyue.top/Article/details/gtvbivmwbm.html

Go:   strings.Join(items, ",")
来源：http://dali.birdmap.top/Article/details/gtiitlqdld.html

Ruby: items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtcyttsfhs.html

C#:   string.Join(",", items)
来源：http://dali.wangdashe.top/Article/details/gtkvdpospi.html

[E09] 去除所有空白字符
来源：http://dali.mhx1999.top/Article/details/gtrmchjcnh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigufen.top/Article/details/gtynjrefpj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtznyqenxg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gtxjnykmxd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gogol.net.cn/Article/details/gtiddfsuek.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gtppinykwo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cqqwz.cn/Article/details/gtdwwdpyru.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jlsjyb.cn/Article/details/gtullyaszo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guannengcc.top/Article/details/gtbmcybqnw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yongpay.top/Article/details/gtlzghhxlb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtssazgorl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yonumen.top/Article/details/gtunydythm.html

JS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtnxrgurzi.html

TS:   "7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtzumineqw.html

Java: String.format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gthjodnmqu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gtlukaidpb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtbqorlurx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ppjwa.cn/Article/details/gtzsyokvne.html

[E11] 反转字符串
来源：http://dali.xinyue.icu/Article/details/gthsyijppj.html

Py:   s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gtxsoxqmvu.html

PHP:  strrev($s);
来源：http://dali.tian-w.cn/Article/details/gtmzcwveem.html

JS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtkjtqqyxh.html

TS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtdeciegrd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxuanxn.top/Article/details/gtcqkgbvsx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.meibo888.top/Article/details/gtnqhfrevl.html

Ruby: s.reverse
来源：http://dali.mhx1999.top/Article/details/gtyjxzvhtz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gtnuediool.html

[E12] 统计某字符出现次数
来源：http://dali.cashguo.top/Article/details/gteantgpmb.html

Py:   s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gteiokodnq.html

PHP:  substr_count($s, "a");
来源：http://dali.zhengqikj.top/Article/details/gtucnkmthl.html

JS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gtbpprwaay.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gtcydizbay.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fengsongda.top/Article/details/gtzkgzonma.html

Go:   strings.Count(s, "a")
来源：http://dali.hfpthk.cn/Article/details/gtaatiovvg.html

Ruby: s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gtmfuukwew.html

C#:   s.Count(c => c == 'a')
来源：http://dali.bjfxy.top/Article/details/gtltgqapzn.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdsowvye.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqgvhylq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbaieuave.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtypgkaznm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtgtlczcwg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtlkgzmmbx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shzxlz.cn/Article/details/gtmdbcdzff.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yvedp.cn/Article/details/gtuyubekkg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hysaishi.cn/Article/details/gttmqolhvv.html

[E14] URL 编码与 Base64
来源：http://dali.yuxming.cn/Article/details/gtfkotxley.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cqqwz.cn/Article/details/gtsnqmvssd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.smart0.xyz/Article/details/gtlmnwzheb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenjidiqi.icu/Article/details/gtvlxemxrl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjjcsape.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtcjzexlta.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hongshengwenyu.top/Article/details/gtlstrfjer.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.smart0.xyz/Article/details/gtfkeumoha.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hysaishi.cn/Article/details/gtbgbimoeu.html

[E15] HTML 转义 / 反转义
来源：http://dali.yueranfly.top/Article/details/gtalwwxmrl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jianghu66.top/Article/details/gtgqiaqfio.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ybcxt.top/Article/details/gtteugqmnu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jyoumei.cn/Article/details/gtpocheqlm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fengsongda.top/Article/details/gtdgvalbqh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.redwolf501.top/Article/details/gtyimbrviw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ybcxt.top/Article/details/gtrnoadwrg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aizwys.cn/Article/details/gtipuewriq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dashuyun.cn/Article/details/gtchdzimve.html

[E16] 数字千分位
来源：http://dali.cdnleiting.top/Article/details/gtgovyqcih.html

Py:   f"{1234567:,}"
来源：http://dali.sweek.top/Article/details/gtxkgbktwr.html

PHP:  number_format(1234567);
来源：http://dali.yj202588.top/Article/details/gtzibrsrbg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvwvcbnw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gtslbdojxh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daria6918.cn/Article/details/gtujilpgaw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.meibo888.top/Article/details/gtvtoknypy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmunixdhj.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gtdejktpls.html

[E17] 首字母大写
来源：http://dali.tian-w.cn/Article/details/gtzjpziiqq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daria6918.cn/Article/details/gtgziywkkv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ydzc1.top/Article/details/gtyxsjyrkk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gtsjunhpiq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtsxdmsswh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhengqikj.top/Article/details/gtfdqhbngq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtgaivohrl.html

Ruby: s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gtxwzjyhgs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.havefunace.top/Article/details/gtqvdfyrsn.html

[E18] 模板占位符替换
来源：http://dali.guannengcc.top/Article/details/gthzfibuch.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tanke756.top/Article/details/gtzxmrenty.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.daxiang520.top/Article/details/gtybtnrftp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtolousfol.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtisggrnur.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtktoeqstf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtflmsrjdj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigufen.top/Article/details/gtgtppojwz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhiwuduotai.top/Article/details/gtrbsferbh.html

[E19] 多行文本按行拆分
来源：http://dali.cheryme.top/Article/details/gteekkjanw.html

Py:   s.splitlines()
来源：http://dali.bjfxy.top/Article/details/gthuvilajq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtikfvoocn.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtbzqmsufi.html

TS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gtylzuqiil.html

Java: s.lines().toList()
来源：http://dali.snrcjt.cn/Article/details/gtgbrkpgka.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258888.top/Article/details/gtsljwehwo.html

Ruby: s.lines
来源：http://dali.hammf.cn/Article/details/gthnqyscuy.html

C#:   s.Split('\n')
来源：http://dali.wangdashe.top/Article/details/gtcpztjhet.html

[E20] 判断字符串是否为空
来源：http://dali.cqqwz.cn/Article/details/gtfepwxdwd.html

Py:   if not s:
来源：http://dali.haohaochexian.top/Article/details/gtmksmvkud.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daria6918.cn/Article/details/gtkdabugze.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tanke756.top/Article/details/gtxhejottw.html

TS:   if (s === "") {}
来源：http://dali.xinyue.icu/Article/details/gtpwvczpwc.html

Java: if (s.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gtckolvbqq.html

Go:   if s == "" {}
来源：http://dali.yuxming.cn/Article/details/gtpnxeusnc.html

Ruby: if s.empty?
来源：http://dali.hywenlv.cn/Article/details/gtjjauvwnp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.kuanghao11.cn/Article/details/gtwlxwwmke.html

[E21] 超长截断加省略号
来源：http://dali.xuanzx.com/Article/details/gtcmmhllrb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258.top/Article/details/gtkhsosbll.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtlcnfmipj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtqhpfxaya.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtvsvallpk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtfbljmsgo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzbzitdl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtyylzxkry.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtpmwuzizb.html

[E22] 字节长度与字符长度
来源：http://dali.yanxiufei.cn/Article/details/gtidomimud.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ehwqpu.com/Article/details/gtgtjmrgyy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtkgsvigie.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtrpsfrhtr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gtyhezorut.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.meibo888.top/Article/details/gtcgkarddn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cashguo.top/Article/details/gtmlzidvpr.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gttrfhrhrm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guowangkeji.top/Article/details/gtmbmuopmm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtpyjwxcna.html

F. 文件与目录
来源：http://dali.cucudq.cn/Article/details/gtazvioult.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gttwqupwrz.html

[F01] 读取整个文件
来源：http://dali.aibaodan.cn/Article/details/gtwzxtrebi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.c1oappe.top/Article/details/gthutpgpde.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtiwfdnpyu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pengpengdd.cyou/Article/details/gtktpvdapi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtdwootwfm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtkdzwmzbe.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gogol.net.cn/Article/details/gtzcreoccq.html

Ruby: File.read("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqferstmc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtsnlkfnwc.html

[F02] 逐行读取文件
来源：http://dali.wangshuangyany.cn/Article/details/gtvtniccui.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemuffuxc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtguwbcisf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gtcuveomdu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gtvavrzwwk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gtdnfzmuft.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258888.top/Article/details/gtubvhphyu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ivvv.top/Article/details/gtzovfodpm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pycfn.com/Article/details/gtkufnyeyp.html

[F03] 写入文件（覆盖）
来源：http://dali.mhx1999.top/Article/details/gtheyznujq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aibaodan.cn/Article/details/gtmusvwbru.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gtzjfqjorf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtntcrekxy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtgddwoxws.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnxiangtu.top/Article/details/gtntawmadf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daxiang520.top/Article/details/gtwrztwurt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ehwqpu.com/Article/details/gtwrxkdvgl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gtaebwcbev.html

[F04] 追加写入文件
来源：http://dali.yj202588.top/Article/details/gtpwtnfgny.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sxryk.cn/Article/details/gtqqxtnmpq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hywenlv.cn/Article/details/gtflqgnsuh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gthuwocjdp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbbvifci.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sweek.top/Article/details/gtwcnsvoqe.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtwnhxejsd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhixingplan.top/Article/details/gtsnlhvcaa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.svipenyu.cn/Article/details/gtanhkxaiv.html

[F05] 判断文件或目录是否存在
来源：http://dali.aizwys.cn/Article/details/gtibrqkqwz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aibaodan.cn/Article/details/gtoqflpxzd.html

PHP:  file_exists("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtbncetxcv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtpnanswqd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtizlgmqrc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gteiizmohh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.9152youxi.cn/Article/details/gtsqtomccj.html

Ruby: File.exist?("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtpyqmsono.html

C#:   File.Exists("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtyarahrio.html

[F06] 删除文件
来源：http://dali.chenjidiqi.icu/Article/details/gtcempzqbr.html

Py:   os.remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gthziyjejd.html

PHP:  unlink("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtkrzrhnum.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqzastwr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtpivnbdcx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtnuufkvej.html

Go:   os.Remove("a.txt")
来源：http://dali.hammf.cn/Article/details/gthlrwqoyp.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtlruzaetz.html

C#:   File.Delete("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtuqyqzofy.html

[F07] 创建目录（含多级）
来源：http://dali.smart0.xyz/Article/details/gtahixwfxu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gtcmmfzvbq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenzaomai.com/Article/details/gtlamlhkow.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtpvjzyfgz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.bjfxy.top/Article/details/gtqtekcbsc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jlsjyb.cn/Article/details/gtqiafqitp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.svipenyu.cn/Article/details/gtiptuhkvq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ivvv.top/Article/details/gtvsfqcxlm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cdnleiting.top/Article/details/gtfoujdxfr.html

[F08] 遍历目录
来源：http://dali.yvedp.cn/Article/details/gtyzezzjfy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fengsongda.top/Article/details/gtjdwwhsvg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.bjfxy.top/Article/details/gtwwrsxiod.html

JS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtjccjualg.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtvoalsagm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gtnfcfjvwq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daxiang520.top/Article/details/gtmkcfkpif.html

Ruby: Dir.children("dir")
来源：http://dali.ivvv.top/Article/details/gtwywstmxw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fengsongda.top/Article/details/gtfaqbmyrd.html

[F09] 获取文件大小
来源：http://dali.jiagoushi.top/Article/details/gtolhllyhy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtfalqekzx.html

PHP:  filesize("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtdqimctgg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gtfomxulfv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gthspdkgav.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtqgtkrmqx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guannengcc.top/Article/details/gtkyblclxb.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtakivyonl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zycfv.cn/Article/details/gtxjvaagsx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gtbofsziej.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtvuedmwvd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtucomsrep.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtkboajhsw.html

TS:   path.extname("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtvcwankui.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gtjpnquiej.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtzhorzrei.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtuvizqdrc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtdjiusist.html

[F11] 复制与移动文件
来源：http://dali.gzhubu.top/Article/details/gtpxchyotf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtvwlrswpg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ivvv.top/Article/details/gtehwluvvf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtiaaodeeo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtycwbnrou.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnfqggnmp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.redwolf501.top/Article/details/gteidqutqj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtgocobfgi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zdqjudy.top/Article/details/gtdqrtepqx.html

[F12] CSV 读写
来源：http://dali.wangshuangyany.cn/Article/details/gtrmfaypst.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuanzhike.top/Article/details/gtzyenvivq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangshuangyany.cn/Article/details/gtrwdblhyx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fengsongda.top/Article/details/gttbgjvkhg.html

TS:   // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gtivjzvwpw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangtech.top/Article/details/gtyyupspax.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258888.top/Article/details/gtbkyldbtp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.redwolf501.top/Article/details/gtgkijxrdz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cucudq.cn/Article/details/gtthorvbvd.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtvzsmecvg.html

G. 面向对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtwthgntpv.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gttprtscyg.html

[G01] 定义类
来源：http://dali.birdmap.top/Article/details/gtypbnplpe.html

Py:   class User: pass
来源：http://dali.redwolf501.top/Article/details/gtmdcneidf.html

PHP:  class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtpfrsmsri.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtrlunjmhj.html

TS:   class User { name: string = ""; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjagzlgph.html

Java: class User {}
来源：http://dali.yongpay.top/Article/details/gtqbfwtsko.html

Go:   type User struct { Name string }
来源：http://dali.smart0.xyz/Article/details/gthfhfcioy.html

Ruby: class User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljzfymeg.html

C#:   class User {}
来源：http://dali.sweek.top/Article/details/gtscemjdxx.html

[G02] 构造函数
来源：http://dali.yj202588.top/Article/details/gthyvmwqni.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxuanxn.top/Article/details/gtgwatcxcl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxhgpiok.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtxowzubhy.html

TS:   constructor(public name: string) {}
来源：http://dali.gotoacloud.top/Article/details/gtvlzfdven.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gtnjnrwdcf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gtyxfncvnn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gtpvefwttv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtbcgthndk.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gtzlrbipvg.html

Py:   self.name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtuflxbdxd.html

PHP:  public string $name = "x";
来源：http://dali.jqgfzy.top/Article/details/gttlwougzl.html

JS:   this.name = "x";
来源：http://dali.redwolf501.top/Article/details/gtllmhxdjq.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gtejxfewdy.html

Java: private String name;
来源：http://dali.jinqigufen.top/Article/details/gtcaxubvni.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuetiantiany.cn/Article/details/gtleorcgam.html


<!-- 参考信息 -->