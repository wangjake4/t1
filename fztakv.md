代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gtkavtjorv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtjfumqdlu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.iojbl.cn/Article/details/gtogowyieg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ybcxt.top/Article/details/gtsvdndxty.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gtrfhcqyud.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtlcrjsxoo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtngazhbby.html

[D06] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gttcpwefbm.html

Py:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gtfgnmbtge.html

PHP:  count($arr);
来源：http://dali.jyoumei.cn/Article/details/gtbnixhjzf.html

JS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gtokqnksfw.html

TS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gtsaxakddi.html

Java: list.size();
来源：http://dali.yuxming.cn/Article/details/gtnkbujuff.html

Go:   len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gteoztenfr.html

Ruby: arr.length; arr.size
来源：http://dali.jqgufenzy.top/Article/details/gtrqjbwcbr.html

C#:   list.Count;
来源：http://dali.wangshuangyany.cn/Article/details/gtwlvzczli.html

[D07] 切片 / 取子数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhgkoqzn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cdnleiting.top/Article/details/gtawjvelof.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yueranfly.top/Article/details/gtrkqsdufh.html

JS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtdnncxyfo.html

TS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtjhxogdpq.html

Java: list.subList(1, 4);
来源：http://dali.yj202588.top/Article/details/gtbinshuqb.html

Go:   arr[1:4]
来源：http://dali.zhengqikj.top/Article/details/gtgbsmvdsp.html

Ruby: arr[1, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehdeuens.html

C#:   list.GetRange(1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtltbxscoc.html

[D08] 合并两个数组
来源：http://dali.ehwqpu.com/Article/details/gtikzwktke.html

Py:   a + b;  a.extend(b)
来源：http://dali.xylfe.cn/Article/details/gtszvszimw.html

PHP:  array_merge($a, $b);
来源：http://dali.tianlin.xyz/Article/details/gtlrrljzvi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenlongwang.top/Article/details/gtqclrquum.html

TS:   [...a, ...b];
来源：http://dali.yj202588.top/Article/details/gtkpycmrwu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258888.top/Article/details/gtygnlnmjp.html

Go:   append(a, b...)
来源：http://dali.9152youxi.cn/Article/details/gtgcvjqsqu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxyzzaqxb.html

C#:   a.Concat(b).ToList()
来源：http://dali.birdmap.top/Article/details/gthxselqxb.html

[D09] 排序（升序）
来源：http://dali.hywenlv.cn/Article/details/gtpmxyhocc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gtxbgaofer.html

PHP:  sort($arr);
来源：http://dali.yuanzhike.top/Article/details/gtidtyishy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xinyue.icu/Article/details/gtdpboqefx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuxming.cn/Article/details/gthltyyzud.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tanke756.top/Article/details/gtjdvtkgga.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gtjwpgteox.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtrvszmrns.html

C#:   list.Sort();
来源：http://dali.xuanzx.com/Article/details/gtlhygdzgw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shuidangran.top/Article/details/gtbyiukqgn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxuanxn.top/Article/details/gtsdwawlix.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dashuyun.cn/Article/details/gtvfgubnor.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gtgrkyedly.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorhopqij.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pycfn.com/Article/details/gttwzjixbh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigufen.top/Article/details/gttjizghid.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hammf.cn/Article/details/gtktqbfxxl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.vqdsnc.cn/Article/details/gtryyauuup.html

[D11] 反转数组
来源：http://dali.zhixingplan.top/Article/details/gttjtdpdfi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fengsongda.top/Article/details/gtfhkkrlyl.html

PHP:  array_reverse($arr);
来源：http://dali.xziqi.cn/Article/details/gtvitsgncf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sweek.top/Article/details/gtubpmwgrr.html

TS:   [...arr].reverse();
来源：http://dali.hammf.cn/Article/details/gtryigslmt.html

Java: Collections.reverse(list);
来源：http://dali.zhoulong.xyz/Article/details/gtawiybkvq.html

Go:   slices.Reverse(arr)
来源：http://dali.ydzc1.top/Article/details/gtacxbhsgz.html

Ruby: arr.reverse
来源：http://dali.snrcjt.cn/Article/details/gtaspiwipm.html

C#:   list.Reverse();
来源：http://dali.0kj1m.cn/Article/details/gtuhyjmbxg.html

[D12] 查找元素下标
来源：http://dali.chenzaomai.com/Article/details/gtzwzpuzfj.html

Py:   arr.index(x);  x in arr
来源：http://dali.xziqi.cn/Article/details/gtiqudrsxb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangdashe.top/Article/details/gttvbapmoy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gtwakcfjdu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtjfizkuwc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jlsjyb.cn/Article/details/gtwepwalih.html

Go:   slices.Index(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthridngbb.html

Ruby: arr.index(x)
来源：http://dali.gaohongyu789.top/Article/details/gtimhjbznc.html

C#:   list.IndexOf(x);
来源：http://dali.hfpthk.cn/Article/details/gtclowdlwc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.0kj1m.cn/Article/details/gttwkhifnp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dashuyun.cn/Article/details/gtzeksvjsf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jianghu66.top/Article/details/gtkggjkamj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtdboafmkh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gtmdnjfqcb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gogol.net.cn/Article/details/gtgtqwquby.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guannengcc.top/Article/details/gtnrdrttnw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sufxvd.cn/Article/details/gtqrswtzlt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtumafoohi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yonumen.top/Article/details/gtiotjowom.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.haohaochexian.top/Article/details/gtatlbnffo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aizwys.cn/Article/details/gtpzrxniim.html

JS:   arr.map(x => x * 2)
来源：http://dali.zdqjudy.top/Article/details/gtjphwakzs.html

TS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gtploqglrn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jyoumei.cn/Article/details/gtzzndxoai.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gtiflxiddw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aizwys.cn/Article/details/gtfgiegajw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtdveclilm.html

[D15] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gthbnccbes.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ppjwa.cn/Article/details/gtttpkqhds.html

PHP:  array_unique($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtgneltfyc.html

JS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gthshnnsqp.html

TS:   [...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gttvjlpsod.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgtfusoy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fengsongda.top/Article/details/gtqvoqmqqa.html

Ruby: arr.uniq
来源：http://dali.zhongyouzk.top/Article/details/gtfgutbtgd.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtdfaazuaa.html

[D16] 求和与平均值
来源：http://dali.tianlin.xyz/Article/details/gtitdiyssp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sysykeji.top/Article/details/gtskuhtvrh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ydzc1.top/Article/details/gtshtukylt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gteukukdpq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gtxogxodhv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazqxqyda.html

Go:   // 手写循环累加
来源：http://dali.pycfn.com/Article/details/gtzyunapvr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shzxlz.cn/Article/details/gtsoooovgl.html

C#:   list.Sum();  list.Average()
来源：http://dali.havefunace.top/Article/details/gtotcabudi.html

[D17] 最大值与最小值
来源：http://dali.xuetiantiany.cn/Article/details/gtoessopnm.html

Py:   max(arr);  min(arr)
来源：http://dali.redwolf501.top/Article/details/gtcucjuide.html

PHP:  max($arr);  min($arr);
来源：http://dali.tianlin.xyz/Article/details/gtqebypgvq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuxming.cn/Article/details/gtbqfqisek.html

TS:   Math.max(...arr);
来源：http://dali.bjfxy.top/Article/details/gtnabfnfbi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dianchejie.cn/Article/details/gtsjcrdnac.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daxiang520.top/Article/details/gtemjvrlrj.html

Ruby: arr.max;  arr.min
来源：http://dali.zycfv.cn/Article/details/gtzjwyrvdb.html

C#:   list.Max();  list.Min()
来源：http://dali.zhoulong.xyz/Article/details/gtxvwxldgf.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxinkj.top/Article/details/gtheasfylt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258.top/Article/details/gtawtjfzpu.html

PHP:  array_merge(...$nested);
来源：http://dali.sxryk.cn/Article/details/gtdcxgfhns.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoclgtmex.html

TS:   nested.flat();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwwcmauo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dianchejie.cn/Article/details/gtrsflohka.html

Go:   // 手写双层循环
来源：http://dali.0kj1m.cn/Article/details/gttmhtjwly.html

Ruby: nested.flatten
来源：http://dali.tian-w.cn/Article/details/gtqnebqumv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.andypj.xyz/Article/details/gtpnzpajxg.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gtgzufjkly.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.0kj1m.cn/Article/details/gtttjoimzg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fzhhl.top/Article/details/gtnxrgarfs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xinyue.icu/Article/details/gtobwpdgun.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ydzc1.top/Article/details/gtdplzcxjk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhaelhok.html

Go:   // 手写 map[string][]T
来源：http://dali.vqdsnc.cn/Article/details/gttrokgocl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxinkj.top/Article/details/gtqvfejqto.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ehwqpu.com/Article/details/gtcpodpibe.html

[D20] 统计每个元素出现次数
来源：http://dali.cheryme.top/Article/details/gtpjpmlmhw.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gtkitfkslu.html

PHP:  array_count_values($arr);
来源：http://dali.birdmap.top/Article/details/gtszombepk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gtmnswzyld.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gteuhwljaz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.c1oappe.top/Article/details/gtkvxiowmg.html

Go:   // 手写 map[T]int
来源：http://dali.yj20258.top/Article/details/gtosmvvyte.html

Ruby: arr.tally
来源：http://dali.ppjwa.cn/Article/details/gtdylsjyql.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.meibo888.top/Article/details/gtupycdogy.html

[D21] 判断是否包含某元素
来源：http://dali.jqgfzy.top/Article/details/gtzyvanqwv.html

Py:   x in arr
来源：http://dali.meibo888.top/Article/details/gtkirvxrcl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinqigufen.top/Article/details/gtecicrxaw.html

JS:   arr.includes(x)
来源：http://dali.shuidangran.top/Article/details/gtpqcegiye.html

TS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gtkmibmpcw.html

Java: list.contains(x)
来源：http://dali.hnqzz.top/Article/details/gtivdycaaq.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtkbrrpaqm.html

Ruby: arr.include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdevwges.html

C#:   list.Contains(x)
来源：http://dali.cheryme.top/Article/details/gttwauomql.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cucudq.cn/Article/details/gtifnjlznh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhengqikj.top/Article/details/gtjfnzocoa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shuidangran.top/Article/details/gtmqgkybkl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqnyudxg.html

TS:   [...arr];
来源：http://dali.nwbrower.top/Article/details/gtrwazrjoc.html

Java: new ArrayList<>(list);
来源：http://dali.svipenyu.cn/Article/details/gtsxfgelpx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gtpypavucn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daxiang520.top/Article/details/gtlprhwzyq.html

C#:   new List<int>(list);
来源：http://dali.zhixingplan.top/Article/details/gtzistyozv.html

[D23] reduce 累积计算
来源：http://dali.cashguo.top/Article/details/gtwynvoefx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sysykeji.top/Article/details/gtwlhejtqs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.bjfxy.top/Article/details/gtgvyfrnpw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gtmuvxurpg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gtkpwycmcm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shuidangran.top/Article/details/gteemhkicl.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gtzvttwpup.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcljwjzox.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daria6918.cn/Article/details/gtrkkkzmga.html

[D24] 字典 / Map 基本操作
来源：http://dali.gzhubu.top/Article/details/gtoxtpoowm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daxiang520.top/Article/details/gtjekiirip.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dashuyun.cn/Article/details/gtvxyjoaip.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtcvukhxly.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtkrvszwgy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tianlin.xyz/Article/details/gtwuehtrbk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gzhubu.top/Article/details/gtngncoxlv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gaohongyu789.top/Article/details/gtivpfdrtb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenzaomai.com/Article/details/gtzbvidwgo.html

[D25] Set 集合去重与交并差
来源：http://dali.iojbl.cn/Article/details/gtdtbrriov.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.bjfxy.top/Article/details/gtapponyhd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllwybrqt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ppjwa.cn/Article/details/gtqrkhevic.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.fengsongda.top/Article/details/gtsaewqrqb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cheryme.top/Article/details/gtzwvigvsl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.vqdsnc.cn/Article/details/gtddvrvuxf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.meibo888.top/Article/details/gtniqxtrgo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ybcxt.top/Article/details/gtqsypcenn.html

[D26] 数组转字符串
来源：http://dali.yangfankeji.com/Article/details/gthvtebnpg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hfpthk.cn/Article/details/gtcemjsieu.html

PHP:  implode(", ", $arr);
来源：http://dali.tian-w.cn/Article/details/gtsldaxxgh.html

JS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtqerxaubo.html

TS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gthwchjijk.html

Java: String.join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtbahyoute.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aibaodan.cn/Article/details/gtsqfrqzsw.html

Ruby: arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtijrbnfpp.html

C#:   string.Join(", ", list)
来源：http://dali.bjfxy.top/Article/details/gtcfimnovn.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtryefjsuz.html

E. 字符串处理
来源：http://dali.sxryk.cn/Article/details/gtensvsdyz.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtyqhzaiob.html

[E01] 拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtewafpymq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shzxlz.cn/Article/details/gtqsopramx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigfzy.top/Article/details/gtjtkvtgah.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gtjexwqjfr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gtyfvzjfpg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhongyouzk.top/Article/details/gtejqoxoez.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtzfagvrar.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sufxvd.cn/Article/details/gtodpzgbnl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtzccfdqxg.html

[E02] 重复字符串
来源：http://dali.bjfxy.top/Article/details/gtirsxqpco.html

Py:   "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gtjfdlmghb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.0kj1m.cn/Article/details/gtnuepctez.html

JS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gtqpsrilxp.html

TS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtbraghfiu.html

Java: "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtxkdmovpi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hammf.cn/Article/details/gtomiefpkg.html

Ruby: "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gtuxmeuzsn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhiwuduotai.top/Article/details/gtucfhoroy.html

[E03] 截取子串
来源：http://dali.wangdashe.top/Article/details/gtzjbpxmcd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yueranfly.top/Article/details/gtwsjkikij.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtwuvjvwnr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtxofsaphj.html

TS:   s.slice(1, 4)
来源：http://dali.bjfxy.top/Article/details/gtbnwffmca.html

Java: s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtispxlfhs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gtipkjdret.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhengqikj.top/Article/details/gtwqvlunqq.html

C#:   s.Substring(1, 3)
来源：http://dali.daria6918.cn/Article/details/gtoesowhkx.html

[E04] 查找子串位置
来源：http://dali.hywenlv.cn/Article/details/gtdztgywwz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gtpllotvcr.html

PHP:  strpos($s, "x");
来源：http://dali.xuetiantiany.cn/Article/details/gtdsawworv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xylfe.cn/Article/details/gttrbkkohp.html

TS:   s.indexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gtistbdvbi.html

Java: s.indexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gtolfroami.html

Go:   strings.Index(s, "x")
来源：http://dali.andypj.xyz/Article/details/gtpkjbfnwg.html

Ruby: s.index("x")
来源：http://dali.jianghu66.top/Article/details/gtvmfwnflk.html

C#:   s.IndexOf("x")
来源：http://dali.redwolf501.top/Article/details/gtdxksqgin.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.0kj1m.cn/Article/details/gtjeltltaw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.havefunace.top/Article/details/gtkelgwvvi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cqqwz.cn/Article/details/gtoejubmbs.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkagqmmvu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ivvv.top/Article/details/gtkodffaip.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphklvisr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hongshengwenyu.top/Article/details/gtzajxgqpa.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdixkvnst.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtpgmcgbln.html

[E06] 替换子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqaqjwfji.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gthzfodnme.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jiagoushi.top/Article/details/gtiepltckf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtwvpcjpgm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gttlzggwri.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzobmtryx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.birdmap.top/Article/details/gtbtivtdqh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cashguo.top/Article/details/gtothivamf.html

C#:   s.Replace("a", "b")
来源：http://dali.ivvv.top/Article/details/gtemgrocyo.html

[E07] 按分隔符拆分
来源：http://dali.xziqi.cn/Article/details/gttkfnytju.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hongshengwenyu.top/Article/details/gtvmabtssx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zycfv.cn/Article/details/gtkitlnpfq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gotoacloud.top/Article/details/gttsqusvgq.html

TS:   s.split(",")
来源：http://dali.hywenlv.cn/Article/details/gtspmnjxuo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhiwuduotai.top/Article/details/gteugpxbsg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenzaomai.com/Article/details/gtllptfjdv.html

Ruby: s.split(",");  s.split
来源：http://dali.9152youxi.cn/Article/details/gtdhaoraxa.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnqzz.top/Article/details/gtxitiwbjj.html

[E08] 数组按分隔符合并
来源：http://dali.xylfe.cn/Article/details/gtyoiqyzgj.html

Py:   ",".join(items)
来源：http://dali.ppjwa.cn/Article/details/gthnhbhlhg.html

PHP:  implode(",", $items);
来源：http://dali.mhx1999.top/Article/details/gtbyiwstvt.html

JS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtsbwimmhg.html

TS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtkuncofry.html

Java: String.join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gtukffdwwo.html

Go:   strings.Join(items, ",")
来源：http://dali.jlsjyb.cn/Article/details/gtdstuahqe.html

Ruby: items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtltjprszw.html

C#:   string.Join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gtwbiawipp.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gthdlalxzm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sxryk.cn/Article/details/gtyakputdx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxinkj.top/Article/details/gttfxbaydf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtbjvplnyl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gtxekkwsot.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagnelehr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.feifeiyinyue.top/Article/details/gtvljzizlk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtamjyppwk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gtytbfpukz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ehwqpu.com/Article/details/gtpsnsqcfs.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpyjpodu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guowangkeji.top/Article/details/gtpliyapbc.html

JS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtrrafdjqf.html

TS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtqitudggx.html

Java: String.format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtgwtmneky.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtosxdrclt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtsrpowenk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xuetiantiany.cn/Article/details/gtezhlzuhq.html

[E11] 反转字符串
来源：http://dali.hfpthk.cn/Article/details/gtmuklnczo.html

Py:   s[::-1]
来源：http://dali.ydzc1.top/Article/details/gtdfjhinos.html

PHP:  strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdmcrnjf.html

JS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtohppnrrp.html

TS:   [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtwqczeysp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtxugwiuox.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aibaodan.cn/Article/details/gtkbrvkwmy.html

Ruby: s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfuhuwxhs.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zycfv.cn/Article/details/gtzcjvrsdj.html

[E12] 统计某字符出现次数
来源：http://dali.hnqzz.top/Article/details/gtszmguffo.html

Py:   s.count("a")
来源：http://dali.tanke756.top/Article/details/gtzqqyxsrl.html


<!-- 参考信息 -->