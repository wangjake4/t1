代发 wailian999

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cashguo.top/Article/details/gt2vwivigwq.html

[D20] 统计每个元素出现次数
来源：http://dali.hfpthk.cn/Article/details/gt2vzydzqfa.html

Py:   Counter(arr)
来源：http://dali.wangdashe.top/Article/details/gt2czagyvso.html

PHP:  array_count_values($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2mbrvljiz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gt2deutfrpj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gt2kmbnqlup.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxuanxn.top/Article/details/gt2bjnsikcm.html

Go:   // 手写 map[T]int
来源：http://dali.jlsjyb.cn/Article/details/gt2byhtcvwi.html

Ruby: arr.tally
来源：http://dali.cucudq.cn/Article/details/gt2lvixfdzq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cxuumshn.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gt2xcqmjnvi.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrrijvv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.iojbl.cn/Article/details/gt2isftagtq.html

JS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2tqaazfsx.html

TS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gt2cfhjhxoi.html

Java: list.contains(x)
来源：http://dali.hammf.cn/Article/details/gt2wmkyhgri.html

Go:   slices.Contains(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2bownuyam.html

Ruby: arr.include?(x)
来源：http://dali.cqqwz.cn/Article/details/gt2laplrtlk.html

C#:   list.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gt2jwhhokjy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2feqamamj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gzhubu.top/Article/details/gt2fzozaujz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigfzy.top/Article/details/gt2nhylchbs.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywumzjcq.html

TS:   [...arr];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fwvevodq.html

Java: new ArrayList<>(list);
来源：http://dali.daxiang520.top/Article/details/gt2yydftbgy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.andypj.xyz/Article/details/gt2jrpiilix.html

Ruby: arr.dup;  arr.clone
来源：http://dali.snrcjt.cn/Article/details/gt2stfzpapx.html

C#:   new List<int>(list);
来源：http://dali.svipenyu.cn/Article/details/gt2wvqyphgx.html

[D23] reduce 累积计算
来源：http://dali.xuetiantiany.cn/Article/details/gt2kjsccllb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2qsxavbyr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2btxdkpqp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gt2ybfmqgfj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2otntuflz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.feifeiyinyue.top/Article/details/gt2skicayxv.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2grwdyhoj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sweek.top/Article/details/gt2pvvnjxey.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qwqduhgw.html

[D24] 字典 / Map 基本操作
来源：http://dali.aibaodan.cn/Article/details/gt2cbrofmon.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj202588.top/Article/details/gt2rdrrukej.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hysaishi.cn/Article/details/gt2kuyieztt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nbguhorf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2qnjvmewy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sxryk.cn/Article/details/gt2svmnhxww.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pycfn.com/Article/details/gt2ozcihxhk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigufen.top/Article/details/gt2knpcxqbx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tanke756.top/Article/details/gt2hhomidtd.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxinkj.top/Article/details/gt2fvvzfqfv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhixingplan.top/Article/details/gt2yoosfsqk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258.top/Article/details/gt2qfogxdup.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jianghu66.top/Article/details/gt2lwgatcgu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tian-w.cn/Article/details/gt2zkeuodcf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.0kj1m.cn/Article/details/gt2kqcpbryx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258.top/Article/details/gt2ligfgsxm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guowangkeji.top/Article/details/gt2gvrhrbva.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hysaishi.cn/Article/details/gt2mpfwpbav.html

[D26] 数组转字符串
来源：http://dali.yj202588.top/Article/details/gt2abkafvcv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yangfankeji.com/Article/details/gt2sawezumc.html

PHP:  implode(", ", $arr);
来源：http://dali.sxryk.cn/Article/details/gt2uvbbnhrd.html

JS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gt2oyabncyy.html

TS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gt2indcztzh.html

Java: String.join(", ", list)
来源：http://dali.cashguo.top/Article/details/gt2hpodojet.html

Go:   strings.Join(strs, ", ")
来源：http://dali.fzhhl.top/Article/details/gt2grtumthf.html

Ruby: arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gt2urmgycho.html

C#:   string.Join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gt2bbaaqdxd.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2wcbhbnac.html

E. 字符串处理
来源：http://dali.aizwys.cn/Article/details/gt2qtgannzl.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2mtftiapd.html

[E01] 拼接字符串
来源：http://dali.cashguo.top/Article/details/gt2acrnuich.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gotoacloud.top/Article/details/gt2llialoit.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yangfankeji.com/Article/details/gt2wbllnbfw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uzrsxuao.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gt2xmzuwtxb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.9152youxi.cn/Article/details/gt2rbgqojkp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cheryme.top/Article/details/gt2cibkmteo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj20258.top/Article/details/gt2psjfdilz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2cuxkkwlq.html

[E02] 重复字符串
来源：http://dali.jyoumei.cn/Article/details/gt2fwzppayq.html

Py:   "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gt2rpfnzqnj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xowdhpqc.html

JS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gt2qiutfyrv.html

TS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gt2sfqcekwv.html

Java: "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gt2qqkgyvlh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.redwolf501.top/Article/details/gt2lixontgu.html

Ruby: "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gt2oumwcgae.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnqzz.top/Article/details/gt2ynsajlnc.html

[E03] 截取子串
来源：http://dali.tanke756.top/Article/details/gt2utnlcssb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jwzvayfc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cpmeodjj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gt2fvtbowln.html

TS:   s.slice(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gt2vvvknilu.html

Java: s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gt2wnrlyzfb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.c1oappe.top/Article/details/gt2nqbimiud.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.guowangkeji.top/Article/details/gt2vdocetai.html

C#:   s.Substring(1, 3)
来源：http://dali.tian-w.cn/Article/details/gt2tnjpeett.html

[E04] 查找子串位置
来源：http://dali.316326.xyz/Article/details/gt2nppstiyd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sxryk.cn/Article/details/gt2wpeahcpx.html

PHP:  strpos($s, "x");
来源：http://dali.zhoulong.xyz/Article/details/gt2gkpeohzn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxuanxn.top/Article/details/gt2hnarbmpk.html

TS:   s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gt2fyvyzuoy.html

Java: s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gt2xghuznto.html

Go:   strings.Index(s, "x")
来源：http://dali.zdqjudy.top/Article/details/gt2qodkhxra.html

Ruby: s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gt2fhcbbitb.html

C#:   s.IndexOf("x")
来源：http://dali.shuidangran.top/Article/details/gt2gzbdzawv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ytzrvwip.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2izfltejd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ybcxt.top/Article/details/gt2lfpoegjw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gt2gailbpcx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cdnleiting.top/Article/details/gt2xhwoyrqu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gt2zmjtqrmb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgfzy.top/Article/details/gt2yfcshknv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aizwys.cn/Article/details/gt2ubtvepfn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ybcxt.top/Article/details/gt2sswfyhdo.html

[E06] 替换子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zarxpnca.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gt2evytajhv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sysykeji.top/Article/details/gt2oaadcvau.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2ifbsqmuv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2ffuwbomy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wpzngfxu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cucudq.cn/Article/details/gt2ydjrncji.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2rtjylyaa.html

C#:   s.Replace("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2prmdfgvl.html

[E07] 按分隔符拆分
来源：http://dali.hnqzz.top/Article/details/gt2bumplquf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.guannengcc.top/Article/details/gt2lsqjnglb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zycfv.cn/Article/details/gt2aqnsgvne.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tian-w.cn/Article/details/gt2cypnaoyn.html

TS:   s.split(",")
来源：http://dali.yuxming.cn/Article/details/gt2vrlkcgll.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ietlqcvk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hywenlv.cn/Article/details/gt2yunmpnmt.html

Ruby: s.split(",");  s.split
来源：http://dali.cheryme.top/Article/details/gt2gxydibrk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnxiangtu.top/Article/details/gt2hthphiyd.html

[E08] 数组按分隔符合并
来源：http://dali.aibaodan.cn/Article/details/gt2ebcmmere.html

Py:   ",".join(items)
来源：http://dali.ivvv.top/Article/details/gt2ajmddchs.html

PHP:  implode(",", $items);
来源：http://dali.tian-w.cn/Article/details/gt2vdsmfbot.html

JS:   items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gt2navlttuu.html

TS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qbvvvhyn.html

Java: String.join(",", items)
来源：http://dali.andypj.xyz/Article/details/gt2dobzshed.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpkrqrm.html

Ruby: items.join(",")
来源：http://dali.wangdashe.top/Article/details/gt2tfmfezoa.html

C#:   string.Join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gt2nmcxngcz.html

[E09] 去除所有空白字符
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uhpiocwc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thqrhtgb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.316326.xyz/Article/details/gt2ccrulvsx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.vqdsnc.cn/Article/details/gt2hyatnrcg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gt2hatnqtsg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gt2zqxvjarb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zdqjudy.top/Article/details/gt2nvukcraz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fvavbxnx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gt2kqgdhrrv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258.top/Article/details/gt2asbgghbx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258888.top/Article/details/gt2djgimhrt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sysykeji.top/Article/details/gt2voxsndfw.html

JS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2cpicnirr.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gt2oezvozou.html

Java: String.format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gt2nwpvupum.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gt2exbhgbqf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gt2yvyiiiaa.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigfzy.top/Article/details/gt2fuizswjr.html

[E11] 反转字符串
来源：http://dali.xylfe.cn/Article/details/gt2ofltzmxh.html

Py:   s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gt2xyuqmhyf.html

PHP:  strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xixfeqdf.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2potzgezi.html

TS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gt2thzkwgzz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yonumen.top/Article/details/gt2gertlxnu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yueranfly.top/Article/details/gt2wnhgaxca.html

Ruby: s.reverse
来源：http://dali.shzxlz.cn/Article/details/gt2dvgnypej.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gt2rcpxwwfn.html

[E12] 统计某字符出现次数
来源：http://dali.nwbrower.top/Article/details/gt2cvtxoymq.html

Py:   s.count("a")
来源：http://dali.ybcxt.top/Article/details/gt2secsafsj.html

PHP:  substr_count($s, "a");
来源：http://dali.yangfankeji.com/Article/details/gt2hbyveknf.html

JS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gt2ooycjtma.html

TS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gt2msovrfma.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2djgdectx.html

Go:   strings.Count(s, "a")
来源：http://dali.ivvv.top/Article/details/gt2nbzdmaef.html

Ruby: s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gt2opcczlxx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hnqzz.top/Article/details/gt2oqswtqgd.html

[E13] 逐字符遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2lkogaafe.html

Py:   for ch in s: print(ch)
来源：http://dali.iojbl.cn/Article/details/gt2tufnmwew.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cheryme.top/Article/details/gt2wzgwcxqf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gt2tfvvivug.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gt2mlpypxqd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sysykeji.top/Article/details/gt2pedlgbdd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.c1oappe.top/Article/details/gt2dmnorfmz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.birdmap.top/Article/details/gt2pyrfykap.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxinkj.top/Article/details/gt2mjgimlzu.html

[E14] URL 编码与 Base64
来源：http://dali.aibaodan.cn/Article/details/gt2zctuesln.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shuidangran.top/Article/details/gt2wlfmhyjs.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jiagoushi.top/Article/details/gt2atmotavj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtxaiof.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sxryk.cn/Article/details/gt2cfdncvhk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cahzoujw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangdashe.top/Article/details/gt2xgrmkzst.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vdaveesm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wehssqhb.html

[E15] HTML 转义 / 反转义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jbuknjeg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhixingplan.top/Article/details/gt2byvyjher.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2uymjbwsx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cqqwz.cn/Article/details/gt2ovvnlwso.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhiwuduotai.top/Article/details/gt2ndvfkcyg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuetiantiany.cn/Article/details/gt2ovwbgoty.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.smart0.xyz/Article/details/gt2afucedlq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yongpay.top/Article/details/gt2yrmqokxy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuanzhike.top/Article/details/gt2myujbgfq.html

[E16] 数字千分位
来源：http://dali.wangdashe.top/Article/details/gt2mkjxmken.html

Py:   f"{1234567:,}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2eijpbuvb.html

PHP:  number_format(1234567);
来源：http://dali.sysykeji.top/Article/details/gt2ojrrxnpv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gt2yjtbygny.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gt2bgiejdoi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gt2yrytpmdc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shuidangran.top/Article/details/gt2ydvhhvnx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenlongwang.top/Article/details/gt2drgvmtew.html

C#:   1234567.ToString("N0")
来源：http://dali.cdnleiting.top/Article/details/gt2xwvbmmyz.html

[E17] 首字母大写
来源：http://dali.zhoulong.xyz/Article/details/gt2pikrawwv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gt2rogqparw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ciyepmsi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gt2zdufvafa.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gt2czmbuhot.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.mhx1999.top/Article/details/gt2fyaxetjt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.svipenyu.cn/Article/details/gt2mblwbibs.html

Ruby: s.capitalize
来源：http://dali.zycfv.cn/Article/details/gt2cfhpkszu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guannengcc.top/Article/details/gt2syznyjfj.html

[E18] 模板占位符替换
来源：http://dali.yj20258888.top/Article/details/gt2mkkuzpkg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hongshengwenyu.top/Article/details/gt2sitycnut.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cheryme.top/Article/details/gt2jlbjkwdk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gt2qjfsqdsb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kwephrag.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gtujbrky.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gt2eiaotjro.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxuanxn.top/Article/details/gt2pcpjaktz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.c1oappe.top/Article/details/gt2xlkaxsyt.html

[E19] 多行文本按行拆分
来源：http://dali.jlsjyb.cn/Article/details/gt2feyubcwh.html

Py:   s.splitlines()
来源：http://dali.hywenlv.cn/Article/details/gt2venwtzbg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2ntlsjlsp.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gt2cyfppqmj.html

TS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gt2daphgwhf.html

Java: s.lines().toList()
来源：http://dali.nanxinkj.top/Article/details/gt2mhvqesqn.html

Go:   strings.Split(s, "\n")
来源：http://dali.xinyue.icu/Article/details/gt2vnezpdua.html

Ruby: s.lines
来源：http://dali.nanxinkj.top/Article/details/gt2gwbbdbrx.html

C#:   s.Split('\n')
来源：http://dali.zhixingplan.top/Article/details/gt2vtdzvfhr.html

[E20] 判断字符串是否为空
来源：http://dali.c1oappe.top/Article/details/gt2ovrqfagf.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2gkslgjjz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhoulong.xyz/Article/details/gt2dkjrvdsu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2jpuzqpsu.html

TS:   if (s === "") {}
来源：http://dali.birdmap.top/Article/details/gt2npixqeys.html

Java: if (s.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gt2qphwlzzo.html

Go:   if s == "" {}
来源：http://dali.xylfe.cn/Article/details/gt2kjbogdwo.html

Ruby: if s.empty?
来源：http://dali.zhoulong.xyz/Article/details/gt2ulwcfzct.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuxming.cn/Article/details/gt2iocnmdcm.html

[E21] 超长截断加省略号
来源：http://dali.chenjidiqi.icu/Article/details/gt2gzkfpead.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sufxvd.cn/Article/details/gt2wtpkeegt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yongpay.top/Article/details/gt2zztjfgoj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gt2movhraxi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2vtpqljdm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2ophrjdfp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ehwqpu.com/Article/details/gt2nczqmkwo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gt2ahsfbvbf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gt2yavbqjqz.html

[E22] 字节长度与字符长度
来源：http://dali.cdnleiting.top/Article/details/gt2mifltohs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ydzc1.top/Article/details/gt2taasgsjd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gt2kofkvkec.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gt2hjwewjyj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gt2aqunxcqx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gt2ohrepgtk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ivvv.top/Article/details/gt2uujmuzsv.html

Ruby: s.bytesize;  s.length
来源：http://dali.zycfv.cn/Article/details/gt2vtlvalgo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenlongwang.top/Article/details/gt2dihvvjjc.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2qadtreya.html

F. 文件与目录
来源：http://dali.redwolf501.top/Article/details/gt2zeurlnbw.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2joppkhrm.html

[F01] 读取整个文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2yoackdko.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jyoumei.cn/Article/details/gt2prmbfskt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2jbbjpqgl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.mhx1999.top/Article/details/gt2ppxfiocn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gt2frknywzf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gt2zgqbxbsb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.birdmap.top/Article/details/gt2gxhfuozb.html

Ruby: File.read("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2qnfgjlly.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2axjfppps.html

[F02] 逐行读取文件
来源：http://dali.aizwys.cn/Article/details/gt2ywvpryzm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gogol.net.cn/Article/details/gt2cavjiwgk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gt2nnetprgx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gt2kghtvxea.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gt2kbykpyrz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gt2hlbsmgoe.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ulhbaasv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guannengcc.top/Article/details/gt2eayszmzr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ppjwa.cn/Article/details/gt2thfqbjca.html

[F03] 写入文件（覆盖）
来源：http://dali.yanxiufei.cn/Article/details/gt2jpgzcjmv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yonumen.top/Article/details/gt2dahgzuyv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2cdlcmuap.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pycfn.com/Article/details/gt2aucezgas.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gt2cerfnimz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258.top/Article/details/gt2vvqgieoi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.andypj.xyz/Article/details/gt2lrcgqlba.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ehwqpu.com/Article/details/gt2qxdydhuk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gt2xoraxxuz.html

[F04] 追加写入文件
来源：http://dali.hammf.cn/Article/details/gt2xwaoogya.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2zkoshzol.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxinkj.top/Article/details/gt2kdiweosu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gt2xlggpkks.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2reffjheq.html


<!-- 参考信息 -->