代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.haohaochexian.top/Article/details/gtgsooidro.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cheryme.top/Article/details/gtygccvsrc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sufxvd.cn/Article/details/gtgpjlgvva.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtczbgleoi.html

[E02] 重复字符串
来源：http://dali.zycfv.cn/Article/details/gtutzblvra.html

Py:   "ab" * 3
来源：http://dali.hammf.cn/Article/details/gtsqcimbrm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.316326.xyz/Article/details/gtupmxjlgl.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtazdhkpvz.html

TS:   "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtagyruzpo.html

Java: "ab".repeat(3)
来源：http://dali.pycfn.com/Article/details/gtzrdtgcys.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj202588.top/Article/details/gtzwdidflq.html

Ruby: "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gtfwiobipy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.svipenyu.cn/Article/details/gtarliusxc.html

[E03] 截取子串
来源：http://dali.mhx1999.top/Article/details/gttpshbphf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hywenlv.cn/Article/details/gtbznihtmd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtyfuebwzd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtsptepkzc.html

TS:   s.slice(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtbmxpsaum.html

Java: s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtbbhikyjh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.dianchejie.cn/Article/details/gtlhrnuwai.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.daria6918.cn/Article/details/gtwhciyema.html

C#:   s.Substring(1, 3)
来源：http://dali.yueranfly.top/Article/details/gtvxvwwgek.html

[E04] 查找子串位置
来源：http://dali.haohaochexian.top/Article/details/gtlhfxyzvk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gtljtxbgvu.html

PHP:  strpos($s, "x");
来源：http://dali.quarkkingdee.top/Article/details/gtwsnsleil.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pengpengdd.cyou/Article/details/gtwkfniprb.html

TS:   s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gtczhmvbve.html

Java: s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtqjghbwiy.html

Go:   strings.Index(s, "x")
来源：http://dali.xinyue.icu/Article/details/gtxomewivf.html

Ruby: s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gtkmowftit.html

C#:   s.IndexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gtyrlmfvnr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.fengsongda.top/Article/details/gtelnqlhxy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpbrhdtv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cashguo.top/Article/details/gtvnqhdxuj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtnzqynuyc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.quarkkingdee.top/Article/details/gtfjlphofd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gtquflvujv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgufenzy.top/Article/details/gtiuilwyxu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gtflswrmhv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gzhubu.top/Article/details/gtolddvabr.html

[E06] 替换子串
来源：http://dali.hammf.cn/Article/details/gtvzhuafqw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xylfe.cn/Article/details/gtxmxpwkbd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cdnleiting.top/Article/details/gtfkqffwvz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtupqjhfeh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gtuwumckry.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtoqnrbubk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gtqaiphmfl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtbnvkhmae.html

C#:   s.Replace("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtfzudftnw.html

[E07] 按分隔符拆分
来源：http://dali.fengsongda.top/Article/details/gtgwodvjwr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.meibo888.top/Article/details/gtbykprwca.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtjuighclg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.316326.xyz/Article/details/gtmcwadyqw.html

TS:   s.split(",")
来源：http://dali.aizwys.cn/Article/details/gtokcexsdn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hfpthk.cn/Article/details/gtmgdhzkwu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthhkmwpl.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkigkgzr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.snrcjt.cn/Article/details/gtjbujmoky.html

[E08] 数组按分隔符合并
来源：http://dali.zhongyouzk.top/Article/details/gthdzuzdzv.html

Py:   ",".join(items)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaoszqoge.html

PHP:  implode(",", $items);
来源：http://dali.jqgufenzy.top/Article/details/gtdbxmcnro.html

JS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtgifjemgq.html

TS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gtkzblozvk.html

Java: String.join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gthmiiqzno.html

Go:   strings.Join(items, ",")
来源：http://dali.ehwqpu.com/Article/details/gtpolwlfug.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gthnfgidap.html

C#:   string.Join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gtezmfrlhe.html

[E09] 去除所有空白字符
来源：http://dali.dianchejie.cn/Article/details/gtpfloljre.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258.top/Article/details/gtdenwtapx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtrvshchgo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gtsrpjedai.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gtqpgjsywl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gtjlzxkwyd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhoulong.xyz/Article/details/gtdnglbyjq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtpchcampm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gtvldfqktm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nwbrower.top/Article/details/gtnmonijie.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtrudydqzs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sufxvd.cn/Article/details/gtnrvrdfbi.html

JS:   "7".padStart(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtgdqmocgr.html

TS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gtczrlenjt.html

Java: String.format("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gtdhchmxka.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gtamnpfsgf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtgfvtrdvo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgufenzy.top/Article/details/gtknrbqrjc.html

[E11] 反转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtvbdheswg.html

Py:   s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gtupjygawa.html

PHP:  strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrcnzwhb.html

JS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtzoqvaaaw.html

TS:   [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gterlmqhgx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhongyouzk.top/Article/details/gtvzgfrxqg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtqxtpyxdc.html

Ruby: s.reverse
来源：http://dali.haohaochexian.top/Article/details/gtmkikxxpw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gtlgaklemc.html

[E12] 统计某字符出现次数
来源：http://dali.chenzaomai.com/Article/details/gtgarqktkd.html

Py:   s.count("a")
来源：http://dali.pycfn.com/Article/details/gtafysgsug.html

PHP:  substr_count($s, "a");
来源：http://dali.ydzc1.top/Article/details/gtftkhkxrc.html

JS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gtvdfzdzbg.html

TS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtchpouion.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangshuangyany.cn/Article/details/gtfswspsyb.html

Go:   strings.Count(s, "a")
来源：http://dali.cashguo.top/Article/details/gtjwwhszdo.html

Ruby: s.count("a")
来源：http://dali.havefunace.top/Article/details/gtjzzgnlke.html

C#:   s.Count(c => c == 'a')
来源：http://dali.feifeiyinyue.top/Article/details/gtvumiursd.html

[E13] 逐字符遍历
来源：http://dali.ybcxt.top/Article/details/gtsfzfbhpw.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigufen.top/Article/details/gtawwpjveq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sysykeji.top/Article/details/gtjzscuitq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gttcreariw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgsyhcse.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xylfe.cn/Article/details/gtawwjibur.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.meibo888.top/Article/details/gtwqhsfgiz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gtyxdondpn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xziqi.cn/Article/details/gtgijiujjq.html

[E14] URL 编码与 Base64
来源：http://dali.pengpengdd.cyou/Article/details/gtrkfwycod.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.birdmap.top/Article/details/gtixfjqhpp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzoruiye.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hammf.cn/Article/details/gtquulgpqe.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.svipenyu.cn/Article/details/gtvdpqwcnb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yonumen.top/Article/details/gtdefdybfz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shzxlz.cn/Article/details/gtgwmhbcts.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpzhsarw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.birdmap.top/Article/details/gtgxteycnb.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gthhkegpuu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yongpay.top/Article/details/gtipugikeg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnqzz.top/Article/details/gtttrcpbim.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aizwys.cn/Article/details/gtqdmpxybl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.andypj.xyz/Article/details/gtmieumarg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnxiangtu.top/Article/details/gtqamaxswm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtquyrfroi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gtpcxofqtd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shuidangran.top/Article/details/gtqbbxfitg.html

[E16] 数字千分位
来源：http://dali.yj202588.top/Article/details/gtsjotnxao.html

Py:   f"{1234567:,}"
来源：http://dali.hfpthk.cn/Article/details/gtnbwjkdyn.html

PHP:  number_format(1234567);
来源：http://dali.birdmap.top/Article/details/gtzworxnol.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gtgikkiutm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gtxhgemsee.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shzxlz.cn/Article/details/gtjcsazoiv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zdqjudy.top/Article/details/gtqiabkxoh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.meibo888.top/Article/details/gtentwhtxe.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gtxfklsaue.html

[E17] 首字母大写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdykhrtxu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnsgrnziw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gtrkllrbzp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gtvgttjrnp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gtyvmceinq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ppjwa.cn/Article/details/gtmgwaetyc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.birdmap.top/Article/details/gtkwgtwwey.html

Ruby: s.capitalize
来源：http://dali.jinqigufen.top/Article/details/gtbdxuisgp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sufxvd.cn/Article/details/gtiwayvzau.html

[E18] 模板占位符替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzibafwr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhongyouzk.top/Article/details/gtjxmbwbvn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.havefunace.top/Article/details/gtyauxuagz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtnksateda.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.meibo888.top/Article/details/gtgyhxqgyb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gticqqgjsd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtoxoihxvl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yvedp.cn/Article/details/gtkreyhtoa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tanke756.top/Article/details/gtljegupsd.html

[E19] 多行文本按行拆分
来源：http://dali.yonumen.top/Article/details/gtffathvyi.html

Py:   s.splitlines()
来源：http://dali.yangfankeji.com/Article/details/gtzgbmrvxd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtgsbansvu.html

JS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gtgrlobgdd.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gtfhgepayw.html

Java: s.lines().toList()
来源：http://dali.jinqigufen.top/Article/details/gtjulwwolg.html

Go:   strings.Split(s, "\n")
来源：http://dali.havefunace.top/Article/details/gtjsxgpbwf.html

Ruby: s.lines
来源：http://dali.pycfn.com/Article/details/gtlxmtvhoo.html

C#:   s.Split('\n')
来源：http://dali.jinqigfzy.top/Article/details/gtcgidcblz.html

[E20] 判断字符串是否为空
来源：http://dali.yuxming.cn/Article/details/gtlydergnz.html

Py:   if not s:
来源：http://dali.ehwqpu.com/Article/details/gtfakccnos.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guannengcc.top/Article/details/gtiikrofcg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhongyouzk.top/Article/details/gtjynchuki.html

TS:   if (s === "") {}
来源：http://dali.jinqigfzy.top/Article/details/gtzhoevaqq.html

Java: if (s.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gtlzoywkrj.html

Go:   if s == "" {}
来源：http://dali.fengsongda.top/Article/details/gtsxzxwqsv.html

Ruby: if s.empty?
来源：http://dali.pycfn.com/Article/details/gtbmbnatbj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dianchejie.cn/Article/details/gtmrntmfdt.html

[E21] 超长截断加省略号
来源：http://dali.mhx1999.top/Article/details/gtltlykmch.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shangyingyoupin.top/Article/details/gtbescfrln.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtnodflyfi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtxqdttzmh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdorucdmu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtsjmpjxaz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hammf.cn/Article/details/gteawllbxt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtnmcsooog.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtiaplpole.html

[E22] 字节长度与字符长度
来源：http://dali.haohaochexian.top/Article/details/gtycstwpgs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hammf.cn/Article/details/gtfhadhdno.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzaazlvpk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gtoplawqey.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gtdhkwkram.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhixingplan.top/Article/details/gtkxmuewlj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sweek.top/Article/details/gtbtrihrsb.html

Ruby: s.bytesize;  s.length
来源：http://dali.meibo888.top/Article/details/gtkmijejem.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtmptrenym.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtlgqyupjb.html

F. 文件与目录
来源：http://dali.yongpay.top/Article/details/gtcsdtlehg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtyphftfef.html

[F01] 读取整个文件
来源：http://dali.zhiwuduotai.top/Article/details/gtssfidyny.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.vqdsnc.cn/Article/details/gtstrzdpyy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmpaeuwx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinghuilouyu.cn/Article/details/gtjarnkujx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtmeainxgt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtkyvencji.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cdnleiting.top/Article/details/gteoeneaxq.html

Ruby: File.read("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtocrayhdq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtjxtvtszt.html

[F02] 逐行读取文件
来源：http://dali.gzhubu.top/Article/details/gthnrbulwp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcesbtor.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zycfv.cn/Article/details/gtaxnyqanh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gtfvboawaq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gtporpzwvr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gtcaawxddp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.bjfxy.top/Article/details/gttzzzczhj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenjidiqi.icu/Article/details/gtvwbywhos.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aibaodan.cn/Article/details/gtcabkquuu.html

[F03] 写入文件（覆盖）
来源：http://dali.chenzaomai.com/Article/details/gtqycwackb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj202588.top/Article/details/gtrzrowpoy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gtezpfjial.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gtwvxzsiks.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gtalvzjetv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jianghu66.top/Article/details/gtgmxnepff.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuxming.cn/Article/details/gtkokfxcbp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aizwys.cn/Article/details/gtbagbhhus.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtxxutaykh.html

[F04] 追加写入文件
来源：http://dali.zhixingplan.top/Article/details/gtxpenjzrf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtburjhhio.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yvedp.cn/Article/details/gtfuplllve.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gthszwyfzi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgcyrapz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hywenlv.cn/Article/details/gteqhxkmyw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.9152youxi.cn/Article/details/gtznfczptx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.vqdsnc.cn/Article/details/gtzfcbraft.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cucudq.cn/Article/details/gthamfksqi.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gtjehdqqxb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yanxiufei.cn/Article/details/gtascsrezs.html

PHP:  file_exists("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtnapahhob.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjyboyhl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtvnojdfve.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtvxkjgpuu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nwbrower.top/Article/details/gtvfshgeaa.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtzfzmqnhv.html

C#:   File.Exists("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtpleqckjq.html

[F06] 删除文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufhhkzne.html

Py:   os.remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtvsxuchup.html

PHP:  unlink("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtfeihcuox.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gthchdoema.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzabxtxmi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtnqkgvupf.html

Go:   os.Remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtywckwhjv.html

Ruby: File.delete("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtmujwfdcq.html

C#:   File.Delete("a.txt");
来源：http://dali.tanke756.top/Article/details/gtvmqmfoxz.html

[F07] 创建目录（含多级）
来源：http://dali.pengpengdd.cyou/Article/details/gtydrblccv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gtfqgcfpis.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aizwys.cn/Article/details/gtvsibfulv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gtvilfqdfd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gtbxkzrerv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.316326.xyz/Article/details/gtmkmgoecp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.birdmap.top/Article/details/gtgrzdixqn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhzmkapn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cdnleiting.top/Article/details/gtleyrljni.html

[F08] 遍历目录
来源：http://dali.c1oappe.top/Article/details/gtjkmwfmiv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sweek.top/Article/details/gtrzoznpcw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ppjwa.cn/Article/details/gthauzyxfg.html

JS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gtvehhfviq.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gtbofmoxsb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shuidangran.top/Article/details/gtisdceyho.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenzaomai.com/Article/details/gterhnprcx.html

Ruby: Dir.children("dir")
来源：http://dali.meibo888.top/Article/details/gtcntnneya.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbtxckuc.html

[F09] 获取文件大小
来源：http://dali.aibaodan.cn/Article/details/gtufhwsgsf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtqwenwigm.html

PHP:  filesize("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtmwtbcqzs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gtdexqaqxi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfwqzavd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtdoftmbnp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pycfn.com/Article/details/gtjmhdchla.html

Ruby: File.size("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtimcgwsfd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cashguo.top/Article/details/gtrulxrwss.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuanzx.com/Article/details/gtpbrzaurh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtupoamemk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.redwolf501.top/Article/details/gtimqvvneu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrkfpdpi.html

TS:   path.extname("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqrtvxyq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnydcqqm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtaqoqjdzm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gthjrvyzre.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtyyyynkby.html

[F11] 复制与移动文件
来源：http://dali.ehwqpu.com/Article/details/gtrwtbdeto.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtgbialrza.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jianghu66.top/Article/details/gtrvgsjupw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtuoakuskm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtjkjnkquk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cheryme.top/Article/details/gtzmbhdboz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sweek.top/Article/details/gtcuouhckn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtejsggrtm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gotoacloud.top/Article/details/gtrafizxsw.html

[F12] CSV 读写
来源：http://dali.c1oappe.top/Article/details/gtbtthsdtx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.haohaochexian.top/Article/details/gtnsbfxymd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ppjwa.cn/Article/details/gtxzefnwuy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gtxchbfxun.html

TS:   // 同上
来源：http://dali.chenzaomai.com/Article/details/gtsdvecpta.html


<!-- 参考信息 -->