代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.meibo888.top/Article/details/gtktevsmgl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxuanxn.top/Article/details/gtrnkpgghe.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nanxuanxn.top/Article/details/gtxwituypb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtsomwzvtz.html

[E02] 重复字符串
来源：http://dali.kuanghao11.cn/Article/details/gtswqbefba.html

Py:   "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gtgryewvvq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsuxvuej.html

JS:   "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gtxjzhfwgc.html

TS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtlwaytuas.html

Java: "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtmsanwpks.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtetzynuwd.html

Ruby: "ab" * 3
来源：http://dali.sweek.top/Article/details/gtqqtxuyez.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttecfxoxq.html

[E03] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gtzhwytumj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tianlin.xyz/Article/details/gtvdossvff.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtearauikk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtoghvthic.html

TS:   s.slice(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtjcvtcafg.html

Java: s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gtlgdjxtjq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjchtngpx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.guowangkeji.top/Article/details/gtctcofysi.html

C#:   s.Substring(1, 3)
来源：http://dali.daria6918.cn/Article/details/gtxopqsmio.html

[E04] 查找子串位置
来源：http://dali.jqgfzy.top/Article/details/gtlvndbnqi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ybcxt.top/Article/details/gtdfptfcgf.html

PHP:  strpos($s, "x");
来源：http://dali.hywenlv.cn/Article/details/gtmcshwfpt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxinkj.top/Article/details/gtecpfhohd.html

TS:   s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtthboirjt.html

Java: s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtgyfvqnnt.html

Go:   strings.Index(s, "x")
来源：http://dali.vqdsnc.cn/Article/details/gtdgpoplfb.html

Ruby: s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtjkhoii.html

C#:   s.IndexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtidptypyy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.9152youxi.cn/Article/details/gtrexwviym.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhixingplan.top/Article/details/gtyiumfecg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fzhhl.top/Article/details/gtazhyglbj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtehhuiacg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.vqdsnc.cn/Article/details/gtfhlrigfx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gtvuuhtkwy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.aizwys.cn/Article/details/gthjsrtuwh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.dashuyun.cn/Article/details/gtepmgccld.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtyctzqezy.html

[E06] 替换子串
来源：http://dali.jyoumei.cn/Article/details/gtmtvtofmm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gtszypbvmu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ydzc1.top/Article/details/gtwestjfra.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtjzzfvfuq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtuteefhfi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtvqbnodgn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxuanxn.top/Article/details/gtbduiqlpl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtedadbwjd.html

C#:   s.Replace("a", "b")
来源：http://dali.ivvv.top/Article/details/gtleailypn.html

[E07] 按分隔符拆分
来源：http://dali.xziqi.cn/Article/details/gtboihlubz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangtech.top/Article/details/gtddudzutp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.pycfn.com/Article/details/gtrmokzaiv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sweek.top/Article/details/gtsjzxflxc.html

TS:   s.split(",")
来源：http://dali.nanxinkj.top/Article/details/gtrjwfafld.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ivvv.top/Article/details/gtxzroqwcs.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangdashe.top/Article/details/gtycfwmpxh.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgufenzy.top/Article/details/gthhwnftlf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavptiqnu.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigufen.top/Article/details/gttdhgzhen.html

Py:   ",".join(items)
来源：http://dali.sufxvd.cn/Article/details/gtjnfpuria.html

PHP:  implode(",", $items);
来源：http://dali.chenjidiqi.icu/Article/details/gtzvaunjom.html

JS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtvauofaje.html

TS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtnkjbghxi.html

Java: String.join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gtsctwaigy.html

Go:   strings.Join(items, ",")
来源：http://dali.hnqzz.top/Article/details/gttthbiarq.html

Ruby: items.join(",")
来源：http://dali.ydzc1.top/Article/details/gtzggzewnu.html

C#:   string.Join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gtbhcawnth.html

[E09] 去除所有空白字符
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzeyaoycv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jlsjyb.cn/Article/details/gtfhvqfodg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tanke756.top/Article/details/gtpfoyeepp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gtqostlkrc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gtmflkuqtf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258888.top/Article/details/gtajqttckc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shuidangran.top/Article/details/gttjtgdjhx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hammf.cn/Article/details/gtclmcdvhd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.andypj.xyz/Article/details/gtyrahnvax.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenjidiqi.icu/Article/details/gtpzqxmpnl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtecvokxmu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtziavwqag.html

JS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtubjadzkd.html

TS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtbjurfwax.html

Java: String.format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gttrmjmryw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtdogpbyrm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtodfvxqhq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuanzhike.top/Article/details/gtsyquxonp.html

[E11] 反转字符串
来源：http://dali.snrcjt.cn/Article/details/gtkbxroqwc.html

Py:   s[::-1]
来源：http://dali.yuxming.cn/Article/details/gteyjtnspk.html

PHP:  strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtsuahggme.html

JS:   [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtygjhandz.html

TS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtnjdmmgib.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.birdmap.top/Article/details/gtcftiomgy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tianlin.xyz/Article/details/gtszwhxbld.html

Ruby: s.reverse
来源：http://dali.yueranfly.top/Article/details/gttubkzvlg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gtytuksnth.html

[E12] 统计某字符出现次数
来源：http://dali.smart0.xyz/Article/details/gteoadddom.html

Py:   s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtgvhwgjav.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258888.top/Article/details/gtnpvmqadd.html

JS:   s.split("a").length - 1
来源：http://dali.fzhhl.top/Article/details/gtxyzbtlli.html

TS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gtjsamilcw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangshuangyany.cn/Article/details/gtszzzgdxv.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gtoyyyjdjv.html

Ruby: s.count("a")
来源：http://dali.yongpay.top/Article/details/gtbjgkhnqo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.0kj1m.cn/Article/details/gthtfixxsx.html

[E13] 逐字符遍历
来源：http://dali.ehwqpu.com/Article/details/gtualqtytr.html

Py:   for ch in s: print(ch)
来源：http://dali.zhoulong.xyz/Article/details/gtowchmwfx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.0kj1m.cn/Article/details/gtfinjhpyw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxglvovgc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtumvwtxje.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xinyue.icu/Article/details/gtcbxcdhnk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.snrcjt.cn/Article/details/gttghxlnud.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.kuanghao11.cn/Article/details/gttsayzsau.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuxming.cn/Article/details/gtcgzktbnu.html

[E14] URL 编码与 Base64
来源：http://dali.yuanzhike.top/Article/details/gtygkzsiso.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgufenzy.top/Article/details/gtxvcopzvj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gzhubu.top/Article/details/gtmatrslee.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxinkj.top/Article/details/gtibmecblp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jyoumei.cn/Article/details/gtlcllccfk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fzhhl.top/Article/details/gtblmwybjp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gtunmonwuq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenlongwang.top/Article/details/gtyirzqxny.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gtasokshjr.html

[E15] HTML 转义 / 反转义
来源：http://dali.yvedp.cn/Article/details/gtsexwejea.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.snrcjt.cn/Article/details/gtlemjywnx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.c1oappe.top/Article/details/gtzmrjuemy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.c1oappe.top/Article/details/gtwdnztpef.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenlongwang.top/Article/details/gtaelrvqak.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.redwolf501.top/Article/details/gtnmequwnn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zdqjudy.top/Article/details/gtdnwxomsd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhoulong.xyz/Article/details/gtroralukf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gtkyauxbpk.html

[E16] 数字千分位
来源：http://dali.meibo888.top/Article/details/gteudirvix.html

Py:   f"{1234567:,}"
来源：http://dali.yueranfly.top/Article/details/gtyqqgsikl.html

PHP:  number_format(1234567);
来源：http://dali.zhengqikj.top/Article/details/gtkbqalwvi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gtilyysfmn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gtdfhywzyf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxinkj.top/Article/details/gtotcrqsif.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhixingplan.top/Article/details/gtwksdpgtb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.mhx1999.top/Article/details/gtynoqxqfz.html

C#:   1234567.ToString("N0")
来源：http://dali.zhixingplan.top/Article/details/gtjfjruoas.html

[E17] 首字母大写
来源：http://dali.cashguo.top/Article/details/gtojrlegwn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yonumen.top/Article/details/gthtogtkth.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ppjwa.cn/Article/details/gtxiyajmup.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gtnvkbvnde.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gtcpxwoszz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ybcxt.top/Article/details/gtddscpzrx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gtcqfirzqs.html

Ruby: s.capitalize
来源：http://dali.zhixingplan.top/Article/details/gtbpfbxokq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gotoacloud.top/Article/details/gthavsmuqc.html

[E18] 模板占位符替换
来源：http://dali.jinqigufen.top/Article/details/gtknasumka.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hywenlv.cn/Article/details/gtyxsivdrq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hongshengwenyu.top/Article/details/gtqbmuvygl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtfdquckpz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtlaroultm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtxgdgkpkh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwuiyrln.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pengpengdd.cyou/Article/details/gtrievjbvg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258.top/Article/details/gtsdnpuoey.html

[E19] 多行文本按行拆分
来源：http://dali.9152youxi.cn/Article/details/gtzjwujizl.html

Py:   s.splitlines()
来源：http://dali.jqgufenzy.top/Article/details/gtpwobbbjq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gteqouzers.html

JS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gtfeuefxti.html

TS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gtxurvwvpl.html

Java: s.lines().toList()
来源：http://dali.yangfankeji.com/Article/details/gtgvclyyne.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxinkj.top/Article/details/gtpfezlkfu.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gtfmfeardb.html

C#:   s.Split('\n')
来源：http://dali.zhongyouzk.top/Article/details/gtiohgoguj.html

[E20] 判断字符串是否为空
来源：http://dali.yuanzhike.top/Article/details/gtjhlipahp.html

Py:   if not s:
来源：http://dali.nanxinkj.top/Article/details/gtfzhaccnn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gthaywktru.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xinyue.icu/Article/details/gtokknnbso.html

TS:   if (s === "") {}
来源：http://dali.birdmap.top/Article/details/gtyeccvsgf.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzdzfuda.html

Go:   if s == "" {}
来源：http://dali.aibaodan.cn/Article/details/gtdckxurur.html

Ruby: if s.empty?
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcluhckx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.vqdsnc.cn/Article/details/gtyxucqcgh.html

[E21] 超长截断加省略号
来源：http://dali.xylfe.cn/Article/details/gtmqcydptl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gtzriubhth.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtghsqmlnu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gttdwhuoau.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtacgpbmpi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtoltzddfu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.9152youxi.cn/Article/details/gttctfciun.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgasfavlv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtoudgtmld.html

[E22] 字节长度与字符长度
来源：http://dali.316326.xyz/Article/details/gtnlrvdpwk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.9152youxi.cn/Article/details/gtbntlgpxd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtvqsqnlfs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gtaelwaxhx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtzvmdpeyh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tian-w.cn/Article/details/gtifeyzqcj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258888.top/Article/details/gtzdbxiwsj.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gtchqbkakp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gotoacloud.top/Article/details/gtcodtomfx.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtvvabynuk.html

F. 文件与目录
来源：http://dali.ybcxt.top/Article/details/gtyxwbjkcz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtuuhojlfh.html

[F01] 读取整个文件
来源：http://dali.quarkkingdee.top/Article/details/gtdzbobacj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.9152youxi.cn/Article/details/gtpkrnnyiu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohdomjjk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhengqikj.top/Article/details/gtfwphqvbx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtkecuizmb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtqksinlmj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhixingplan.top/Article/details/gtagmzrbqj.html

Ruby: File.read("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtyglrhrjz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtqbgvcgqd.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gtnwpzuaqn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dashuyun.cn/Article/details/gtqbtjfqcj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfvdpmmi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gtafavyrhu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gtmibofybr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gtxskwxwyq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangdashe.top/Article/details/gtawwvaxsh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqhsncuj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jlsjyb.cn/Article/details/gtxupzoehj.html

[F03] 写入文件（覆盖）
来源：http://dali.tanke756.top/Article/details/gtvnsbvsas.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.kuanghao11.cn/Article/details/gtysvmnxac.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gtmbciufev.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gttilnmode.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcokztclt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guannengcc.top/Article/details/gtxgazoxwx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtteflaxxv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ehwqpu.com/Article/details/gtyddzktrc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gtnvdcdjjf.html

[F04] 追加写入文件
来源：http://dali.cdnleiting.top/Article/details/gtorqmywhx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtjdvprcqn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yvedp.cn/Article/details/gtsyydzlvj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gtyautcout.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gtowxzevfd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhiwuduotai.top/Article/details/gtnnjlyaxh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtgtxstkdg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangshuangyany.cn/Article/details/gtjbyikuru.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenjidiqi.icu/Article/details/gtxetxxvgc.html

[F05] 判断文件或目录是否存在
来源：http://dali.fengsongda.top/Article/details/gtvyukwviu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.smart0.xyz/Article/details/gtswzmqlma.html

PHP:  file_exists("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdocwyljz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbjvbyfi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gthreslpzt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtddkrqwut.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jiagoushi.top/Article/details/gtgakkhcco.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gttjkmoskp.html

C#:   File.Exists("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmedscctq.html

[F06] 删除文件
来源：http://dali.yonumen.top/Article/details/gtdjmmqdcr.html

Py:   os.remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtkhexsjgk.html

PHP:  unlink("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtwchwxvau.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtipwadgpu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtxjysxivr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtiususisc.html

Go:   os.Remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtgxwdlnxo.html

Ruby: File.delete("a.txt")
来源：http://dali.birdmap.top/Article/details/gtsgnbgcue.html

C#:   File.Delete("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtfabgkpul.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gtosbrybaw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.meibo888.top/Article/details/gtpvlnrawq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhoulong.xyz/Article/details/gtfammcwgl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtxvxmndkx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gttjyvvjsp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sysykeji.top/Article/details/gtwsvnhtiv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cdnleiting.top/Article/details/gtgjpyqbvk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yangfankeji.com/Article/details/gtdhxgkqgh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hywenlv.cn/Article/details/gtuyoruujl.html

[F08] 遍历目录
来源：http://dali.chenlongwang.top/Article/details/gthkgupgrk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhiwuduotai.top/Article/details/gtkjltoczx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jlsjyb.cn/Article/details/gtanviclkz.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gtejfdmbdz.html

TS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gtzodhrrjg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gtdhlcfyoa.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ybcxt.top/Article/details/gtmubabtvm.html

Ruby: Dir.children("dir")
来源：http://dali.meibo888.top/Article/details/gtxyittzhl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.0kj1m.cn/Article/details/gtmuabgjok.html

[F09] 获取文件大小
来源：http://dali.hnxiangtu.top/Article/details/gttcwmkvrd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtghvdnvsm.html

PHP:  filesize("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtblgywxgo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gtndzqjcmw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtdpyduizg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtaqnfxvfm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnxiangtu.top/Article/details/gtsirhbuxc.html

Ruby: File.size("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtgvfhjdro.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cashguo.top/Article/details/gtedltspsu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvrafzln.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxxqurnq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtlzqlfxfw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtfphprffz.html

TS:   path.extname("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtmmxthqez.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tanke756.top/Article/details/gtjnudyswz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtispjrgir.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexfnncep.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtducmsdxk.html

[F11] 复制与移动文件
来源：http://dali.hfpthk.cn/Article/details/gtzztvdplv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtpexzkcwj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtaojoqrws.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtzimdlnvp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtditbwdsh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gtievertjy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cqqwz.cn/Article/details/gtjcyarkqf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtkohcoxsg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.kuanghao11.cn/Article/details/gtazafnxey.html

[F12] CSV 读写
来源：http://dali.hnxiangtu.top/Article/details/gtkvtyhssw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ehwqpu.com/Article/details/gthufrpgln.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.redwolf501.top/Article/details/gtxwwkgoxl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.meibo888.top/Article/details/gtgrorycbs.html

TS:   // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtumljhgrq.html


<!-- 参考信息 -->