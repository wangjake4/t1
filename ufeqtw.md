代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtescdnelr.html

C#:   a.Concat(b).ToList()
来源：http://dali.yuxming.cn/Article/details/gtduxjymox.html

[D09] 排序（升序）
来源：http://dali.jyoumei.cn/Article/details/gtzwkyvsdy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gtbxutkbis.html

PHP:  sort($arr);
来源：http://dali.chenzaomai.com/Article/details/gtciwuvmgn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ehwqpu.com/Article/details/gtsnjactki.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258.top/Article/details/gtfijolzrm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yueranfly.top/Article/details/gtnznrltmx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sweek.top/Article/details/gtxtzixxas.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gtnyqchnsk.html

C#:   list.Sort();
来源：http://dali.sysykeji.top/Article/details/gtbajqwdfz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenlongwang.top/Article/details/gtladvyyao.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.quarkkingdee.top/Article/details/gtphrrmetp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gtuimrilxr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cheryme.top/Article/details/gtwpehtorw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangdashe.top/Article/details/gtieqxwsck.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dashuyun.cn/Article/details/gtbwlujvic.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shuidangran.top/Article/details/gtshipbzgc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zycfv.cn/Article/details/gtkehzwtpp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hywenlv.cn/Article/details/gtevqsnsij.html

[D11] 反转数组
来源：http://dali.tianlin.xyz/Article/details/gtuwjrhfqw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dianchejie.cn/Article/details/gtkqxrunms.html

PHP:  array_reverse($arr);
来源：http://dali.ybcxt.top/Article/details/gtrtigbrnl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ivvv.top/Article/details/gtnloexkol.html

TS:   [...arr].reverse();
来源：http://dali.nanxuanxn.top/Article/details/gtxssomdzb.html

Java: Collections.reverse(list);
来源：http://dali.nwbrower.top/Article/details/gtjagkpdnd.html

Go:   slices.Reverse(arr)
来源：http://dali.jyoumei.cn/Article/details/gthjfhhemx.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtwnnwbjvi.html

C#:   list.Reverse();
来源：http://dali.yuxming.cn/Article/details/gtpwtjlqxh.html

[D12] 查找元素下标
来源：http://dali.yonumen.top/Article/details/gtpjwkkuuy.html

Py:   arr.index(x);  x in arr
来源：http://dali.dashuyun.cn/Article/details/gthszkwmkg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.0kj1m.cn/Article/details/gtcqgsrjyo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gtgnglkzkh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtrqgojuis.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258888.top/Article/details/gtsondqdzb.html

Go:   slices.Index(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtzaroleos.html

Ruby: arr.index(x)
来源：http://dali.guannengcc.top/Article/details/gtyltgtclp.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258.top/Article/details/gtckyezsqu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.feifeiyinyue.top/Article/details/gtieyqrjjo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhkvzdlc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jqgfzy.top/Article/details/gtcrcswtwv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gtjsaeitrn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gtfseozihb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hywenlv.cn/Article/details/gtlknmkijc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhongyouzk.top/Article/details/gtntjuwvaz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.vqdsnc.cn/Article/details/gtojvopjce.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtayrnkxyl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gtdberhcrn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.c1oappe.top/Article/details/gtcqjwlxdw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuxming.cn/Article/details/gtxygutdli.html

JS:   arr.map(x => x * 2)
来源：http://dali.dianchejie.cn/Article/details/gtcgwpnoya.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhengqikj.top/Article/details/gtmnajklbw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yangfankeji.com/Article/details/gtaddphira.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtxtzbxj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtmdhopkee.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuxming.cn/Article/details/gtgdebaqya.html

[D15] 去重
来源：http://dali.sufxvd.cn/Article/details/gtlwkjznyz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gtsrguoinn.html

PHP:  array_unique($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsijnxqz.html

JS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gthqzyyzhf.html

TS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gtmglrmovw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpukyfpz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj20258.top/Article/details/gtprgejbum.html

Ruby: arr.uniq
来源：http://dali.jianghu66.top/Article/details/gtnmcvfkrc.html

C#:   list.Distinct().ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtelqvrkua.html

[D16] 求和与平均值
来源：http://dali.yj20258888.top/Article/details/gtabjbzeyw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtippisycw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenzaomai.com/Article/details/gtcionybqb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gtjdtozvfe.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtgghasxet.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuanzhike.top/Article/details/gtedzkgxvp.html

Go:   // 手写循环累加
来源：http://dali.yuanzhike.top/Article/details/gtnzbvwfgi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhixingplan.top/Article/details/gtqryhyucp.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxuanxn.top/Article/details/gthscvscic.html

[D17] 最大值与最小值
来源：http://dali.cucudq.cn/Article/details/gturktgwsj.html

Py:   max(arr);  min(arr)
来源：http://dali.jyoumei.cn/Article/details/gtcpdprtfi.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj202588.top/Article/details/gtwujnujom.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.andypj.xyz/Article/details/gtpvygknrv.html

TS:   Math.max(...arr);
来源：http://dali.c1oappe.top/Article/details/gtndmsvkys.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtholbjmox.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthkdkrgb.html

Ruby: arr.max;  arr.min
来源：http://dali.ehwqpu.com/Article/details/gtyqffhiyn.html

C#:   list.Max();  list.Min()
来源：http://dali.vqdsnc.cn/Article/details/gtqjwllaxy.html

[D18] 扁平化嵌套数组
来源：http://dali.ydzc1.top/Article/details/gtfqtttlsq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hfpthk.cn/Article/details/gtqqxbswqv.html

PHP:  array_merge(...$nested);
来源：http://dali.gaohongyu789.top/Article/details/gtgonnhjki.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.havefunace.top/Article/details/gtmplnuudw.html

TS:   nested.flat();
来源：http://dali.zhoulong.xyz/Article/details/gthyyomhab.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yvedp.cn/Article/details/gtxdevesio.html

Go:   // 手写双层循环
来源：http://dali.gaohongyu789.top/Article/details/gtgwfxbmbp.html

Ruby: nested.flatten
来源：http://dali.chenzaomai.com/Article/details/gtmstksjnu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtwzndkrlt.html

[D19] 按字段分组
来源：http://dali.zhengqikj.top/Article/details/gtcwjcpvee.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tianlin.xyz/Article/details/gtbxvrzwdc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.smart0.xyz/Article/details/gtcobhlvlm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cashguo.top/Article/details/gtmdyxmmyq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gtibkhayba.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.c1oappe.top/Article/details/gtbbqoktqw.html

Go:   // 手写 map[string][]T
来源：http://dali.yvedp.cn/Article/details/gtnohtvmvi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daria6918.cn/Article/details/gtvmageqdq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ybcxt.top/Article/details/gtqatbmsoh.html

[D20] 统计每个元素出现次数
来源：http://dali.chenlongwang.top/Article/details/gtoshryryk.html

Py:   Counter(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvmounux.html

PHP:  array_count_values($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtnurcdode.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gtyxvforez.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gtwmdjpczu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.mhx1999.top/Article/details/gtozypnjvn.html

Go:   // 手写 map[T]int
来源：http://dali.0kj1m.cn/Article/details/gtnbuwaehd.html

Ruby: arr.tally
来源：http://dali.hammf.cn/Article/details/gtymyysytr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gotoacloud.top/Article/details/gtjjtbtvxg.html

[D21] 判断是否包含某元素
来源：http://dali.9152youxi.cn/Article/details/gtywafjyxe.html

Py:   x in arr
来源：http://dali.c1oappe.top/Article/details/gtgzfbcxyg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtleqhjiei.html

JS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtvbgivrfl.html

TS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtnmbmaxlw.html

Java: list.contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtdoadpsgd.html

Go:   slices.Contains(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtnpqzrouk.html

Ruby: arr.include?(x)
来源：http://dali.nwbrower.top/Article/details/gtzuryaxbd.html

C#:   list.Contains(x)
来源：http://dali.sxryk.cn/Article/details/gtxycbweqn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.bjfxy.top/Article/details/gtvsnccaqs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hysaishi.cn/Article/details/gtsmspchqn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daxiang520.top/Article/details/gtuwbvruhy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatbgjgby.html

TS:   [...arr];
来源：http://dali.hnqzz.top/Article/details/gtjtedzdrz.html

Java: new ArrayList<>(list);
来源：http://dali.zhixingplan.top/Article/details/gtdgcvbcmu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.iojbl.cn/Article/details/gtddjwfgxo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sufxvd.cn/Article/details/gtcsiuptbx.html

C#:   new List<int>(list);
来源：http://dali.gzhubu.top/Article/details/gtmwbtlevv.html

[D23] reduce 累积计算
来源：http://dali.havefunace.top/Article/details/gttdtzzxiv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.wangdashe.top/Article/details/gtpdusmfcf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtozkeakhj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gtggaxysqu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgajamuw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgufenzy.top/Article/details/gthqjphzik.html

Go:   // 手写循环
来源：http://dali.0kj1m.cn/Article/details/gtrqwjzvun.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangdashe.top/Article/details/gtdlxkvnmh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj202588.top/Article/details/gthhpncjgz.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhongyouzk.top/Article/details/gteseeovcx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hysaishi.cn/Article/details/gtusveypew.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuanzhike.top/Article/details/gtpoxoiwbp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkcemtnd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtcekkzuex.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtfztzvwbm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.mhx1999.top/Article/details/gtahecrwbl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangdashe.top/Article/details/gtmixyhrua.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.bjfxy.top/Article/details/gtgxbnycpk.html

[D25] Set 集合去重与交并差
来源：http://dali.yueranfly.top/Article/details/gtlfxbdwmb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenzaomai.com/Article/details/gtsxvmedwn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jiagoushi.top/Article/details/gtzendlcng.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbbedoua.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jianghu66.top/Article/details/gtinzuidbw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtbqhoenvr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hfpthk.cn/Article/details/gtoyjtwxjl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yongpay.top/Article/details/gtxfpjucte.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jyoumei.cn/Article/details/gtcznkurql.html

[D26] 数组转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtfkxeagaf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sufxvd.cn/Article/details/gtgfoojtib.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgfzy.top/Article/details/gtfqonlmvy.html

JS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmsttnwry.html

TS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gthtpnunkm.html

Java: String.join(", ", list)
来源：http://dali.xylfe.cn/Article/details/gtckxajbmj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzpxnpcz.html

Ruby: arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtrfawecvd.html

C#:   string.Join(", ", list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmwhsglb.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gthfxdqhzn.html

E. 字符串处理
来源：http://dali.sweek.top/Article/details/gtjhkfqeja.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtdptxxjdx.html

[E01] 拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgxrzbyf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.havefunace.top/Article/details/gtcvluinqr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pycfn.com/Article/details/gturqgoryx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gtnqbvrzsk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gtywtozjgt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigufen.top/Article/details/gtxrkimttn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guannengcc.top/Article/details/gtjprmnoxs.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj202588.top/Article/details/gtnzksqgpu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtdgvwmbne.html

[E02] 重复字符串
来源：http://dali.nwbrower.top/Article/details/gtulkxwkmb.html

Py:   "ab" * 3
来源：http://dali.tian-w.cn/Article/details/gtowbkvcli.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cqqwz.cn/Article/details/gtatyyszqf.html

JS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtlzgvunig.html

TS:   "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gtytgkspiy.html

Java: "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtbjhmoult.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.vqdsnc.cn/Article/details/gtdhmpulwk.html

Ruby: "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gtzmvlqmfq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gttiwpvqdf.html

[E03] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gtisfkrsud.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cheryme.top/Article/details/gtplromrow.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtoexrckkj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gtenphdcfq.html

TS:   s.slice(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtgniifnat.html

Java: s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtkacknmcq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gtmhmeqjqj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yanxiufei.cn/Article/details/gtfbblkgrz.html

C#:   s.Substring(1, 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbfipklm.html

[E04] 查找子串位置
来源：http://dali.hongshengwenyu.top/Article/details/gtzflcwhny.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gtyhyavhab.html

PHP:  strpos($s, "x");
来源：http://dali.jlsjyb.cn/Article/details/gtactrjxyu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yuanzhike.top/Article/details/gtwbbjvzzu.html

TS:   s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gtrzqxbfwo.html

Java: s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gtzfzctqjc.html

Go:   strings.Index(s, "x")
来源：http://dali.pycfn.com/Article/details/gtfmkboddp.html

Ruby: s.index("x")
来源：http://dali.xylfe.cn/Article/details/gtiawrozuc.html

C#:   s.IndexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gtiatpkkjj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tian-w.cn/Article/details/gteooilwvj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xuanzx.com/Article/details/gtqxzfmoqt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.wangdashe.top/Article/details/gtuakbpvwd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjaoxdot.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsexdhiy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtmpkxyxhv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dashuyun.cn/Article/details/gtgvpeadyp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hfpthk.cn/Article/details/gtedvjgmok.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gtzfkoidod.html

[E06] 替换子串
来源：http://dali.xziqi.cn/Article/details/gtdmtuacqg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gtrqmvplly.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jianghu66.top/Article/details/gtkursoaju.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtiuokcvsb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtohlfkosr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtxyznmswf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuanzx.com/Article/details/gtjvmpvrho.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtxfmkmzqz.html

C#:   s.Replace("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtdovfnzfe.html

[E07] 按分隔符拆分
来源：http://dali.ivvv.top/Article/details/gtonfijasf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.vqdsnc.cn/Article/details/gtetrdvozn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuxming.cn/Article/details/gtrzcqxfzc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yuanzhike.top/Article/details/gtbwwuqolq.html

TS:   s.split(",")
来源：http://dali.tian-w.cn/Article/details/gtgiyicqqm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jyoumei.cn/Article/details/gtlizsnxcn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigufen.top/Article/details/gtanabnwfr.html

Ruby: s.split(",");  s.split
来源：http://dali.sysykeji.top/Article/details/gtesiuojrr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jianghu66.top/Article/details/gtgyuvlubh.html

[E08] 数组按分隔符合并
来源：http://dali.redwolf501.top/Article/details/gtmpoqigkx.html

Py:   ",".join(items)
来源：http://dali.fzhhl.top/Article/details/gtlrnvsarq.html

PHP:  implode(",", $items);
来源：http://dali.yangfankeji.com/Article/details/gtojfkvgkr.html

JS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtamykhgge.html

TS:   items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gtjjfpkjsl.html

Java: String.join(",", items)
来源：http://dali.tanke756.top/Article/details/gtjwkxjdsj.html

Go:   strings.Join(items, ",")
来源：http://dali.jianghu66.top/Article/details/gtszvqbxcb.html

Ruby: items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtycunthaj.html

C#:   string.Join(",", items)
来源：http://dali.yuanzhike.top/Article/details/gtcdrioecc.html

[E09] 去除所有空白字符
来源：http://dali.xinyue.icu/Article/details/gtvuawveye.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ybcxt.top/Article/details/gthjxizqyb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtevzuthmb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gtpahnikcm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gtitwwpgxy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gtqkdvmtsb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigfzy.top/Article/details/gtpanncehr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hfpthk.cn/Article/details/gtursgwzpr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gtnnramvka.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aibaodan.cn/Article/details/gtttwmzscg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtpkivprzn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gogol.net.cn/Article/details/gtfmkygjul.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtonwszeep.html

TS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gthwtxwgmy.html

Java: String.format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gtydvjuble.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtouyafejb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiycvpgyz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tanke756.top/Article/details/gtgjjtxzuz.html

[E11] 反转字符串
来源：http://dali.ppjwa.cn/Article/details/gtkonlcpkb.html

Py:   s[::-1]
来源：http://dali.xinyue.icu/Article/details/gtpeosknup.html

PHP:  strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtnevycvmn.html

JS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtzumviqdp.html

TS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtzdbfvpup.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxinkj.top/Article/details/gtekeeinjz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.vqdsnc.cn/Article/details/gtqefiamqn.html

Ruby: s.reverse
来源：http://dali.daxiang520.top/Article/details/gtjtsbtkzr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gtmltoioeh.html

[E12] 统计某字符出现次数
来源：http://dali.xuetiantiany.cn/Article/details/gtrfdpcdzu.html

Py:   s.count("a")
来源：http://dali.svipenyu.cn/Article/details/gtabrdbtap.html

PHP:  substr_count($s, "a");
来源：http://dali.yangfankeji.com/Article/details/gtoylxakzr.html

JS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gtelcytzmd.html

TS:   s.split("a").length - 1
来源：http://dali.birdmap.top/Article/details/gtavaurter.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ydzc1.top/Article/details/gtpfztgfpw.html

Go:   strings.Count(s, "a")
来源：http://dali.birdmap.top/Article/details/gtmtkuzmcj.html

Ruby: s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gtarxepbua.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daria6918.cn/Article/details/gttsvpqriy.html

[E13] 逐字符遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtpchptndp.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkdufoji.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.bjfxy.top/Article/details/gthhmezzgt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtbzlivonm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gtatsnyfuf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdaxnodqx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hywenlv.cn/Article/details/gthnvwigux.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenjidiqi.icu/Article/details/gtcmufigxy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhengqikj.top/Article/details/gttxbbjdpj.html

[E14] URL 编码与 Base64
来源：http://dali.jlsjyb.cn/Article/details/gttmpdqstx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hfpthk.cn/Article/details/gtauxyyifa.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guowangkeji.top/Article/details/gtqkoesspr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aizwys.cn/Article/details/gtkvdlbpja.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhongyouzk.top/Article/details/gtujkcllok.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cheryme.top/Article/details/gtxgdagfsk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tian-w.cn/Article/details/gtzsptddjy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhongyouzk.top/Article/details/gtomhrklxl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.birdmap.top/Article/details/gtnykttnwe.html

[E15] HTML 转义 / 反转义
来源：http://dali.zdqjudy.top/Article/details/gtyjesmxva.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtpnrtifla.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ydzc1.top/Article/details/gtsioyvlxq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xylfe.cn/Article/details/gtuzlsbxzq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yongpay.top/Article/details/gtuscyicov.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jlsjyb.cn/Article/details/gtbidnqkqd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.svipenyu.cn/Article/details/gtoaxwlduj.html


<!-- 参考信息 -->