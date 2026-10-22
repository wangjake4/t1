代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gtgfdbdbwc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtrcskzyvd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ivvv.top/Article/details/gtipybbfbh.html

[D06] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gtgduaxogh.html

Py:   len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtgqrrwhav.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gttvbimcuv.html

JS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gtssvnbwsb.html

TS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gtmiunojbu.html

Java: list.size();
来源：http://dali.sxryk.cn/Article/details/gtpmkjethy.html

Go:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtlnrtjvwg.html

Ruby: arr.length; arr.size
来源：http://dali.dashuyun.cn/Article/details/gtmjogvfiz.html

C#:   list.Count;
来源：http://dali.jianghu66.top/Article/details/gtokrbleup.html

[D07] 切片 / 取子数组
来源：http://dali.0kj1m.cn/Article/details/gtqmyvxbzx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuetiantiany.cn/Article/details/gtawjkrvkk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gotoacloud.top/Article/details/gtelbqdjxe.html

JS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gtyuytylpy.html

TS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gtynypwygf.html

Java: list.subList(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtjsjryvbb.html

Go:   arr[1:4]
来源：http://dali.316326.xyz/Article/details/gtnkdbunzm.html

Ruby: arr[1, 3]
来源：http://dali.zycfv.cn/Article/details/gtqmmzcjgt.html

C#:   list.GetRange(1, 3);
来源：http://dali.cheryme.top/Article/details/gtfqmotzpq.html

[D08] 合并两个数组
来源：http://dali.zhengqikj.top/Article/details/gthfwfztee.html

Py:   a + b;  a.extend(b)
来源：http://dali.cheryme.top/Article/details/gtjhrljqsd.html

PHP:  array_merge($a, $b);
来源：http://dali.jianghu66.top/Article/details/gtkgqnthsh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgfzy.top/Article/details/gtowxjwwwe.html

TS:   [...a, ...b];
来源：http://dali.havefunace.top/Article/details/gtodloxpjm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.kuanghao11.cn/Article/details/gteyadmdiy.html

Go:   append(a, b...)
来源：http://dali.pengpengdd.cyou/Article/details/gtmdknnkjp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nwbrower.top/Article/details/gtgczqnjhx.html

C#:   a.Concat(b).ToList()
来源：http://dali.andypj.xyz/Article/details/gttofqocsi.html

[D09] 排序（升序）
来源：http://dali.9152youxi.cn/Article/details/gtdprbcaei.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.vqdsnc.cn/Article/details/gtekgmspxk.html

PHP:  sort($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtabfwbxbs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenjidiqi.icu/Article/details/gtbspttxta.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cqqwz.cn/Article/details/gtmcijtcmg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuetiantiany.cn/Article/details/gtiwvtfrhq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gttkirizje.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gtykhwobxe.html

C#:   list.Sort();
来源：http://dali.havefunace.top/Article/details/gtfpfgzbyq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yonumen.top/Article/details/gtairnebwe.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvhbemin.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cqqwz.cn/Article/details/gtikoshhni.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gtbtoctlui.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gtflgxiaoh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgfzy.top/Article/details/gtifgicpoi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yueranfly.top/Article/details/gtjgpkplrz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sweek.top/Article/details/gtqbdqqliq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tianlin.xyz/Article/details/gtufhourab.html

[D11] 反转数组
来源：http://dali.gzhubu.top/Article/details/gtffphfuqc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.316326.xyz/Article/details/gtejptfaxq.html

PHP:  array_reverse($arr);
来源：http://dali.cheryme.top/Article/details/gtjsnmqxwq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sufxvd.cn/Article/details/gtjcdxdedl.html

TS:   [...arr].reverse();
来源：http://dali.jinqigfzy.top/Article/details/gtamfrtgkv.html

Java: Collections.reverse(list);
来源：http://dali.yonumen.top/Article/details/gtjvegsmgo.html

Go:   slices.Reverse(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtlfpnxwah.html

Ruby: arr.reverse
来源：http://dali.cqqwz.cn/Article/details/gtckrcqlat.html

C#:   list.Reverse();
来源：http://dali.fengsongda.top/Article/details/gtlbatwooo.html

[D12] 查找元素下标
来源：http://dali.kuanghao11.cn/Article/details/gtahhkpuxz.html

Py:   arr.index(x);  x in arr
来源：http://dali.yonumen.top/Article/details/gtezjogzte.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtukqjkcfv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gttfbfjwlh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gtosevuver.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhongyouzk.top/Article/details/gtgysfakul.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlpnowgz.html

Ruby: arr.index(x)
来源：http://dali.jqgfzy.top/Article/details/gtcjpaekrc.html

C#:   list.IndexOf(x);
来源：http://dali.shangyingyoupin.top/Article/details/gtjogfcfuu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.0kj1m.cn/Article/details/gtrcxsncas.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtshgybfcm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dashuyun.cn/Article/details/gtgpgoapqo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtvbytxfgw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gtmbjhqtll.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuanzx.com/Article/details/gtuslrsglv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cqqwz.cn/Article/details/gtnawyjwpq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jyoumei.cn/Article/details/gtcduvtlgo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yonumen.top/Article/details/gtzeemgdpk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pycfn.com/Article/details/gtxshlounz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jyoumei.cn/Article/details/gtkfynvnre.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zdqjudy.top/Article/details/gtyjlvnuht.html

JS:   arr.map(x => x * 2)
来源：http://dali.fengsongda.top/Article/details/gtfqwldkus.html

TS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gtpcafmwrd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jyoumei.cn/Article/details/gtlogibefx.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gtkxsltpri.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtrwtkffzk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtjqbhxvaq.html

[D15] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvuecbmp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.redwolf501.top/Article/details/gtyxgtvnxo.html

PHP:  array_unique($arr);
来源：http://dali.pycfn.com/Article/details/gtlkvsckwp.html

JS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gtayplnhli.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvexalxho.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gogol.net.cn/Article/details/gtikxpyanf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fengsongda.top/Article/details/gtbkimunwa.html

Ruby: arr.uniq
来源：http://dali.ybcxt.top/Article/details/gttxbvgekj.html

C#:   list.Distinct().ToList()
来源：http://dali.cdnleiting.top/Article/details/gtrqjinakc.html

[D16] 求和与平均值
来源：http://dali.chenjidiqi.icu/Article/details/gtwimujmma.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtqzfgklso.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yangfankeji.com/Article/details/gtbzliyxxy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gthjtxrnyh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gtxzbmsojh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhiwuduotai.top/Article/details/gtndljnjop.html

Go:   // 手写循环累加
来源：http://dali.jinqigufen.top/Article/details/gthhrbjjxk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hywenlv.cn/Article/details/gtsnkanwck.html

C#:   list.Sum();  list.Average()
来源：http://dali.316326.xyz/Article/details/gtcbgixmec.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gtmghydmfl.html

Py:   max(arr);  min(arr)
来源：http://dali.sysykeji.top/Article/details/gtuiwnkhpf.html

PHP:  max($arr);  min($arr);
来源：http://dali.yueranfly.top/Article/details/gtegyfouxk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tian-w.cn/Article/details/gtwvjzzzpf.html

TS:   Math.max(...arr);
来源：http://dali.yonumen.top/Article/details/gtfyqwarng.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtbxybsmhj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daria6918.cn/Article/details/gtvmwmrole.html

Ruby: arr.max;  arr.min
来源：http://dali.cqqwz.cn/Article/details/gtjhtmftzj.html

C#:   list.Max();  list.Min()
来源：http://dali.ybcxt.top/Article/details/gttkwyvpwt.html

[D18] 扁平化嵌套数组
来源：http://dali.xinyue.icu/Article/details/gtspreivta.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gtivvsisai.html

PHP:  array_merge(...$nested);
来源：http://dali.vqdsnc.cn/Article/details/gtrqxkdjcw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nanxinkj.top/Article/details/gtediafqtp.html

TS:   nested.flat();
来源：http://dali.shangyingyoupin.top/Article/details/gtcklbplfb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtuqodtccr.html

Go:   // 手写双层循环
来源：http://dali.yuanzhike.top/Article/details/gtsaafxlir.html

Ruby: nested.flatten
来源：http://dali.xinyue.icu/Article/details/gtlxhcqaeq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cucudq.cn/Article/details/gtsxtsacmc.html

[D19] 按字段分组
来源：http://dali.jiagoushi.top/Article/details/gtoomsjrfk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenlongwang.top/Article/details/gtdlqwrqcv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.havefunace.top/Article/details/gtqufoeilj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gtystdclto.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gotoacloud.top/Article/details/gtdyxagmna.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yangfankeji.com/Article/details/gtsxafnmbs.html

Go:   // 手写 map[string][]T
来源：http://dali.chenjidiqi.icu/Article/details/gtxtooglyz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenlongwang.top/Article/details/gtzurnfqqs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yuanzhike.top/Article/details/gthcwsdmmc.html

[D20] 统计每个元素出现次数
来源：http://dali.gogol.net.cn/Article/details/gtdrntvmsl.html

Py:   Counter(arr)
来源：http://dali.smart0.xyz/Article/details/gtuzokqvdf.html

PHP:  array_count_values($arr);
来源：http://dali.hysaishi.cn/Article/details/gttboboqsg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gtdxoufvdu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gtfdypskmr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.birdmap.top/Article/details/gtoyqbkvpn.html

Go:   // 手写 map[T]int
来源：http://dali.yonumen.top/Article/details/gtdokljpil.html

Ruby: arr.tally
来源：http://dali.c1oappe.top/Article/details/gtqyksanzi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cashguo.top/Article/details/gtwcplotuo.html

[D21] 判断是否包含某元素
来源：http://dali.aibaodan.cn/Article/details/gtidpgvlqw.html

Py:   x in arr
来源：http://dali.hnxiangtu.top/Article/details/gtdzlrudzz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtziseepxn.html

JS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtofcusjwy.html

TS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtfrkbggjl.html

Java: list.contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtdthixqpq.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtcltnmwpr.html

Ruby: arr.include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtskicrtld.html

C#:   list.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gtfvsmgpad.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangshuangyany.cn/Article/details/gtyrnvsgde.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.redwolf501.top/Article/details/gtamzhtcam.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jlsjyb.cn/Article/details/gtprwqgyfo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuanzx.com/Article/details/gtvsfnkome.html

TS:   [...arr];
来源：http://dali.hysaishi.cn/Article/details/gtgdnyypxj.html

Java: new ArrayList<>(list);
来源：http://dali.yuxming.cn/Article/details/gtkpoihbna.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.c1oappe.top/Article/details/gtkfsbidtv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yonumen.top/Article/details/gtnldxnqht.html

C#:   new List<int>(list);
来源：http://dali.yuanzhike.top/Article/details/gtshqbkgrp.html

[D23] reduce 累积计算
来源：http://dali.zhongyouzk.top/Article/details/gtcepulbyn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuuybbdfp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxinkj.top/Article/details/gtrqbscidf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdtlzncn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gtwjbfwovo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgfzy.top/Article/details/gtrjxhqsvu.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gtnavcxoog.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pycfn.com/Article/details/gtrvaploxr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shangyingyoupin.top/Article/details/gtbbaiphrt.html

[D24] 字典 / Map 基本操作
来源：http://dali.ehwqpu.com/Article/details/gtgrrrgeea.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuxming.cn/Article/details/gtubtnecng.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tanke756.top/Article/details/gtpfgadlwr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gttbnpaenx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtsiwlbfye.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fzhhl.top/Article/details/gtnmvyesbo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangshuangyany.cn/Article/details/gtaerzjkox.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtkmrenedy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.redwolf501.top/Article/details/gtzedoiied.html

[D25] Set 集合去重与交并差
来源：http://dali.c1oappe.top/Article/details/gtsougngyb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.c1oappe.top/Article/details/gtemwifpkr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xylfe.cn/Article/details/gttvkrpjkp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guannengcc.top/Article/details/gtajfwyeyo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangshuangyany.cn/Article/details/gtnwgahrut.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.meibo888.top/Article/details/gtepvpwmwd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yvedp.cn/Article/details/gttcpuvpko.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.mhx1999.top/Article/details/gtaxrqxdru.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.vqdsnc.cn/Article/details/gtjvfhnvvc.html

[D26] 数组转字符串
来源：http://dali.yuxming.cn/Article/details/gtojychkbr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jiagoushi.top/Article/details/gtleqgbqol.html

PHP:  implode(", ", $arr);
来源：http://dali.ivvv.top/Article/details/gttqtpribn.html

JS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gtbybvapau.html

TS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtbmnwsyxm.html

Java: String.join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gtmsqxiyfs.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuanzhike.top/Article/details/gtthzloyrh.html

Ruby: arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gttcsukbdv.html

C#:   string.Join(", ", list)
来源：http://dali.c1oappe.top/Article/details/gtglyugytn.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuuqqmwcr.html

E. 字符串处理
来源：http://dali.cdnleiting.top/Article/details/gtnfdlgnmx.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtadaonguv.html

[E01] 拼接字符串
来源：http://dali.jianghu66.top/Article/details/gtferwxzee.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jianghu66.top/Article/details/gtcblnkhks.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jlsjyb.cn/Article/details/gtxigihisu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtrlvqaxca.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.snrcjt.cn/Article/details/gtzrutfykr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jlsjyb.cn/Article/details/gtrkanfbus.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cheryme.top/Article/details/gthzbweryi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guowangkeji.top/Article/details/gtbdscreyx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtzijhmgmu.html

[E02] 重复字符串
来源：http://dali.xuanzx.com/Article/details/gtjnwofkwt.html

Py:   "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gtkuyjtyvp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gthgkvtcpc.html

JS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtgttraagl.html

TS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gtvzyocikl.html

Java: "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gtdpjnjxhj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hywenlv.cn/Article/details/gtpfcsegrz.html

Ruby: "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gtrionkqex.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxuanxn.top/Article/details/gtypejuzjo.html

[E03] 截取子串
来源：http://dali.cashguo.top/Article/details/gtwujseycb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgufenzy.top/Article/details/gthqvobqpu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtgxfxeypj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtajekzjin.html

TS:   s.slice(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtxhhqyyyj.html

Java: s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtwljykgif.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbyymqito.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhengqikj.top/Article/details/gthkjkorzb.html

C#:   s.Substring(1, 3)
来源：http://dali.daria6918.cn/Article/details/gttoiskzat.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfxtsmhl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxinkj.top/Article/details/gtlccczrgj.html

PHP:  strpos($s, "x");
来源：http://dali.sysykeji.top/Article/details/gtgscephkz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yanxiufei.cn/Article/details/gtxumbbtzi.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtihsabprg.html

Java: s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtcmxrvocs.html

Go:   strings.Index(s, "x")
来源：http://dali.yvedp.cn/Article/details/gthzuponxj.html

Ruby: s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskngnzla.html

C#:   s.IndexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gtvgohnndg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jlsjyb.cn/Article/details/gtesbfdqrb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtsufkzmbm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinghuilouyu.cn/Article/details/gtswitokgf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtwtgbolju.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.andypj.xyz/Article/details/gttzcinsvx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucoogdnx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.havefunace.top/Article/details/gtyjzftdrt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.quarkkingdee.top/Article/details/gtqfvxzsjy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yongpay.top/Article/details/gtyvtxlgxj.html

[E06] 替换子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiaqyntco.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtszimqgwo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jyoumei.cn/Article/details/gtqsfnszrv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtlwfucsim.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtjcnwlqor.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtutqcseyo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtlneanexk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtcbmbmmnf.html

C#:   s.Replace("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtjqmqszev.html

[E07] 按分隔符拆分
来源：http://dali.jqgufenzy.top/Article/details/gtggrsntlh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zycfv.cn/Article/details/gtidbokifl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xuanzx.com/Article/details/gtjqcgtnmi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cqqwz.cn/Article/details/gteqbtveyo.html

TS:   s.split(",")
来源：http://dali.snrcjt.cn/Article/details/gtykpgimoa.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tianlin.xyz/Article/details/gtpopvjvtx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jianghu66.top/Article/details/gtzhlwzbjn.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyluwbngt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigfzy.top/Article/details/gtcgaeprgk.html

[E08] 数组按分隔符合并
来源：http://dali.xinyue.icu/Article/details/gtwamwweam.html

Py:   ",".join(items)
来源：http://dali.sxryk.cn/Article/details/gtspeslfpt.html

PHP:  implode(",", $items);
来源：http://dali.tian-w.cn/Article/details/gtgkguhfxj.html

JS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gtmmaztzby.html

TS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gtjhjhqawq.html

Java: String.join(",", items)
来源：http://dali.redwolf501.top/Article/details/gttxlladch.html

Go:   strings.Join(items, ",")
来源：http://dali.tianlin.xyz/Article/details/gtrdlfqvbi.html

Ruby: items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtbgjyvngv.html

C#:   string.Join(",", items)
来源：http://dali.feifeiyinyue.top/Article/details/gtvmmppknh.html

[E09] 去除所有空白字符
来源：http://dali.jinqigufen.top/Article/details/gtijhteamy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hysaishi.cn/Article/details/gtzhxkbnlc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hysaishi.cn/Article/details/gtqzvnbxhq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gtcsfyvmgk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gtzgjumwur.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258888.top/Article/details/gtodkyormq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.vqdsnc.cn/Article/details/gtutcnjfvg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hammf.cn/Article/details/gtpiystkyz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.c1oappe.top/Article/details/gtmompqrwg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shanyushiyangtech.top/Article/details/gtjeckqavh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtqowpxqcf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daria6918.cn/Article/details/gtfbdayeie.html

JS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtnwsuspfm.html

TS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtdbzqzzkj.html

Java: String.format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gtpxhugmru.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gthlwebydh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtojaqswri.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.0kj1m.cn/Article/details/gtgtoaoate.html

[E11] 反转字符串
来源：http://dali.nanxinkj.top/Article/details/gttfmsfpho.html

Py:   s[::-1]
来源：http://dali.havefunace.top/Article/details/gtdipvicot.html

PHP:  strrev($s);
来源：http://dali.redwolf501.top/Article/details/gtvouyuffi.html

JS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtbkuydtmt.html

TS:   [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtbvhztyuq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gotoacloud.top/Article/details/gticmpkxri.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xylfe.cn/Article/details/gtzeyekqug.html

Ruby: s.reverse
来源：http://dali.yueranfly.top/Article/details/gtiudrxjcp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gtlwskjrzz.html

[E12] 统计某字符出现次数
来源：http://dali.xziqi.cn/Article/details/gtjqdekpaj.html

Py:   s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gtwfqeeycm.html

PHP:  substr_count($s, "a");
来源：http://dali.zdqjudy.top/Article/details/gtxlqnkexr.html

JS:   s.split("a").length - 1
来源：http://dali.guannengcc.top/Article/details/gtauqursnx.html

TS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gtlthdwusv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gzhubu.top/Article/details/gtgemahfow.html


<!-- 参考信息 -->