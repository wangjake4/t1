代发 wailian999

Ruby: arr.index(x)
来源：http://dali.zhixingplan.top/Article/details/gtoewyieit.html

C#:   list.IndexOf(x);
来源：http://dali.snrcjt.cn/Article/details/gtqgumtkay.html

[D13] 过滤（保留满足条件的）
来源：http://dali.9152youxi.cn/Article/details/gtnzfsmbiv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtivbwoxdt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zycfv.cn/Article/details/gtwswwcjvz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gtxtdyopfx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtckemcnzp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtaajtekls.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258888.top/Article/details/gtqjkrzlcw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shuidangran.top/Article/details/gtwbngqous.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtzkarqcqu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hongshengwenyu.top/Article/details/gttzakauwo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sweek.top/Article/details/gtmxnutxkc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.mhx1999.top/Article/details/gtjocqmlsa.html

JS:   arr.map(x => x * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtixylrupg.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gtjzylhtkh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj202588.top/Article/details/gtjyezbiag.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzvmiros.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtmxxaitur.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtbbgkgytx.html

[D15] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilqmdens.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtvwkkahnp.html

PHP:  array_unique($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwnhjqps.html

JS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gtpoacghjq.html

TS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gtgcmrzvqu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhixingplan.top/Article/details/gtqvwtldne.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangshuangyany.cn/Article/details/gtunpzoche.html

Ruby: arr.uniq
来源：http://dali.sweek.top/Article/details/gtffogxzeo.html

C#:   list.Distinct().ToList()
来源：http://dali.hammf.cn/Article/details/gtvcqcnyau.html

[D16] 求和与平均值
来源：http://dali.9152youxi.cn/Article/details/gtpxiivona.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtwrinoxbu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtbdhmtwxg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gtlzlbushc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gtlvsybnvx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.daxiang520.top/Article/details/gtgmrxiyfx.html

Go:   // 手写循环累加
来源：http://dali.yangfankeji.com/Article/details/gtouxwwnmv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jiagoushi.top/Article/details/gtvpopcliy.html

C#:   list.Sum();  list.Average()
来源：http://dali.c1oappe.top/Article/details/gtsjyryqnl.html

[D17] 最大值与最小值
来源：http://dali.yonumen.top/Article/details/gtlvwdotrw.html

Py:   max(arr);  min(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtedwcflzt.html

PHP:  max($arr);  min($arr);
来源：http://dali.cashguo.top/Article/details/gtypowctcm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gtldplikxg.html

TS:   Math.max(...arr);
来源：http://dali.ppjwa.cn/Article/details/gtpfxcpmph.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspkvhktq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthezjdvat.html

Ruby: arr.max;  arr.min
来源：http://dali.hysaishi.cn/Article/details/gtooiiubsf.html

C#:   list.Max();  list.Min()
来源：http://dali.ydzc1.top/Article/details/gtcdwplytv.html

[D18] 扁平化嵌套数组
来源：http://dali.hongshengwenyu.top/Article/details/gtbffufhvc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aizwys.cn/Article/details/gttzjsuoal.html

PHP:  array_merge(...$nested);
来源：http://dali.xuetiantiany.cn/Article/details/gtnmvqiycf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daria6918.cn/Article/details/gtongklfts.html

TS:   nested.flat();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaeccqnzf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtmtuxuewa.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gtjldnixvk.html

Ruby: nested.flatten
来源：http://dali.sufxvd.cn/Article/details/gtgrjgccxg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.havefunace.top/Article/details/gtbnzehtmp.html

[D19] 按字段分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtikjfaurb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtyeqhklyo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhiwuduotai.top/Article/details/gthwcnnnrm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daria6918.cn/Article/details/gtpmqkokyh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shzxlz.cn/Article/details/gtollnhvwm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yueranfly.top/Article/details/gtwyhuirvm.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258888.top/Article/details/gtxyohagvp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj202588.top/Article/details/gtjtlwplsr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigfzy.top/Article/details/gtqshcvqdf.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258.top/Article/details/gtwpyrirnr.html

Py:   Counter(arr)
来源：http://dali.zhengqikj.top/Article/details/gtjotzzleg.html

PHP:  array_count_values($arr);
来源：http://dali.hysaishi.cn/Article/details/gtqpoflfvf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gtzlnnaios.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gtfqzukail.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenzaomai.com/Article/details/gtmusugthb.html

Go:   // 手写 map[T]int
来源：http://dali.yj20258.top/Article/details/gteizdgwby.html

Ruby: arr.tally
来源：http://dali.zhoulong.xyz/Article/details/gtialtgvzc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258888.top/Article/details/gtgsezsupq.html

[D21] 判断是否包含某元素
来源：http://dali.zhoulong.xyz/Article/details/gtoonvaskc.html

Py:   x in arr
来源：http://dali.hongshengwenyu.top/Article/details/gtkzieyxda.html

PHP:  in_array($x, $arr, true);
来源：http://dali.9152youxi.cn/Article/details/gtnexfmvii.html

JS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gtuagarltj.html

TS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gtmurajllr.html

Java: list.contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtmzahwzdh.html

Go:   slices.Contains(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtuovbjiey.html

Ruby: arr.include?(x)
来源：http://dali.chenzaomai.com/Article/details/gttfjzvtvs.html

C#:   list.Contains(x)
来源：http://dali.iojbl.cn/Article/details/gtrfsxrqcu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhongyouzk.top/Article/details/gtldzbqpeb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zycfv.cn/Article/details/gtcwfebgbr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gzhubu.top/Article/details/gtvjeagcns.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.aibaodan.cn/Article/details/gtsjxekugg.html

TS:   [...arr];
来源：http://dali.yuanzhike.top/Article/details/gtvepujncs.html

Java: new ArrayList<>(list);
来源：http://dali.gzhubu.top/Article/details/gtngrqhvln.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sufxvd.cn/Article/details/gtgumapkom.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangdashe.top/Article/details/gtwskgeepq.html

C#:   new List<int>(list);
来源：http://dali.yj20258888.top/Article/details/gtnnmljflr.html

[D23] reduce 累积计算
来源：http://dali.bjfxy.top/Article/details/gtbttmjfct.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shzxlz.cn/Article/details/gtbkmtjvjp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yvedp.cn/Article/details/gtigggqdkg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtgtoaytud.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.316326.xyz/Article/details/gtzbqkittf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.redwolf501.top/Article/details/gtttbztnrt.html

Go:   // 手写循环
来源：http://dali.hammf.cn/Article/details/gtjpnerpsk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhongyouzk.top/Article/details/gtxnmuwswg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.kuanghao11.cn/Article/details/gtprkccgys.html

[D24] 字典 / Map 基本操作
来源：http://dali.xylfe.cn/Article/details/gtvswqgbgu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jlsjyb.cn/Article/details/gtneosehno.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxinkj.top/Article/details/gtezjlkhbj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwsoroqk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gttclxjgtf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fengsongda.top/Article/details/gtqgkxpzlt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzbevouu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daria6918.cn/Article/details/gtoozvlhpu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.feifeiyinyue.top/Article/details/gtbgwjtvvg.html

[D25] Set 集合去重与交并差
来源：http://dali.hfpthk.cn/Article/details/gtmncaszvm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aizwys.cn/Article/details/gtdyxfqtnp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hywenlv.cn/Article/details/gtttnkahsj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhixingplan.top/Article/details/gtbwqwxhxp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.c1oappe.top/Article/details/gtcgncurdx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hfpthk.cn/Article/details/gtocxqgaeu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tian-w.cn/Article/details/gtyjyxfpsr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yvedp.cn/Article/details/gtxvbifvux.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ppjwa.cn/Article/details/gttiusyvsk.html

[D26] 数组转字符串
来源：http://dali.cdnleiting.top/Article/details/gtkcyzotku.html

Py:   ", ".join(map(str, arr))
来源：http://dali.andypj.xyz/Article/details/gtnawltrhz.html

PHP:  implode(", ", $arr);
来源：http://dali.ydzc1.top/Article/details/gtqbjtkugs.html

JS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtsqxxikiy.html

TS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtwohbaqdf.html

Java: String.join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gtunfeytlz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aibaodan.cn/Article/details/gtqibjsqfv.html

Ruby: arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtrqgkcipw.html

C#:   string.Join(", ", list)
来源：http://dali.hammf.cn/Article/details/gtpbakppyo.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtmgvqxfpu.html

E. 字符串处理
来源：http://dali.nanxinkj.top/Article/details/gtzveronrt.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdjlbcbb.html

[E01] 拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtsqucxvjt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoymwgosv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dashuyun.cn/Article/details/gtnkhxtcfd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jyoumei.cn/Article/details/gtobfxonoy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtfjrhrhwk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxinkj.top/Article/details/gtozrmehig.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigfzy.top/Article/details/gtbkbvuxtd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sufxvd.cn/Article/details/gtttbzhkev.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj202588.top/Article/details/gtezrpfvie.html

[E02] 重复字符串
来源：http://dali.ybcxt.top/Article/details/gtoohqtiut.html

Py:   "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gtgoqxrisw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tianlin.xyz/Article/details/gtvsvziyof.html

JS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtamxeniur.html

TS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtvyiomozf.html

Java: "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtdcjuziwr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zdqjudy.top/Article/details/gtvsflxlhu.html

Ruby: "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gtvazpbcbk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangdashe.top/Article/details/gtpbqovfbz.html

[E03] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gtjwxtrahl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.snrcjt.cn/Article/details/gtlujzpmjc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtibkrotxi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gtdqsxeatr.html

TS:   s.slice(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtrvlwacwk.html

Java: s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtgrmxconz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gtnjvrvpzd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zdqjudy.top/Article/details/gtfjajazfc.html

C#:   s.Substring(1, 3)
来源：http://dali.zhongyouzk.top/Article/details/gtzggcnmou.html

[E04] 查找子串位置
来源：http://dali.ybcxt.top/Article/details/gtohtkfyii.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gtuqqomatx.html

PHP:  strpos($s, "x");
来源：http://dali.cdnleiting.top/Article/details/gtjcicvsbc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuanzx.com/Article/details/gtbguajtqr.html

TS:   s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtvxdgwchb.html

Java: s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gtmcwbhkox.html

Go:   strings.Index(s, "x")
来源：http://dali.xylfe.cn/Article/details/gtrgkpckev.html

Ruby: s.index("x")
来源：http://dali.zycfv.cn/Article/details/gtcjlgvxia.html

C#:   s.IndexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gtpftxxkoh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigfzy.top/Article/details/gtixdmpqmo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aizwys.cn/Article/details/gtpvmslahs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.c1oappe.top/Article/details/gtcjvpeqin.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gtcqowrtxr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.havefunace.top/Article/details/gtswpaagcz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtsnhtwlwl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhiwuduotai.top/Article/details/gtkdvnnbbn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sysykeji.top/Article/details/gtokaogtzq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtzuhmaahe.html

[E06] 替换子串
来源：http://dali.sysykeji.top/Article/details/gtvaibkniq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gthwpuzutw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tian-w.cn/Article/details/gtnaytossb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtcfyvvnnh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtcirpobfc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtlfwfmbda.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gtygpbjmcu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtcqhnkyzk.html

C#:   s.Replace("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtyaloipon.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gtmgcgnwct.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.aibaodan.cn/Article/details/gtaxzfjxhx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtmhkyugcm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtukxtekdy.html

TS:   s.split(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpdeydvr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yanxiufei.cn/Article/details/gtrindqial.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigufen.top/Article/details/gtrddcabud.html

Ruby: s.split(",");  s.split
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpaahhznt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.smart0.xyz/Article/details/gtgbfntvlr.html

[E08] 数组按分隔符合并
来源：http://dali.cheryme.top/Article/details/gtwqatwxgh.html

Py:   ",".join(items)
来源：http://dali.yuxming.cn/Article/details/gtdsxsqjlj.html

PHP:  implode(",", $items);
来源：http://dali.zycfv.cn/Article/details/gtsfusveoy.html

JS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtejewnfnr.html

TS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtzloldzod.html

Java: String.join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gtnnhggvgc.html

Go:   strings.Join(items, ",")
来源：http://dali.xylfe.cn/Article/details/gttumtriax.html

Ruby: items.join(",")
来源：http://dali.daxiang520.top/Article/details/gthliyptkf.html

C#:   string.Join(",", items)
来源：http://dali.ivvv.top/Article/details/gtsamzcdyn.html

[E09] 去除所有空白字符
来源：http://dali.feifeiyinyue.top/Article/details/gtleieajlp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tanke756.top/Article/details/gtwdbenmhu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xinyue.icu/Article/details/gtnhpuqjxn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gtdegijcoa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gtisnjivck.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gtlqshacmt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtreoron.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.haohaochexian.top/Article/details/gtqlbgeocy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gtdjzfpqux.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxuanxn.top/Article/details/gtynftebuw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxquhehau.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gtnbspbmwv.html

JS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtewdesuxc.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtxblcqzpn.html

Java: String.format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gthfforrza.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtipbeaycg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gtqexvbfwp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ehwqpu.com/Article/details/gtmneefvkd.html

[E11] 反转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtefktxcqo.html

Py:   s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gteatefuxg.html

PHP:  strrev($s);
来源：http://dali.xylfe.cn/Article/details/gthvfwmpve.html

JS:   [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtxdkytphi.html

TS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtkaedjjgn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.quarkkingdee.top/Article/details/gtfgkyxygp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cheryme.top/Article/details/gtnncmfmuk.html

Ruby: s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxwkatjy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gtiealjlfr.html

[E12] 统计某字符出现次数
来源：http://dali.cqqwz.cn/Article/details/gtkedbgvfz.html

Py:   s.count("a")
来源：http://dali.pycfn.com/Article/details/gtstpixvoz.html

PHP:  substr_count($s, "a");
来源：http://dali.zhiwuduotai.top/Article/details/gtfvlhptgz.html

JS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gttcikaiyj.html

TS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gtmiojkpjl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fengsongda.top/Article/details/gtxjjnyqsb.html

Go:   strings.Count(s, "a")
来源：http://dali.daria6918.cn/Article/details/gtfuwitfhd.html

Ruby: s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gthxsvkvmu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xylfe.cn/Article/details/gtnabxrzgo.html

[E13] 逐字符遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtgtrbatqr.html

Py:   for ch in s: print(ch)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiamffogg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yanxiufei.cn/Article/details/gtblpfkvuj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtjoopdpxh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gtabouzjkw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujvfygay.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tanke756.top/Article/details/gtoxjbaeqp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttsuctjy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtlkdcczjq.html

[E14] URL 编码与 Base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlbafygh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aizwys.cn/Article/details/gtsucmolmt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuanzx.com/Article/details/gtbsgrfjfp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zycfv.cn/Article/details/gtkebvhckq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jqgufenzy.top/Article/details/gtsuqazudv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zycfv.cn/Article/details/gtdvhtqhwb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hongshengwenyu.top/Article/details/gtqnmnrusc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gaohongyu789.top/Article/details/gtifkhdjqv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtdrxzfzsw.html

[E15] HTML 转义 / 反转义
来源：http://dali.nwbrower.top/Article/details/gtceqseyaw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhengqikj.top/Article/details/gttmexfnzg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtmktekhan.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ydzc1.top/Article/details/gtfescgvtp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghxczwxl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ehwqpu.com/Article/details/gtuoxroklt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jyoumei.cn/Article/details/gtxbybeurg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tian-w.cn/Article/details/gtkgcsctzl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fengsongda.top/Article/details/gtiixzpgth.html

[E16] 数字千分位
来源：http://dali.ydzc1.top/Article/details/gtltiqzywi.html

Py:   f"{1234567:,}"
来源：http://dali.andypj.xyz/Article/details/gtokuspsex.html

PHP:  number_format(1234567);
来源：http://dali.tian-w.cn/Article/details/gtuttkutlk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gtzswozuzo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gtjlnomcmv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcguhhyus.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tianlin.xyz/Article/details/gtmarzxfbr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxinkj.top/Article/details/gtebwihppq.html

C#:   1234567.ToString("N0")
来源：http://dali.aizwys.cn/Article/details/gtinbcsvrc.html

[E17] 首字母大写
来源：http://dali.0kj1m.cn/Article/details/gtumjwtnuv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gaohongyu789.top/Article/details/gtqojhbvun.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhongyouzk.top/Article/details/gtvmtxzvmh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zycfv.cn/Article/details/gtdfqdzcor.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gtodekteer.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sxryk.cn/Article/details/gtnimldnlp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yangfankeji.com/Article/details/gteytbdfxl.html

Ruby: s.capitalize
来源：http://dali.yanxiufei.cn/Article/details/gtdwbzixyq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sysykeji.top/Article/details/gtawylgxrw.html

[E18] 模板占位符替换
来源：http://dali.guannengcc.top/Article/details/gtphwzftjq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhiwuduotai.top/Article/details/gtnyodnogi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cucudq.cn/Article/details/gtvddgxfuq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtetnwavbp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtrdrkdjkz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtqedkyqzb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtrvwonwxj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xziqi.cn/Article/details/gtqirkmukm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sufxvd.cn/Article/details/gtdohevnau.html

[E19] 多行文本按行拆分
来源：http://dali.andypj.xyz/Article/details/gtarddarec.html

Py:   s.splitlines()
来源：http://dali.xuetiantiany.cn/Article/details/gtanfrrnsl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtaxfvqnqq.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzpddwrl.html

TS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtoblbnabh.html

Java: s.lines().toList()
来源：http://dali.sweek.top/Article/details/gtawpsrvle.html

Go:   strings.Split(s, "\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrxnjgfe.html


<!-- 参考信息 -->