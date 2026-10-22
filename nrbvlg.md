代发 wailian999

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gt2zejuaxqe.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.havefunace.top/Article/details/gt2ziglamei.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gt2osaflrel.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sufxvd.cn/Article/details/gt2fwiothgy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aizwys.cn/Article/details/gt2bfsrjhyg.html

[D24] 字典 / Map 基本操作
来源：http://dali.fengsongda.top/Article/details/gt2wasxgotv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.havefunace.top/Article/details/gt2tqbmlbbi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cqqwz.cn/Article/details/gt2zluwtffw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuanzhike.top/Article/details/gt2gsmnmhrb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2cjwzmjpj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yueranfly.top/Article/details/gt2pcoirbzd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.mhx1999.top/Article/details/gt2vuofqawv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhoulong.xyz/Article/details/gt2ckvhyojs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.vqdsnc.cn/Article/details/gt2eeprfcdj.html

[D25] Set 集合去重与交并差
来源：http://dali.daria6918.cn/Article/details/gt2ftzkppef.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xziqi.cn/Article/details/gt2tataqfdo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shuidangran.top/Article/details/gt2iuewerey.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daria6918.cn/Article/details/gt2yqabyktz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.0kj1m.cn/Article/details/gt2axzwkpzm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ybcxt.top/Article/details/gt2etnynskt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnqzz.top/Article/details/gt2ejuizbtl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pycfn.com/Article/details/gt2xzlrlzhg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zpfwlwjz.html

[D26] 数组转字符串
来源：http://dali.sweek.top/Article/details/gt2bawvxzdc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxuanxn.top/Article/details/gt2pzpcxwer.html

PHP:  implode(", ", $arr);
来源：http://dali.jyoumei.cn/Article/details/gt2noxilltb.html

JS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gt2yoascxzh.html

TS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gt2oqcynfen.html

Java: String.join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gt2zqerarzq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yueranfly.top/Article/details/gt2bxdsfces.html

Ruby: arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gt2uhypikaf.html

C#:   string.Join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gt2cvzfkrrd.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2evkxlqji.html

E. 字符串处理
来源：http://dali.gzhubu.top/Article/details/gt2dbbqyhci.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2abaiefqs.html

[E01] 拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gt2fpbozwgq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pzjltqhg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.birdmap.top/Article/details/gt2mqzhuloc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gt2xotcdhdq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gt2wjgwxhqk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuxming.cn/Article/details/gt2ytpnofgf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tanke756.top/Article/details/gt2rjzllxil.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nanxinkj.top/Article/details/gt2uromxpzc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gt2hfmevltt.html

[E02] 重复字符串
来源：http://dali.iojbl.cn/Article/details/gt2scqmbygy.html

Py:   "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gt2uknrixul.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shuidangran.top/Article/details/gt2yorqkcch.html

JS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jdhghqgb.html

TS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2xrsvjvjc.html

Java: "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xfjdtnsi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgfzy.top/Article/details/gt2mydbuzpe.html

Ruby: "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gt2mrwhygwm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cashguo.top/Article/details/gt2ebacplgx.html

[E03] 截取子串
来源：http://dali.bjfxy.top/Article/details/gt2rzaaqfdd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xylfe.cn/Article/details/gt2ivjvhzjv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2brkbrvrm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gt2zxmvruar.html

TS:   s.slice(1, 4)
来源：http://dali.xylfe.cn/Article/details/gt2nyblffpt.html

Java: s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gt2bcbtjdjx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gt2jyqcipie.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gaohongyu789.top/Article/details/gt2nbptnaan.html

C#:   s.Substring(1, 3)
来源：http://dali.bjfxy.top/Article/details/gt2rxnfwria.html

[E04] 查找子串位置
来源：http://dali.cheryme.top/Article/details/gt2myccryri.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hammf.cn/Article/details/gt2bwwjmwme.html

PHP:  strpos($s, "x");
来源：http://dali.cashguo.top/Article/details/gt2atrqknyl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.iojbl.cn/Article/details/gt2agjqmfid.html

TS:   s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gt2fbgmlxwn.html

Java: s.indexOf("x")
来源：http://dali.jianghu66.top/Article/details/gt2mjierkob.html

Go:   strings.Index(s, "x")
来源：http://dali.jlsjyb.cn/Article/details/gt2yjbisibg.html

Ruby: s.index("x")
来源：http://dali.ivvv.top/Article/details/gt2yffuikre.html

C#:   s.IndexOf("x")
来源：http://dali.yuxming.cn/Article/details/gt2qrhkvjyk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhoulong.xyz/Article/details/gt2sbasitrp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dashuyun.cn/Article/details/gt2yzinphgn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnxiangtu.top/Article/details/gt2yjsxssgl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gt2uxrfmeab.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.bjfxy.top/Article/details/gt2yqajzpgu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gt2hzycqrrc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ppjwa.cn/Article/details/gt2nernazsi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yangfankeji.com/Article/details/gt2jdhfhfub.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fxqaqrkb.html

[E06] 替换子串
来源：http://dali.yangfankeji.com/Article/details/gt2xmuirfss.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gt2cfyzbhxk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2zyzkbwkx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2dkkkerav.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2tkssnniu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2mjpsyrmc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gt2zahdpbbr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cashguo.top/Article/details/gt2xlzqosqy.html

C#:   s.Replace("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2jzhoutej.html

[E07] 按分隔符拆分
来源：http://dali.yueranfly.top/Article/details/gt2wtmrtpzi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.c1oappe.top/Article/details/gt2hkaicwli.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangdashe.top/Article/details/gt2rlsdurdi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jyoumei.cn/Article/details/gt2pgtjtout.html

TS:   s.split(",")
来源：http://dali.shzxlz.cn/Article/details/gt2gtkurxvt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ivvv.top/Article/details/gt2oczxskto.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dianchejie.cn/Article/details/gt2drjgmbmy.html

Ruby: s.split(",");  s.split
来源：http://dali.nanxuanxn.top/Article/details/gt2frnxazdn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jyoumei.cn/Article/details/gt2kfjqqdwb.html

[E08] 数组按分隔符合并
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gybljejv.html

Py:   ",".join(items)
来源：http://dali.gzhubu.top/Article/details/gt2ocouzich.html

PHP:  implode(",", $items);
来源：http://dali.zhiwuduotai.top/Article/details/gt2azkeidvc.html

JS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gt2sqqukhfb.html

TS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gt2pgrnihrw.html

Java: String.join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ktgtwhvm.html

Go:   strings.Join(items, ",")
来源：http://dali.zdqjudy.top/Article/details/gt2lclabtqr.html

Ruby: items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gt2kpapzwvs.html

C#:   string.Join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rsiwvoxe.html

[E09] 去除所有空白字符
来源：http://dali.yj202588.top/Article/details/gt2rvptmdfw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dianchejie.cn/Article/details/gt2tuflencj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2kmopwxre.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhixingplan.top/Article/details/gt2ikmavkou.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gt2qjnfsvrh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gt2ungfgebp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenlongwang.top/Article/details/gt2wqspdbps.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yonumen.top/Article/details/gt2yrbuegki.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gt2bvlphyoq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hysaishi.cn/Article/details/gt2ukeiqywt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gt2bnhtbikb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.aizwys.cn/Article/details/gt2qvkopzic.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gt2ovaatahu.html

TS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gt2ymqslcpg.html

Java: String.format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gt2cplrxidi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2swtkuxxp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gt2rtxvbgmz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yueranfly.top/Article/details/gt2rnmwpbdv.html

[E11] 反转字符串
来源：http://dali.nanxinkj.top/Article/details/gt2wcsgxbmy.html

Py:   s[::-1]
来源：http://dali.hnqzz.top/Article/details/gt2rnigfngg.html

PHP:  strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gt2lzvulmix.html

JS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gt2tlscunvq.html

TS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gt2plzvkkvd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xziqi.cn/Article/details/gt2rcjpcmtc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qfqhstqs.html

Ruby: s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tklnyoba.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gt2yohkvypv.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258888.top/Article/details/gt2qvbghjtk.html

Py:   s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2aeoxfett.html

PHP:  substr_count($s, "a");
来源：http://dali.snrcjt.cn/Article/details/gt2aarosjvd.html

JS:   s.split("a").length - 1
来源：http://dali.quarkkingdee.top/Article/details/gt2zgjdqmjg.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigufen.top/Article/details/gt2onopsouw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xziqi.cn/Article/details/gt2btwfhzun.html

Go:   strings.Count(s, "a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gcgesiao.html

Ruby: s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gt2lciszsqj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hnqzz.top/Article/details/gt2hlwklthm.html

[E13] 逐字符遍历
来源：http://dali.ybcxt.top/Article/details/gt2hhvnbhke.html

Py:   for ch in s: print(ch)
来源：http://dali.dashuyun.cn/Article/details/gt2rkpgqwyt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cdnleiting.top/Article/details/gt2sxolofow.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gt2dumjrfjy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gt2eewajfwv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yongpay.top/Article/details/gt2cwbokzpw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuanzhike.top/Article/details/gt2rsjyecqg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mwsridws.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gogol.net.cn/Article/details/gt2gkdhumzr.html

[E14] URL 编码与 Base64
来源：http://dali.smart0.xyz/Article/details/gt2jspbzsje.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangdashe.top/Article/details/gt2bziqvuym.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tianlin.xyz/Article/details/gt2chikawkk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sxryk.cn/Article/details/gt2ewirciak.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2krnkxnmy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gotoacloud.top/Article/details/gt2grjjsewh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ieejzuhe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.mhx1999.top/Article/details/gt2lmtyiabt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cnwafrdp.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hubgzfwt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wmchjhpr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2eypabzuy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tanke756.top/Article/details/gt2aulfzlzb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tianlin.xyz/Article/details/gt2djstyhtz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.havefunace.top/Article/details/gt2amblswym.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uwcxndji.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ygqxpvxb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gt2asalvjut.html

[E16] 数字千分位
来源：http://dali.tianlin.xyz/Article/details/gt2rpjbpofs.html

Py:   f"{1234567:,}"
来源：http://dali.jlsjyb.cn/Article/details/gt2smzcgkde.html

PHP:  number_format(1234567);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qwwlpupb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gt2umqrqdru.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gt2tjhuvdxl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gt2mhpassem.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cdnleiting.top/Article/details/gt2iwuczfbr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pycfn.com/Article/details/gt2hxunzbaf.html

C#:   1234567.ToString("N0")
来源：http://dali.sxryk.cn/Article/details/gt2uopxtfmk.html

[E17] 首字母大写
来源：http://dali.ehwqpu.com/Article/details/gt2uicxvubv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shangyingyoupin.top/Article/details/gt2iladafuv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fzhhl.top/Article/details/gt2jytczrwd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gt2drvlrxck.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gt2yxaxfqrp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.redwolf501.top/Article/details/gt2nhjbvxmy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tanke756.top/Article/details/gt2dpmvrrla.html

Ruby: s.capitalize
来源：http://dali.gaohongyu789.top/Article/details/gt2llthrfbz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.redwolf501.top/Article/details/gt2jdjuvwvp.html

[E18] 模板占位符替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2tuivkknn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cheryme.top/Article/details/gt2hlfzjfzd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnxiangtu.top/Article/details/gt2zenhqhxh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gt2qiznqfyg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gt2rdxmoahp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nonpzmkw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xylfe.cn/Article/details/gt2rivxdofp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cpzxczxf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zycfv.cn/Article/details/gt2qbqkevke.html

[E19] 多行文本按行拆分
来源：http://dali.gzhubu.top/Article/details/gt2cchnfhxd.html

Py:   s.splitlines()
来源：http://dali.chenzaomai.com/Article/details/gt2ulazhdwk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hammf.cn/Article/details/gt2ivjzduhk.html

JS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gt2onzwctsq.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gt2crgcaqfr.html

Java: s.lines().toList()
来源：http://dali.ehwqpu.com/Article/details/gt2dwfpxikj.html

Go:   strings.Split(s, "\n")
来源：http://dali.snrcjt.cn/Article/details/gt2imljokvh.html

Ruby: s.lines
来源：http://dali.yanxiufei.cn/Article/details/gt2sjeepwhs.html

C#:   s.Split('\n')
来源：http://dali.hnqzz.top/Article/details/gt2xkeqsbds.html

[E20] 判断字符串是否为空
来源：http://dali.yuxming.cn/Article/details/gt2mzwuemxh.html

Py:   if not s:
来源：http://dali.wangshuangyany.cn/Article/details/gt2omawcbwt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhoulong.xyz/Article/details/gt2edfdauss.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sysykeji.top/Article/details/gt2rfljksni.html

TS:   if (s === "") {}
来源：http://dali.jlsjyb.cn/Article/details/gt2onbdfdse.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mkjkhcjq.html

Go:   if s == "" {}
来源：http://dali.xylfe.cn/Article/details/gt2zbvusebs.html

Ruby: if s.empty?
来源：http://dali.yangfankeji.com/Article/details/gt2crrunwkf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gt2eabjugrh.html

[E21] 超长截断加省略号
来源：http://dali.guowangkeji.top/Article/details/gt2xysonulx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yongpay.top/Article/details/gt2lolcamqq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gt2svglsfmx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2vaqjmand.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zuwtinjt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gt2vjjdukrs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gt2flionobr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lshvmvzg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2frjkzgge.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigfzy.top/Article/details/gt2gdizkkgm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gedvrbnb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gt2uhppzkoq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gogol.net.cn/Article/details/gt2fdfxvzmx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gt2ntxtgtcn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jyoumei.cn/Article/details/gt2pwtsgloe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258.top/Article/details/gt2slllcpsc.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gt2dgaiaivj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tianlin.xyz/Article/details/gt2nnkfkcfy.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2zuczholl.html

F. 文件与目录
来源：http://dali.jyoumei.cn/Article/details/gt2ugzdkhnk.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2tbxpqvrl.html

[F01] 读取整个文件
来源：http://dali.chenzaomai.com/Article/details/gt2hmoekwso.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.andypj.xyz/Article/details/gt2vsilrfdc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2rzvqohrb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xinyue.icu/Article/details/gt2kzqneqhg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gt2rmesygsd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gt2yvrbzhoy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.svipenyu.cn/Article/details/gt2ftxwaewa.html

Ruby: File.read("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2atrteisa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2ieovhrfd.html

[F02] 逐行读取文件
来源：http://dali.cucudq.cn/Article/details/gt2dawpkkyi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ydzc1.top/Article/details/gt2djvttnzr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.c1oappe.top/Article/details/gt2zfpkmazv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gt2jkibzuog.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gt2tefeipwa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gt2usjyqiur.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xuanzx.com/Article/details/gt2zfkoirxr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxuanxn.top/Article/details/gt2aiyhzfbh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhengqikj.top/Article/details/gt2vreibkoe.html

[F03] 写入文件（覆盖）
来源：http://dali.ppjwa.cn/Article/details/gt2rpwimrwt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yonumen.top/Article/details/gt2jbbwinzm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gt2ejzygrpg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gt2jopqbzkp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gt2wapodkpd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gzhubu.top/Article/details/gt2jkavnlba.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nzrxpnxr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258.top/Article/details/gt2qrdzfwwj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gt2nbaekwqf.html

[F04] 追加写入文件
来源：http://dali.xylfe.cn/Article/details/gt2gznmwzwf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2uaoedudd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ehwqpu.com/Article/details/gt2khoiqcrm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2nityfrlk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gt2jmbrwqpr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sweek.top/Article/details/gt2tjuouvtl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pycfn.com/Article/details/gt2xhdycyqc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj202588.top/Article/details/gt2eudelrnp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guowangkeji.top/Article/details/gt2utcqbyqr.html

[F05] 判断文件或目录是否存在
来源：http://dali.guowangkeji.top/Article/details/gt2abpddamn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dashuyun.cn/Article/details/gt2mzfbviqi.html

PHP:  file_exists("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2dqdaneut.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2hjxgsjgy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2bhcmsajw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2dwsbmljq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgufenzy.top/Article/details/gt2evafirwc.html

Ruby: File.exist?("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2dyukapwh.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2kagrqejx.html

[F06] 删除文件
来源：http://dali.gogol.net.cn/Article/details/gt2xhayxoky.html

Py:   os.remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2uotfsvwm.html

PHP:  unlink("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2vhqsypqn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2ywgvpncr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2cjlmftbv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gt2qmdghdif.html

Go:   os.Remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bnpalhzy.html

Ruby: File.delete("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2pwgtgfbc.html

C#:   File.Delete("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2cdjccwiq.html

[F07] 创建目录（含多级）
来源：http://dali.chenzaomai.com/Article/details/gt2ssdqfrkj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tldzybif.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigfzy.top/Article/details/gt2hoefnhqh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gt2suuxkptc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gt2jwprqtuk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnqzz.top/Article/details/gt2opxkzhek.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xylfe.cn/Article/details/gt2kdufwoyz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhixingplan.top/Article/details/gt2xifroeix.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenlongwang.top/Article/details/gt2uhesiieg.html

[F08] 遍历目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sccrmlpl.html


<!-- 参考信息 -->