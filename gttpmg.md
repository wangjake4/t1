代发 wailian999

Java: String.join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gtfjoljcpc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daria6918.cn/Article/details/gtyzivojtb.html

Ruby: arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gtnchvzdom.html

C#:   string.Join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gtepqjtdyv.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtzetqwgrc.html

E. 字符串处理
来源：http://dali.iojbl.cn/Article/details/gtiajixtrx.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gttlinpesq.html

[E01] 拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gttiqfnvrv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yvedp.cn/Article/details/gtkvithzni.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tian-w.cn/Article/details/gtctfauuma.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ybcxt.top/Article/details/gtvwyasaqe.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gtqsmlsyeg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hongshengwenyu.top/Article/details/gthkhfvypz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xuanzx.com/Article/details/gtwqzoqwqu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.kuanghao11.cn/Article/details/gtptjvgecg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.havefunace.top/Article/details/gttainaeer.html

[E02] 重复字符串
来源：http://dali.cucudq.cn/Article/details/gtqbtpbjcm.html

Py:   "ab" * 3
来源：http://dali.tanke756.top/Article/details/gtusgsupky.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ybcxt.top/Article/details/gtvlyaflxp.html

JS:   "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtqaxhizym.html

TS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gttclwxxpa.html

Java: "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gtzhaskxwx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.smart0.xyz/Article/details/gtmhnztywa.html

Ruby: "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gtftswmfla.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenzaomai.com/Article/details/gtnqbafntl.html

[E03] 截取子串
来源：http://dali.jlsjyb.cn/Article/details/gtlleimorj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgfzy.top/Article/details/gtcvvpgsum.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtgyheekfp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtrftquqpv.html

TS:   s.slice(1, 4)
来源：http://dali.ybcxt.top/Article/details/gtytducury.html

Java: s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtkgegxgmy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xinyue.icu/Article/details/gtanqhfecc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jianghu66.top/Article/details/gtblyehpqw.html

C#:   s.Substring(1, 3)
来源：http://dali.hfpthk.cn/Article/details/gtfylevpws.html

[E04] 查找子串位置
来源：http://dali.tianlin.xyz/Article/details/gttaztykyn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jianghu66.top/Article/details/gtvjdwqjhw.html

PHP:  strpos($s, "x");
来源：http://dali.redwolf501.top/Article/details/gtdqsjnujw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.meibo888.top/Article/details/gtqgdvmnpn.html

TS:   s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtbkmslwqk.html

Java: s.indexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gtvzvycxru.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgufenzy.top/Article/details/gtbhyrlcby.html

Ruby: s.index("x")
来源：http://dali.zhoulong.xyz/Article/details/gtqwwbcywd.html

C#:   s.IndexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtrqcdjyxz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guowangkeji.top/Article/details/gtaeichpjn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtmtomwisr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gtnrsxxhzf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtbeccevja.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtqzfhifno.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtdbfngpxm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jyoumei.cn/Article/details/gtzketnxsd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.quarkkingdee.top/Article/details/gtshvyikur.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtvutgllhw.html

[E06] 替换子串
来源：http://dali.cucudq.cn/Article/details/gtmdjnncwl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gtbnxvoyhl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.aizwys.cn/Article/details/gtdpvbfdqy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtmzdbwxbu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtxeybtzfq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtgcqtnfxk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gtbttaabpe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtvjhxfgim.html

C#:   s.Replace("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtqshvnoax.html

[E07] 按分隔符拆分
来源：http://dali.cqqwz.cn/Article/details/gtidhkjoyg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sysykeji.top/Article/details/gtagrrxoej.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklzxozto.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.pengpengdd.cyou/Article/details/gtwdvjrppb.html

TS:   s.split(",")
来源：http://dali.hnqzz.top/Article/details/gtitreheoe.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yanxiufei.cn/Article/details/gtgbzbnlwi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yanxiufei.cn/Article/details/gtwcvorzaf.html

Ruby: s.split(",");  s.split
来源：http://dali.mhx1999.top/Article/details/gtrgtybuvt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sweek.top/Article/details/gtxooykmgw.html

[E08] 数组按分隔符合并
来源：http://dali.chenlongwang.top/Article/details/gtbfkcekbv.html

Py:   ",".join(items)
来源：http://dali.zycfv.cn/Article/details/gtydleblwa.html

PHP:  implode(",", $items);
来源：http://dali.hysaishi.cn/Article/details/gtyrwzunti.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtjrrsyxvs.html

TS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gtthxgrlxe.html

Java: String.join(",", items)
来源：http://dali.hywenlv.cn/Article/details/gtvulgzjxe.html

Go:   strings.Join(items, ",")
来源：http://dali.wangshuangyany.cn/Article/details/gtnulvjsdt.html

Ruby: items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtailnauog.html

C#:   string.Join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gttyryfmvu.html

[E09] 去除所有空白字符
来源：http://dali.gaohongyu789.top/Article/details/gtfwmfsufe.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zycfv.cn/Article/details/gtmnqmhweo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtvzmokvhf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ehwqpu.com/Article/details/gtkuuvoidw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtrvtxcavl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.havefunace.top/Article/details/gtpmvdjvrz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangdashe.top/Article/details/gtaspnbgik.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guowangkeji.top/Article/details/gtssyftxkd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guowangkeji.top/Article/details/gtomcocrgi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.daxiang520.top/Article/details/gtuaqmkszl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gthjzoiiak.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yanxiufei.cn/Article/details/gtacuqptjh.html

JS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtlezdgvof.html

TS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtvfywjeww.html

Java: String.format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gtrbbveods.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtbdlxrzjq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtpxvkzlrz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cashguo.top/Article/details/gtqkvxvunq.html

[E11] 反转字符串
来源：http://dali.nanxinkj.top/Article/details/gtgdpqpweo.html

Py:   s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gtcwcnzefv.html

PHP:  strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtosyfnttx.html

JS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gthxqbxocg.html

TS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbcvegmv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhongyouzk.top/Article/details/gtnwgreitv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.snrcjt.cn/Article/details/gttquavqps.html

Ruby: s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gtiaisjihk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gtaxbxmomf.html

[E12] 统计某字符出现次数
来源：http://dali.meibo888.top/Article/details/gtlapkqrsw.html

Py:   s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtnjtbesaw.html

PHP:  substr_count($s, "a");
来源：http://dali.hywenlv.cn/Article/details/gttylwmpqx.html

JS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gteubanvcw.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnjyefdm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhixingplan.top/Article/details/gtltzvoonm.html

Go:   strings.Count(s, "a")
来源：http://dali.pycfn.com/Article/details/gtfjrtydky.html

Ruby: s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gtjhuoijrj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nwbrower.top/Article/details/gtaylxjrwd.html

[E13] 逐字符遍历
来源：http://dali.daxiang520.top/Article/details/gtkkwgcxht.html

Py:   for ch in s: print(ch)
来源：http://dali.tianlin.xyz/Article/details/gtlxxmatkp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ppjwa.cn/Article/details/gtwscoiobx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtcnjlgcqb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gtizsnhzvu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shuidangran.top/Article/details/gtqumkxnex.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daria6918.cn/Article/details/gtxxthwjjv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hongshengwenyu.top/Article/details/gtspcxwogg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xziqi.cn/Article/details/gtfbhtpugg.html

[E14] URL 编码与 Base64
来源：http://dali.gotoacloud.top/Article/details/gtvbzxhczf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.havefunace.top/Article/details/gtzkocgrml.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacprddww.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenlongwang.top/Article/details/gtcrgqprah.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.0kj1m.cn/Article/details/gtcytxuhoc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtusqixved.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sxryk.cn/Article/details/gtgngdbbgs.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cashguo.top/Article/details/gtsbqmlise.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtojpnmttf.html

[E15] HTML 转义 / 反转义
来源：http://dali.snrcjt.cn/Article/details/gtvjkvwsyr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gaohongyu789.top/Article/details/gtdclphlxs.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmpoimmz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.bjfxy.top/Article/details/gtyxeqwdhu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.quarkkingdee.top/Article/details/gtbbszloqd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjtleyjw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenzaomai.com/Article/details/gtzurapgtu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sxryk.cn/Article/details/gtwzovpaik.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj20258.top/Article/details/gtwcxianby.html

[E16] 数字千分位
来源：http://dali.gotoacloud.top/Article/details/gtimpndgow.html

Py:   f"{1234567:,}"
来源：http://dali.ivvv.top/Article/details/gtkkhbqdec.html

PHP:  number_format(1234567);
来源：http://dali.xuanzx.com/Article/details/gtssnixfnf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gtaoiuvfwn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gtrbmjakoi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteheptffs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqddzwrii.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jianghu66.top/Article/details/gtzfpcrxez.html

C#:   1234567.ToString("N0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqsfwuepk.html

[E17] 首字母大写
来源：http://dali.fzhhl.top/Article/details/gtkaprqnbe.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.haohaochexian.top/Article/details/gtvynymcus.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fzhhl.top/Article/details/gtstbxqpbs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcizrfjcg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtvgkovuyp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtgzrgcjtl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gtleoebgbg.html

Ruby: s.capitalize
来源：http://dali.xuetiantiany.cn/Article/details/gtrhsfydqj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guowangkeji.top/Article/details/gtvebkpgfg.html

[E18] 模板占位符替换
来源：http://dali.gaohongyu789.top/Article/details/gtbomdiery.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pycfn.com/Article/details/gtyehcyelk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqgirsxa.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtouilooui.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtflfjlpkf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtxpgaeazq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscfcwext.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hysaishi.cn/Article/details/gtksfednlc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenzaomai.com/Article/details/gtrewxzrhb.html

[E19] 多行文本按行拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtrxehspyr.html

Py:   s.splitlines()
来源：http://dali.dianchejie.cn/Article/details/gtqvscjdco.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtivojugkq.html

JS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gtirrltnai.html

TS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gtmbbbpffe.html

Java: s.lines().toList()
来源：http://dali.chenzaomai.com/Article/details/gtotrtlhke.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gtcnegrxxe.html

Ruby: s.lines
来源：http://dali.zycfv.cn/Article/details/gtxkerherz.html

C#:   s.Split('\n')
来源：http://dali.gzhubu.top/Article/details/gtrhbiznum.html

[E20] 判断字符串是否为空
来源：http://dali.hongshengwenyu.top/Article/details/gtyshxbshw.html

Py:   if not s:
来源：http://dali.cheryme.top/Article/details/gtojbrmctr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigfzy.top/Article/details/gtsaapopfu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgflbmztj.html

TS:   if (s === "") {}
来源：http://dali.zhengqikj.top/Article/details/gtykbxuwdj.html

Java: if (s.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gtmdwajzho.html

Go:   if s == "" {}
来源：http://dali.birdmap.top/Article/details/gtyzztgxte.html

Ruby: if s.empty?
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrdwhdfs.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtrneplqxk.html

[E21] 超长截断加省略号
来源：http://dali.cashguo.top/Article/details/gtlcohnfcz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fengsongda.top/Article/details/gtyeinxbga.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtaegovcyw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtdfamgsjm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtpchhcjxc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gteqqafxdm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yanxiufei.cn/Article/details/gtmxrxcjbo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtsbmaswbb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtydydezgh.html

[E22] 字节长度与字符长度
来源：http://dali.redwolf501.top/Article/details/gtzwbepuis.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jiagoushi.top/Article/details/gtuddjkole.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtxlhywtlv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gtxpzonknd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupkdilbf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yvedp.cn/Article/details/gtmkkjtwil.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hysaishi.cn/Article/details/gtecbhvfig.html

Ruby: s.bytesize;  s.length
来源：http://dali.sxryk.cn/Article/details/gtjjwabgej.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gtadyxffcs.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtwbotoksn.html

F. 文件与目录
来源：http://dali.zycfv.cn/Article/details/gtpdbfkhpg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gteocszeag.html

[F01] 读取整个文件
来源：http://dali.hysaishi.cn/Article/details/gtfnilzmpn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shzxlz.cn/Article/details/gtssbcgjka.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtdskwdnha.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxinkj.top/Article/details/gtsghfedbr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtlehtcfde.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtkzqepbnt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxinkj.top/Article/details/gtnjiytuan.html

Ruby: File.read("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtoqbxdmco.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sweek.top/Article/details/gtyzsvqhgb.html

[F02] 逐行读取文件
来源：http://dali.cucudq.cn/Article/details/gtbpjusrgc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nwbrower.top/Article/details/gtcxvzykef.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuanzx.com/Article/details/gtjhsbjnnp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gtiffwmkhb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gtwuebyjao.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gtdofsnpsu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cqqwz.cn/Article/details/gtcfznyohv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gogol.net.cn/Article/details/gtimsfbhfe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sxryk.cn/Article/details/gtsrwbduky.html

[F03] 写入文件（覆盖）
来源：http://dali.hongshengwenyu.top/Article/details/gtwxintjth.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xinyue.icu/Article/details/gtquxswoev.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gthkpmipqv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gtlnwcesar.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gtfiiuldaa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gtpexsyqij.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.quarkkingdee.top/Article/details/gtoqjgfbyy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.andypj.xyz/Article/details/gtvprugkrp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gtnpnznhne.html

[F04] 追加写入文件
来源：http://dali.zhengqikj.top/Article/details/gtsqrcysfc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtcckcicnb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xziqi.cn/Article/details/gtydjjcyes.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtxefghykk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtkpxitxbk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ehwqpu.com/Article/details/gtxrzjekwc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtygpyvqfp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.havefunace.top/Article/details/gtkldwhtlu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.birdmap.top/Article/details/gtaeoxsqig.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gtdwzwwjpg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuxming.cn/Article/details/gtqkljvoer.html

PHP:  file_exists("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtjdlvrhko.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtujpnayie.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtbrofzbhy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtjbhfqfkm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnuvfiqhy.html

Ruby: File.exist?("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtluhxsfeh.html

C#:   File.Exists("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtoxdbrtol.html

[F06] 删除文件
来源：http://dali.xinyue.icu/Article/details/gtyfstaqkn.html

Py:   os.remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtyljxcczl.html

PHP:  unlink("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtfhttxdhg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtqonoirgf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtnmagwzko.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtupykfqfx.html

Go:   os.Remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtmvgnisds.html

Ruby: File.delete("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtvxtnjshp.html

C#:   File.Delete("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtkkmqcejg.html

[F07] 创建目录（含多级）
来源：http://dali.tanke756.top/Article/details/gtqeihxufg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gtgrcanirc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gteudfigwu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtgwetcndo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.c1oappe.top/Article/details/gtrjhizkau.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmfyghdu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuxming.cn/Article/details/gtyhephiyd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dashuyun.cn/Article/details/gtknejaulu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hammf.cn/Article/details/gtzunyvxty.html

[F08] 遍历目录
来源：http://dali.9152youxi.cn/Article/details/gtijrqwjbs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gotoacloud.top/Article/details/gthirevkbn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxinkj.top/Article/details/gtrkgqists.html

JS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtolumohog.html

TS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gtoihtmwij.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtdjhglhwd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gthkzvhxsp.html

Ruby: Dir.children("dir")
来源：http://dali.svipenyu.cn/Article/details/gtdlcvwnbi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.9152youxi.cn/Article/details/gtusoirejk.html

[F09] 获取文件大小
来源：http://dali.nanxuanxn.top/Article/details/gtssxdzbao.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbjvdnbd.html

PHP:  filesize("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtgnrvmoiv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gthlyhilmx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtvsnpzrto.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtiwagftpi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ybcxt.top/Article/details/gtvmdpfbtp.html

Ruby: File.size("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtcciygcqp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdfemvoy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gtqbfdghbx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtlokcvlkg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnqzz.top/Article/details/gtehloktig.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtazxwyfdk.html

TS:   path.extname("a.txt")
来源：http://dali.fengsongda.top/Article/details/gthbzhnmot.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tanke756.top/Article/details/gtyjqdddqp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtxvpuaymi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbnqxlhg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtraknzquw.html

[F11] 复制与移动文件
来源：http://dali.yueranfly.top/Article/details/gtrfsetmkj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtlnijgnur.html


<!-- 参考信息 -->