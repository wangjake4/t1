代发 wailian999

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xinyue.icu/Article/details/gtuxleyaey.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.birdmap.top/Article/details/gtnaucbmmr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gotoacloud.top/Article/details/gtjeueueqp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgdpadtq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.birdmap.top/Article/details/gtwakcaaku.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.svipenyu.cn/Article/details/gtdisrfdof.html

[D25] Set 集合去重与交并差
来源：http://dali.guowangkeji.top/Article/details/gtpradhpei.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuxming.cn/Article/details/gtednbaetd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hysaishi.cn/Article/details/gtvssoepka.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxinkj.top/Article/details/gtqdbycbmg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tianlin.xyz/Article/details/gtzubepjum.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.birdmap.top/Article/details/gthdipkmwd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangtech.top/Article/details/gtxgmsqokp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtxiawuuyf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xziqi.cn/Article/details/gtljmawchg.html

[D26] 数组转字符串
来源：http://dali.sweek.top/Article/details/gtaxhecqxk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yangfankeji.com/Article/details/gtkfhxpwgv.html

PHP:  implode(", ", $arr);
来源：http://dali.jyoumei.cn/Article/details/gtkgqqzlyl.html

JS:   arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gtxmkpwajq.html

TS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtyzguwszr.html

Java: String.join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gtgzdhnilo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zycfv.cn/Article/details/gtzokumxpw.html

Ruby: arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gtzowabzqf.html

C#:   string.Join(", ", list)
来源：http://dali.yj202588.top/Article/details/gttifgvpku.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtmrrvaurh.html

E. 字符串处理
来源：http://dali.ppjwa.cn/Article/details/gtqmvsqzqs.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwenxnkt.html

[E01] 拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtydbswdme.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhoulong.xyz/Article/details/gtogvnuzzw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nwbrower.top/Article/details/gtyxdbcahs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtjiokemdv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gtjoqpmxfl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tianlin.xyz/Article/details/gtqozmychd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ppjwa.cn/Article/details/gtqdokmgug.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jianghu66.top/Article/details/gtopqpqunq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtfnbrjlyg.html

[E02] 重复字符串
来源：http://dali.shzxlz.cn/Article/details/gtkpfsgicz.html

Py:   "ab" * 3
来源：http://dali.haohaochexian.top/Article/details/gtkaoozplo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aibaodan.cn/Article/details/gtfxcxpnuo.html

JS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gtcsxcfqbi.html

TS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtxzvxclvh.html

Java: "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtdxeartey.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenlongwang.top/Article/details/gtvminjzbq.html

Ruby: "ab" * 3
来源：http://dali.cdnleiting.top/Article/details/gtdfhumhol.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cucudq.cn/Article/details/gtzqpnaglp.html

[E03] 截取子串
来源：http://dali.hnqzz.top/Article/details/gtaoovuruj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tianlin.xyz/Article/details/gtcjqujqrc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtfbzuskws.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gtofcrtwfh.html

TS:   s.slice(1, 4)
来源：http://dali.redwolf501.top/Article/details/gtnkpjvqiq.html

Java: s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gthybllipm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ybcxt.top/Article/details/gtptkntphc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hongshengwenyu.top/Article/details/gtrecaixll.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxuanxn.top/Article/details/gtrlsrjced.html

[E04] 查找子串位置
来源：http://dali.yuxming.cn/Article/details/gtvhehhqdp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pycfn.com/Article/details/gtlfhyhhjv.html

PHP:  strpos($s, "x");
来源：http://dali.jinqigufen.top/Article/details/gtefjmwzod.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gtlfijuyys.html

TS:   s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gtzlxuzquh.html

Java: s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gtbccjhrje.html

Go:   strings.Index(s, "x")
来源：http://dali.nwbrower.top/Article/details/gtzwdmktip.html

Ruby: s.index("x")
来源：http://dali.tanke756.top/Article/details/gtmaznvxbj.html

C#:   s.IndexOf("x")
来源：http://dali.yvedp.cn/Article/details/gttyqcgtmc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hongshengwenyu.top/Article/details/gtuesklqnr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shuidangran.top/Article/details/gtsfjekqdc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.kuanghao11.cn/Article/details/gtttsheiqa.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtvfqjmtme.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.pycfn.com/Article/details/gtbyooaqrk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gtetcpxiti.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.iojbl.cn/Article/details/gtaluiuizt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zycfv.cn/Article/details/gtraksptdc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtmrzakrdw.html

[E06] 替换子串
来源：http://dali.jqgfzy.top/Article/details/gtvlgyjhhi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gtktxjvcrd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.guowangkeji.top/Article/details/gtmnbyiiee.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtuxvnvjut.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtzysileie.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtsuiwukmn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.wangdashe.top/Article/details/gtfqgugnpq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtggusztqr.html

C#:   s.Replace("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtzylyumpo.html

[E07] 按分隔符拆分
来源：http://dali.hywenlv.cn/Article/details/gtumagdshm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daria6918.cn/Article/details/gtbyxocztc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtgoiqqxde.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ydzc1.top/Article/details/gtaidcoaqp.html

TS:   s.split(",")
来源：http://dali.tanke756.top/Article/details/gtyilmqtti.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gotoacloud.top/Article/details/gtfmlnanvs.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj202588.top/Article/details/gtmchxntsm.html

Ruby: s.split(",");  s.split
来源：http://dali.fengsongda.top/Article/details/gtuauibffc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daxiang520.top/Article/details/gtwbaxvzwz.html

[E08] 数组按分隔符合并
来源：http://dali.hongshengwenyu.top/Article/details/gtytdlidqb.html

Py:   ",".join(items)
来源：http://dali.shzxlz.cn/Article/details/gtodbtlohs.html

PHP:  implode(",", $items);
来源：http://dali.hywenlv.cn/Article/details/gtfunzomkj.html

JS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtkflwruds.html

TS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gtewxvumhy.html

Java: String.join(",", items)
来源：http://dali.yongpay.top/Article/details/gtkmsrkpjk.html

Go:   strings.Join(items, ",")
来源：http://dali.zhixingplan.top/Article/details/gtkzafrnpl.html

Ruby: items.join(",")
来源：http://dali.hnqzz.top/Article/details/gtxkscfgsa.html

C#:   string.Join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gtbqzfumua.html

[E09] 去除所有空白字符
来源：http://dali.ehwqpu.com/Article/details/gtxxelqouk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258888.top/Article/details/gtojrdxptd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jyoumei.cn/Article/details/gtckejreox.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gtmwruaxdu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gtcaocrihj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.daxiang520.top/Article/details/gtbykunfre.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dashuyun.cn/Article/details/gtmdvogdsq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnxiangtu.top/Article/details/gttrzsbngj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sysykeji.top/Article/details/gtkpqvadvd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.kuanghao11.cn/Article/details/gtexuhwyao.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtxpwacbjh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangshuangyany.cn/Article/details/gtwgahurxa.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtzckheeba.html

TS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtocuqtvcb.html

Java: String.format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtutqzsyln.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtjmdaxqvl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtmwkfnplg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.smart0.xyz/Article/details/gtbkkfkgmg.html

[E11] 反转字符串
来源：http://dali.jiagoushi.top/Article/details/gthqevhzzs.html

Py:   s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gthrhqkglg.html

PHP:  strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gtnxlodaxn.html

JS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gthrdfxtuf.html

TS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtpjoomeco.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.svipenyu.cn/Article/details/gtykzeorkc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gtoykulosc.html

Ruby: s.reverse
来源：http://dali.hysaishi.cn/Article/details/gtezmacnzq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gtlqazqgud.html

[E12] 统计某字符出现次数
来源：http://dali.mhx1999.top/Article/details/gtdklmnrye.html

Py:   s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtruteemav.html

PHP:  substr_count($s, "a");
来源：http://dali.cucudq.cn/Article/details/gtbbuqyhnu.html

JS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gtpigjhmgp.html

TS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gtmxjbeava.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.haohaochexian.top/Article/details/gtqjmjcvsz.html

Go:   strings.Count(s, "a")
来源：http://dali.chenlongwang.top/Article/details/gtuajransx.html

Ruby: s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gtjqmzuolm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.havefunace.top/Article/details/gtzegmnzia.html

[E13] 逐字符遍历
来源：http://dali.zhoulong.xyz/Article/details/gtdnwtprma.html

Py:   for ch in s: print(ch)
来源：http://dali.cucudq.cn/Article/details/gtmlttwyll.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxuanxn.top/Article/details/gteemvktzv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gtynbgiwcr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvldhwoh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtnxkfsiuw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ydzc1.top/Article/details/gtagqrlbrp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cqqwz.cn/Article/details/gtcbyakrpn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj202588.top/Article/details/gtanrksskl.html

[E14] URL 编码与 Base64
来源：http://dali.xylfe.cn/Article/details/gtgztevved.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.vqdsnc.cn/Article/details/gtthidfxwf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gzhubu.top/Article/details/gtdkmjmecg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigfzy.top/Article/details/gtpatlmcft.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtlgucflcc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guowangkeji.top/Article/details/gttkraoxup.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hongshengwenyu.top/Article/details/gtmvihjtcu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zycfv.cn/Article/details/gtvtzmvcax.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gthnqdgzpk.html

[E15] HTML 转义 / 反转义
来源：http://dali.hammf.cn/Article/details/gtqownihts.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.iojbl.cn/Article/details/gtfmiaxddv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xziqi.cn/Article/details/gtgaubgkcp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.havefunace.top/Article/details/gtdtflyfwd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj202588.top/Article/details/gtrfmkqbxh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sxryk.cn/Article/details/gtyiqsfgcf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zdqjudy.top/Article/details/gtzbmdpilm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtlkomadvn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yvedp.cn/Article/details/gtijionyqe.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gtrrrhonkv.html

Py:   f"{1234567:,}"
来源：http://dali.chenlongwang.top/Article/details/gtuaojhpez.html

PHP:  number_format(1234567);
来源：http://dali.ivvv.top/Article/details/gtdifopghy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gtzqscxsai.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gtldghjsiq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuxming.cn/Article/details/gtzpgjiyuu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aizwys.cn/Article/details/gtfllkducj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinqigfzy.top/Article/details/gtvmahcijr.html

C#:   1234567.ToString("N0")
来源：http://dali.yj202588.top/Article/details/gtiddsxxjt.html

[E17] 首字母大写
来源：http://dali.dashuyun.cn/Article/details/gtjdzcliec.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ybcxt.top/Article/details/gtyigluhqp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gtmnygebnm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtayzaxqeg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gtwdeyrpyp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ybcxt.top/Article/details/gtboflebvu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtrpgmmryz.html

Ruby: s.capitalize
来源：http://dali.hnxiangtu.top/Article/details/gtyzoifsho.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.andypj.xyz/Article/details/gtdusayfwr.html

[E18] 模板占位符替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmcplnwh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cashguo.top/Article/details/gtszuileww.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tianlin.xyz/Article/details/gtvahdoiad.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gtxtmkhjxg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtldcscwtp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtjusscumz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj202588.top/Article/details/gtviuwiywf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hammf.cn/Article/details/gtjoytyvzb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cheryme.top/Article/details/gtgtqikfpv.html

[E19] 多行文本按行拆分
来源：http://dali.9152youxi.cn/Article/details/gtytboteoa.html

Py:   s.splitlines()
来源：http://dali.dianchejie.cn/Article/details/gtdavtalzm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtyejnonwq.html

JS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gtduaixhya.html

TS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gtnxyeostx.html

Java: s.lines().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtztkcsany.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj202588.top/Article/details/gtgonhdfiw.html

Ruby: s.lines
来源：http://dali.chenlongwang.top/Article/details/gtubvzevtd.html

C#:   s.Split('\n')
来源：http://dali.tanke756.top/Article/details/gtrpkfolny.html

[E20] 判断字符串是否为空
来源：http://dali.zdqjudy.top/Article/details/gteqnvxiai.html

Py:   if not s:
来源：http://dali.zhiwuduotai.top/Article/details/gtggmofxcb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhixingplan.top/Article/details/gtyjxoiqwq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.meibo888.top/Article/details/gtlfhihszp.html

TS:   if (s === "") {}
来源：http://dali.daria6918.cn/Article/details/gtwmfuyvlv.html

Java: if (s.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gtkxqbgzjt.html

Go:   if s == "" {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdywtjlq.html

Ruby: if s.empty?
来源：http://dali.xinyue.icu/Article/details/gtrbolpdkv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangdashe.top/Article/details/gtouddetzg.html

[E21] 超长截断加省略号
来源：http://dali.quarkkingdee.top/Article/details/gtfzrwpfwe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hywenlv.cn/Article/details/gtlcyitxsk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtzspdoihs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtxhjrczvd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtdmnmunds.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtwjrplqcf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.mhx1999.top/Article/details/gtosfvajtt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gtlhwwcrrd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtwdnqdaix.html

[E22] 字节长度与字符长度
来源：http://dali.daria6918.cn/Article/details/gtpwlccclr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jlsjyb.cn/Article/details/gtranvxfvn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtnzbjcbkz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gtdvuxsgkq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gtdkcbmysm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.haohaochexian.top/Article/details/gtwvvwiwto.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.smart0.xyz/Article/details/gtpobezsor.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtwqwxbvnl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtaxzpajyc.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtycdodswj.html

F. 文件与目录
来源：http://dali.svipenyu.cn/Article/details/gtzhjfpolx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtoejormek.html

[F01] 读取整个文件
来源：http://dali.yangfankeji.com/Article/details/gtsjwxdfsb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfnynygnz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhvkmulz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dashuyun.cn/Article/details/gtjavtzpwg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtyujjuvxa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gttsfovmyr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhoulong.xyz/Article/details/gtvfbynltx.html

Ruby: File.read("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtltqitsmu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtjonhinvb.html

[F02] 逐行读取文件
来源：http://dali.jqgfzy.top/Article/details/gttnskmrfv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pengpengdd.cyou/Article/details/gtithjabqz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.kuanghao11.cn/Article/details/gtcwevedrb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtdyndyobk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gtklrgrlks.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbiockbmq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yanxiufei.cn/Article/details/gtitkaytqo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xylfe.cn/Article/details/gtkettweks.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dianchejie.cn/Article/details/gtprunuumy.html

[F03] 写入文件（覆盖）
来源：http://dali.gogol.net.cn/Article/details/gtqdvomckw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtgncsnxur.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtgjcchkom.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cucudq.cn/Article/details/gtwjufvswk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cucudq.cn/Article/details/gtbuuhxkxg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gtusfnbftx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenlongwang.top/Article/details/gtlvdfbncq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jiagoushi.top/Article/details/gtuomdqduo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gtuvunostk.html

[F04] 追加写入文件
来源：http://dali.yanxiufei.cn/Article/details/gtxrtbmgbl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.svipenyu.cn/Article/details/gtbmzdsowx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pycfn.com/Article/details/gtckxtzlcm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gtlgksvfor.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtlgrdwkcd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.quarkkingdee.top/Article/details/gtfulmfxmh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ivvv.top/Article/details/gtnlzxcwcf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.smart0.xyz/Article/details/gtwjrzbdpd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhiwuduotai.top/Article/details/gtnwoxzhea.html

[F05] 判断文件或目录是否存在
来源：http://dali.kuanghao11.cn/Article/details/gthvgaeyme.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxuanxn.top/Article/details/gtshbyguuw.html

PHP:  file_exists("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtpqguyshx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtpdantezt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxvjjdjr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gthfpeufkp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pengpengdd.cyou/Article/details/gtphcdwpoj.html

Ruby: File.exist?("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtuchttgel.html

C#:   File.Exists("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtxgtbcdan.html

[F06] 删除文件
来源：http://dali.cheryme.top/Article/details/gtcsnhllzq.html

Py:   os.remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtuigdsalv.html

PHP:  unlink("a.txt");
来源：http://dali.yongpay.top/Article/details/gtvunpyroa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtjsloneok.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtyqsndsko.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtpwvbwsrs.html

Go:   os.Remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtjctqzkyp.html

Ruby: File.delete("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtgbbjkujn.html

C#:   File.Delete("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtyzzgalck.html

[F07] 创建目录（含多级）
来源：http://dali.sysykeji.top/Article/details/gtxhxwsrcv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwlwxwxs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.andypj.xyz/Article/details/gthnvgsfda.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gttbtnjadi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtghggyrwh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.316326.xyz/Article/details/gttvxezbop.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.svipenyu.cn/Article/details/gthfnrtlsz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gtvxrsqnsn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cashguo.top/Article/details/gtoqlxivtl.html

[F08] 遍历目录
来源：http://dali.dianchejie.cn/Article/details/gtfigkjaih.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.dashuyun.cn/Article/details/gtedxaaehw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ppjwa.cn/Article/details/gtfsskpdqd.html

JS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtfexdwquv.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtiwjslzbk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gtssvkrmcn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.haohaochexian.top/Article/details/gtxdmmwwqz.html

Ruby: Dir.children("dir")
来源：http://dali.daxiang520.top/Article/details/gtwwpjeqkn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gzhubu.top/Article/details/gtbuqvddqb.html


<!-- 参考信息 -->