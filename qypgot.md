代发 wailian999

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnxiangtu.top/Article/details/gtnwzfwhtt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ppjwa.cn/Article/details/gtotruurjl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.andypj.xyz/Article/details/gtrxyomcal.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jianghu66.top/Article/details/gtqurhgjki.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nwbrower.top/Article/details/gtuyoqdseq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtornculmd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.svipenyu.cn/Article/details/gtxbqpghvm.html

[D26] 数组转字符串
来源：http://dali.xziqi.cn/Article/details/gtrumtjqed.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuanzhike.top/Article/details/gttxrdhfay.html

PHP:  implode(", ", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjijxdwp.html

JS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtvtgervqs.html

TS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gttdguxpkx.html

Java: String.join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gtkxtvpjkd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.birdmap.top/Article/details/gtajeytuso.html

Ruby: arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtxjrtrgti.html

C#:   string.Join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gtczdqgxyg.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtzeoysvoh.html

E. 字符串处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfxlkcgc.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtogudtufk.html

[E01] 拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtfpdkclln.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.9152youxi.cn/Article/details/gtvwacysjy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ybcxt.top/Article/details/gtrsngwofs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gtyrjkcksx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gtifrbojwq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pengpengdd.cyou/Article/details/gtpcoqgooi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.0kj1m.cn/Article/details/gtzueiifqj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.haohaochexian.top/Article/details/gtdfzuatzk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtqibvpskv.html

[E02] 重复字符串
来源：http://dali.sweek.top/Article/details/gtnypybnqo.html

Py:   "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gttitaefvg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hfpthk.cn/Article/details/gtcvptbkif.html

JS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtpxoilcwv.html

TS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtfbusddny.html

Java: "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtljolcubi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cdnleiting.top/Article/details/gtzibiqdbk.html

Ruby: "ab" * 3
来源：http://dali.chenjidiqi.icu/Article/details/gtvpanxjvd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gzhubu.top/Article/details/gtgoplvikf.html

[E03] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxnhkkaj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ybcxt.top/Article/details/gtnjzxdxtp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwaprvkp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtbidxiciw.html

TS:   s.slice(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtepyvirgg.html

Java: s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtstveodeu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnqzz.top/Article/details/gtdximlhui.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hysaishi.cn/Article/details/gtgfpffsfe.html

C#:   s.Substring(1, 3)
来源：http://dali.gotoacloud.top/Article/details/gtdkkgsldm.html

[E04] 查找子串位置
来源：http://dali.fzhhl.top/Article/details/gtekcnsslk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtjembaviv.html

PHP:  strpos($s, "x");
来源：http://dali.hnxiangtu.top/Article/details/gtrqbunuox.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxinkj.top/Article/details/gtuckgjurm.html

TS:   s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gtyrifyaga.html

Java: s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtrvlijksk.html

Go:   strings.Index(s, "x")
来源：http://dali.xziqi.cn/Article/details/gtcishtwrs.html

Ruby: s.index("x")
来源：http://dali.shuidangran.top/Article/details/gtobnlemse.html

C#:   s.IndexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gtlmgjequi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenjidiqi.icu/Article/details/gthvdkvbsj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtxrmmotwy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.pengpengdd.cyou/Article/details/gtmdcibhgw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtaltidmyt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tianlin.xyz/Article/details/gtciqxaqwx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gtoybddsix.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xinyue.icu/Article/details/gtplogwdlv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.0kj1m.cn/Article/details/gtghqmjivl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtbljakhuf.html

[E06] 替换子串
来源：http://dali.fzhhl.top/Article/details/gtlmwdlnll.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyehfbgpe.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepgqzqyx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtmmavxmfn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtcyffcjuz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtqvxplwaz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gtbadzacpt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtkaasvlzb.html

C#:   s.Replace("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmsccwixo.html

[E07] 按分隔符拆分
来源：http://dali.iojbl.cn/Article/details/gtpbomxblh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shangyingyoupin.top/Article/details/gtrafotpzq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangdashe.top/Article/details/gtsodfqpmp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.0kj1m.cn/Article/details/gtkwfatlzk.html

TS:   s.split(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgegkdotz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangdashe.top/Article/details/gtehkhqrfj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.mhx1999.top/Article/details/gtsblbrvko.html

Ruby: s.split(",");  s.split
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxcywxbn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yangfankeji.com/Article/details/gtniwgncki.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gtnddtfxto.html

Py:   ",".join(items)
来源：http://dali.fengsongda.top/Article/details/gtsknnwxeb.html

PHP:  implode(",", $items);
来源：http://dali.yueranfly.top/Article/details/gtpudpepdw.html

JS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtrgybribm.html

TS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gtwvycfqai.html

Java: String.join(",", items)
来源：http://dali.bjfxy.top/Article/details/gtgflhjhhr.html

Go:   strings.Join(items, ",")
来源：http://dali.xuetiantiany.cn/Article/details/gtblmvxgkn.html

Ruby: items.join(",")
来源：http://dali.ivvv.top/Article/details/gtuvsvsjwk.html

C#:   string.Join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmocdoml.html

[E09] 去除所有空白字符
来源：http://dali.zycfv.cn/Article/details/gtbewpjbek.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxinkj.top/Article/details/gtiaavjgcd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sweek.top/Article/details/gtktsqvczn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gtyyhrwmxy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gtkbyvvlpr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yvedp.cn/Article/details/gtcuqrpqfs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpjeasay.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hysaishi.cn/Article/details/gtlvdczccc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gtquawuequ.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hnxiangtu.top/Article/details/gtxxypxwtl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtmgcrdjkd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daria6918.cn/Article/details/gtcwzpnfis.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtjipdxiyw.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtnycoxwmw.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtbypkiyxw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtjlqtjxut.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtrsfdlzcq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gtmyofyhwc.html

[E11] 反转字符串
来源：http://dali.chenlongwang.top/Article/details/gtrvftiowj.html

Py:   s[::-1]
来源：http://dali.yonumen.top/Article/details/gtkmcjztxa.html

PHP:  strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gtqagxswgz.html

JS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtepttlaac.html

TS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtzmulmktb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fzhhl.top/Article/details/gtycfjtbiv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hfpthk.cn/Article/details/gtdswghuoh.html

Ruby: s.reverse
来源：http://dali.ppjwa.cn/Article/details/gthvdeivih.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cheryme.top/Article/details/gtfzynovct.html

[E12] 统计某字符出现次数
来源：http://dali.sufxvd.cn/Article/details/gtpkatrwnw.html

Py:   s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gtclhzsdaj.html

PHP:  substr_count($s, "a");
来源：http://dali.jiagoushi.top/Article/details/gtnuqfvwod.html

JS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtzcdrrnsb.html

TS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gtufnskfgs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cdnleiting.top/Article/details/gtaptaewot.html

Go:   strings.Count(s, "a")
来源：http://dali.guowangkeji.top/Article/details/gtzpvsigqt.html

Ruby: s.count("a")
来源：http://dali.wangdashe.top/Article/details/gtgvbbluns.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sweek.top/Article/details/gtxcetpdnd.html

[E13] 逐字符遍历
来源：http://dali.aibaodan.cn/Article/details/gtxghpgneb.html

Py:   for ch in s: print(ch)
来源：http://dali.zhengqikj.top/Article/details/gtavspxnya.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenzaomai.com/Article/details/gtmvikmwfs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtmwkuowgd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtkbcomcai.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zycfv.cn/Article/details/gtbjvvhajo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenlongwang.top/Article/details/gtlcquxkxa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xziqi.cn/Article/details/gtguwyegtl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cucudq.cn/Article/details/gtmaojwzeb.html

[E14] URL 编码与 Base64
来源：http://dali.cucudq.cn/Article/details/gthkbyeghj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgfzy.top/Article/details/gtpsnwhlnz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtfisvyafu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gtfrwdfslk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guowangkeji.top/Article/details/gtyvngamaz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pycfn.com/Article/details/gtsafgrqkk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hfpthk.cn/Article/details/gtojjjdfdv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gtnfymdipd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigufen.top/Article/details/gthiupbelt.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnimxhmjc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xziqi.cn/Article/details/gtbbdxmhfk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.guannengcc.top/Article/details/gtivdpaiel.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhixingplan.top/Article/details/gtxgiaqpld.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.dashuyun.cn/Article/details/gtwshjuemd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pycfn.com/Article/details/gtycjjdsrl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigufen.top/Article/details/gtwsctishh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guowangkeji.top/Article/details/gtjoodbqsq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sysykeji.top/Article/details/gtbfxlfmhj.html

[E16] 数字千分位
来源：http://dali.sweek.top/Article/details/gtcbiruogq.html

Py:   f"{1234567:,}"
来源：http://dali.316326.xyz/Article/details/gtxuwotflk.html

PHP:  number_format(1234567);
来源：http://dali.nanxinkj.top/Article/details/gthtpeaguu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gtpirqqdqd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gtvklivyum.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hywenlv.cn/Article/details/gtevafgmwr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hfpthk.cn/Article/details/gtxoocxtcy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gzhubu.top/Article/details/gtzgnzqiaj.html

C#:   1234567.ToString("N0")
来源：http://dali.cqqwz.cn/Article/details/gtsieibreo.html

[E17] 首字母大写
来源：http://dali.birdmap.top/Article/details/gtxaizmyeo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jianghu66.top/Article/details/gttjobzdmb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.9152youxi.cn/Article/details/gtfbfwakax.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gtmzehiyyd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gtnmhydksz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pycfn.com/Article/details/gtmnzunnad.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.vqdsnc.cn/Article/details/gtmhqqkzqv.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gtueempwbn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.vqdsnc.cn/Article/details/gtxlufvxqi.html

[E18] 模板占位符替换
来源：http://dali.jlsjyb.cn/Article/details/gtmvlctwad.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhoulong.xyz/Article/details/gtqhgnbmwy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinghuilouyu.cn/Article/details/gtleeuaoxl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtmecfgeec.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosziqlut.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggjlaxxe.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtdvqgmnqz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shangyingyoupin.top/Article/details/gtmzkrnrxj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xziqi.cn/Article/details/gterqbsrwf.html

[E19] 多行文本按行拆分
来源：http://dali.hfpthk.cn/Article/details/gtsjluhakc.html

Py:   s.splitlines()
来源：http://dali.hnxiangtu.top/Article/details/gtwhzdwljz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtarbfhocq.html

JS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gtkxtseqnm.html

TS:   s.split(/\r?\n/)
来源：http://dali.feifeiyinyue.top/Article/details/gtbuxsnlrf.html

Java: s.lines().toList()
来源：http://dali.shuidangran.top/Article/details/gttdhkdeks.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuanzhike.top/Article/details/gttckcdfyx.html

Ruby: s.lines
来源：http://dali.zhongyouzk.top/Article/details/gtvcxddupa.html

C#:   s.Split('\n')
来源：http://dali.feifeiyinyue.top/Article/details/gtssuctxth.html

[E20] 判断字符串是否为空
来源：http://dali.andypj.xyz/Article/details/gtsfawxwac.html

Py:   if not s:
来源：http://dali.aibaodan.cn/Article/details/gtjviolxfn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxuanxn.top/Article/details/gtgllwxcxj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumbtdlsb.html

TS:   if (s === "") {}
来源：http://dali.cucudq.cn/Article/details/gtnofhkeaf.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gtnglnjyoi.html

Go:   if s == "" {}
来源：http://dali.gotoacloud.top/Article/details/gtgzeymcei.html

Ruby: if s.empty?
来源：http://dali.zhengqikj.top/Article/details/gtmvyjftdz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aibaodan.cn/Article/details/gtdluurvgb.html

[E21] 超长截断加省略号
来源：http://dali.xuanzx.com/Article/details/gtpxiadwuk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenlongwang.top/Article/details/gtxwwwnntu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtgetkmxgy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtxvqmojgn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtmxzginnw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtfvaywlro.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.haohaochexian.top/Article/details/gtdbzhoyzd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtniwqcepi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtxtvcpwke.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258888.top/Article/details/gtckuyruta.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jianghu66.top/Article/details/gtcmmlytll.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtuxumucif.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gthzhyrsqb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtqlhysiym.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gtzqiojxth.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.kuanghao11.cn/Article/details/gtyfjudgya.html

Ruby: s.bytesize;  s.length
来源：http://dali.aizwys.cn/Article/details/gtghmhuvhb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gtzvexiztd.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtncbeconj.html

F. 文件与目录
来源：http://dali.hnxiangtu.top/Article/details/gthelumtcx.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtsfqjxdii.html

[F01] 读取整个文件
来源：http://dali.hongshengwenyu.top/Article/details/gtuhzfjetn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjpfdekis.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffoxyygp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258.top/Article/details/gtwgynlybr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtswtpylln.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtmxwloknt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hysaishi.cn/Article/details/gtstcetzgi.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtherxnmyt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtqziniwhb.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gtsyipetxb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gogol.net.cn/Article/details/gtpqygejma.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.kuanghao11.cn/Article/details/gtgeinqpcj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtywdssgqt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gtkwttlfjj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtdrmnkqmj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tanke756.top/Article/details/gthqbochsw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.andypj.xyz/Article/details/gtpfkifgcg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shangyingyoupin.top/Article/details/gtnvdoqwsq.html

[F03] 写入文件（覆盖）
来源：http://dali.sufxvd.cn/Article/details/gtjcpwlaca.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sweek.top/Article/details/gtzybsixtu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtxophgcqd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gttxhedokg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtuhhomkwg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ppjwa.cn/Article/details/gtakdscynk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pengpengdd.cyou/Article/details/gtdhtawlkj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cqqwz.cn/Article/details/gtbgwudsme.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gtnznapfsf.html

[F04] 追加写入文件
来源：http://dali.ybcxt.top/Article/details/gtqjodefgh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtpchjpcoc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.svipenyu.cn/Article/details/gtjkjsfved.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gtrdlocoku.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtxyypgwat.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.0kj1m.cn/Article/details/gtwxdmfcjt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.redwolf501.top/Article/details/gtbmbbfout.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shzxlz.cn/Article/details/gtbmjzqgde.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gtnqfkjrtg.html

[F05] 判断文件或目录是否存在
来源：http://dali.daria6918.cn/Article/details/gtzjtzmuwe.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hysaishi.cn/Article/details/gtvskfdohb.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtwwojjiuf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtgvcdjyej.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtispuphcm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtobbrqzyy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.c1oappe.top/Article/details/gtjeksgaaa.html

Ruby: File.exist?("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtthcruoxo.html

C#:   File.Exists("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtdvnnzcrk.html

[F06] 删除文件
来源：http://dali.sufxvd.cn/Article/details/gtqurhusxx.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtbssrepwo.html

PHP:  unlink("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gttmbbexwu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtkqqwgrpa.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtpcjznomp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtbkhmqryo.html

Go:   os.Remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtszwyqhda.html

Ruby: File.delete("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtarmoojbw.html

C#:   File.Delete("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtwulbxxum.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gtonzruiha.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxuanxn.top/Article/details/gtrdfwcpjo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hysaishi.cn/Article/details/gtxfokmxuk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gtwfdijxij.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtuylqevsg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xinyue.icu/Article/details/gtvnvupels.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gthaazshte.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tanke756.top/Article/details/gtzsutjqlg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhjfwofh.html

[F08] 遍历目录
来源：http://dali.jlsjyb.cn/Article/details/gtghtyelxf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.smart0.xyz/Article/details/gtqhiqjnqt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yanxiufei.cn/Article/details/gtmhomdvrp.html

JS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtnwvgxuik.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtqgqcviuz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gtxfdzjpdc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.havefunace.top/Article/details/gtkbhlbwgk.html

Ruby: Dir.children("dir")
来源：http://dali.smart0.xyz/Article/details/gtunzisnnt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gtgplsnzsi.html

[F09] 获取文件大小
来源：http://dali.redwolf501.top/Article/details/gtqelhdewj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtwlxrjmuw.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtwyylqide.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gteszfecpn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gtipzqnaar.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtmawzkvje.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gaohongyu789.top/Article/details/gthguucorx.html

Ruby: File.size("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtrkaxzlhz.html


<!-- 参考信息 -->