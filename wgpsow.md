代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shzxlz.cn/Article/details/gtspohkwdw.html

TS:   arr.splice(0, 1);
来源：http://dali.hfpthk.cn/Article/details/gtcxkvfngt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aizwys.cn/Article/details/gtrfpxjlzu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhttwzbb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.kuanghao11.cn/Article/details/gtrttndnob.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cucudq.cn/Article/details/gtvepchhvc.html

[D05] 访问与修改元素
来源：http://dali.zhoulong.xyz/Article/details/gtpzbzyodd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtfhrcywmw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gtxhozmyjd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gtywgmghev.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhiwuduotai.top/Article/details/gtoiwujmwp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daxiang520.top/Article/details/gtrytvwkhn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtfvfrukhd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtdsmibqkc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cashguo.top/Article/details/gttrubrall.html

[D06] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gtqnxomsry.html

Py:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gtgrblwtcu.html

PHP:  count($arr);
来源：http://dali.hywenlv.cn/Article/details/gtnfcjymaf.html

JS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gtdrmhhodh.html

TS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gtjbrpzydr.html

Java: list.size();
来源：http://dali.yongpay.top/Article/details/gtihfbgpgr.html

Go:   len(arr)
来源：http://dali.shzxlz.cn/Article/details/gtmezxcfki.html

Ruby: arr.length; arr.size
来源：http://dali.guannengcc.top/Article/details/gteiltbbyb.html

C#:   list.Count;
来源：http://dali.zhiwuduotai.top/Article/details/gtnzjuooiy.html

[D07] 切片 / 取子数组
来源：http://dali.9152youxi.cn/Article/details/gtgsznjldb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hammf.cn/Article/details/gtolsrruis.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sweek.top/Article/details/gtkbmfvwcz.html

JS:   arr.slice(1, 4);
来源：http://dali.xylfe.cn/Article/details/gtzxnujsna.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjdkowvj.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqaympco.html

Go:   arr[1:4]
来源：http://dali.hfpthk.cn/Article/details/gtdzhlodye.html

Ruby: arr[1, 3]
来源：http://dali.vqdsnc.cn/Article/details/gthoqcyhvi.html

C#:   list.GetRange(1, 3);
来源：http://dali.cashguo.top/Article/details/gtauzyapmj.html

[D08] 合并两个数组
来源：http://dali.cashguo.top/Article/details/gtmfogsnou.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtqrwismhb.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258888.top/Article/details/gttydeehiv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.9152youxi.cn/Article/details/gtwvtlofya.html

TS:   [...a, ...b];
来源：http://dali.yuanzhike.top/Article/details/gtarsrthpe.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hysaishi.cn/Article/details/gtpixeqopo.html

Go:   append(a, b...)
来源：http://dali.svipenyu.cn/Article/details/gtqquprhvv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinqigufen.top/Article/details/gtladxxlsm.html

C#:   a.Concat(b).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gttssajbtf.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gtqnnctilv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gtvbtcsubg.html

PHP:  sort($arr);
来源：http://dali.cheryme.top/Article/details/gtxyztlkkr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nanxuanxn.top/Article/details/gtosavucyn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dianchejie.cn/Article/details/gtnxvvlboh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yangfankeji.com/Article/details/gterpovfej.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gtpznlytpg.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gtjoypyent.html

C#:   list.Sort();
来源：http://dali.nwbrower.top/Article/details/gtsplgbbjt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj20258888.top/Article/details/gtwdugokbx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj20258.top/Article/details/gtclmzuqst.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ybcxt.top/Article/details/gtmzykvhpo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gtjgewthsz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtclrqdrcf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sufxvd.cn/Article/details/gtglosffkn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigfzy.top/Article/details/gtgpzteqhd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgfzy.top/Article/details/gtowewsmdc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.quarkkingdee.top/Article/details/gtgmsqegmy.html

[D11] 反转数组
来源：http://dali.andypj.xyz/Article/details/gtcvllevnf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dianchejie.cn/Article/details/gtjjpcxkzp.html

PHP:  array_reverse($arr);
来源：http://dali.ppjwa.cn/Article/details/gtwckmmtmn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhengqikj.top/Article/details/gtytydsbrt.html

TS:   [...arr].reverse();
来源：http://dali.yvedp.cn/Article/details/gtqemdkrxa.html

Java: Collections.reverse(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqwkyptv.html

Go:   slices.Reverse(arr)
来源：http://dali.bjfxy.top/Article/details/gtmmeuadsa.html

Ruby: arr.reverse
来源：http://dali.aibaodan.cn/Article/details/gtmdmnwreb.html

C#:   list.Reverse();
来源：http://dali.hammf.cn/Article/details/gtcxbscdei.html

[D12] 查找元素下标
来源：http://dali.guowangkeji.top/Article/details/gtmdzwmdge.html

Py:   arr.index(x);  x in arr
来源：http://dali.ehwqpu.com/Article/details/gtdcptgvdx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.svipenyu.cn/Article/details/gtohwnymup.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nwbrower.top/Article/details/gtallnhzzc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gtrkcmpifd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sxryk.cn/Article/details/gtebpbbrks.html

Go:   slices.Index(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtgarxrjas.html

Ruby: arr.index(x)
来源：http://dali.hammf.cn/Article/details/gtpqgljnbw.html

C#:   list.IndexOf(x);
来源：http://dali.pengpengdd.cyou/Article/details/gttkomlgpl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.mhx1999.top/Article/details/gtpxlhoflg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtohvquzcy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jianghu66.top/Article/details/gtxjnypwrl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtlngyzcxk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gthnatsifl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aibaodan.cn/Article/details/gtyxcjvxoj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dashuyun.cn/Article/details/gtizyhywtx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangshuangyany.cn/Article/details/gtbnocpson.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtsdhncjnx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gtcsjndlcg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hywenlv.cn/Article/details/gtpohikwmk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guowangkeji.top/Article/details/gtetavayrc.html

JS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gtzhhfashq.html

TS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gtpvvupbes.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.iojbl.cn/Article/details/gtevlgtads.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbknmgkvc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhengqikj.top/Article/details/gtncmpcaab.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtzpcboxyk.html

[D15] 去重
来源：http://dali.0kj1m.cn/Article/details/gteicpyfas.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gthxysbcsc.html

PHP:  array_unique($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtpdbxcuaa.html

JS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtjehtynhj.html

TS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gtowllretz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangtech.top/Article/details/gtnoybnbjq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangshuangyany.cn/Article/details/gtrlvxgwzg.html

Ruby: arr.uniq
来源：http://dali.jiagoushi.top/Article/details/gtcdbgjrbc.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgfzy.top/Article/details/gtiuopxozu.html

[D16] 求和与平均值
来源：http://dali.pycfn.com/Article/details/gtxvvrwbml.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yueranfly.top/Article/details/gtxesvzctn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtmmbddlkv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gtfbsuxhcq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gtilxlinnu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hysaishi.cn/Article/details/gtobarbawe.html

Go:   // 手写循环累加
来源：http://dali.hammf.cn/Article/details/gtytyjppxy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jlsjyb.cn/Article/details/gtadybwtka.html

C#:   list.Sum();  list.Average()
来源：http://dali.xylfe.cn/Article/details/gtrtkrfnho.html

[D17] 最大值与最小值
来源：http://dali.yj202588.top/Article/details/gttrzbutsx.html

Py:   max(arr);  min(arr)
来源：http://dali.guannengcc.top/Article/details/gtkexuydkq.html

PHP:  max($arr);  min($arr);
来源：http://dali.ybcxt.top/Article/details/gtxzogfyza.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jianghu66.top/Article/details/gtzjdkikan.html

TS:   Math.max(...arr);
来源：http://dali.aibaodan.cn/Article/details/gtzlavyqmb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aizwys.cn/Article/details/gtlqtwjlbo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtsmgfgwvx.html

Ruby: arr.max;  arr.min
来源：http://dali.sufxvd.cn/Article/details/gtlgbgxulx.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258888.top/Article/details/gtznlcprpo.html

[D18] 扁平化嵌套数组
来源：http://dali.haohaochexian.top/Article/details/gtdjlobyfo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hammf.cn/Article/details/gtcqbzdzfv.html

PHP:  array_merge(...$nested);
来源：http://dali.pengpengdd.cyou/Article/details/gtvkotrkwc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgfzy.top/Article/details/gtttribhsz.html

TS:   nested.flat();
来源：http://dali.ivvv.top/Article/details/gthknlkzux.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvndyngoe.html

Go:   // 手写双层循环
来源：http://dali.quarkkingdee.top/Article/details/gtasaobvwj.html

Ruby: nested.flatten
来源：http://dali.yvedp.cn/Article/details/gttmfwmlib.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzuhgxjlp.html

[D19] 按字段分组
来源：http://dali.xuetiantiany.cn/Article/details/gtqurxzijs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gotoacloud.top/Article/details/gtkhpxybez.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.redwolf501.top/Article/details/gtfhdzmtoe.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangdashe.top/Article/details/gthxhkmsic.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gtyzddhugs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tian-w.cn/Article/details/gtjyrzycbi.html

Go:   // 手写 map[string][]T
来源：http://dali.jinqigfzy.top/Article/details/gtuoyatbzf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aibaodan.cn/Article/details/gtrtzczvsh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.9152youxi.cn/Article/details/gtosdytdrr.html

[D20] 统计每个元素出现次数
来源：http://dali.bjfxy.top/Article/details/gthwhzgovl.html

Py:   Counter(arr)
来源：http://dali.birdmap.top/Article/details/gtogayzaxh.html

PHP:  array_count_values($arr);
来源：http://dali.zhengqikj.top/Article/details/gtljuvbuch.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtxpjtqfyr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtvriumdge.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhixingplan.top/Article/details/gthlbfplae.html

Go:   // 手写 map[T]int
来源：http://dali.zhiwuduotai.top/Article/details/gtkwmxycqx.html

Ruby: arr.tally
来源：http://dali.vqdsnc.cn/Article/details/gtswxkjjqg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.bjfxy.top/Article/details/gtzcdpwyog.html

[D21] 判断是否包含某元素
来源：http://dali.guannengcc.top/Article/details/gtkivaychc.html

Py:   x in arr
来源：http://dali.yuxming.cn/Article/details/gtcrtolzog.html

PHP:  in_array($x, $arr, true);
来源：http://dali.mhx1999.top/Article/details/gtmaqjrjes.html

JS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gtdlyrwvuw.html

TS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtjkxphysf.html

Java: list.contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtbdzrlyle.html

Go:   slices.Contains(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtzacbciyj.html

Ruby: arr.include?(x)
来源：http://dali.jyoumei.cn/Article/details/gtrafomgcz.html

C#:   list.Contains(x)
来源：http://dali.nwbrower.top/Article/details/gtubbvdxvu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hysaishi.cn/Article/details/gtpgaxzhhk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xinyue.icu/Article/details/gtatiieavb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangshuangyany.cn/Article/details/gtlgwvlgrh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sufxvd.cn/Article/details/gtcuftdkam.html

TS:   [...arr];
来源：http://dali.wangshuangyany.cn/Article/details/gtpnrfiwjc.html

Java: new ArrayList<>(list);
来源：http://dali.wangdashe.top/Article/details/gtciiffrhu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.0kj1m.cn/Article/details/gtzgpaleaz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhengqikj.top/Article/details/gtaoetdmuq.html

C#:   new List<int>(list);
来源：http://dali.nanxuanxn.top/Article/details/gtdtikyvhw.html

[D23] reduce 累积计算
来源：http://dali.sxryk.cn/Article/details/gtpkanzxmh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlnpnrajc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtwtmzfhie.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gtxnayfupr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gtilurpusi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tian-w.cn/Article/details/gtkaubaitp.html

Go:   // 手写循环
来源：http://dali.aizwys.cn/Article/details/gtdtzkbjuz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxinkj.top/Article/details/gtleexcxvh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.wangdashe.top/Article/details/gtqrplsszz.html

[D24] 字典 / Map 基本操作
来源：http://dali.pycfn.com/Article/details/gtgmrwrnrp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj20258888.top/Article/details/gtgipcxjxj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtpamvdpvo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hfpthk.cn/Article/details/gtjrhgwcis.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtkcnnmxdj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tian-w.cn/Article/details/gtbspportj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pengpengdd.cyou/Article/details/gtdtssrviy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxidqywn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ehwqpu.com/Article/details/gttxmlhdue.html

[D25] Set 集合去重与交并差
来源：http://dali.ydzc1.top/Article/details/gtbczbtmzz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.havefunace.top/Article/details/gtscfhpptc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gtcaizelvn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangdashe.top/Article/details/gtqwzbwxbh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gaohongyu789.top/Article/details/gtqaqaieed.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ehwqpu.com/Article/details/gtctodlmix.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tanke756.top/Article/details/gtbiilcimm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhongyouzk.top/Article/details/gtacsmrnzm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gtvlxufabg.html

[D26] 数组转字符串
来源：http://dali.xinyue.icu/Article/details/gtwrfduank.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cdnleiting.top/Article/details/gtoscvsedn.html

PHP:  implode(", ", $arr);
来源：http://dali.dashuyun.cn/Article/details/gtgcvplrcw.html

JS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtvlvcfoqa.html

TS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gtbnnllpwg.html

Java: String.join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gtnrmyiaaz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xziqi.cn/Article/details/gtjnyqdbue.html

Ruby: arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gtfpvjjqhd.html

C#:   string.Join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gtfrxkhxpn.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtiirtstjq.html

E. 字符串处理
来源：http://dali.sweek.top/Article/details/gtkbicyqbc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtmsvojfap.html

[E01] 拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gteknzcaty.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hammf.cn/Article/details/gtaqaucnzi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhprdktn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gteonnpoks.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gtppmzsgbr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuanzhike.top/Article/details/gtfbnpomov.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gttfztsmqq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhoulong.xyz/Article/details/gtobdbnzma.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtxchqvamf.html

[E02] 重复字符串
来源：http://dali.havefunace.top/Article/details/gtwpdcwevi.html

Py:   "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gtnnsfgfzq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnxiangtu.top/Article/details/gtzkskijbu.html

JS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtbyqufufw.html

TS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtnzcyrzth.html

Java: "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtppsgkhpt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxrsooeu.html

Ruby: "ab" * 3
来源：http://dali.316326.xyz/Article/details/gtamiqzeon.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsomdmxk.html

[E03] 截取子串
来源：http://dali.jlsjyb.cn/Article/details/gtenhoswtb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.snrcjt.cn/Article/details/gtlgayuumd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtmqkdzhac.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtprlghdcm.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtldzoxyqd.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtmaxdweql.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cucudq.cn/Article/details/gtjrebxpkw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yanxiufei.cn/Article/details/gtqkymdyuq.html

C#:   s.Substring(1, 3)
来源：http://dali.dianchejie.cn/Article/details/gtouvbyojg.html

[E04] 查找子串位置
来源：http://dali.hywenlv.cn/Article/details/gtmfykpqcb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfuyxfho.html

PHP:  strpos($s, "x");
来源：http://dali.dashuyun.cn/Article/details/gtzrspqnde.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tianlin.xyz/Article/details/gtotgxngcj.html

TS:   s.indexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gttxybofoz.html

Java: s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gtjbfmcrun.html

Go:   strings.Index(s, "x")
来源：http://dali.ydzc1.top/Article/details/gtofqfoowc.html

Ruby: s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtamtkjwoc.html

C#:   s.IndexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtkzuchaum.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhongyouzk.top/Article/details/gtpzdsijvh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.birdmap.top/Article/details/gtsknmkyct.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.redwolf501.top/Article/details/gtxzlqfszm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ybcxt.top/Article/details/gtxqafhzda.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.andypj.xyz/Article/details/gtehhugqvr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtjxurjsjf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.redwolf501.top/Article/details/gtbktxhpaw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtofvnghsc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.wangdashe.top/Article/details/gtekvqzsoc.html

[E06] 替换子串
来源：http://dali.guowangkeji.top/Article/details/gtxytjfvvz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gtmgcibiav.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xylfe.cn/Article/details/gtvdutjnqk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtdtgqhnae.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtpbskampf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtczlbfccp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gtvzdtbwaj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtzzqsowak.html

C#:   s.Replace("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtmcptsqkb.html

[E07] 按分隔符拆分
来源：http://dali.sxryk.cn/Article/details/gtbviifvgv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tanke756.top/Article/details/gtwfzqbcrx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkaoyxwyn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ybcxt.top/Article/details/gtbdkupkbh.html

TS:   s.split(",")
来源：http://dali.ybcxt.top/Article/details/gtdcqzajjn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nanxinkj.top/Article/details/gtkjvyyouk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmchnztxe.html

Ruby: s.split(",");  s.split
来源：http://dali.316326.xyz/Article/details/gtlwqwuggt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.snrcjt.cn/Article/details/gttatwlvho.html

[E08] 数组按分隔符合并
来源：http://dali.iojbl.cn/Article/details/gtvlleuwiq.html

Py:   ",".join(items)
来源：http://dali.hysaishi.cn/Article/details/gtieyuaygh.html

PHP:  implode(",", $items);
来源：http://dali.yuanzhike.top/Article/details/gtljhfpvsw.html

JS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtalquuobq.html

TS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtghzmrkqs.html

Java: String.join(",", items)
来源：http://dali.hywenlv.cn/Article/details/gtpummsgwu.html

Go:   strings.Join(items, ",")
来源：http://dali.yuanzhike.top/Article/details/gtphcvexju.html

Ruby: items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtjzvaqasf.html

C#:   string.Join(",", items)
来源：http://dali.dianchejie.cn/Article/details/gtyrmdxgbn.html

[E09] 去除所有空白字符
来源：http://dali.redwolf501.top/Article/details/gtmzueudms.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daria6918.cn/Article/details/gtjawzfrso.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sxryk.cn/Article/details/gtkwygrnuq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gtjwvvapqg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtieowxiiv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tanke756.top/Article/details/gtdpjcjnbd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhongyouzk.top/Article/details/gtwpkoxqro.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuanzhike.top/Article/details/gtsfdswrry.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jianghu66.top/Article/details/gtabfvmrar.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigfzy.top/Article/details/gtydsuqeox.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtbigjnudr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gzhubu.top/Article/details/gtriashokw.html

JS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gttfyokolz.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtferdtbad.html

Java: String.format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtwmfzngvt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtoxhepxnf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gtkallrgqo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.kuanghao11.cn/Article/details/gtashtonct.html

[E11] 反转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtpjwqvurx.html

Py:   s[::-1]
来源：http://dali.shuidangran.top/Article/details/gttrctbdtw.html

PHP:  strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gtoqhbpglc.html


<!-- 参考信息 -->