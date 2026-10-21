代发 wailian999

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.birdmap.top/Article/details/gtmshmbfba.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nwbrower.top/Article/details/gtyidmajzd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.316326.xyz/Article/details/gtyubuawff.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258.top/Article/details/gtmahrhtot.html

[D11] 反转数组
来源：http://dali.cqqwz.cn/Article/details/gtffnwxlnm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.andypj.xyz/Article/details/gtwxbytoyq.html

PHP:  array_reverse($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtwuutgabm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.snrcjt.cn/Article/details/gtwuloxnxn.html

TS:   [...arr].reverse();
来源：http://dali.nwbrower.top/Article/details/gtwzttekqi.html

Java: Collections.reverse(list);
来源：http://dali.jiagoushi.top/Article/details/gtovbboqpb.html

Go:   slices.Reverse(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtkymvlygn.html

Ruby: arr.reverse
来源：http://dali.dianchejie.cn/Article/details/gtborxwnjl.html

C#:   list.Reverse();
来源：http://dali.guowangkeji.top/Article/details/gtrxflisan.html

[D12] 查找元素下标
来源：http://dali.hammf.cn/Article/details/gtxkvoyfdm.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhongyouzk.top/Article/details/gtmxlcgdvw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gzhubu.top/Article/details/gtizjsfgwa.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gtmfbinydu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gtwaakqsoj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.bjfxy.top/Article/details/gtfpoqygcl.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gthcxezppc.html

Ruby: arr.index(x)
来源：http://dali.gotoacloud.top/Article/details/gthpswvjjb.html

C#:   list.IndexOf(x);
来源：http://dali.dianchejie.cn/Article/details/gtlpwuuson.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhengqikj.top/Article/details/gtkoiuatch.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhoulong.xyz/Article/details/gtqaifwxqz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtkcdnkxux.html

JS:   arr.filter(x => x > 3)
来源：http://dali.redwolf501.top/Article/details/gtaumiwixh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gtlrmamrfa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtvijxkntv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.pengpengdd.cyou/Article/details/gtnphuqrns.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sxryk.cn/Article/details/gthrczotkh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtutpjfikw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cdnleiting.top/Article/details/gtgsldyetz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtfxangmlx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtarzucaxg.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gtxhqtkscv.html

TS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gtycvarsor.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cqqwz.cn/Article/details/gtspfcttqb.html

Go:   // 手写循环
来源：http://dali.zdqjudy.top/Article/details/gtglnrsmtq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtswavpbpv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtttcyczzg.html

[D15] 去重
来源：http://dali.jqgufenzy.top/Article/details/gtfikyoapy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtekaovxqt.html

PHP:  array_unique($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtaaaycoab.html

JS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gthopjeqar.html

TS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gtssredesn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangshuangyany.cn/Article/details/gtyrkqaqtf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hywenlv.cn/Article/details/gtgbilyltl.html

Ruby: arr.uniq
来源：http://dali.ehwqpu.com/Article/details/gtzwkvsddd.html

C#:   list.Distinct().ToList()
来源：http://dali.jiagoushi.top/Article/details/gtieatutkn.html

[D16] 求和与平均值
来源：http://dali.bjfxy.top/Article/details/gtbvnyyjgh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtfadctilo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hammf.cn/Article/details/gtzienncos.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtuwquilno.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gtyierhriy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cucudq.cn/Article/details/gtwrhfxlmi.html

Go:   // 手写循环累加
来源：http://dali.ivvv.top/Article/details/gtuzwjppyo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gtpmsghlza.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuxming.cn/Article/details/gtovhzwgmt.html

[D17] 最大值与最小值
来源：http://dali.jqgfzy.top/Article/details/gtgkwvfbut.html

Py:   max(arr);  min(arr)
来源：http://dali.chenzaomai.com/Article/details/gtqtqxfqob.html

PHP:  max($arr);  min($arr);
来源：http://dali.xylfe.cn/Article/details/gtgpkzshpb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zycfv.cn/Article/details/gtarmhkywt.html

TS:   Math.max(...arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtxdbwokrs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zdqjudy.top/Article/details/gttoovntdd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtjtqpmkcu.html

Ruby: arr.max;  arr.min
来源：http://dali.tanke756.top/Article/details/gtjvfznlkw.html

C#:   list.Max();  list.Min()
来源：http://dali.gaohongyu789.top/Article/details/gtpspytppl.html

[D18] 扁平化嵌套数组
来源：http://dali.gzhubu.top/Article/details/gtmbcnxcyp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yangfankeji.com/Article/details/gtyceiwfoc.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzpuwzlt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhiwuduotai.top/Article/details/gtovkwfwiv.html

TS:   nested.flat();
来源：http://dali.yonumen.top/Article/details/gtcisqihbf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yueranfly.top/Article/details/gtvrpfitfj.html

Go:   // 手写双层循环
来源：http://dali.ivvv.top/Article/details/gteigbzujr.html

Ruby: nested.flatten
来源：http://dali.yj20258.top/Article/details/gtlvjdsdsy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtabgaoyua.html

[D19] 按字段分组
来源：http://dali.0kj1m.cn/Article/details/gtgdjyunmr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.vqdsnc.cn/Article/details/gtyzkykdfc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangshuangyany.cn/Article/details/gthiadcagt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhiwuduotai.top/Article/details/gtuuqrcbae.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gtlsicgzaz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dashuyun.cn/Article/details/gtqnevgzuq.html

Go:   // 手写 map[string][]T
来源：http://dali.shuidangran.top/Article/details/gtmjwegehi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.0kj1m.cn/Article/details/gtrhhiwnaa.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.redwolf501.top/Article/details/gtgqtltdsn.html

[D20] 统计每个元素出现次数
来源：http://dali.xuanzx.com/Article/details/gtpnvvukno.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gtwlhoxyaa.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtrvrfunjf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtocdgckqm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gtjsbibjsx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ppjwa.cn/Article/details/gtchmynzha.html

Go:   // 手写 map[T]int
来源：http://dali.yj20258888.top/Article/details/gtzdjndren.html

Ruby: arr.tally
来源：http://dali.yonumen.top/Article/details/gtradnwuqy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.andypj.xyz/Article/details/gtgrkrzuzq.html

[D21] 判断是否包含某元素
来源：http://dali.yonumen.top/Article/details/gtmyisytqb.html

Py:   x in arr
来源：http://dali.birdmap.top/Article/details/gtvhdzebst.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yueranfly.top/Article/details/gtlyvunsnf.html

JS:   arr.includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gtypptvtom.html

TS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtycjobqxd.html

Java: list.contains(x)
来源：http://dali.redwolf501.top/Article/details/gtfupxxcby.html

Go:   slices.Contains(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtsltixedm.html

Ruby: arr.include?(x)
来源：http://dali.ydzc1.top/Article/details/gtehgctqlt.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtbxzeancw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.9152youxi.cn/Article/details/gtfvaluzaa.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jianghu66.top/Article/details/gtvbpfmikl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhengqikj.top/Article/details/gtqomwbuni.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj202588.top/Article/details/gthgqpwhmc.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gtrdlyfncf.html

Java: new ArrayList<>(list);
来源：http://dali.sufxvd.cn/Article/details/gtymllejmz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daria6918.cn/Article/details/gtxfxxrlia.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cucudq.cn/Article/details/gtwronflxb.html

C#:   new List<int>(list);
来源：http://dali.0kj1m.cn/Article/details/gtjstjrbtl.html

[D23] reduce 累积计算
来源：http://dali.andypj.xyz/Article/details/gtbukpyevn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuanzx.com/Article/details/gtlcenrsax.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pycfn.com/Article/details/gtevjslyib.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtwdquwbtv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gtrezcdlqz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yueranfly.top/Article/details/gtyuykfxlx.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gtvjmyvwxh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aizwys.cn/Article/details/gtgmvsambp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pycfn.com/Article/details/gtighamcpa.html

[D24] 字典 / Map 基本操作
来源：http://dali.fengsongda.top/Article/details/gtvjelqhow.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ybcxt.top/Article/details/gtewwbbgid.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jiagoushi.top/Article/details/gtzorpnoup.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhongyouzk.top/Article/details/gtduprxzdb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.meibo888.top/Article/details/gtxtzcbqdo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guannengcc.top/Article/details/gtndjiatyv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.vqdsnc.cn/Article/details/gtfsjarelv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxuanxn.top/Article/details/gtpwbqqsqb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yonumen.top/Article/details/gtmelsjmdd.html

[D25] Set 集合去重与交并差
来源：http://dali.guannengcc.top/Article/details/gtthmbifnh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nwbrower.top/Article/details/gtahqthpwl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yueranfly.top/Article/details/gtjbnjdfcv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtxqsqlkyz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aibaodan.cn/Article/details/gtdxsvluyl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dashuyun.cn/Article/details/gtfhoeofgw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sufxvd.cn/Article/details/gtmgyetndn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuxming.cn/Article/details/gtwuvcryjr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258.top/Article/details/gthhtjnidh.html

[D26] 数组转字符串
来源：http://dali.jyoumei.cn/Article/details/gteoumfgkz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhoulong.xyz/Article/details/gtmchtrrhq.html

PHP:  implode(", ", $arr);
来源：http://dali.wangdashe.top/Article/details/gtntyphszj.html

JS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gteqwuqxxu.html

TS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtvthtacqd.html

Java: String.join(", ", list)
来源：http://dali.xinyue.icu/Article/details/gtczaasptc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtiiudslwz.html

Ruby: arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtqspewacf.html

C#:   string.Join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gttshemldh.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhxgmiga.html

E. 字符串处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlfwzffx.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtujafkigb.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjppkcod.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnxiangtu.top/Article/details/gtqepchemf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhixingplan.top/Article/details/gtxaheowac.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gtxyjodune.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtubzoqsbo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aizwys.cn/Article/details/gtbtyrucfm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.meibo888.top/Article/details/gtrhibwdvw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.haohaochexian.top/Article/details/gtxmbpoboi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtjyljhkdm.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gttozrdvfh.html

Py:   "ab" * 3
来源：http://dali.sweek.top/Article/details/gtpuadvjyl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jiagoushi.top/Article/details/gtydqceprm.html

JS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqgzrbqg.html

TS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtjwfctval.html

Java: "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gtzhwxkewr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gtilounoeh.html

Ruby: "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gtzzwnaipu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnxiangtu.top/Article/details/gtbpqhvuww.html

[E03] 截取子串
来源：http://dali.nwbrower.top/Article/details/gtvfusdlzr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xylfe.cn/Article/details/gtlfkbgmch.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtrvgfmldm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhothkqv.html

TS:   s.slice(1, 4)
来源：http://dali.ybcxt.top/Article/details/gtjcbgdcag.html

Java: s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtgnnmloel.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgufenzy.top/Article/details/gtxcgzhtcl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhiwuduotai.top/Article/details/gtjhecltfb.html

C#:   s.Substring(1, 3)
来源：http://dali.zhoulong.xyz/Article/details/gtanlsqcfi.html

[E04] 查找子串位置
来源：http://dali.sweek.top/Article/details/gtxjqswgez.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenzaomai.com/Article/details/gtxapvivlj.html

PHP:  strpos($s, "x");
来源：http://dali.316326.xyz/Article/details/gtwixixoyt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gaohongyu789.top/Article/details/gtectyzomh.html

TS:   s.indexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpegrffn.html

Java: s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtaaqhbvxj.html

Go:   strings.Index(s, "x")
来源：http://dali.xylfe.cn/Article/details/gtxbekxoom.html

Ruby: s.index("x")
来源：http://dali.bjfxy.top/Article/details/gtpjooplqo.html

C#:   s.IndexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gtigolckie.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ydzc1.top/Article/details/gtoovjvern.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tian-w.cn/Article/details/gtwaymxjkb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xziqi.cn/Article/details/gtasngfpiu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevctsoed.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cdnleiting.top/Article/details/gtiqxkmptt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gtizrsldrp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ppjwa.cn/Article/details/gtblvyyqfu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.andypj.xyz/Article/details/gtqzucprge.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtzktduqrb.html

[E06] 替换子串
来源：http://dali.sweek.top/Article/details/gtdzyvgsft.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.iojbl.cn/Article/details/gtnjjpxvxw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.9152youxi.cn/Article/details/gtetxmsjxu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtbkdkgdmp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtbebwnjyz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtopwlwkse.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gtxgejmmnf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsrkzumu.html

C#:   s.Replace("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtolwkmjou.html

[E07] 按分隔符拆分
来源：http://dali.tian-w.cn/Article/details/gtyeznvslp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigfzy.top/Article/details/gtepisvwxk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtwjqifwoc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ydzc1.top/Article/details/gtmlnmrjqn.html

TS:   s.split(",")
来源：http://dali.smart0.xyz/Article/details/gtilanldqd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gogol.net.cn/Article/details/gtcokokhqr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pycfn.com/Article/details/gtrkcbddaf.html

Ruby: s.split(",");  s.split
来源：http://dali.snrcjt.cn/Article/details/gtfwswbkdr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhongyouzk.top/Article/details/gtvmsxcalq.html

[E08] 数组按分隔符合并
来源：http://dali.fzhhl.top/Article/details/gtvcuxzola.html

Py:   ",".join(items)
来源：http://dali.yonumen.top/Article/details/gtjnsecauv.html

PHP:  implode(",", $items);
来源：http://dali.bjfxy.top/Article/details/gtqekzsash.html

JS:   items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtaipigcgx.html

TS:   items.join(",")
来源：http://dali.xylfe.cn/Article/details/gtynljnpvy.html

Java: String.join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gtgsmvpkmk.html

Go:   strings.Join(items, ",")
来源：http://dali.sweek.top/Article/details/gtzpsetsfp.html

Ruby: items.join(",")
来源：http://dali.hnqzz.top/Article/details/gtblkrliec.html

C#:   string.Join(",", items)
来源：http://dali.zycfv.cn/Article/details/gttuqossup.html

[E09] 去除所有空白字符
来源：http://dali.dashuyun.cn/Article/details/gtugxoqfjf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258.top/Article/details/gttsvbrvcu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cucudq.cn/Article/details/gtuxinllbq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gtkuutdxai.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cqqwz.cn/Article/details/gtwefwxvvj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gttbohmfue.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aizwys.cn/Article/details/gtseojolbu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nwbrower.top/Article/details/gteznbydtl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gtxiurgsjb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhengqikj.top/Article/details/gtdfpgucza.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtnjvqnols.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ydzc1.top/Article/details/gtpuweawhi.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gteseeqtyv.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtkruvlotl.html

Java: String.format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtknkzvldr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtapxownzh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gtsgpxvxht.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigfzy.top/Article/details/gtfpdelblt.html

[E11] 反转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtanpohpfx.html

Py:   s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gtxcgbobqj.html

PHP:  strrev($s);
来源：http://dali.cashguo.top/Article/details/gtyjzppart.html

JS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtyhvfglsd.html

TS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtewokrckg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.iojbl.cn/Article/details/gtejcogtjg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jiagoushi.top/Article/details/gtjqfmwdtu.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gtcmfrmchh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gtwwgqhplj.html

[E12] 统计某字符出现次数
来源：http://dali.shzxlz.cn/Article/details/gtqkxazfdx.html

Py:   s.count("a")
来源：http://dali.wangdashe.top/Article/details/gtwreeiurf.html

PHP:  substr_count($s, "a");
来源：http://dali.hongshengwenyu.top/Article/details/gtlwgfrqpi.html

JS:   s.split("a").length - 1
来源：http://dali.hammf.cn/Article/details/gthdzptdtu.html

TS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gtxhuybbrm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yueranfly.top/Article/details/gtjrmxgtsy.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258888.top/Article/details/gtvkfocftr.html

Ruby: s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gtwjhbqwdr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenzaomai.com/Article/details/gtbxwypqcr.html

[E13] 逐字符遍历
来源：http://dali.dashuyun.cn/Article/details/gtwbxgcuwx.html

Py:   for ch in s: print(ch)
来源：http://dali.hywenlv.cn/Article/details/gtlygmxlym.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shzxlz.cn/Article/details/gtefyvzkmd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtcsabgwqz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtkfugchej.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtpreklbca.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.svipenyu.cn/Article/details/gtnpuvodat.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ybcxt.top/Article/details/gtmdynqvap.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtqxzxnydm.html

[E14] URL 编码与 Base64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhrhaxsp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hywenlv.cn/Article/details/gterhkxezi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.0kj1m.cn/Article/details/gtrxfzjyiv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ydzc1.top/Article/details/gtvaktatjt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxuanxn.top/Article/details/gthkamewql.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtndgrbgen.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fengsongda.top/Article/details/gtagrejbpw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgfzy.top/Article/details/gtuiusjyfj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtskiapcmo.html

[E15] HTML 转义 / 反转义
来源：http://dali.nwbrower.top/Article/details/gthlxvtycj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jlsjyb.cn/Article/details/gtzaohncvo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhongyouzk.top/Article/details/gtikkgriqd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnqzz.top/Article/details/gtfohlyyfm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pycfn.com/Article/details/gtarmxwnun.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.smart0.xyz/Article/details/gtinfpbzrf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.iojbl.cn/Article/details/gtswvkizdf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.vqdsnc.cn/Article/details/gtnnibcmlq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.redwolf501.top/Article/details/gtdduigfyz.html

[E16] 数字千分位
来源：http://dali.xylfe.cn/Article/details/gtdswlkgcm.html

Py:   f"{1234567:,}"
来源：http://dali.ybcxt.top/Article/details/gtjbooqfby.html

PHP:  number_format(1234567);
来源：http://dali.yueranfly.top/Article/details/gtxekxqoit.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gtmpcqaaju.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jlsjyb.cn/Article/details/gtmbgaljln.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jianghu66.top/Article/details/gtsqefwjtv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cqqwz.cn/Article/details/gtbgycfoya.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhengqikj.top/Article/details/gtciwoqfzw.html

C#:   1234567.ToString("N0")
来源：http://dali.yanxiufei.cn/Article/details/gtmnzrmxke.html

[E17] 首字母大写
来源：http://dali.hywenlv.cn/Article/details/gtmbfrjfot.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.meibo888.top/Article/details/gtfykruavq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jyoumei.cn/Article/details/gtpcdahngb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gtchmrjmfv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gtpqdzwstq.html


<!-- 参考信息 -->