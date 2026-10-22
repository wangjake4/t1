代发 wailian999

Java: String.join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gtdvihjpxi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhixingplan.top/Article/details/gtlpnggozx.html

Ruby: arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gttsbnypfr.html

C#:   string.Join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gtgimgooex.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtghrrciqh.html

E. 字符串处理
来源：http://dali.jyoumei.cn/Article/details/gtbgwourui.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtexjfnpno.html

[E01] 拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtlautamah.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnnbcsdo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aizwys.cn/Article/details/gthoyaeeui.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hfpthk.cn/Article/details/gtlkcsveoc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtakwufbpq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgfzy.top/Article/details/gtgihvmtkd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shuidangran.top/Article/details/gtkuwkapwx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj202588.top/Article/details/gtzpotptjj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthixqmpwk.html

[E02] 重复字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtwmwetobf.html

Py:   "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepojgxnb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shangyingyoupin.top/Article/details/gteujjrtir.html

JS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtqotlsdrn.html

TS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtyofazvfi.html

Java: "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtnpjyjfzk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nanxinkj.top/Article/details/gtazdgrxdd.html

Ruby: "ab" * 3
来源：http://dali.sweek.top/Article/details/gtmkyqdras.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizcwgoqm.html

[E03] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gtahxqtylr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zycfv.cn/Article/details/gthkkhrrhx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtjusyvepv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtbylgznfc.html

TS:   s.slice(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtwxqryzjd.html

Java: s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtcazwikft.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yueranfly.top/Article/details/gtxykfbcja.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.andypj.xyz/Article/details/gtzbtsnlvk.html

C#:   s.Substring(1, 3)
来源：http://dali.yonumen.top/Article/details/gtwshfxshg.html

[E04] 查找子串位置
来源：http://dali.yonumen.top/Article/details/gtbnkjvsmq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.daxiang520.top/Article/details/gtdhjdnykb.html

PHP:  strpos($s, "x");
来源：http://dali.feifeiyinyue.top/Article/details/gtgepywegr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yuxming.cn/Article/details/gtuzotdohb.html

TS:   s.indexOf("x")
来源：http://dali.redwolf501.top/Article/details/gtqekwbjal.html

Java: s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gtkwzvnbvj.html

Go:   strings.Index(s, "x")
来源：http://dali.kuanghao11.cn/Article/details/gtrlqxhkxb.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gtssdesrvc.html

C#:   s.IndexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtphdqezek.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenvkmhha.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258.top/Article/details/gtetxjnzkh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhongyouzk.top/Article/details/gtupqibumy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtfotmvemm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ivvv.top/Article/details/gtlewxyboq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gtsoctpkvf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yueranfly.top/Article/details/gtblafbtff.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.iojbl.cn/Article/details/gtcanjnkoi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtplpdhjgw.html

[E06] 替换子串
来源：http://dali.sxryk.cn/Article/details/gtuhdukkff.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gtuveiicud.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xziqi.cn/Article/details/gtgxisfexi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtankbxzun.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtvcsjgdkj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtdiiywwco.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gtnlcscybl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtthppgfxs.html

C#:   s.Replace("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtxsypblco.html

[E07] 按分隔符拆分
来源：http://dali.aibaodan.cn/Article/details/gtvctuknxd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenlongwang.top/Article/details/gtmsydquzz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtlqwwbdci.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxinkj.top/Article/details/gtomlgpwxu.html

TS:   s.split(",")
来源：http://dali.hnxiangtu.top/Article/details/gtqlznlnnz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fengsongda.top/Article/details/gteloiccvo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxuanxn.top/Article/details/gtowkqbztn.html

Ruby: s.split(",");  s.split
来源：http://dali.havefunace.top/Article/details/gtqnvgtznz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenlongwang.top/Article/details/gtfrmxgynu.html

[E08] 数组按分隔符合并
来源：http://dali.hysaishi.cn/Article/details/gtwxpeljzu.html

Py:   ",".join(items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstnznqfb.html

PHP:  implode(",", $items);
来源：http://dali.zhiwuduotai.top/Article/details/gtxtzznwbd.html

JS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlicjgukh.html

TS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpoxpbpuh.html

Java: String.join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gtnlnvaukh.html

Go:   strings.Join(items, ",")
来源：http://dali.hfpthk.cn/Article/details/gtbuvdauec.html

Ruby: items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtlmtagdkh.html

C#:   string.Join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gtyhxyuuyo.html

[E09] 去除所有空白字符
来源：http://dali.nwbrower.top/Article/details/gtcfqulpfe.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cdnleiting.top/Article/details/gtdzwtfpcd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.redwolf501.top/Article/details/gtlbcdntfv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gtkptbloxq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gtughpyrfp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gtqcgzppho.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cqqwz.cn/Article/details/gtkkaupvop.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pycfn.com/Article/details/gtwihscejj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gtmuolircd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqxxohrt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtftvkvhzy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.c1oappe.top/Article/details/gtpywmkgao.html

JS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtreupdyqk.html

TS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtoesckmov.html

Java: String.format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtltfpnurn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtapjewjue.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtuotjkokj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmumnweeb.html

[E11] 反转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexgxeond.html

Py:   s[::-1]
来源：http://dali.xuanzx.com/Article/details/gteeidaqwu.html

PHP:  strrev($s);
来源：http://dali.xziqi.cn/Article/details/gtbwznsrpw.html

JS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtsckgptpz.html

TS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtyidjcfom.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtznkhlobb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dianchejie.cn/Article/details/gtnktbahzn.html

Ruby: s.reverse
来源：http://dali.jyoumei.cn/Article/details/gtoupshkrp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gtlbekuzbq.html

[E12] 统计某字符出现次数
来源：http://dali.daxiang520.top/Article/details/gtaisktzkr.html

Py:   s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gtcqrbujmc.html

PHP:  substr_count($s, "a");
来源：http://dali.sysykeji.top/Article/details/gtnaksbmvd.html

JS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnrvwhbj.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gtfbbdhozh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tian-w.cn/Article/details/gtxljsllgx.html

Go:   strings.Count(s, "a")
来源：http://dali.cqqwz.cn/Article/details/gtmbbrjxnd.html

Ruby: s.count("a")
来源：http://dali.aizwys.cn/Article/details/gtdmufwcvr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.snrcjt.cn/Article/details/gtaxezgrjt.html

[E13] 逐字符遍历
来源：http://dali.yueranfly.top/Article/details/gttjeoejyd.html

Py:   for ch in s: print(ch)
来源：http://dali.sweek.top/Article/details/gtizqfbqtk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tianlin.xyz/Article/details/gtflufqirg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gtfrnmkvog.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtigrycguv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibgdwule.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.wangdashe.top/Article/details/gtmugzuoug.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.kuanghao11.cn/Article/details/gtyumnjdft.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.316326.xyz/Article/details/gtknwqhpty.html

[E14] URL 编码与 Base64
来源：http://dali.xziqi.cn/Article/details/gtvzgdfzhn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cdnleiting.top/Article/details/gtteqdewoa.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hysaishi.cn/Article/details/gtituplmng.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenjidiqi.icu/Article/details/gtvlcpwbts.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gaohongyu789.top/Article/details/gtejfnmtym.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aizwys.cn/Article/details/gtcpukazqy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.havefunace.top/Article/details/gtggydfgua.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangshuangyany.cn/Article/details/gttxdscmfe.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtggtbakzz.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnxiangtu.top/Article/details/gtbiuvdsdg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigfzy.top/Article/details/gtscqiooht.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xinyue.icu/Article/details/gtiablrtat.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sufxvd.cn/Article/details/gtyefxoylt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuanzhike.top/Article/details/gtmnqtuzxv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhixingplan.top/Article/details/gtqkidpojz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnxiangtu.top/Article/details/gtxfvxupzp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.dianchejie.cn/Article/details/gtwcukovrb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowqovbla.html

[E16] 数字千分位
来源：http://dali.shzxlz.cn/Article/details/gtgcptethk.html

Py:   f"{1234567:,}"
来源：http://dali.vqdsnc.cn/Article/details/gtnrwkglrd.html

PHP:  number_format(1234567);
来源：http://dali.aibaodan.cn/Article/details/gtrxeqovcn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gtxpelyzgo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gtmkohydij.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gtjjbvggut.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nwbrower.top/Article/details/gtjxnqlknk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.smart0.xyz/Article/details/gterxhqqbs.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258888.top/Article/details/gtjlbjpobm.html

[E17] 首字母大写
来源：http://dali.yangfankeji.com/Article/details/gtjiurierh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhixingplan.top/Article/details/gtpmkoynxw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hysaishi.cn/Article/details/gtnyondgej.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gtkgjgvlfb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shzxlz.cn/Article/details/gtjrevpond.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ivvv.top/Article/details/gtfrbvhuep.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtyoccgjpl.html

Ruby: s.capitalize
来源：http://dali.xinyue.icu/Article/details/gttbfuahqa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258888.top/Article/details/gtrfjydvzy.html

[E18] 模板占位符替换
来源：http://dali.cqqwz.cn/Article/details/gtfilebpur.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.andypj.xyz/Article/details/gttkrkvxgi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cqqwz.cn/Article/details/gtwfmijlpy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtaqgqcxiu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtsgjzuvxz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtipktxhrm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.havefunace.top/Article/details/gthwafqlbo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aibaodan.cn/Article/details/gtsfeypahl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhengqikj.top/Article/details/gtyiaykytr.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigufen.top/Article/details/gtoqtoppsw.html

Py:   s.splitlines()
来源：http://dali.tianlin.xyz/Article/details/gtatvstxjt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fengsongda.top/Article/details/gttrwlwhug.html

JS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gtadscspts.html

TS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtmrjpdkrt.html

Java: s.lines().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtwqlhpdst.html

Go:   strings.Split(s, "\n")
来源：http://dali.0kj1m.cn/Article/details/gtrcuwxwho.html

Ruby: s.lines
来源：http://dali.jiagoushi.top/Article/details/gtmrqaqksx.html

C#:   s.Split('\n')
来源：http://dali.cqqwz.cn/Article/details/gtylqhmrbd.html

[E20] 判断字符串是否为空
来源：http://dali.feifeiyinyue.top/Article/details/gtlizclzdj.html

Py:   if not s:
来源：http://dali.cucudq.cn/Article/details/gtbjvibffi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nwbrower.top/Article/details/gtkzzhqswb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.316326.xyz/Article/details/gtxunoiesv.html

TS:   if (s === "") {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqcavxwee.html

Java: if (s.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gttzregjsv.html

Go:   if s == "" {}
来源：http://dali.gzhubu.top/Article/details/gtmcpiigcu.html

Ruby: if s.empty?
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfswpcij.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.9152youxi.cn/Article/details/gtkdfuydso.html

[E21] 超长截断加省略号
来源：http://dali.yj20258.top/Article/details/gtzwboepgj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgufenzy.top/Article/details/gtldmmyhvj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtirnzettq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtjcjezhil.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtnrfvalwh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtsfhytsff.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuetiantiany.cn/Article/details/gtvdcmquso.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtyyamrtpx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtrhqzpjap.html

[E22] 字节长度与字符长度
来源：http://dali.xuetiantiany.cn/Article/details/gtvgivcjgu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjksbnzea.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtfgzjeaxg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gtctmwezwk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gtckjxqqsi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gtiuggaooa.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sysykeji.top/Article/details/gtxpmvbeea.html

Ruby: s.bytesize;  s.length
来源：http://dali.sweek.top/Article/details/gtfdnnnqvt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tian-w.cn/Article/details/gtetifmhzm.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtsbepgcwx.html

F. 文件与目录
来源：http://dali.jlsjyb.cn/Article/details/gtiooqmsmq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpxopkab.html

[F01] 读取整个文件
来源：http://dali.yj202588.top/Article/details/gtcffuycbg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cashguo.top/Article/details/gtibrxjzna.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ydzc1.top/Article/details/gttshurcsn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gotoacloud.top/Article/details/gtaitqxgav.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtvyddylav.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gteqyqreov.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhongyouzk.top/Article/details/gtjijbrayo.html

Ruby: File.read("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtobxubdmz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtjstogrkh.html

[F02] 逐行读取文件
来源：http://dali.9152youxi.cn/Article/details/gttcadongm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fzhhl.top/Article/details/gtwusrxedh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.smart0.xyz/Article/details/gtbfsdzphc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gtsangjfik.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtmnvgcprg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gtnrynhzhl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhengqikj.top/Article/details/gthxnxdksw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhixingplan.top/Article/details/gthakttcvw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shzxlz.cn/Article/details/gtkmxxnqbc.html

[F03] 写入文件（覆盖）
来源：http://dali.ppjwa.cn/Article/details/gtsbrwfjtf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sufxvd.cn/Article/details/gtgirdbhcs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fengsongda.top/Article/details/gtukfuorbl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtunzmfabz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtukmtqyfx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtofbnezui.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgufenzy.top/Article/details/gtfacdaqhe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sweek.top/Article/details/gtqiqlmmwx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtogsgmbzp.html

[F04] 追加写入文件
来源：http://dali.gaohongyu789.top/Article/details/gtqnrptsbp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gtjcrjqlxu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenzaomai.com/Article/details/gtvmkpoodk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gtormhrbac.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtdzyoqdvq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xylfe.cn/Article/details/gtlanheqhc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtohfqokca.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ivvv.top/Article/details/gtjmxfkcnp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yongpay.top/Article/details/gtjsdeoqgh.html

[F05] 判断文件或目录是否存在
来源：http://dali.sweek.top/Article/details/gtbhqoreoc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ybcxt.top/Article/details/gtncesunez.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtsyxjtbwp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtcjtfruku.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtkzhycqzw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtpsvmpjwj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yueranfly.top/Article/details/gthqzubztr.html

Ruby: File.exist?("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtozrelkoo.html

C#:   File.Exists("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkffqwts.html

[F06] 删除文件
来源：http://dali.meibo888.top/Article/details/gtgmoacmrj.html

Py:   os.remove("a.txt")
来源：http://dali.sweek.top/Article/details/gtvqkbwexr.html

PHP:  unlink("a.txt");
来源：http://dali.hammf.cn/Article/details/gtymmhtkes.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtuwihyndk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtpmtugrfs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtncnebfdz.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gtwqqjbvpt.html

Ruby: File.delete("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtfqcjytgf.html

C#:   File.Delete("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtpbciaofi.html

[F07] 创建目录（含多级）
来源：http://dali.jlsjyb.cn/Article/details/gtilufdxof.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhixingplan.top/Article/details/gtgwtzdsew.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gzhubu.top/Article/details/gtbpuuuxen.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gtqqvjhvwq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gtcihxhjhn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daria6918.cn/Article/details/gtrytflxbb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhongyouzk.top/Article/details/gtjapoqxdn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yueranfly.top/Article/details/gtmgujushz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nwbrower.top/Article/details/gtqbwrrtnt.html

[F08] 遍历目录
来源：http://dali.gotoacloud.top/Article/details/gttvoaszbj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nwbrower.top/Article/details/gthmvwdmde.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gtlvlavqpe.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtiegngkwu.html

TS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gtizotixsq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gtejutomhf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ydzc1.top/Article/details/gtlnvtsnjy.html

Ruby: Dir.children("dir")
来源：http://dali.shuidangran.top/Article/details/gtucfjgexq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.snrcjt.cn/Article/details/gtkuqprwoo.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gtqzerljxr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtmoqostui.html

PHP:  filesize("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtrqnxxdpc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gtickjbctk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gtlemhniqv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtvwrtbhtm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuanzx.com/Article/details/gtltqeecmw.html

Ruby: File.size("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtkfwbqtuz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.kuanghao11.cn/Article/details/gtomvtomii.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhixingplan.top/Article/details/gtnkvjfqom.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtantweftl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtqqulhceg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtisaevftw.html

TS:   path.extname("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtchdevfss.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.quarkkingdee.top/Article/details/gtibdvgnlo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtoornmkpk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtltalddsn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gttsfcjsmt.html

[F11] 复制与移动文件
来源：http://dali.jianghu66.top/Article/details/gtxssorvsr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtsdwitalu.html


<!-- 参考信息 -->