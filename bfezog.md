代发 wailian999

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xuanzx.com/Article/details/gtkwjfwjux.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.mhx1999.top/Article/details/gtwlpvrazk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gtmgkirhjw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gtladnbrsj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xziqi.cn/Article/details/gtdxvhyhcu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.316326.xyz/Article/details/gtomcnsprx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hammf.cn/Article/details/gtwvgxmxib.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tanke756.top/Article/details/gtcbcmrbeh.html

[D11] 反转数组
来源：http://dali.zhongyouzk.top/Article/details/gtjyfupcla.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fzhhl.top/Article/details/gtobelmdjt.html

PHP:  array_reverse($arr);
来源：http://dali.xylfe.cn/Article/details/gtlncprozj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guowangkeji.top/Article/details/gtdlrlvhwb.html

TS:   [...arr].reverse();
来源：http://dali.tian-w.cn/Article/details/gtepfmvrvq.html

Java: Collections.reverse(list);
来源：http://dali.yanxiufei.cn/Article/details/gtcdubbvph.html

Go:   slices.Reverse(arr)
来源：http://dali.tian-w.cn/Article/details/gtcyurhvmp.html

Ruby: arr.reverse
来源：http://dali.zdqjudy.top/Article/details/gtphzvsmbd.html

C#:   list.Reverse();
来源：http://dali.yj202588.top/Article/details/gtmdtphxjp.html

[D12] 查找元素下标
来源：http://dali.xuetiantiany.cn/Article/details/gtwhefzqxx.html

Py:   arr.index(x);  x in arr
来源：http://dali.guowangkeji.top/Article/details/gtyxbsuarq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hywenlv.cn/Article/details/gtwyfxycjk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gtxnzzckbt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gtcxzadfme.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zdqjudy.top/Article/details/gttsjhjjxn.html

Go:   slices.Index(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtasveecqv.html

Ruby: arr.index(x)
来源：http://dali.zhengqikj.top/Article/details/gthfllzeov.html

C#:   list.IndexOf(x);
来源：http://dali.nanxinkj.top/Article/details/gtjwyzfkem.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tian-w.cn/Article/details/gtpszwlrhj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtavrsoefm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtqmcctodq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gthkjibmfp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtbudsiwou.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.smart0.xyz/Article/details/gtvrvjxtly.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhongyouzk.top/Article/details/gtuorxjscl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sufxvd.cn/Article/details/gtnduagfnl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtikkammfs.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zdqjudy.top/Article/details/gttliyoxkb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yueranfly.top/Article/details/gtpmfomiif.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nwbrower.top/Article/details/gtqfgmpyki.html

JS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtckreqzhi.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtqimkipmq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fzhhl.top/Article/details/gtrlpjsgvr.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gtkzacruoq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhixingplan.top/Article/details/gthmfnlmhr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrleeynez.html

[D15] 去重
来源：http://dali.hongshengwenyu.top/Article/details/gtuhvxkyeg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gtskbisrsv.html

PHP:  array_unique($arr);
来源：http://dali.nanxinkj.top/Article/details/gtkvpavikg.html

JS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gtusbgjmfg.html

TS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtlrgvnads.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jianghu66.top/Article/details/gtdaixvuvm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbupoblj.html

Ruby: arr.uniq
来源：http://dali.chenjidiqi.icu/Article/details/gtjlaiqfqc.html

C#:   list.Distinct().ToList()
来源：http://dali.hfpthk.cn/Article/details/gtfpzjbbwe.html

[D16] 求和与平均值
来源：http://dali.chenzaomai.com/Article/details/gtyhtqxbvi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtescldiwk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbygetxn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gtflvvaloo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtttwprkgu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jiagoushi.top/Article/details/gttfdosmqk.html

Go:   // 手写循环累加
来源：http://dali.zdqjudy.top/Article/details/gtxcnkeyxs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhixingplan.top/Article/details/gtdncdpcqs.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgrbpfzs.html

[D17] 最大值与最小值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxkmryyu.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxinkj.top/Article/details/gtpisqnzpw.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gteonpjcfm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yongpay.top/Article/details/gtahwrmclc.html

TS:   Math.max(...arr);
来源：http://dali.yj20258.top/Article/details/gtcetmalbs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ppjwa.cn/Article/details/gtnlmwqdqf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ydzc1.top/Article/details/gtzszdmjxk.html

Ruby: arr.max;  arr.min
来源：http://dali.ehwqpu.com/Article/details/gtmindugwc.html

C#:   list.Max();  list.Min()
来源：http://dali.sweek.top/Article/details/gtquplwiva.html

[D18] 扁平化嵌套数组
来源：http://dali.aizwys.cn/Article/details/gtirtvizmt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxinkj.top/Article/details/gtswxlsyux.html

PHP:  array_merge(...$nested);
来源：http://dali.chenzaomai.com/Article/details/gtilywjfuj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.9152youxi.cn/Article/details/gttlkxcwvu.html

TS:   nested.flat();
来源：http://dali.zhongyouzk.top/Article/details/gtyoqoflji.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nwbrower.top/Article/details/gtivkzfnvi.html

Go:   // 手写双层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvrdyngq.html

Ruby: nested.flatten
来源：http://dali.sysykeji.top/Article/details/gtuoygkulo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.daxiang520.top/Article/details/gtfcxmoars.html

[D19] 按字段分组
来源：http://dali.xylfe.cn/Article/details/gtsqsfkwdb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhoulong.xyz/Article/details/gtckoqxuyu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuanzhike.top/Article/details/gtlzpuolox.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gtthnacotq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shangyingyoupin.top/Article/details/gtoxbxumzp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.quarkkingdee.top/Article/details/gtpdoeplwq.html

Go:   // 手写 map[string][]T
来源：http://dali.ydzc1.top/Article/details/gtbslnjeuo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ehwqpu.com/Article/details/gtvrscxddb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yvedp.cn/Article/details/gtibrhmgcy.html

[D20] 统计每个元素出现次数
来源：http://dali.daria6918.cn/Article/details/gtjoseaniv.html

Py:   Counter(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtfcjaqkse.html

PHP:  array_count_values($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtnyhouhwc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gtzubkxsuz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gtjekeuvst.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fengsongda.top/Article/details/gttlzmuumw.html

Go:   // 手写 map[T]int
来源：http://dali.vqdsnc.cn/Article/details/gttdpdtdvj.html

Ruby: arr.tally
来源：http://dali.zhoulong.xyz/Article/details/gtranwacoq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.snrcjt.cn/Article/details/gtzjzsdztr.html

[D21] 判断是否包含某元素
来源：http://dali.yuxming.cn/Article/details/gtgwfljpvp.html

Py:   x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtxzrhii.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhoulong.xyz/Article/details/gtqtqmygos.html

JS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtwlxdkaol.html

TS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gtjymwbpuw.html

Java: list.contains(x)
来源：http://dali.chenzaomai.com/Article/details/gtzuxpwdfh.html

Go:   slices.Contains(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtrrsojpub.html

Ruby: arr.include?(x)
来源：http://dali.jqgfzy.top/Article/details/gtjwxflzup.html

C#:   list.Contains(x)
来源：http://dali.iojbl.cn/Article/details/gtvmcedgya.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gaohongyu789.top/Article/details/gtxidqczms.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj202588.top/Article/details/gtdjpdtzzc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenzaomai.com/Article/details/gtnwjbjwvr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ivvv.top/Article/details/gtqtdaynju.html

TS:   [...arr];
来源：http://dali.dianchejie.cn/Article/details/gtvfgoyrie.html

Java: new ArrayList<>(list);
来源：http://dali.yangfankeji.com/Article/details/gtrrwcurmb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gtiidcafzo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yvedp.cn/Article/details/gtjuuhamqi.html

C#:   new List<int>(list);
来源：http://dali.xziqi.cn/Article/details/gtoiykhand.html

[D23] reduce 累积计算
来源：http://dali.bjfxy.top/Article/details/gtgqazqgdh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtcayxyvij.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.bjfxy.top/Article/details/gtvvzzejcn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gtkxshgntj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvapyecem.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shangyingyoupin.top/Article/details/gtdnzazoba.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gttpswwnvq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.316326.xyz/Article/details/gtkivzgrwb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.wangdashe.top/Article/details/gtvaesuejk.html

[D24] 字典 / Map 基本操作
来源：http://dali.hfpthk.cn/Article/details/gtffcyjbad.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gtjsishtei.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pycfn.com/Article/details/gtuqgbkbou.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtnbonmczp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtzcltvmnc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnxiangtu.top/Article/details/gtbqpfafuz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.daxiang520.top/Article/details/gtgbdgdoqw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenjidiqi.icu/Article/details/gtlfiprpax.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daria6918.cn/Article/details/gtzznemfuj.html

[D25] Set 集合去重与交并差
来源：http://dali.shuidangran.top/Article/details/gttydkwgoz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hywenlv.cn/Article/details/gthjyhnsxw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yangfankeji.com/Article/details/gtqhqdnbnf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dashuyun.cn/Article/details/gtangwpmha.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daxiang520.top/Article/details/gthkmsttfv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvgtsstz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gogol.net.cn/Article/details/gtbstsmths.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrawlijc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtqyjwjiwa.html

[D26] 数组转字符串
来源：http://dali.svipenyu.cn/Article/details/gteicsywvv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gotoacloud.top/Article/details/gtgktjhlez.html

PHP:  implode(", ", $arr);
来源：http://dali.316326.xyz/Article/details/gtnamafnks.html

JS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gttldowqdk.html

TS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gtvddguvyw.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqlayjgq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfygzaut.html

Ruby: arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtlwacvith.html

C#:   string.Join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gthrjbcxll.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtucsxrdlu.html

E. 字符串处理
来源：http://dali.sweek.top/Article/details/gthqqhohba.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtrnbtnuzk.html

[E01] 拼接字符串
来源：http://dali.daxiang520.top/Article/details/gttvraidov.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yueranfly.top/Article/details/gtjanoclqb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenzaomai.com/Article/details/gtxhlsknfg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gtdfyzthyv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gtrzmwdrez.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hfpthk.cn/Article/details/gttixltrpx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj202588.top/Article/details/gtyctqosti.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxzvnvrj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtxbgzjdlt.html

[E02] 重复字符串
来源：http://dali.gogol.net.cn/Article/details/gtmfyggsxu.html

Py:   "ab" * 3
来源：http://dali.xinyue.icu/Article/details/gtjcosyfzj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zycfv.cn/Article/details/gtjffonkpr.html

JS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtrhwlukpp.html

TS:   "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gtwnbtthsu.html

Java: "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtxomtkwor.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.redwolf501.top/Article/details/gtdnoxnxrk.html

Ruby: "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gtjqrsreaj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hywenlv.cn/Article/details/gtaamqkvzl.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gttrjawmem.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinqigufen.top/Article/details/gtwbcfvjpt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtraoxiguy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gthgsefnyw.html

TS:   s.slice(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gttyzecwen.html

Java: s.substring(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtapkkspdg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtvbdlxacz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.vqdsnc.cn/Article/details/gtpthlrddv.html

C#:   s.Substring(1, 3)
来源：http://dali.iojbl.cn/Article/details/gtflyyokzw.html

[E04] 查找子串位置
来源：http://dali.zycfv.cn/Article/details/gtpjxxmdqy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnorfembh.html

PHP:  strpos($s, "x");
来源：http://dali.meibo888.top/Article/details/gtaparzcpu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yongpay.top/Article/details/gtcdblqfpt.html

TS:   s.indexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewgmpric.html

Java: s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gtkkyignlq.html

Go:   strings.Index(s, "x")
来源：http://dali.gzhubu.top/Article/details/gtugsnsopc.html

Ruby: s.index("x")
来源：http://dali.guannengcc.top/Article/details/gtwzsrrtwe.html

C#:   s.IndexOf("x")
来源：http://dali.havefunace.top/Article/details/gtactrosfd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhengqikj.top/Article/details/gthshptlgy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.smart0.xyz/Article/details/gtdaxzzqay.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aizwys.cn/Article/details/gtinttgwpn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtjbuyakof.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevxwsleo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gthobsbrfi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.316326.xyz/Article/details/gtmktyazmb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258.top/Article/details/gtwvnijrqg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtifnyqdzh.html

[E06] 替换子串
来源：http://dali.daria6918.cn/Article/details/gteheqbvjg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gtpebwgzzj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fengsongda.top/Article/details/gtsijfxfxl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtqgjtpziq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtcxijyjwq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtphkyeaom.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gtkgymopmm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtnzzxhiag.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvepvixnm.html

[E07] 按分隔符拆分
来源：http://dali.havefunace.top/Article/details/gtuoqhitrd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhixingplan.top/Article/details/gtysiaeixa.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtqsyvutbt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aizwys.cn/Article/details/gtmpgugmpy.html

TS:   s.split(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtdgkbugom.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.0kj1m.cn/Article/details/gtzraerqmm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tanke756.top/Article/details/gtybhvewan.html

Ruby: s.split(",");  s.split
来源：http://dali.dashuyun.cn/Article/details/gtidzsyxfw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tanke756.top/Article/details/gtbxrlcqft.html

[E08] 数组按分隔符合并
来源：http://dali.xziqi.cn/Article/details/gtcbngsbuu.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gtjqaxgbgr.html

PHP:  implode(",", $items);
来源：http://dali.cdnleiting.top/Article/details/gtxeofxdzi.html

JS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtbrzoepxe.html

TS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gttzicwrxe.html

Java: String.join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtjvbnymfr.html

Go:   strings.Join(items, ",")
来源：http://dali.yangfankeji.com/Article/details/gtdyacnwvy.html

Ruby: items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtyfwgirnd.html

C#:   string.Join(",", items)
来源：http://dali.yonumen.top/Article/details/gtgyjawoew.html

[E09] 去除所有空白字符
来源：http://dali.sxryk.cn/Article/details/gtatqzhcua.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtkkxfrukj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gttnirahqy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gtruoepfou.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.316326.xyz/Article/details/gtiytuzcvr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigfzy.top/Article/details/gtdvsqwemd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj202588.top/Article/details/gtsafdpsau.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gaohongyu789.top/Article/details/gtolthqrak.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgryfliim.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangdashe.top/Article/details/gtbtgvhira.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtmfuvrmgk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daxiang520.top/Article/details/gtqtpvbgvb.html

JS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtkqixeugh.html

TS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtqufrwwya.html

Java: String.format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtiqhapklo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpqqjdph.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkpedsxm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cucudq.cn/Article/details/gtilsommpm.html

[E11] 反转字符串
来源：http://dali.316326.xyz/Article/details/gtofbsfgcx.html

Py:   s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gtemoechds.html

PHP:  strrev($s);
来源：http://dali.yongpay.top/Article/details/gtgdnzmwng.html

JS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtfhsputiq.html

TS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtfuwnnvyp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yvedp.cn/Article/details/gtzwqqxvti.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinghuilouyu.cn/Article/details/gthhzakssb.html

Ruby: s.reverse
来源：http://dali.zycfv.cn/Article/details/gtmorcajtf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbtvegon.html

[E12] 统计某字符出现次数
来源：http://dali.cucudq.cn/Article/details/gtectubtaf.html

Py:   s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gtqpiuznrz.html

PHP:  substr_count($s, "a");
来源：http://dali.xuetiantiany.cn/Article/details/gtfciqhpda.html

JS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gtaelifeea.html

TS:   s.split("a").length - 1
来源：http://dali.tianlin.xyz/Article/details/gtatetflas.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sufxvd.cn/Article/details/gtyhwvtlym.html

Go:   strings.Count(s, "a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfabvwmcg.html

Ruby: s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gtsumuvljj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shangyingyoupin.top/Article/details/gtdgvvtkgw.html

[E13] 逐字符遍历
来源：http://dali.shuidangran.top/Article/details/gtoudgdzac.html

Py:   for ch in s: print(ch)
来源：http://dali.dianchejie.cn/Article/details/gtitbuhdip.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnxiangtu.top/Article/details/gtrsmpqfre.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gtnsegadyk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtfcrzmybn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtrpdxqese.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.svipenyu.cn/Article/details/gtxhsbvnci.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuxming.cn/Article/details/gteobasbca.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtfqqgxnyr.html

[E14] URL 编码与 Base64
来源：http://dali.jyoumei.cn/Article/details/gtabjtqhxy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhengqikj.top/Article/details/gtzwmlgdkm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvqotbsm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gotoacloud.top/Article/details/gtktsiozkm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sufxvd.cn/Article/details/gtexzowiue.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nwbrower.top/Article/details/gtgfhcrtou.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daxiang520.top/Article/details/gtdhzmykdq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yanxiufei.cn/Article/details/gtrctuflqc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zdqjudy.top/Article/details/gtwzrujaev.html

[E15] HTML 转义 / 反转义
来源：http://dali.wangshuangyany.cn/Article/details/gtprmmgxxw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hammf.cn/Article/details/gtbgkvvyjy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhkhvreu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenjidiqi.icu/Article/details/gttrvnacfk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.vqdsnc.cn/Article/details/gtfjzkfwvk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigfzy.top/Article/details/gtidinsrnl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtdbumywmo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtziurrdxq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtklsntnrm.html

[E16] 数字千分位
来源：http://dali.redwolf501.top/Article/details/gtvnsjlsvx.html

Py:   f"{1234567:,}"
来源：http://dali.yvedp.cn/Article/details/gtgecdcvkl.html

PHP:  number_format(1234567);
来源：http://dali.redwolf501.top/Article/details/gtlyqlktma.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gthrguvezr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gtistzdmwg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shzxlz.cn/Article/details/gtgfoqrwiz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daria6918.cn/Article/details/gtpdyziymp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtrhrkwobm.html

C#:   1234567.ToString("N0")
来源：http://dali.zhiwuduotai.top/Article/details/gtorqzmapi.html

[E17] 首字母大写
来源：http://dali.yuxming.cn/Article/details/gtmcwwbjkf.html


<!-- 参考信息 -->