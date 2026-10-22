代发 wailian999

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tanke756.top/Article/details/gtlkmuomge.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigufen.top/Article/details/gtlzukzeyl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yangfankeji.com/Article/details/gtbxrlbqtj.html

[D26] 数组转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtzgxlzmpy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zdqjudy.top/Article/details/gttkfcibvs.html

PHP:  implode(", ", $arr);
来源：http://dali.dianchejie.cn/Article/details/gtlqslcdlh.html

JS:   arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gtggpdrbjw.html

TS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gthoeyqivs.html

Java: String.join(", ", list)
来源：http://dali.tian-w.cn/Article/details/gtyucnihqt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhongyouzk.top/Article/details/gtkqsedlye.html

Ruby: arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtvtgybnjn.html

C#:   string.Join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gttmnqwhcu.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gteanvxbju.html

E. 字符串处理
来源：http://dali.yuxming.cn/Article/details/gtbinqkcim.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtpbgfsvjp.html

[E01] 拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gtftpbpsfr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.andypj.xyz/Article/details/gtfpzchlqq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zdqjudy.top/Article/details/gtqsvymxgl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gtqdviyfte.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtuuigjvrz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgufenzy.top/Article/details/gtthivozls.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgfzy.top/Article/details/gtibvmpycg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigfzy.top/Article/details/gtpphazjko.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gttuieefgw.html

[E02] 重复字符串
来源：http://dali.chenzaomai.com/Article/details/gtritndguh.html

Py:   "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gtnbqeocts.html

PHP:  str_repeat("ab", 3);
来源：http://dali.kuanghao11.cn/Article/details/gtyyjqgkzx.html

JS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtegwcolme.html

TS:   "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzanqlube.html

Java: "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtrsiswgoe.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yueranfly.top/Article/details/gtlhztitds.html

Ruby: "ab" * 3
来源：http://dali.meibo888.top/Article/details/gtpzjkhngz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ppjwa.cn/Article/details/gtahsjpvjs.html

[E03] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gtmryvxucm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tian-w.cn/Article/details/gtujkvxrod.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtbpeojlyj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gtmnpvcigd.html

TS:   s.slice(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtwyynynyw.html

Java: s.substring(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtayothtjg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gtebjrhrgw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.birdmap.top/Article/details/gtkwzahevo.html

C#:   s.Substring(1, 3)
来源：http://dali.zhixingplan.top/Article/details/gtluieabxg.html

[E04] 查找子串位置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhvohtjt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.daria6918.cn/Article/details/gtafojgbsv.html

PHP:  strpos($s, "x");
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwogvvti.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xylfe.cn/Article/details/gtprtbwdvp.html

TS:   s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtzgxabk.html

Java: s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtknwnqacz.html

Go:   strings.Index(s, "x")
来源：http://dali.xuetiantiany.cn/Article/details/gttrwxspum.html

Ruby: s.index("x")
来源：http://dali.mhx1999.top/Article/details/gtoarozktq.html

C#:   s.IndexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtrgnfdfks.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daria6918.cn/Article/details/gtxpclllnh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmsvtlav.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.andypj.xyz/Article/details/gtycfkjpnl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gthabcczcf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xziqi.cn/Article/details/gthpgzufac.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gtizpmkity.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gaohongyu789.top/Article/details/gtalipinat.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhixingplan.top/Article/details/gthyryllvt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gtowlrrdgl.html

[E06] 替换子串
来源：http://dali.cdnleiting.top/Article/details/gtiqjelskl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gtftshjqyq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.quarkkingdee.top/Article/details/gtulemmfxj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtgilxsizn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtqjeihtqf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpicgjbfh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gtbggmphqr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.meibo888.top/Article/details/gtxkahqomi.html

C#:   s.Replace("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtbncrzqaa.html

[E07] 按分隔符拆分
来源：http://dali.chenlongwang.top/Article/details/gttvklxgyg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpiorjti.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtrrtinmzc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fzhhl.top/Article/details/gtmcuovomn.html

TS:   s.split(",")
来源：http://dali.quarkkingdee.top/Article/details/gtzqplxbqg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfjammiz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daria6918.cn/Article/details/gtkbnxhpwl.html

Ruby: s.split(",");  s.split
来源：http://dali.tianlin.xyz/Article/details/gtdqvbekvh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258888.top/Article/details/gtttkbgnya.html

[E08] 数组按分隔符合并
来源：http://dali.zhengqikj.top/Article/details/gtxipfmxpk.html

Py:   ",".join(items)
来源：http://dali.yuxming.cn/Article/details/gtswjyvbrh.html

PHP:  implode(",", $items);
来源：http://dali.zdqjudy.top/Article/details/gtwjskxiou.html

JS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gtzewtkeqs.html

TS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtbozrvqaq.html

Java: String.join(",", items)
来源：http://dali.hnxiangtu.top/Article/details/gtwmwnvdcx.html

Go:   strings.Join(items, ",")
来源：http://dali.chenlongwang.top/Article/details/gtawjwgwmn.html

Ruby: items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gttntlkxqd.html

C#:   string.Join(",", items)
来源：http://dali.ybcxt.top/Article/details/gtpdmbqmmw.html

[E09] 去除所有空白字符
来源：http://dali.yj202588.top/Article/details/gtuuagyrvc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shuidangran.top/Article/details/gtogohsbhc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hfpthk.cn/Article/details/gtqxwlaido.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtwqwvfhmd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gtjkspbipp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gtntwibxoh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xylfe.cn/Article/details/gtbjoechbq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.snrcjt.cn/Article/details/gtucgalksk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.birdmap.top/Article/details/gtxmvzogsf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.redwolf501.top/Article/details/gtplknlfpn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258.top/Article/details/gtcwwwuuhg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jianghu66.top/Article/details/gtooikunox.html

JS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtblvihjus.html

TS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtrmoztkxm.html

Java: String.format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtqwmukyzy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtqcqkmcsx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtxqszveoq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.wangshuangyany.cn/Article/details/gtmmlircgq.html

[E11] 反转字符串
来源：http://dali.chenzaomai.com/Article/details/gtupogsdhb.html

Py:   s[::-1]
来源：http://dali.pycfn.com/Article/details/gtwshdjdzq.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtxzvwrqkx.html

JS:   [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtfakejfng.html

TS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtuerycgxf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.c1oappe.top/Article/details/gtvfnxysdg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yongpay.top/Article/details/gtezdkauko.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gtmvvxofxl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gtjnceehts.html

[E12] 统计某字符出现次数
来源：http://dali.smart0.xyz/Article/details/gtlcxwkmft.html

Py:   s.count("a")
来源：http://dali.ybcxt.top/Article/details/gtcrrjxffu.html

PHP:  substr_count($s, "a");
来源：http://dali.feifeiyinyue.top/Article/details/gtefijgdlv.html

JS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtajjpcmca.html

TS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gtkaqkokkj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ydzc1.top/Article/details/gtladvhnqa.html

Go:   strings.Count(s, "a")
来源：http://dali.ehwqpu.com/Article/details/gtodwwcbxk.html

Ruby: s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gthwpscynf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yueranfly.top/Article/details/gtnorvekjb.html

[E13] 逐字符遍历
来源：http://dali.9152youxi.cn/Article/details/gtdkvmmatx.html

Py:   for ch in s: print(ch)
来源：http://dali.dashuyun.cn/Article/details/gtyglabixf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hywenlv.cn/Article/details/gtvtcfrxrb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gturkkfxry.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtkzqcpeyf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daxiang520.top/Article/details/gtxvmqkaru.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ivvv.top/Article/details/gtrsyouzbv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xinyue.icu/Article/details/gtcnatkecr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xylfe.cn/Article/details/gtlxnwrrks.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258888.top/Article/details/gtbbwjtuce.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gtjcbuicta.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258888.top/Article/details/gtgwrbiiql.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ivvv.top/Article/details/gtjfnibmit.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtdkzugdxb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.bjfxy.top/Article/details/gtvaotukpf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.9152youxi.cn/Article/details/gtvqwqtcur.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cqqwz.cn/Article/details/gtwqhdztwg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daria6918.cn/Article/details/gtsisosntj.html

[E15] HTML 转义 / 反转义
来源：http://dali.haohaochexian.top/Article/details/gtlblmhxex.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gzhubu.top/Article/details/gtxyfuvknl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.kuanghao11.cn/Article/details/gtuhvreoxc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zdqjudy.top/Article/details/gtjukpxmle.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gogol.net.cn/Article/details/gtrsrlgzut.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.fengsongda.top/Article/details/gtchjkklas.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jiagoushi.top/Article/details/gtjygtwdga.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aizwys.cn/Article/details/gtzlwxodqm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuanzhike.top/Article/details/gtvyrrhjup.html

[E16] 数字千分位
来源：http://dali.hysaishi.cn/Article/details/gtwosuvyzx.html

Py:   f"{1234567:,}"
来源：http://dali.zdqjudy.top/Article/details/gttfahnhuy.html

PHP:  number_format(1234567);
来源：http://dali.fzhhl.top/Article/details/gtpxpjzyni.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gtskcicxge.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gtgdrmekzc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hammf.cn/Article/details/gtvkvcwtpx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgufenzy.top/Article/details/gtbywcobze.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuanzx.com/Article/details/gtxvmfmsel.html

C#:   1234567.ToString("N0")
来源：http://dali.feifeiyinyue.top/Article/details/gtbvstzxfs.html

[E17] 首字母大写
来源：http://dali.jianghu66.top/Article/details/gthcwmsfjk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xinyue.icu/Article/details/gtayaijwin.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigufen.top/Article/details/gtctrjhpqu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gtephivmdn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gtckmxvtjb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gzhubu.top/Article/details/gtecsgoimf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.svipenyu.cn/Article/details/gtslnyzpfu.html

Ruby: s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gthsfteios.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tianlin.xyz/Article/details/gtiknikrll.html

[E18] 模板占位符替换
来源：http://dali.tian-w.cn/Article/details/gtjpicrdfr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jlsjyb.cn/Article/details/gtczwcmnes.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.iojbl.cn/Article/details/gtgxdtheau.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtqrclqxps.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gthgbmjmmz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtflvujwzm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtfjoxoxgu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jyoumei.cn/Article/details/gtclhxsuam.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tianlin.xyz/Article/details/gtixokhozc.html

[E19] 多行文本按行拆分
来源：http://dali.yonumen.top/Article/details/gthwohogvt.html

Py:   s.splitlines()
来源：http://dali.tian-w.cn/Article/details/gtarrneyjy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtmdzmycoq.html

JS:   s.split(/\r?\n/)
来源：http://dali.sufxvd.cn/Article/details/gtltgaprtx.html

TS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gtrxxhualz.html

Java: s.lines().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtdutjjhwl.html

Go:   strings.Split(s, "\n")
来源：http://dali.sxryk.cn/Article/details/gtoutsokfr.html

Ruby: s.lines
来源：http://dali.gaohongyu789.top/Article/details/gtrvavvjtx.html

C#:   s.Split('\n')
来源：http://dali.yanxiufei.cn/Article/details/gthvhkpeko.html

[E20] 判断字符串是否为空
来源：http://dali.tian-w.cn/Article/details/gtbtmnhtac.html

Py:   if not s:
来源：http://dali.jyoumei.cn/Article/details/gtupjovcgt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhmufgla.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.meibo888.top/Article/details/gtzodqgywd.html

TS:   if (s === "") {}
来源：http://dali.svipenyu.cn/Article/details/gttcdteiik.html

Java: if (s.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gtsgeumnpp.html

Go:   if s == "" {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkmmwxof.html

Ruby: if s.empty?
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjauxediq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dashuyun.cn/Article/details/gtnhvsfruo.html

[E21] 超长截断加省略号
来源：http://dali.cdnleiting.top/Article/details/gtujwabqnb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gzhubu.top/Article/details/gtbwlqklyb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtaiyxfqhc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtxhynstpu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtwgjdbtgf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtegdipmhf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrdopuyl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtuxmvpokz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtzmknzwju.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gtgnnrgoiv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aibaodan.cn/Article/details/gtrwrcpuaa.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtqofavdnx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gtxlyjfwps.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gtzoljvthe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ybcxt.top/Article/details/gtktscflnl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhiwuduotai.top/Article/details/gtoqtrfgxo.html

Ruby: s.bytesize;  s.length
来源：http://dali.c1oappe.top/Article/details/gtwvfrrlxy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnxiangtu.top/Article/details/gtcldhnxwj.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtlrowlsmt.html

F. 文件与目录
来源：http://dali.nanxinkj.top/Article/details/gtdzegztsa.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtrzylxrse.html

[F01] 读取整个文件
来源：http://dali.nanxinkj.top/Article/details/gtbyghmsjd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.guannengcc.top/Article/details/gthjmqgspq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtdwngvewe.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.quarkkingdee.top/Article/details/gtasuqysis.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daxiang520.top/Article/details/gtrxrspetn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtkcgmwver.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjflxzmse.html

Ruby: File.read("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtwauldqrq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtfjtlmyva.html

[F02] 逐行读取文件
来源：http://dali.wangshuangyany.cn/Article/details/gtqsylykpn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhoulong.xyz/Article/details/gtkfzvbkae.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwvkuqrzy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtfgvkbmez.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gtohraewdy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gtjtufatkj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ydzc1.top/Article/details/gtlqitebga.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cucudq.cn/Article/details/gtawaflxzp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.mhx1999.top/Article/details/gtxhltgqii.html

[F03] 写入文件（覆盖）
来源：http://dali.ehwqpu.com/Article/details/gthrisorfw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jyoumei.cn/Article/details/gtwnwiamvh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gtzacrgcpt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtjmznxzea.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtwgfxtyxq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjusceofn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenlongwang.top/Article/details/gtfdangetm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ivvv.top/Article/details/gtmwgncudz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtmwsyehuj.html

[F04] 追加写入文件
来源：http://dali.xziqi.cn/Article/details/gtqwpxtjtp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtixyfnari.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.0kj1m.cn/Article/details/gthsbnbowg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtbemjubwr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtigkzzbsj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhoulong.xyz/Article/details/gtiemsabwl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtgcxvxvnf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hfpthk.cn/Article/details/gtbdomodkj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yangfankeji.com/Article/details/gtgfbvwhwp.html

[F05] 判断文件或目录是否存在
来源：http://dali.andypj.xyz/Article/details/gttjyumnqe.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinghuilouyu.cn/Article/details/gtypuycncw.html

PHP:  file_exists("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtqccsrflv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggupuvgl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtbkyevvmt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gthuxfaxsi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnxiangtu.top/Article/details/gtxmqdhwij.html

Ruby: File.exist?("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gteiqxxbrv.html

C#:   File.Exists("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtkzcuopvu.html

[F06] 删除文件
来源：http://dali.sysykeji.top/Article/details/gtqfvmgnqm.html

Py:   os.remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtnljrajny.html

PHP:  unlink("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtufhgixjg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtafgscuxz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtndxxrlrc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtmlzudpjr.html

Go:   os.Remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtpecqxutu.html

Ruby: File.delete("a.txt")
来源：http://dali.havefunace.top/Article/details/gtghdgcbbg.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtrguoimnf.html

[F07] 创建目录（含多级）
来源：http://dali.smart0.xyz/Article/details/gtqmafltnn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gtnyinulps.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenlongwang.top/Article/details/gtrpzrpauv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gtdsgviooz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gtcaougffw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258888.top/Article/details/gtxvhkkopo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.mhx1999.top/Article/details/gtsleyysyd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.snrcjt.cn/Article/details/gtbckgkysm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.feifeiyinyue.top/Article/details/gtjfcvudme.html

[F08] 遍历目录
来源：http://dali.nwbrower.top/Article/details/gtkxqkqngp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pycfn.com/Article/details/gtdghborhz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoermswsg.html

JS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtxuabggmp.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtdstdfgzt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gtlxkzekhn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwfcdiwd.html

Ruby: Dir.children("dir")
来源：http://dali.yuxming.cn/Article/details/gtoyfmblty.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sweek.top/Article/details/gtxldrtypz.html

[F09] 获取文件大小
来源：http://dali.fzhhl.top/Article/details/gtqvcpnvtu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtvkcyxtnh.html

PHP:  filesize("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtgzeyppce.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gtfxkokols.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gtobmbzikv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtuwmtgxnf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxuanxn.top/Article/details/gtdzetvetz.html

Ruby: File.size("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gterzqjuxw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yongpay.top/Article/details/gtlvpdtsfl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnxiangtu.top/Article/details/gtpdgkfbam.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtnrgbgdtv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtlvfclerf.html


<!-- 参考信息 -->