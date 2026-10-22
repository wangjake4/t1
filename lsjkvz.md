代发 wailian999

C#:   list.Distinct().ToList()
来源：http://dali.ybcxt.top/Article/details/gt2iaerwqyz.html

[D16] 求和与平均值
来源：http://dali.jqgufenzy.top/Article/details/gt2sxczerju.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2gpdudpjd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2fsgjcowv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gt2zxyjzfzs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zycfv.cn/Article/details/gt2dtavztqo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.kuanghao11.cn/Article/details/gt2rwygniet.html

Go:   // 手写循环累加
来源：http://dali.jinqigufen.top/Article/details/gt2ryhldzxh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipjzntbp.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shhbmmnm.html

[D17] 最大值与最小值
来源：http://dali.meibo888.top/Article/details/gt2eihzmxtm.html

Py:   max(arr);  min(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2buwonoim.html

PHP:  max($arr);  min($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2bgkkemjn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jyoumei.cn/Article/details/gt2mivjfkci.html

TS:   Math.max(...arr);
来源：http://dali.birdmap.top/Article/details/gt2dzsukcfj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gogol.net.cn/Article/details/gt2hnidwcqp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.iojbl.cn/Article/details/gt2jbgqtbts.html

Ruby: arr.max;  arr.min
来源：http://dali.hywenlv.cn/Article/details/gt2mavsfrnf.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgufenzy.top/Article/details/gt2xwyvayco.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgufenzy.top/Article/details/gt2bztzddcd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yvedp.cn/Article/details/gt2smzqwnqb.html

PHP:  array_merge(...$nested);
来源：http://dali.hywenlv.cn/Article/details/gt2dvvtcxyz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bpwvykmd.html

TS:   nested.flat();
来源：http://dali.svipenyu.cn/Article/details/gt2lvucrfhe.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2dhtxbxbd.html

Go:   // 手写双层循环
来源：http://dali.meibo888.top/Article/details/gt2gulrkrbr.html

Ruby: nested.flatten
来源：http://dali.wangdashe.top/Article/details/gt2kqoxiadb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.birdmap.top/Article/details/gt2heduhbrk.html

[D19] 按字段分组
来源：http://dali.iojbl.cn/Article/details/gt2ggijbmhq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2rcdyxvlb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuxming.cn/Article/details/gt2tmumqtit.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenjidiqi.icu/Article/details/gt2avqxmkeb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ajfkoksz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuanzx.com/Article/details/gt2bjeonzal.html

Go:   // 手写 map[string][]T
来源：http://dali.ivvv.top/Article/details/gt2corfiuhf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigfzy.top/Article/details/gt2mnhovjgs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aizwys.cn/Article/details/gt2ihdwgbxz.html

[D20] 统计每个元素出现次数
来源：http://dali.yvedp.cn/Article/details/gt2akalmbzc.html

Py:   Counter(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2moqatzht.html

PHP:  array_count_values($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2lqhoffbu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sweek.top/Article/details/gt2tqsdbmux.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gt2kamazvjq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ouusibaq.html

Go:   // 手写 map[T]int
来源：http://dali.gotoacloud.top/Article/details/gt2mxjrqrdv.html

Ruby: arr.tally
来源：http://dali.tianlin.xyz/Article/details/gt2einatmuf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shuidangran.top/Article/details/gt2nttuqavh.html

[D21] 判断是否包含某元素
来源：http://dali.iojbl.cn/Article/details/gt2oqqynolw.html

Py:   x in arr
来源：http://dali.yonumen.top/Article/details/gt2uwagzqis.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bkdinjfh.html

JS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2wqbvkpvc.html

TS:   arr.includes(x)
来源：http://dali.cqqwz.cn/Article/details/gt2hjnmejjp.html

Java: list.contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2yzsqzhhr.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2cwpfahgv.html

Ruby: arr.include?(x)
来源：http://dali.sweek.top/Article/details/gt2uewiyupm.html

C#:   list.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gt2iesapoji.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yongpay.top/Article/details/gt2qrmrudjk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2kmjnnjqf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj202588.top/Article/details/gt2mprzuphs.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2tfdyrmwp.html

TS:   [...arr];
来源：http://dali.yonumen.top/Article/details/gt2yedjwspc.html

Java: new ArrayList<>(list);
来源：http://dali.daria6918.cn/Article/details/gt2sxgrjkxi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.kuanghao11.cn/Article/details/gt2khqpfpww.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gaohongyu789.top/Article/details/gt2fxfjpzyg.html

C#:   new List<int>(list);
来源：http://dali.smart0.xyz/Article/details/gt2atsarqlg.html

[D23] reduce 累积计算
来源：http://dali.haohaochexian.top/Article/details/gt2ionqdyyt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aizwys.cn/Article/details/gt2taccjuvr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wfpkuzjx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gt2vnufnvcx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2lzbedwtg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ppjwa.cn/Article/details/gt2cqdaizzd.html

Go:   // 手写循环
来源：http://dali.hfpthk.cn/Article/details/gt2hiyunyhc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ehwqpu.com/Article/details/gt2miyaylqf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hysaishi.cn/Article/details/gt2lkxasbbg.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsppzwi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pycfn.com/Article/details/gt2pllsrjjm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sysykeji.top/Article/details/gt2gpwmgitw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vohebbzp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nwbrower.top/Article/details/gt2ovuomkhn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guowangkeji.top/Article/details/gt2ruaurstm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pengpengdd.cyou/Article/details/gt2megvpqdo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hammf.cn/Article/details/gt2sopbqoui.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangdashe.top/Article/details/gt2tsmdbcqm.html

[D25] Set 集合去重与交并差
来源：http://dali.tian-w.cn/Article/details/gt2mheddjvr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.meibo888.top/Article/details/gt2zrbguimc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lwehcvfg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxinkj.top/Article/details/gt2oqrsmgpx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hnqzz.top/Article/details/gt2buoxjjvw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.andypj.xyz/Article/details/gt2klzbcjfe.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2elckjwau.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nwbrower.top/Article/details/gt2hbyfqhtv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hnqzz.top/Article/details/gt2cujicpmw.html

[D26] 数组转字符串
来源：http://dali.zdqjudy.top/Article/details/gt2ikgipogv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.quarkkingdee.top/Article/details/gt2iswproyw.html

PHP:  implode(", ", $arr);
来源：http://dali.zycfv.cn/Article/details/gt2wbckncye.html

JS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gt2fyatkaal.html

TS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gt2ibjxyidz.html

Java: String.join(", ", list)
来源：http://dali.tanke756.top/Article/details/gt2edadsjyi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.9152youxi.cn/Article/details/gt2gdpyeywo.html

Ruby: arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gt2jlgbxema.html

C#:   string.Join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gt2gnlzdmtz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2hxumkpsa.html

E. 字符串处理
来源：http://dali.haohaochexian.top/Article/details/gt2qmcaoqxh.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2snzupjgi.html

[E01] 拼接字符串
来源：http://dali.wangdashe.top/Article/details/gt2grxouvvd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhiwuduotai.top/Article/details/gt2clpseiqp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jqgfzy.top/Article/details/gt2wefgbrbx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gt2qfyuivpq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mifarjrj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cheryme.top/Article/details/gt2eqqlfhyl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lrhndqev.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj20258.top/Article/details/gt2wnqhadcr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gt2yykknrxw.html

[E02] 重复字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2btjwixom.html

Py:   "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gt2dtkjxwdj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ivvv.top/Article/details/gt2vyaztmpd.html

JS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gt2mkwgjvnm.html

TS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vinmndsc.html

Java: "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2bwyrdiop.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xziqi.cn/Article/details/gt2milwqpsu.html

Ruby: "ab" * 3
来源：http://dali.mhx1999.top/Article/details/gt2yvqvyfsi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuanzx.com/Article/details/gt2rdrktjtx.html

[E03] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gt2alectxug.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xziqi.cn/Article/details/gt2akyyrili.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gt2vfrmtdat.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.redwolf501.top/Article/details/gt2bzrnsyrt.html

TS:   s.slice(1, 4)
来源：http://dali.yongpay.top/Article/details/gt2wofvlbla.html

Java: s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gt2jeeffgkp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hammf.cn/Article/details/gt2bjnawtef.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gogol.net.cn/Article/details/gt2wncxicjl.html

C#:   s.Substring(1, 3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yrwfhpeg.html

[E04] 查找子串位置
来源：http://dali.fengsongda.top/Article/details/gt2lvilunry.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nwbrower.top/Article/details/gt2kplecccm.html

PHP:  strpos($s, "x");
来源：http://dali.chenzaomai.com/Article/details/gt2xblthvim.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daria6918.cn/Article/details/gt2mbsexytw.html

TS:   s.indexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gt2wljnxmzx.html

Java: s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gt2ikeaezwt.html

Go:   strings.Index(s, "x")
来源：http://dali.sufxvd.cn/Article/details/gt2phrjoeku.html

Ruby: s.index("x")
来源：http://dali.vqdsnc.cn/Article/details/gt2veuuxkjm.html

C#:   s.IndexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gt2zolpfest.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigufen.top/Article/details/gt2msxfnaaa.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2tztbpqpu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.smart0.xyz/Article/details/gt2dfvbqsxm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bitdyvtm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shuidangran.top/Article/details/gt2uzrjblvd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gt2tcxacsgz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tian-w.cn/Article/details/gt2rktlptte.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sweek.top/Article/details/gt2digcqotn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tanke756.top/Article/details/gt2paofkgdj.html

[E06] 替换子串
来源：http://dali.sxryk.cn/Article/details/gt2zxdqtdfv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ydzc1.top/Article/details/gt2vvdnhqfj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhengqikj.top/Article/details/gt2ksyeuedb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gt2vmjsmxss.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2dufftivu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmnjjox.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guannengcc.top/Article/details/gt2koixrtva.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2nzvydwvo.html

C#:   s.Replace("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2adjmbtln.html

[E07] 按分隔符拆分
来源：http://dali.birdmap.top/Article/details/gt2phrtbjvu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangshuangyany.cn/Article/details/gt2wbowlusx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2oktrigzo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ybcxt.top/Article/details/gt2wtmvxtuk.html

TS:   s.split(",")
来源：http://dali.wangshuangyany.cn/Article/details/gt2sxqlfyra.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ppjwa.cn/Article/details/gt2iuiwujkm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.aizwys.cn/Article/details/gt2wjuobftr.html

Ruby: s.split(",");  s.split
来源：http://dali.mhx1999.top/Article/details/gt2oxfrlswp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shzxlz.cn/Article/details/gt2urnspisv.html

[E08] 数组按分隔符合并
来源：http://dali.sufxvd.cn/Article/details/gt2xnezirqw.html

Py:   ",".join(items)
来源：http://dali.yuanzhike.top/Article/details/gt2jauuljcx.html

PHP:  implode(",", $items);
来源：http://dali.cucudq.cn/Article/details/gt2uuvoivrf.html

JS:   items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gt2sxiywgnh.html

TS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gt2pwpvsqmp.html

Java: String.join(",", items)
来源：http://dali.hammf.cn/Article/details/gt2cgbrerep.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgufenzy.top/Article/details/gt2hiujpbzc.html

Ruby: items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gt2iyzxwjkt.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2crdkzhqy.html

[E09] 去除所有空白字符
来源：http://dali.yongpay.top/Article/details/gt2xcacsozw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rqdhfdbg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxlcjryq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gt2jikcqfcx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gt2cbrbjrbv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cheryme.top/Article/details/gt2zhimwokz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nwbrower.top/Article/details/gt2vlkczyya.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zqqmophg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gt2lbxidkcv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.havefunace.top/Article/details/gt2mkllokmv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2xrmihsny.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tianlin.xyz/Article/details/gt2ntpazzqj.html

JS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cfaublbp.html

TS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gt2mrmmlqwa.html

Java: String.format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gt2kusyavbf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gt2uqxjdgoj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vjnahbky.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhiwuduotai.top/Article/details/gt2iokvhvpg.html

[E11] 反转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2togfdrpp.html

Py:   s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gt2fhkesjsa.html

PHP:  strrev($s);
来源：http://dali.fengsongda.top/Article/details/gt2xvratkqd.html

JS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gt2yqdqypeb.html

TS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gt2hpcoywun.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shzxlz.cn/Article/details/gt2zfznywao.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cmfalrdd.html

Ruby: s.reverse
来源：http://dali.ybcxt.top/Article/details/gt2wyewfkny.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gt2iazlerxa.html

[E12] 统计某字符出现次数
来源：http://dali.hnxiangtu.top/Article/details/gt2wxydqfot.html

Py:   s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2eylkcmdw.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ybhgachu.html

JS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nukoumrj.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnifegp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgfzy.top/Article/details/gt2fgxzzmuz.html

Go:   strings.Count(s, "a")
来源：http://dali.mhx1999.top/Article/details/gt2movehlwb.html

Ruby: s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2zaqptqri.html

C#:   s.Count(c => c == 'a')
来源：http://dali.meibo888.top/Article/details/gt2kopnahsi.html

[E13] 逐字符遍历
来源：http://dali.nanxinkj.top/Article/details/gt2kbvpfmne.html

Py:   for ch in s: print(ch)
来源：http://dali.9152youxi.cn/Article/details/gt2mbnoxhxw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.svipenyu.cn/Article/details/gt2hnkthlih.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vgrurjlq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2buiyuzuw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nwbrower.top/Article/details/gt2ewagdmzj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hammf.cn/Article/details/gt2nzhfgevr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tanke756.top/Article/details/gt2gtvmrmxv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2kptjrgvj.html

[E14] URL 编码与 Base64
来源：http://dali.cheryme.top/Article/details/gt2uribcvac.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dashuyun.cn/Article/details/gt2gwrupplj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ppjwa.cn/Article/details/gt2nhagqjca.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zycfv.cn/Article/details/gt2fvmxvtbi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cheryme.top/Article/details/gt2hnepmqwy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.wangdashe.top/Article/details/gt2qyesfwma.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhongyouzk.top/Article/details/gt2wzcvfupa.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.birdmap.top/Article/details/gt2ekuwazdv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gt2njazzjkw.html

[E15] HTML 转义 / 反转义
来源：http://dali.iojbl.cn/Article/details/gt2vpthobys.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ybcxt.top/Article/details/gt2dhrbeahr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ppjwa.cn/Article/details/gt2qqauffxr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangdashe.top/Article/details/gt2mrhuzlmx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sysykeji.top/Article/details/gt2famamnlj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.vqdsnc.cn/Article/details/gt2caxqhdpn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ivvv.top/Article/details/gt2soazoult.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tlimymsw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.andypj.xyz/Article/details/gt2sguljtdw.html

[E16] 数字千分位
来源：http://dali.chenlongwang.top/Article/details/gt2ibobbvdj.html

Py:   f"{1234567:,}"
来源：http://dali.guannengcc.top/Article/details/gt2bqcscdix.html

PHP:  number_format(1234567);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ekhugntg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gt2zcmorwjf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gt2qjxhtpdh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ybcxt.top/Article/details/gt2ywnnnlnn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ppjwa.cn/Article/details/gt2fdjuxydw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hongshengwenyu.top/Article/details/gt2fllnxxnl.html

C#:   1234567.ToString("N0")
来源：http://dali.fengsongda.top/Article/details/gt2ipxxdymx.html

[E17] 首字母大写
来源：http://dali.chenzaomai.com/Article/details/gt2zpbwtoed.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ybcxt.top/Article/details/gt2mcsbmdcx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gt2ohzdbrlt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gt2jteqhfxp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gt2wcfaydsz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2anpwvqpt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aibaodan.cn/Article/details/gt2vutmfigx.html

Ruby: s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zkpprjlr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xlgdyatw.html

[E18] 模板占位符替换
来源：http://dali.nanxinkj.top/Article/details/gt2pdsonkjo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sweek.top/Article/details/gt2uzrmaekq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.kuanghao11.cn/Article/details/gt2rrpidkpw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zisrlvmd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gt2rieilbea.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ivvv.top/Article/details/gt2qfyxqwax.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dgbwftkb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.haohaochexian.top/Article/details/gt2mujoahax.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgufenzy.top/Article/details/gt2vnmkhkxn.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigfzy.top/Article/details/gt2aswptaep.html

Py:   s.splitlines()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2obxcuxdt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2ymltvwct.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxyzgpk.html

TS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gt2rprpwisd.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2apdclalb.html

Go:   strings.Split(s, "\n")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ogmiyamj.html

Ruby: s.lines
来源：http://dali.guannengcc.top/Article/details/gt2kcenwmcf.html

C#:   s.Split('\n')
来源：http://dali.nanxinkj.top/Article/details/gt2gpesmcaw.html

[E20] 判断字符串是否为空
来源：http://dali.snrcjt.cn/Article/details/gt2bjpqxvnu.html

Py:   if not s:
来源：http://dali.svipenyu.cn/Article/details/gt2yrifmlki.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jyoumei.cn/Article/details/gt2striyguq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tianlin.xyz/Article/details/gt2ykaltykz.html

TS:   if (s === "") {}
来源：http://dali.nanxinkj.top/Article/details/gt2ausznrhu.html

Java: if (s.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qakxacdm.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gt2rltofuxx.html

Ruby: if s.empty?
来源：http://dali.dashuyun.cn/Article/details/gt2tzinkyvt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sxryk.cn/Article/details/gt2ahkijiep.html

[E21] 超长截断加省略号
来源：http://dali.zhixingplan.top/Article/details/gt2wpnboodk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jianghu66.top/Article/details/gt2nqdpyowi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.havefunace.top/Article/details/gt2xbzhitld.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2xiaagked.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gt2amfmmawu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gt2vbzolvkf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhoulong.xyz/Article/details/gt2rzqljlpr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gt2kphiazrr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gt2ehsurgdt.html

[E22] 字节长度与字符长度
来源：http://dali.jqgfzy.top/Article/details/gt2gduyibcq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aizwys.cn/Article/details/gt2efxedxnm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2uvhpagel.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gt2vmmfstsz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2bcubtrbo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yvedp.cn/Article/details/gt2ojmysaxz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2luwwobpb.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhixingplan.top/Article/details/gt2kiiwgqoe.html


<!-- 参考信息 -->