代发 wailian999

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ydzc1.top/Article/details/gt2bjhfpass.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sufxvd.cn/Article/details/gt2tqcppvlh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cqqwz.cn/Article/details/gt2gnmwdjac.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gotoacloud.top/Article/details/gt2mfbusjxp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.mhx1999.top/Article/details/gt2nqcflkqj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tian-w.cn/Article/details/gt2wdvvrzug.html

JS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gt2zeiwpyic.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpsqjuz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2miflyehg.html

Go:   // 手写循环
来源：http://dali.zhongyouzk.top/Article/details/gt2ddgxdeek.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fzhhl.top/Article/details/gt2pjuwilwf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2clfmyzkr.html

[D15] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gt2nramkmco.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2bmslhdgn.html

PHP:  array_unique($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2iwmkqnne.html

JS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gt2dgsimnol.html

TS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gt2rlifgedg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kgpzaaso.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.316326.xyz/Article/details/gt2gfisrqxe.html

Ruby: arr.uniq
来源：http://dali.cucudq.cn/Article/details/gt2kpfoxecb.html

C#:   list.Distinct().ToList()
来源：http://dali.fzhhl.top/Article/details/gt2tgqjudzu.html

[D16] 求和与平均值
来源：http://dali.kuanghao11.cn/Article/details/gt2usndxnvk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2grfyadpd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shuidangran.top/Article/details/gt2wcvekoae.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gt2fvnzidqn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2sndnmlvn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cdnleiting.top/Article/details/gt2fnzxqhms.html

Go:   // 手写循环累加
来源：http://dali.yj20258888.top/Article/details/gt2kehwwint.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zdqjudy.top/Article/details/gt2czjrkmfe.html

C#:   list.Sum();  list.Average()
来源：http://dali.meibo888.top/Article/details/gt2bojnxpwq.html

[D17] 最大值与最小值
来源：http://dali.guowangkeji.top/Article/details/gt2sfwsqkgd.html

Py:   max(arr);  min(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2jsvbgqxp.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dehiyhcc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yueranfly.top/Article/details/gt2gteemist.html

TS:   Math.max(...arr);
来源：http://dali.fengsongda.top/Article/details/gt2xstyguth.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhongyouzk.top/Article/details/gt2xcjqijgx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2woqityuz.html

Ruby: arr.max;  arr.min
来源：http://dali.hfpthk.cn/Article/details/gt2vevuutdf.html

C#:   list.Max();  list.Min()
来源：http://dali.aizwys.cn/Article/details/gt2pppbhflo.html

[D18] 扁平化嵌套数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zdlrrcoa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cdnleiting.top/Article/details/gt2tlzfyakh.html

PHP:  array_merge(...$nested);
来源：http://dali.guannengcc.top/Article/details/gt2nfbctvca.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.316326.xyz/Article/details/gt2sepstjtc.html

TS:   nested.flat();
来源：http://dali.havefunace.top/Article/details/gt2xtbvjbrh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhengqikj.top/Article/details/gt2vwfikvpx.html

Go:   // 手写双层循环
来源：http://dali.shzxlz.cn/Article/details/gt2vagebqfx.html

Ruby: nested.flatten
来源：http://dali.xuanzx.com/Article/details/gt2qutivard.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2nhbbklap.html

[D19] 按字段分组
来源：http://dali.yuanzhike.top/Article/details/gt2pgwidhuh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sxryk.cn/Article/details/gt2niqthukp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gzhubu.top/Article/details/gt2hqkrymvu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cucudq.cn/Article/details/gt2yujsbkqw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.quarkkingdee.top/Article/details/gt2tmxxagra.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ybcxt.top/Article/details/gt2bhynygzh.html

Go:   // 手写 map[string][]T
来源：http://dali.jinqigufen.top/Article/details/gt2juwbvcfh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sweek.top/Article/details/gt2gulbgjed.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gt2rxamqcaw.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qspbuhob.html

Py:   Counter(arr)
来源：http://dali.wangdashe.top/Article/details/gt2djoxqcvm.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2inabbehd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daria6918.cn/Article/details/gt2tkxruygb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gt2srmkcwor.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhengqikj.top/Article/details/gt2calctjny.html

Go:   // 手写 map[T]int
来源：http://dali.yuanzhike.top/Article/details/gt2btpjzxbs.html

Ruby: arr.tally
来源：http://dali.smart0.xyz/Article/details/gt2fwbxjkkg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gt2nlcqjqzl.html

[D21] 判断是否包含某元素
来源：http://dali.haohaochexian.top/Article/details/gt2zrocywhe.html

Py:   x in arr
来源：http://dali.jiagoushi.top/Article/details/gt2mwpjpkag.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yangfankeji.com/Article/details/gt2sncsvjri.html

JS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gt2riyorfkr.html

TS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gt2bkjmnive.html

Java: list.contains(x)
来源：http://dali.birdmap.top/Article/details/gt2trhkcqai.html

Go:   slices.Contains(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2zpbvygub.html

Ruby: arr.include?(x)
来源：http://dali.cashguo.top/Article/details/gt2efewnadp.html

C#:   list.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gt2vdupighx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jiagoushi.top/Article/details/gt2jpnqaimu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nwbrower.top/Article/details/gt2fwanozfl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jlsjyb.cn/Article/details/gt2wvemajpp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sxryk.cn/Article/details/gt2qpamlzut.html

TS:   [...arr];
来源：http://dali.chenzaomai.com/Article/details/gt2rvjneplj.html

Java: new ArrayList<>(list);
来源：http://dali.c1oappe.top/Article/details/gt2sayehian.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.redwolf501.top/Article/details/gt2volmmrja.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xziqi.cn/Article/details/gt2vuhshjpp.html

C#:   new List<int>(list);
来源：http://dali.sufxvd.cn/Article/details/gt2hwwwbylf.html

[D23] reduce 累积计算
来源：http://dali.zdqjudy.top/Article/details/gt2rusoyikp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2ilvcsqup.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tmtzcjrq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bkfnhjbk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2wdpxtwnx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nwbrower.top/Article/details/gt2tvxylhuy.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lmhhtghy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hysaishi.cn/Article/details/gt2ltuhqlij.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ppjwa.cn/Article/details/gt2papmyznf.html

[D24] 字典 / Map 基本操作
来源：http://dali.xylfe.cn/Article/details/gt2mpzngwlj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zdqjudy.top/Article/details/gt2tjsalpmm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daria6918.cn/Article/details/gt2mukwzbff.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hywenlv.cn/Article/details/gt2nhfsxhaz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2hthfqpgg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuxming.cn/Article/details/gt2mjgngzhv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258.top/Article/details/gt2zsyxvvtt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yongpay.top/Article/details/gt2ofdnrjsd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenlongwang.top/Article/details/gt2quedfuhw.html

[D25] Set 集合去重与交并差
来源：http://dali.vqdsnc.cn/Article/details/gt2dfpausum.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ehwqpu.com/Article/details/gt2xerscxzi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yonumen.top/Article/details/gt2ktanbkdm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yuxming.cn/Article/details/gt2sxeivowo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2smoopeup.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2uaguhcnv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jlsjyb.cn/Article/details/gt2dexjahkk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2fuqseotx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shzxlz.cn/Article/details/gt2rjrvtjir.html

[D26] 数组转字符串
来源：http://dali.jyoumei.cn/Article/details/gt2qwajgsct.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gt2ytzdphzc.html

PHP:  implode(", ", $arr);
来源：http://dali.ehwqpu.com/Article/details/gt2eizqaxjl.html

JS:   arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gt2ksaqeniq.html

TS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gt2iooxzyhk.html

Java: String.join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gt2zqdhmgnn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cdnleiting.top/Article/details/gt2nkqjihde.html

Ruby: arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gt2vyswpsje.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zjflqvhx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oafxzufr.html

E. 字符串处理
来源：http://dali.xinyue.icu/Article/details/gt2gkoykuli.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2bxbaljdg.html

[E01] 拼接字符串
来源：http://dali.shuidangran.top/Article/details/gt2dbqqzgrf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ppjwa.cn/Article/details/gt2aaxxicxx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jlsjyb.cn/Article/details/gt2dwdktwoj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gt2crhwqzar.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gt2iipovxxh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnxiangtu.top/Article/details/gt2wjraomzz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aizwys.cn/Article/details/gt2twfyxavl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xylfe.cn/Article/details/gt2kaoarjiy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2snaqewga.html

[E02] 重复字符串
来源：http://dali.redwolf501.top/Article/details/gt2qdtnugkj.html

Py:   "ab" * 3
来源：http://dali.hfpthk.cn/Article/details/gt2uibyrvlv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tianlin.xyz/Article/details/gt2cqaanlzv.html

JS:   "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gt2wypkzyve.html

TS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gt2qyxkiimg.html

Java: "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gt2ctyepowj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.haohaochexian.top/Article/details/gt2pmgldkcc.html

Ruby: "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gt2crfwinjw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aizwys.cn/Article/details/gt2zjiitrhk.html

[E03] 截取子串
来源：http://dali.yj202588.top/Article/details/gt2rofyhmjq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinqigufen.top/Article/details/gt2fmhydvnc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gt2vecqywoz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gt2xmpvqesy.html

TS:   s.slice(1, 4)
来源：http://dali.guannengcc.top/Article/details/gt2emmxpdbw.html

Java: s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gt2jbjxawqx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258.top/Article/details/gt2pcynsves.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sweek.top/Article/details/gt2gsalxsxm.html

C#:   s.Substring(1, 3)
来源：http://dali.redwolf501.top/Article/details/gt2crtugimn.html

[E04] 查找子串位置
来源：http://dali.hysaishi.cn/Article/details/gt2fkbxpuup.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gt2bghrnbna.html

PHP:  strpos($s, "x");
来源：http://dali.fzhhl.top/Article/details/gt2eydixycl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdpvumr.html

TS:   s.indexOf("x")
来源：http://dali.pycfn.com/Article/details/gt2pvyyibog.html

Java: s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gt2nipslnwf.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258888.top/Article/details/gt2tjjcpmsv.html

Ruby: s.index("x")
来源：http://dali.sxryk.cn/Article/details/gt2yrdbpwzl.html

C#:   s.IndexOf("x")
来源：http://dali.ivvv.top/Article/details/gt2tqwlhgzx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shangyingyoupin.top/Article/details/gt2zmwlkwdz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ppjwa.cn/Article/details/gt2ffjzzwqr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aibaodan.cn/Article/details/gt2mgtriryz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gt2fnrrpjdn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yuanzhike.top/Article/details/gt2ypkuhjsl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gt2iavfdxbh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.iojbl.cn/Article/details/gt2pdplfxuc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhixingplan.top/Article/details/gt2ocdbmjnq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.wangdashe.top/Article/details/gt2yrwhclga.html

[E06] 替换子串
来源：http://dali.yuanzhike.top/Article/details/gt2dbldikwj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.9152youxi.cn/Article/details/gt2ygpjpozu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2sfzwyukw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gt2bafsdfvj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gt2betlchzq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2lwypntbi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gt2rpunkwxh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2llfxshrf.html

C#:   s.Replace("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2sweujqaf.html

[E07] 按分隔符拆分
来源：http://dali.yj20258.top/Article/details/gt2cdpjnuzt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhixingplan.top/Article/details/gt2oacfgxff.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2exqgjjwd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xziqi.cn/Article/details/gt2vszmibjz.html

TS:   s.split(",")
来源：http://dali.yanxiufei.cn/Article/details/gt2agdpxyse.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fmzyzugv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yvedp.cn/Article/details/gt2tjqnyeao.html

Ruby: s.split(",");  s.split
来源：http://dali.quarkkingdee.top/Article/details/gt2jwaxvsev.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2boekjgea.html

[E08] 数组按分隔符合并
来源：http://dali.hnqzz.top/Article/details/gt2pddwqeld.html

Py:   ",".join(items)
来源：http://dali.zycfv.cn/Article/details/gt2rbfozbag.html

PHP:  implode(",", $items);
来源：http://dali.gotoacloud.top/Article/details/gt2zrsjcjzh.html

JS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gt2dnssfbpk.html

TS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gt2sicvpdhz.html

Java: String.join(",", items)
来源：http://dali.fzhhl.top/Article/details/gt2hgjhtptw.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgufenzy.top/Article/details/gt2fnhdsftx.html

Ruby: items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gt2vqlxxdij.html

C#:   string.Join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gt2lwxzrhaf.html

[E09] 去除所有空白字符
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hsebqldy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jqgfzy.top/Article/details/gt2wighgcwn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.andypj.xyz/Article/details/gt2bazeqssf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gogol.net.cn/Article/details/gt2ejvvibga.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gt2jtcpazor.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258.top/Article/details/gt2rggawfbz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.iojbl.cn/Article/details/gt2hhpbvxnc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jmfrlpgk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gt2kosefoze.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tanke756.top/Article/details/gt2daqsvxor.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hlglbamj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zvlnzbtf.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvspbhb.html

TS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gt2qqfgtrhb.html

Java: String.format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gt2xtmnprwq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kattifdk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gt2nouorixx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.9152youxi.cn/Article/details/gt2oijymkpi.html

[E11] 反转字符串
来源：http://dali.daria6918.cn/Article/details/gt2lgpaiwwj.html

Py:   s[::-1]
来源：http://dali.yj20258.top/Article/details/gt2sbrehiil.html

PHP:  strrev($s);
来源：http://dali.ydzc1.top/Article/details/gt2xhrzzvss.html

JS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gt2iowiooel.html

TS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gt2fytkfuls.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mdiljbmv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258.top/Article/details/gt2cefwrtop.html

Ruby: s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gt2lxcfjvpr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gt2yyrwlpys.html

[E12] 统计某字符出现次数
来源：http://dali.guannengcc.top/Article/details/gt2smnwzure.html

Py:   s.count("a")
来源：http://dali.xziqi.cn/Article/details/gt2mscpojes.html

PHP:  substr_count($s, "a");
来源：http://dali.xuanzx.com/Article/details/gt2edrcstxd.html

JS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gt2xjqyjxjt.html

TS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gt2fbphovqu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258.top/Article/details/gt2hleivjkw.html

Go:   strings.Count(s, "a")
来源：http://dali.yanxiufei.cn/Article/details/gt2jdiszryn.html

Ruby: s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gt2gaxwoiqf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daria6918.cn/Article/details/gt2gigynyrm.html

[E13] 逐字符遍历
来源：http://dali.hnqzz.top/Article/details/gt2whutewit.html

Py:   for ch in s: print(ch)
来源：http://dali.jlsjyb.cn/Article/details/gt2amdvdbzp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pycfn.com/Article/details/gt2kgfmfdag.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gt2oavfvqho.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hfpthk.cn/Article/details/gt2adxpvjfl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aizwys.cn/Article/details/gt2zyxiezqm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuanzhike.top/Article/details/gt2zvbasemo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.smart0.xyz/Article/details/gt2mhfwrmoy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2iilugphr.html

[E14] URL 编码与 Base64
来源：http://dali.zhiwuduotai.top/Article/details/gt2qchoyoko.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hfpthk.cn/Article/details/gt2uuzfacxc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxinkj.top/Article/details/gt2skzhrtcm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhoulong.xyz/Article/details/gt2ychovqaw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.iojbl.cn/Article/details/gt2oakregwu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yvedp.cn/Article/details/gt2adxatwha.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.bjfxy.top/Article/details/gt2juyoplwj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.bjfxy.top/Article/details/gt2xbtckplr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hysaishi.cn/Article/details/gt2jbierkzu.html

[E15] HTML 转义 / 反转义
来源：http://dali.cashguo.top/Article/details/gt2wzrugvjh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuanzx.com/Article/details/gt2qtdhnjoj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2tdhckixz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zycfv.cn/Article/details/gt2rktympwz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj202588.top/Article/details/gt2kavtmhqy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.0kj1m.cn/Article/details/gt2pguflzri.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nyizognp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2vofwdxgz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sxryk.cn/Article/details/gt2ianimuqx.html

[E16] 数字千分位
来源：http://dali.jinqigufen.top/Article/details/gt2axxwknqt.html

Py:   f"{1234567:,}"
来源：http://dali.shzxlz.cn/Article/details/gt2zruxpwpk.html

PHP:  number_format(1234567);
来源：http://dali.9152youxi.cn/Article/details/gt2xxqyrtat.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gt2pwzivijh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gt2blirzmoc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jianghu66.top/Article/details/gt2switqcxf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hysaishi.cn/Article/details/gt2jonxrtyh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hongshengwenyu.top/Article/details/gt2dxlivaut.html

C#:   1234567.ToString("N0")
来源：http://dali.mhx1999.top/Article/details/gt2csakneny.html

[E17] 首字母大写
来源：http://dali.guowangkeji.top/Article/details/gt2hmdrcmyr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxinkj.top/Article/details/gt2dbscrxon.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tianlin.xyz/Article/details/gt2dkxwwtul.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2urlvbvjm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gt2dfcnorps.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.316326.xyz/Article/details/gt2dtcaqpvg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gt2nycmaukz.html

Ruby: s.capitalize
来源：http://dali.jqgfzy.top/Article/details/gt2xbqnwqyc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hongshengwenyu.top/Article/details/gt2dfiinrzs.html

[E18] 模板占位符替换
来源：http://dali.yuanzhike.top/Article/details/gt2koizabww.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhixingplan.top/Article/details/gt2jacihqng.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gaohongyu789.top/Article/details/gt2flaaptqg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ijyetzpp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2tkcfngkw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gt2vdpxmxpl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2dbtbwxdy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xinyue.icu/Article/details/gt2sfnupqhr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gt2audchqkx.html

[E19] 多行文本按行拆分
来源：http://dali.ehwqpu.com/Article/details/gt2qwkrwgyd.html

Py:   s.splitlines()
来源：http://dali.pycfn.com/Article/details/gt2jwlxgmsd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hammf.cn/Article/details/gt2bsxydjbj.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gt2qtstekqn.html

TS:   s.split(/\r?\n/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ifehjdjd.html

Java: s.lines().toList()
来源：http://dali.ybcxt.top/Article/details/gt2fppxejmd.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ukuhlgfd.html

Ruby: s.lines
来源：http://dali.xuanzx.com/Article/details/gt2tcuatplj.html

C#:   s.Split('\n')
来源：http://dali.hnxiangtu.top/Article/details/gt2xwpufkgf.html

[E20] 判断字符串是否为空
来源：http://dali.fzhhl.top/Article/details/gt2bdwhpbui.html

Py:   if not s:
来源：http://dali.gotoacloud.top/Article/details/gt2mtedamgt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.c1oappe.top/Article/details/gt2pbsnovan.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2hujwypzk.html

TS:   if (s === "") {}
来源：http://dali.hysaishi.cn/Article/details/gt2xfiozfxb.html

Java: if (s.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gt2qkdonwdy.html


<!-- 参考信息 -->