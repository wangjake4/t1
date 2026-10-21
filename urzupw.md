代发 wailian999

Java: list.size();
来源：http://dali.yj202588.top/Article/details/gtgjteazmu.html

Go:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtyrpplnjb.html

Ruby: arr.length; arr.size
来源：http://dali.jqgufenzy.top/Article/details/gtbvqmzgkd.html

C#:   list.Count;
来源：http://dali.hongshengwenyu.top/Article/details/gttrpqykjn.html

[D07] 切片 / 取子数组
来源：http://dali.pengpengdd.cyou/Article/details/gtwavduivl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258888.top/Article/details/gtjtehintk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jianghu66.top/Article/details/gtpyroazvj.html

JS:   arr.slice(1, 4);
来源：http://dali.yueranfly.top/Article/details/gttcvpqcnl.html

TS:   arr.slice(1, 4);
来源：http://dali.hnqzz.top/Article/details/gttbrqjzpc.html

Java: list.subList(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gtdxaqrpqm.html

Go:   arr[1:4]
来源：http://dali.cucudq.cn/Article/details/gtnhygbdtt.html

Ruby: arr[1, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gtyijvaitv.html

C#:   list.GetRange(1, 3);
来源：http://dali.jiagoushi.top/Article/details/gtaumdjblr.html

[D08] 合并两个数组
来源：http://dali.zdqjudy.top/Article/details/gtqjeleclv.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gtpovafxbv.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258.top/Article/details/gtcnqdgdlm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sweek.top/Article/details/gtwjsffhnh.html

TS:   [...a, ...b];
来源：http://dali.kuanghao11.cn/Article/details/gtywiwrwfa.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.iojbl.cn/Article/details/gtfabtzwnu.html

Go:   append(a, b...)
来源：http://dali.hongshengwenyu.top/Article/details/gtopjgpnkr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.svipenyu.cn/Article/details/gtgicklymk.html

C#:   a.Concat(b).ToList()
来源：http://dali.daxiang520.top/Article/details/gthjbhlebl.html

[D09] 排序（升序）
来源：http://dali.svipenyu.cn/Article/details/gtzmpeyhma.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gtkgdmejhz.html

PHP:  sort($arr);
来源：http://dali.gaohongyu789.top/Article/details/gttepxklnk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sweek.top/Article/details/gtghqiubcz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pycfn.com/Article/details/gtxknznbxl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhengqikj.top/Article/details/gtlkmddemq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gtdrplgddu.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gtcpcdewkp.html

C#:   list.Sort();
来源：http://dali.tanke756.top/Article/details/gtyzfvdpsu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.meibo888.top/Article/details/gtgmbilloz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.kuanghao11.cn/Article/details/gtxygqccxs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhongyouzk.top/Article/details/gtngfqnnwz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gtnairsgod.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gtqosuuwqz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ivvv.top/Article/details/gtujpwoxvz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guowangkeji.top/Article/details/gtazuyjiqn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nwbrower.top/Article/details/gtxendvjvv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxinkj.top/Article/details/gtchsapgmp.html

[D11] 反转数组
来源：http://dali.iojbl.cn/Article/details/gthqcinzvf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sufxvd.cn/Article/details/gtlsnnthfg.html

PHP:  array_reverse($arr);
来源：http://dali.cqqwz.cn/Article/details/gtiwdxmtgd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jiagoushi.top/Article/details/gttkuilqfu.html

TS:   [...arr].reverse();
来源：http://dali.tianlin.xyz/Article/details/gtjbuxblus.html

Java: Collections.reverse(list);
来源：http://dali.tanke756.top/Article/details/gtwfazkkpk.html

Go:   slices.Reverse(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtgvbwhupu.html

Ruby: arr.reverse
来源：http://dali.andypj.xyz/Article/details/gtsgrejhwb.html

C#:   list.Reverse();
来源：http://dali.shuidangran.top/Article/details/gtifrvbpnq.html

[D12] 查找元素下标
来源：http://dali.daria6918.cn/Article/details/gtfaoavxvx.html

Py:   arr.index(x);  x in arr
来源：http://dali.jiagoushi.top/Article/details/gtnxnvmrul.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hysaishi.cn/Article/details/gthuwdwkww.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtejziogpk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.mhx1999.top/Article/details/gtbsesjmgs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yanxiufei.cn/Article/details/gtlavrtitg.html

Go:   slices.Index(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtzoajvxud.html

Ruby: arr.index(x)
来源：http://dali.aibaodan.cn/Article/details/gtsjrjzubf.html

C#:   list.IndexOf(x);
来源：http://dali.smart0.xyz/Article/details/gtvtjrbvfc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.kuanghao11.cn/Article/details/gtofzucouc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.316326.xyz/Article/details/gtozudvrer.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yanxiufei.cn/Article/details/gteshkxgic.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gttaqqvake.html

TS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtztgfabmc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ehwqpu.com/Article/details/gtyjrxxewd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxuanxn.top/Article/details/gtjsrywfgx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxuanxn.top/Article/details/gtapvtwekz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guannengcc.top/Article/details/gtpkilxxmn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gtthbjkpjr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cashguo.top/Article/details/gtrcatgyhu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.svipenyu.cn/Article/details/gtcvmwmjiy.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gtiajpktho.html

TS:   arr.map(x => x * 2)
来源：http://dali.pycfn.com/Article/details/gtbojjyfnv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tianlin.xyz/Article/details/gterpebqfu.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gtgwdxdlpw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gtmwdhmjmf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gzhubu.top/Article/details/gtghtgolfb.html

[D15] 去重
来源：http://dali.guannengcc.top/Article/details/gtftsjqxut.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gtctxckrtt.html

PHP:  array_unique($arr);
来源：http://dali.zhixingplan.top/Article/details/gtzccesxtm.html

JS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gtyndjtfyw.html

TS:   [...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gtkqnkvqbp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cashguo.top/Article/details/gtifyyciaf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.iojbl.cn/Article/details/gthcuwhhsy.html

Ruby: arr.uniq
来源：http://dali.shzxlz.cn/Article/details/gtbpjrgqkr.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtygwgsyux.html

[D16] 求和与平均值
来源：http://dali.yj20258888.top/Article/details/gtxrzmcqfb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtqfbgbjif.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenzaomai.com/Article/details/gtgdrcgfry.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gtyosppcvb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtcxjztwbn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.aibaodan.cn/Article/details/gtavvvuurb.html

Go:   // 手写循环累加
来源：http://dali.zhongyouzk.top/Article/details/gtmbwkvioq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dianchejie.cn/Article/details/gtvyheujjp.html

C#:   list.Sum();  list.Average()
来源：http://dali.jianghu66.top/Article/details/gtjjjtohqa.html

[D17] 最大值与最小值
来源：http://dali.yj202588.top/Article/details/gtpfvqqzyw.html

Py:   max(arr);  min(arr)
来源：http://dali.aizwys.cn/Article/details/gtugvkprjd.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtghgqlxij.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jianghu66.top/Article/details/gtxncschyh.html

TS:   Math.max(...arr);
来源：http://dali.mhx1999.top/Article/details/gtlxcxglzt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtrbuteztl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxinkj.top/Article/details/gtkcmxjxtl.html

Ruby: arr.max;  arr.min
来源：http://dali.aibaodan.cn/Article/details/gtwozqdkjr.html

C#:   list.Max();  list.Min()
来源：http://dali.xinyue.icu/Article/details/gtpsqgstvp.html

[D18] 扁平化嵌套数组
来源：http://dali.mhx1999.top/Article/details/gtfvodaiqf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cdnleiting.top/Article/details/gtnszcabty.html

PHP:  array_merge(...$nested);
来源：http://dali.wangshuangyany.cn/Article/details/gtovftkdtx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.meibo888.top/Article/details/gtnrbhoqpn.html

TS:   nested.flat();
来源：http://dali.ppjwa.cn/Article/details/gtyxcewrfg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cdnleiting.top/Article/details/gtiiqazgso.html

Go:   // 手写双层循环
来源：http://dali.xinyue.icu/Article/details/gtubujbyww.html

Ruby: nested.flatten
来源：http://dali.cheryme.top/Article/details/gtgrqelkzm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtngdwthqi.html

[D19] 按字段分组
来源：http://dali.dashuyun.cn/Article/details/gtovxegkez.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.c1oappe.top/Article/details/gthnplqbby.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daxiang520.top/Article/details/gtkxriuvjp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yueranfly.top/Article/details/gtyvutwcrb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.svipenyu.cn/Article/details/gtgvxocuhf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gaohongyu789.top/Article/details/gtudvurfsp.html

Go:   // 手写 map[string][]T
来源：http://dali.feifeiyinyue.top/Article/details/gtioeoxama.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cashguo.top/Article/details/gtxpgswuwy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shanyushiyangkeji.top/Article/details/gthejdjeqp.html

[D20] 统计每个元素出现次数
来源：http://dali.cdnleiting.top/Article/details/gttzqvrntc.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtcbevtquv.html

PHP:  array_count_values($arr);
来源：http://dali.9152youxi.cn/Article/details/gtarivpljo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gtgdgzbnby.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gtukrinonx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.quarkkingdee.top/Article/details/gtztvzhszx.html

Go:   // 手写 map[T]int
来源：http://dali.yanxiufei.cn/Article/details/gtxmlhywqd.html

Ruby: arr.tally
来源：http://dali.cucudq.cn/Article/details/gtkwcaxjgq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xziqi.cn/Article/details/gtkzoyuxzb.html

[D21] 判断是否包含某元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvhbkqlp.html

Py:   x in arr
来源：http://dali.yvedp.cn/Article/details/gticghbhex.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hfpthk.cn/Article/details/gtqgalawlc.html

JS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gtcrjjpkbh.html

TS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtmbxjnzum.html

Java: list.contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtjkkquxbg.html

Go:   slices.Contains(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtvqlsxlwy.html

Ruby: arr.include?(x)
来源：http://dali.sweek.top/Article/details/gtuqjevvaj.html

C#:   list.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtltpojpny.html

[D22] 复制数组（避免共享引用）
来源：http://dali.svipenyu.cn/Article/details/gtuitdxawp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhengqikj.top/Article/details/gtovrykzky.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xziqi.cn/Article/details/gtavyhfzvc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtkwtvxkha.html

TS:   [...arr];
来源：http://dali.zhengqikj.top/Article/details/gtwqhwgtmr.html

Java: new ArrayList<>(list);
来源：http://dali.gzhubu.top/Article/details/gtxqywqime.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258.top/Article/details/gthudiefiw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jiagoushi.top/Article/details/gthcaekssh.html

C#:   new List<int>(list);
来源：http://dali.jqgfzy.top/Article/details/gtnulizzqi.html

[D23] reduce 累积计算
来源：http://dali.shzxlz.cn/Article/details/gtknakzkbu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.dashuyun.cn/Article/details/gtxjrqyisa.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daria6918.cn/Article/details/gtgcgmdyzz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxayalfd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfmmarnd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ybcxt.top/Article/details/gtrmkojmoh.html

Go:   // 手写循环
来源：http://dali.svipenyu.cn/Article/details/gthozpqrfs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj202588.top/Article/details/gtwtbanbji.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuanzx.com/Article/details/gtjamslysk.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuanzhike.top/Article/details/gtftgzcelb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxuanxn.top/Article/details/gtkiqmqzdq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ydzc1.top/Article/details/gtzqzxijrt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhengqikj.top/Article/details/gtmncmcjia.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yongpay.top/Article/details/gttizhjtgl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.snrcjt.cn/Article/details/gtdctqjzia.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.bjfxy.top/Article/details/gtxhxcwbst.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtehwzjrif.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hywenlv.cn/Article/details/gtpvpumrpq.html

[D25] Set 集合去重与交并差
来源：http://dali.shangyingyoupin.top/Article/details/gtaofzoriv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.bjfxy.top/Article/details/gtyjzaodel.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gtlnpluuwd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hnxiangtu.top/Article/details/gtmnhlfxjx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.316326.xyz/Article/details/gtrnnwxmao.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daria6918.cn/Article/details/gtphvskien.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqrxkidr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pycfn.com/Article/details/gteytsmwlz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daxiang520.top/Article/details/gtrcsklsag.html

[D26] 数组转字符串
来源：http://dali.smart0.xyz/Article/details/gtspegyhhu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtqudnjpqz.html

PHP:  implode(", ", $arr);
来源：http://dali.c1oappe.top/Article/details/gthporgurj.html

JS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtkohbugvn.html

TS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbownqju.html

Java: String.join(", ", list)
来源：http://dali.c1oappe.top/Article/details/gtpodecnck.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigmbhoeq.html

Ruby: arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gtubxuxucm.html

C#:   string.Join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtyrlqaapo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtbxtpnmmv.html

E. 字符串处理
来源：http://dali.hysaishi.cn/Article/details/gtjwhxyvek.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtphnohjlm.html

[E01] 拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtvxhwfvfe.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ybcxt.top/Article/details/gtmmsoeydt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhlqgewr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yonumen.top/Article/details/gtaeowessp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gtmvylpwsl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fzhhl.top/Article/details/gthedahkma.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj202588.top/Article/details/gtliwicfyk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhengqikj.top/Article/details/gtztengyrm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuanzx.com/Article/details/gttdjfemwo.html

[E02] 重复字符串
来源：http://dali.ppjwa.cn/Article/details/gtzjspscqb.html

Py:   "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gtcehaaxzz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jlsjyb.cn/Article/details/gtfwzxmtnk.html

JS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtxyfsjmxf.html

TS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gtasdpqdsv.html

Java: "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtirnpjypp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zdqjudy.top/Article/details/gtzbtznofc.html

Ruby: "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gtzvmuacyf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.havefunace.top/Article/details/gtrskkvayf.html

[E03] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gtofgoovwn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.redwolf501.top/Article/details/gtoohuqxyf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtxdypjdyl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtwjajisye.html

TS:   s.slice(1, 4)
来源：http://dali.nwbrower.top/Article/details/gtqucbqmxy.html

Java: s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtlzaqqmlm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hywenlv.cn/Article/details/gtbzepfgom.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.9152youxi.cn/Article/details/gtrudptyjt.html

C#:   s.Substring(1, 3)
来源：http://dali.cheryme.top/Article/details/gtdyhxhjms.html

[E04] 查找子串位置
来源：http://dali.yangfankeji.com/Article/details/gtxzutgukp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xziqi.cn/Article/details/gtnbtqbaps.html

PHP:  strpos($s, "x");
来源：http://dali.cheryme.top/Article/details/gtnunzsnhm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pycfn.com/Article/details/gtfiyhlqyq.html

TS:   s.indexOf("x")
来源：http://dali.jianghu66.top/Article/details/gtqrpcciez.html

Java: s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtknjebymd.html

Go:   strings.Index(s, "x")
来源：http://dali.chenzaomai.com/Article/details/gtvrmjuolz.html

Ruby: s.index("x")
来源：http://dali.yuxming.cn/Article/details/gtkppbwnro.html

C#:   s.IndexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gtofjhkakb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guowangkeji.top/Article/details/gtrarfqptj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258888.top/Article/details/gtwogiqiit.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqbisvgx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gtyyytppji.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gtxboadfkp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtuhofthli.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkucbkgr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.birdmap.top/Article/details/gtvcgyrwmb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.c1oappe.top/Article/details/gtafmlyxip.html

[E06] 替换子串
来源：http://dali.ydzc1.top/Article/details/gtczblhoaq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ivvv.top/Article/details/gtqtwdkucj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtulxhmrgj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtheddeemf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtjxwquqnc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtujhyvsfy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtpsiclurh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtqtmdmtha.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtjdneeqtw.html

[E07] 按分隔符拆分
来源：http://dali.chenzaomai.com/Article/details/gtpikifgvm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.meibo888.top/Article/details/gttrirfqcr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ivvv.top/Article/details/gtbooiiqcx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258.top/Article/details/gtnbaqtxzt.html

TS:   s.split(",")
来源：http://dali.yuxming.cn/Article/details/gtnarsfkju.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guowangkeji.top/Article/details/gtxbzfjffz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nwbrower.top/Article/details/gtlivgrveg.html

Ruby: s.split(",");  s.split
来源：http://dali.yvedp.cn/Article/details/gtliuxeyho.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhiwuduotai.top/Article/details/gtkppyazwo.html

[E08] 数组按分隔符合并
来源：http://dali.nwbrower.top/Article/details/gtlrcwyyht.html

Py:   ",".join(items)
来源：http://dali.jinqigufen.top/Article/details/gtpwuhvpuc.html

PHP:  implode(",", $items);
来源：http://dali.feifeiyinyue.top/Article/details/gtavgagrnz.html

JS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtadhvjshg.html

TS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtgdgytjom.html

Java: String.join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gtceeurmkt.html

Go:   strings.Join(items, ",")
来源：http://dali.316326.xyz/Article/details/gtquzmiewk.html

Ruby: items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtrledhvea.html

C#:   string.Join(",", items)
来源：http://dali.mhx1999.top/Article/details/gtwyibjxia.html

[E09] 去除所有空白字符
来源：http://dali.hnqzz.top/Article/details/gtmavixcgw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yonumen.top/Article/details/gtzykoygdg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.daria6918.cn/Article/details/gtfqwskqkz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtuidulowt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gtaiqqcsca.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guannengcc.top/Article/details/gtjlpghnty.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daria6918.cn/Article/details/gtjkigwhqn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daria6918.cn/Article/details/gtksyheeag.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtuevrrwtq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.9152youxi.cn/Article/details/gtylysdpdo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtbfotpphh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangshuangyany.cn/Article/details/gthqrkycph.html

JS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtftkhfrqn.html

TS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtafzuyxtf.html

Java: String.format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gttrwsntgl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtqhsublxq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtohuhvtwv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.haohaochexian.top/Article/details/gtdcwxasui.html

[E11] 反转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtyirmjjrn.html

Py:   s[::-1]
来源：http://dali.yongpay.top/Article/details/gtxqdhpixg.html

PHP:  strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gtiwymnvrl.html

JS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtbdlatixk.html

TS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gteqhkzzpn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj202588.top/Article/details/gtcfoursil.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zdqjudy.top/Article/details/gtrmlukifo.html

Ruby: s.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjglmdhhg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gtlbbpncte.html

[E12] 统计某字符出现次数
来源：http://dali.kuanghao11.cn/Article/details/gtmxokedbd.html

Py:   s.count("a")
来源：http://dali.meibo888.top/Article/details/gtlcsxwgsj.html

PHP:  substr_count($s, "a");
来源：http://dali.9152youxi.cn/Article/details/gtlhsjtmdk.html

JS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gtdtddtlih.html

TS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtkutizebh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhengqikj.top/Article/details/gtjvrotgrz.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxuanxn.top/Article/details/gttdhrojqp.html

Ruby: s.count("a")
来源：http://dali.tanke756.top/Article/details/gtrticehyw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.mhx1999.top/Article/details/gtuioglkrb.html

[E13] 逐字符遍历
来源：http://dali.zdqjudy.top/Article/details/gtftgsveub.html

Py:   for ch in s: print(ch)
来源：http://dali.ppjwa.cn/Article/details/gtiapiwwzm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fzhhl.top/Article/details/gtmsknrpov.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gtfuurxhci.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtgvgxbiza.html


<!-- 参考信息 -->