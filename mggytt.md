代发 wailian999

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dashuyun.cn/Article/details/gtbbsxsrod.html

[E03] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gtdoetfgcs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jlsjyb.cn/Article/details/gtulpatyvh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtkmiyjmqs.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gthdlbeslx.html

TS:   s.slice(1, 4)
来源：http://dali.wangdashe.top/Article/details/gttsnaprqx.html

Java: s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gtbrptxqou.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhixingplan.top/Article/details/gtaaeyipyr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pengpengdd.cyou/Article/details/gtwwhomido.html

C#:   s.Substring(1, 3)
来源：http://dali.daria6918.cn/Article/details/gtdbcxsnuv.html

[E04] 查找子串位置
来源：http://dali.snrcjt.cn/Article/details/gttkjwvsje.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yvedp.cn/Article/details/gtvrkbmqjn.html

PHP:  strpos($s, "x");
来源：http://dali.gaohongyu789.top/Article/details/gtunervcfk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jianghu66.top/Article/details/gtureviakw.html

TS:   s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gtoabxwnqo.html

Java: s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtpnqkicyv.html

Go:   strings.Index(s, "x")
来源：http://dali.ybcxt.top/Article/details/gthukpwlnk.html

Ruby: s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gtrojagkbt.html

C#:   s.IndexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtdzgmpopu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tianlin.xyz/Article/details/gtcqulvxal.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ivvv.top/Article/details/gtelslldpu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tian-w.cn/Article/details/gtihgvmbfn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tanke756.top/Article/details/gtppcyobac.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zdqjudy.top/Article/details/gtvpatqgan.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gthrjbnvir.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hywenlv.cn/Article/details/gtqphjlzjn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258888.top/Article/details/gtxhhuiqvv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzliozse.html

[E06] 替换子串
来源：http://dali.havefunace.top/Article/details/gtbnpptlmn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtrrwmqttk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tianlin.xyz/Article/details/gtpnluciaw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtdejcdwxj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtanlfuqya.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtvhlqzqgu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gthrbmriar.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hammf.cn/Article/details/gtjpjupvur.html

C#:   s.Replace("a", "b")
来源：http://dali.yj20258.top/Article/details/gthkhstoky.html

[E07] 按分隔符拆分
来源：http://dali.quarkkingdee.top/Article/details/gtnqhbkyjh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shangyingyoupin.top/Article/details/gtjccrkpve.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.pycfn.com/Article/details/gtvddgaxbl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jlsjyb.cn/Article/details/gttnlwxazt.html

TS:   s.split(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqacdklef.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yanxiufei.cn/Article/details/gtqrwzeftm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtaweyvxii.html

Ruby: s.split(",");  s.split
来源：http://dali.pengpengdd.cyou/Article/details/gtmjevndch.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yangfankeji.com/Article/details/gtqgmjqhwd.html

[E08] 数组按分隔符合并
来源：http://dali.iojbl.cn/Article/details/gtxrntkqtl.html

Py:   ",".join(items)
来源：http://dali.yongpay.top/Article/details/gtkkfxagcs.html

PHP:  implode(",", $items);
来源：http://dali.shangyingyoupin.top/Article/details/gtfrzndcpk.html

JS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gtfxnqnphl.html

TS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtbllezvqq.html

Java: String.join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gtsxgajioy.html

Go:   strings.Join(items, ",")
来源：http://dali.cashguo.top/Article/details/gttpadfzlh.html

Ruby: items.join(",")
来源：http://dali.pycfn.com/Article/details/gteeiazqhm.html

C#:   string.Join(",", items)
来源：http://dali.zhengqikj.top/Article/details/gtxrhdngbd.html

[E09] 去除所有空白字符
来源：http://dali.yj20258.top/Article/details/gtkyipemqe.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtrbgrqhnj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cqqwz.cn/Article/details/gtvuiyhsgq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtdqtarmms.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gtknawiwgf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelglnagx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yonumen.top/Article/details/gtxnwcxbci.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aizwys.cn/Article/details/gtmuffcifq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guannengcc.top/Article/details/gtibnqdnhf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fengsongda.top/Article/details/gtvkjcukvj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtwutjudih.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxinkj.top/Article/details/gtxjnxoazy.html

JS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtmpjdsyrj.html

TS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtilbhpfza.html

Java: String.format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtpwsbpbeh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtvpgozybq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtbkiywgji.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnqzz.top/Article/details/gtfsuoqjoo.html

[E11] 反转字符串
来源：http://dali.hnqzz.top/Article/details/gtqzxlvxbf.html

Py:   s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gtgilucsnh.html

PHP:  strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gtcebjttfc.html

JS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtrusydqqd.html

TS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmrnfegs.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jlsjyb.cn/Article/details/gtnhsuiozc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sxryk.cn/Article/details/gtnzkshxoe.html

Ruby: s.reverse
来源：http://dali.cdnleiting.top/Article/details/gttrszwmwp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gthhtwrlgm.html

[E12] 统计某字符出现次数
来源：http://dali.chenlongwang.top/Article/details/gtjyyckrzp.html

Py:   s.count("a")
来源：http://dali.mhx1999.top/Article/details/gtipvjysex.html

PHP:  substr_count($s, "a");
来源：http://dali.iojbl.cn/Article/details/gtwucjqcnk.html

JS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gtpltygqiw.html

TS:   s.split("a").length - 1
来源：http://dali.hammf.cn/Article/details/gtbfmkaudi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqfkzpsc.html

Go:   strings.Count(s, "a")
来源：http://dali.meibo888.top/Article/details/gthijlgeef.html

Ruby: s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtwaeaoirq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pengpengdd.cyou/Article/details/gtzunxihml.html

[E13] 逐字符遍历
来源：http://dali.cheryme.top/Article/details/gtqmiehuay.html

Py:   for ch in s: print(ch)
来源：http://dali.smart0.xyz/Article/details/gtwqnumrdr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuxming.cn/Article/details/gtltnvkvsc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtskdflwmf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtdbarfojs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.havefunace.top/Article/details/gtfiybimfp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gogol.net.cn/Article/details/gtjzlijxmp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaifcshay.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtpuayvevv.html

[E14] URL 编码与 Base64
来源：http://dali.zdqjudy.top/Article/details/gtogwllpxg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hywenlv.cn/Article/details/gtqrtuervs.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.havefunace.top/Article/details/gtyeyzleiu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.birdmap.top/Article/details/gtjvgvzpnv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hysaishi.cn/Article/details/gttkcychvq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hammf.cn/Article/details/gtfomzkwsm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.316326.xyz/Article/details/gtahectrvy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dianchejie.cn/Article/details/gtjurnaerw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtjvzzwpse.html

[E15] HTML 转义 / 反转义
来源：http://dali.snrcjt.cn/Article/details/gtwrrfxska.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.svipenyu.cn/Article/details/gtmyihsdak.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258888.top/Article/details/gtuatylsdc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtzjaetjiq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.haohaochexian.top/Article/details/gtrpsxthbg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.snrcjt.cn/Article/details/gtgkxxaeiy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gticesjisn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xziqi.cn/Article/details/gthdvgvwgj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guannengcc.top/Article/details/gtbpynxmal.html

[E16] 数字千分位
来源：http://dali.jianghu66.top/Article/details/gtfdfoykeh.html

Py:   f"{1234567:,}"
来源：http://dali.gzhubu.top/Article/details/gtfyknyaoy.html

PHP:  number_format(1234567);
来源：http://dali.redwolf501.top/Article/details/gtitwmukhs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gtbufouasg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gtlwttmglm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhixingplan.top/Article/details/gtaeumiuxd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gzhubu.top/Article/details/gtdddvcjkj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gaohongyu789.top/Article/details/gtdcsrmnda.html

C#:   1234567.ToString("N0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvvqgnkr.html

[E17] 首字母大写
来源：http://dali.chenlongwang.top/Article/details/gtccbluaek.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cqqwz.cn/Article/details/gtokijyggk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jyoumei.cn/Article/details/gtlhdajuab.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtxlskwbjq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtofbjnhkp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhongyouzk.top/Article/details/gthktuioxs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yueranfly.top/Article/details/gtlklgrucn.html

Ruby: s.capitalize
来源：http://dali.hysaishi.cn/Article/details/gtxnelkvix.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dashuyun.cn/Article/details/gtiujycrrm.html

[E18] 模板占位符替换
来源：http://dali.dianchejie.cn/Article/details/gteuiwggld.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hysaishi.cn/Article/details/gtiqdraxjp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sxryk.cn/Article/details/gthlymrcov.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtgbywwoyi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtaakpfrvq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gthlmwcqro.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtgsqcbqse.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.redwolf501.top/Article/details/gtdjganbke.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sysykeji.top/Article/details/gteyczchti.html

[E19] 多行文本按行拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvjbpryu.html

Py:   s.splitlines()
来源：http://dali.ppjwa.cn/Article/details/gtwucdtlaw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtnjmufdue.html

JS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gtkzpbxiuj.html

TS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gttwantpws.html

Java: s.lines().toList()
来源：http://dali.fzhhl.top/Article/details/gtbrjpciex.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258888.top/Article/details/gtdpdnxfiq.html

Ruby: s.lines
来源：http://dali.aibaodan.cn/Article/details/gtczktzpwb.html

C#:   s.Split('\n')
来源：http://dali.yuxming.cn/Article/details/gtmrsgrvct.html

[E20] 判断字符串是否为空
来源：http://dali.guannengcc.top/Article/details/gtmvipmfay.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gteilfjetj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflwlpbiv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcehnavg.html

TS:   if (s === "") {}
来源：http://dali.guowangkeji.top/Article/details/gtkdgajswn.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gtkakcpsvn.html

Go:   if s == "" {}
来源：http://dali.jqgfzy.top/Article/details/gtdutcbpww.html

Ruby: if s.empty?
来源：http://dali.birdmap.top/Article/details/gtwbyrqqih.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nwbrower.top/Article/details/gtosrnifss.html

[E21] 超长截断加省略号
来源：http://dali.xinyue.icu/Article/details/gtxoikbgiu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ppjwa.cn/Article/details/gtcbwwgack.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtqlaxhrdx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtjuwmwwdh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtyxavoccz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtzygsmkqy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pengpengdd.cyou/Article/details/gtdwozhoup.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtnidsiiet.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtntqihayb.html

[E22] 字节长度与字符长度
来源：http://dali.jlsjyb.cn/Article/details/gtrssldcma.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.smart0.xyz/Article/details/gtgerbwsoq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtcinoacoh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqgwigkf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gturhshapf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrssdqsh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gtdnuizlwy.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtfradyjew.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xylfe.cn/Article/details/gtjnvohejm.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtivirlolo.html

F. 文件与目录
来源：http://dali.kuanghao11.cn/Article/details/gtyxnzgbao.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtdtyimbtn.html

[F01] 读取整个文件
来源：http://dali.zhoulong.xyz/Article/details/gtcpxunyed.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhongyouzk.top/Article/details/gtixipqmkq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwjvzxmq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gzhubu.top/Article/details/gteljsdqjx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jianghu66.top/Article/details/gtxzycownz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtlaafalos.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dianchejie.cn/Article/details/gtjmbjflod.html

Ruby: File.read("a.txt")
来源：http://dali.cashguo.top/Article/details/gtaexwhgdd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtxxzvxcet.html

[F02] 逐行读取文件
来源：http://dali.zhongyouzk.top/Article/details/gtttomrtjp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hammf.cn/Article/details/gtbdunzvjm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gtsjptavac.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.mhx1999.top/Article/details/gtlmggzcoe.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gtoxjwmqrj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gthgtozvyl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.birdmap.top/Article/details/gtjoofvonc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258888.top/Article/details/gtrvyktreh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenlongwang.top/Article/details/gtwlxrgova.html

[F03] 写入文件（覆盖）
来源：http://dali.yj202588.top/Article/details/gticcprouq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtiuxkxbvh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gtwgfkzluy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gtetznsrzt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtptzrorvj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aibaodan.cn/Article/details/gtoelstray.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxinkj.top/Article/details/gtealfrxnq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxshnqify.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gtflcgamrs.html

[F04] 追加写入文件
来源：http://dali.meibo888.top/Article/details/gtszzfuiti.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.0kj1m.cn/Article/details/gtveixezst.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cheryme.top/Article/details/gtrbftgcqv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gtrsughosr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtjgmaelyk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.andypj.xyz/Article/details/gtyqmsuvgh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xziqi.cn/Article/details/gtgmzsrmlm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhoulong.xyz/Article/details/gtzfbjrtbr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhoulong.xyz/Article/details/gtwhixmcuo.html

[F05] 判断文件或目录是否存在
来源：http://dali.ydzc1.top/Article/details/gtdvkfuqeg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.havefunace.top/Article/details/gtbhybgmma.html

PHP:  file_exists("a.txt");
来源：http://dali.birdmap.top/Article/details/gtmahbhyno.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtkhnquqwl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtzmzmgfbh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtzfklskhi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktsgsfsl.html

Ruby: File.exist?("a.txt")
来源：http://dali.cheryme.top/Article/details/gtplbgjcjp.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gttkpvnwsq.html

[F06] 删除文件
来源：http://dali.zhengqikj.top/Article/details/gtpjojzvhx.html

Py:   os.remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtwowwwlqx.html

PHP:  unlink("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtzvizxoye.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtgpugvsid.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtcsxfzrbr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gttsieodui.html

Go:   os.Remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtogagjcab.html

Ruby: File.delete("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtosjfvbni.html

C#:   File.Delete("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtjigkzwwd.html

[F07] 创建目录（含多级）
来源：http://dali.chenzaomai.com/Article/details/gtaduazlli.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gtjohkckgp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gthslsvsis.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gtqkpmavrm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtsjnepfio.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zdqjudy.top/Article/details/gtmnzmadeg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daxiang520.top/Article/details/gtqmbdgwzt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shuidangran.top/Article/details/gtlluvyejv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dianchejie.cn/Article/details/gtgmebpgsj.html

[F08] 遍历目录
来源：http://dali.pycfn.com/Article/details/gtbobtbgqg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gtuekclwls.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.316326.xyz/Article/details/gtdtlvedsw.html

JS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gtfnyxelyh.html

TS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtwbceiwyk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gtthxrjhlz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxinkj.top/Article/details/gtgpuqlmgr.html

Ruby: Dir.children("dir")
来源：http://dali.snrcjt.cn/Article/details/gtdtekqrui.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yvedp.cn/Article/details/gtmmftloiz.html

[F09] 获取文件大小
来源：http://dali.dashuyun.cn/Article/details/gtoiupzgjp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtvtemcbie.html

PHP:  filesize("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtpbrasifj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gtqbpkfxyh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gtkxwkjyci.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtxaigxynb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cashguo.top/Article/details/gtmkqxtgbd.html

Ruby: File.size("a.txt")
来源：http://dali.pycfn.com/Article/details/gtyjrgzgqb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gzhubu.top/Article/details/gturgljfyl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.smart0.xyz/Article/details/gtznpimwqn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtuwrqmcve.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtvtsrtvrh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtinhcxdpc.html

TS:   path.extname("a.txt")
来源：http://dali.birdmap.top/Article/details/gtmqjxbmzo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gtupksdqfj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtpxbwhnhu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtzrlwuwzr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtbqvkdjpz.html

[F11] 复制与移动文件
来源：http://dali.snrcjt.cn/Article/details/gthwasubgl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtyzoxkotl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tanke756.top/Article/details/gthecirvug.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtjdjdhujd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqihnozk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaimjvghg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yanxiufei.cn/Article/details/gtywxpdnbk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gthulnigco.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nwbrower.top/Article/details/gtvhwbxlmo.html

[F12] CSV 读写
来源：http://dali.daria6918.cn/Article/details/gtvrmqcric.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.bjfxy.top/Article/details/gthoqkvzsk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.kuanghao11.cn/Article/details/gtwfettfqq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hysaishi.cn/Article/details/gtewmwhshj.html

TS:   // 同上
来源：http://dali.cucudq.cn/Article/details/gtdfhhqzvx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gogol.net.cn/Article/details/gtfowoelfc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ivvv.top/Article/details/gtxjbmbyex.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gtioctbawu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.snrcjt.cn/Article/details/gtmxoqbxey.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtmccluxud.html

G. 面向对象
来源：http://dali.meibo888.top/Article/details/gtgadcimdp.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtablgkcoo.html

[G01] 定义类
来源：http://dali.0kj1m.cn/Article/details/gtmhjlwtex.html

Py:   class User: pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcoznmrw.html

PHP:  class User {}
来源：http://dali.9152youxi.cn/Article/details/gtclxcgmti.html

JS:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtyldtitsz.html

TS:   class User { name: string = ""; }
来源：http://dali.hammf.cn/Article/details/gtudjzouiu.html


<!-- 参考信息 -->