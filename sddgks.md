代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gtbcxsywpr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gtacnlwcdz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gogol.net.cn/Article/details/gtuejdhqjz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangshuangyany.cn/Article/details/gtmldynwpa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtrriebiar.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gtkyguxvbf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sxryk.cn/Article/details/gtbgfkvqky.html

[D06] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gtqhwmwjnt.html

Py:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtqmgyndsl.html

PHP:  count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoeymjjnm.html

JS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gtztcgmnip.html

TS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gtbzzkaqnj.html

Java: list.size();
来源：http://dali.yj20258888.top/Article/details/gtbswgkyoy.html

Go:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtujugmrwm.html

Ruby: arr.length; arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gtsrqxygzl.html

C#:   list.Count;
来源：http://dali.zhoulong.xyz/Article/details/gtjhevsurq.html

[D07] 切片 / 取子数组
来源：http://dali.redwolf501.top/Article/details/gtxwwcbmvk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.pengpengdd.cyou/Article/details/gtezsrsgmo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtdvzwvmyo.html

JS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtfobfvgbw.html

TS:   arr.slice(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gtoeixhbim.html

Java: list.subList(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gtncnoktny.html

Go:   arr[1:4]
来源：http://dali.hnqzz.top/Article/details/gterphjced.html

Ruby: arr[1, 3]
来源：http://dali.dianchejie.cn/Article/details/gtnfckzkvm.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhengqikj.top/Article/details/gtbfrwnlkv.html

[D08] 合并两个数组
来源：http://dali.yj20258888.top/Article/details/gtuawjlgwr.html

Py:   a + b;  a.extend(b)
来源：http://dali.ehwqpu.com/Article/details/gtikhsexqy.html

PHP:  array_merge($a, $b);
来源：http://dali.xylfe.cn/Article/details/gtvxxmnolq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.0kj1m.cn/Article/details/gttyxjuawu.html

TS:   [...a, ...b];
来源：http://dali.shangyingyoupin.top/Article/details/gtubvoxnhh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ehwqpu.com/Article/details/gtgsukckob.html

Go:   append(a, b...)
来源：http://dali.ivvv.top/Article/details/gtyccgzehb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ivvv.top/Article/details/gtgoodqpml.html

C#:   a.Concat(b).ToList()
来源：http://dali.xziqi.cn/Article/details/gtyakhmpfm.html

[D09] 排序（升序）
来源：http://dali.jianghu66.top/Article/details/gtgrurkuft.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtayrrxzsj.html

PHP:  sort($arr);
来源：http://dali.jqgfzy.top/Article/details/gtoiajgjtm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.dashuyun.cn/Article/details/gtxucmzcmh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nwbrower.top/Article/details/gtrskvpcye.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuxming.cn/Article/details/gtwipostdy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gttqeuaohv.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtliyewaib.html

C#:   list.Sort();
来源：http://dali.yj20258.top/Article/details/gtqnmahidn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.feifeiyinyue.top/Article/details/gtlklqfrxz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlucvepra.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ehwqpu.com/Article/details/gtbrizpfid.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gteshoibew.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.mhx1999.top/Article/details/gtglrqmuln.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fengsongda.top/Article/details/gtzqvqlqss.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.redwolf501.top/Article/details/gtmaagtctt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xinyue.icu/Article/details/gtcuunadsr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hywenlv.cn/Article/details/gtyexlsmor.html

[D11] 反转数组
来源：http://dali.gogol.net.cn/Article/details/gtmibkygvv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dashuyun.cn/Article/details/gtkdxnjjwh.html

PHP:  array_reverse($arr);
来源：http://dali.havefunace.top/Article/details/gtuszioprw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuxming.cn/Article/details/gtjwxwnkii.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gthpijrxbo.html

Java: Collections.reverse(list);
来源：http://dali.daria6918.cn/Article/details/gtlsxcrokx.html

Go:   slices.Reverse(arr)
来源：http://dali.shzxlz.cn/Article/details/gtcotjqdkp.html

Ruby: arr.reverse
来源：http://dali.shuidangran.top/Article/details/gtdrosboyo.html

C#:   list.Reverse();
来源：http://dali.jiagoushi.top/Article/details/gtsihxkblk.html

[D12] 查找元素下标
来源：http://dali.xuetiantiany.cn/Article/details/gtyifqebgp.html

Py:   arr.index(x);  x in arr
来源：http://dali.svipenyu.cn/Article/details/gtesntxydu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aibaodan.cn/Article/details/gtqxyvoled.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gtnytydlug.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtoloezulr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fengsongda.top/Article/details/gtofghithr.html

Go:   slices.Index(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtokgkuhko.html

Ruby: arr.index(x)
来源：http://dali.yuxming.cn/Article/details/gtczhnnyxe.html

C#:   list.IndexOf(x);
来源：http://dali.ydzc1.top/Article/details/gtvhmktzza.html

[D13] 过滤（保留满足条件的）
来源：http://dali.c1oappe.top/Article/details/gtwargottp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.bjfxy.top/Article/details/gtlnyppzyj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigufen.top/Article/details/gtmsvaqqkl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gtdcgixkvv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.bjfxy.top/Article/details/gtsnetsmii.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtaszdpnkx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gotoacloud.top/Article/details/gtjrtrayzi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sysykeji.top/Article/details/gtfpzelpii.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtadstozkb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hnqzz.top/Article/details/gtqktdowtt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuanzhike.top/Article/details/gtycrjnncp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtduqkjybt.html

JS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gtgbkynskf.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtruipqsgm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.snrcjt.cn/Article/details/gtpdsvmvrg.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gtufgtwhas.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.316326.xyz/Article/details/gtdzqaatck.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.havefunace.top/Article/details/gtlgqxqhwy.html

[D15] 去重
来源：http://dali.jinqigufen.top/Article/details/gttcfueygm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gtmtvxgcan.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdssejuud.html

JS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtvqkpdqfg.html

TS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtqhsjijjt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dianchejie.cn/Article/details/gtldunsqex.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ivvv.top/Article/details/gtchagmely.html

Ruby: arr.uniq
来源：http://dali.gogol.net.cn/Article/details/gttyluagig.html

C#:   list.Distinct().ToList()
来源：http://dali.andypj.xyz/Article/details/gtztcozkli.html

[D16] 求和与平均值
来源：http://dali.tianlin.xyz/Article/details/gtmksjpiru.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gotoacloud.top/Article/details/gteorrwkou.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangdashe.top/Article/details/gtlamzskdw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtxujzkqvo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtlshlknmx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258.top/Article/details/gtcxicjgct.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkoicvynu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ydzc1.top/Article/details/gtvegfwzhn.html

C#:   list.Sum();  list.Average()
来源：http://dali.dashuyun.cn/Article/details/gtnebleqxv.html

[D17] 最大值与最小值
来源：http://dali.shangyingyoupin.top/Article/details/gtcbyevkeq.html

Py:   max(arr);  min(arr)
来源：http://dali.fzhhl.top/Article/details/gtfctmszwh.html

PHP:  max($arr);  min($arr);
来源：http://dali.mhx1999.top/Article/details/gtwxrcoymu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yonumen.top/Article/details/gtxrxmuqzo.html

TS:   Math.max(...arr);
来源：http://dali.hnqzz.top/Article/details/gtzjasajgu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.c1oappe.top/Article/details/gtnpiminqm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hfpthk.cn/Article/details/gtdpsuihlo.html

Ruby: arr.max;  arr.min
来源：http://dali.yanxiufei.cn/Article/details/gttgxsvvcv.html

C#:   list.Max();  list.Min()
来源：http://dali.shuidangran.top/Article/details/gtaydfzxbo.html

[D18] 扁平化嵌套数组
来源：http://dali.ivvv.top/Article/details/gtkaeozvzs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gogol.net.cn/Article/details/gtblgzqmja.html

PHP:  array_merge(...$nested);
来源：http://dali.mhx1999.top/Article/details/gtmczateab.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jyoumei.cn/Article/details/gtgyedooub.html

TS:   nested.flat();
来源：http://dali.cheryme.top/Article/details/gtllzodjio.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtgqgglkvm.html

Go:   // 手写双层循环
来源：http://dali.dashuyun.cn/Article/details/gtfgtdlvej.html

Ruby: nested.flatten
来源：http://dali.jiagoushi.top/Article/details/gtjnnpvfqj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cucudq.cn/Article/details/gtghtkiwqb.html

[D19] 按字段分组
来源：http://dali.xziqi.cn/Article/details/gtouxcghsv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxuanxn.top/Article/details/gtqqvklccw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jianghu66.top/Article/details/gtcqcbfjnm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.feifeiyinyue.top/Article/details/gtvdyggtab.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuxming.cn/Article/details/gtxdvpvmgj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuetiantiany.cn/Article/details/gtuvkacabp.html

Go:   // 手写 map[string][]T
来源：http://dali.yuxming.cn/Article/details/gtbxnuthcb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shuidangran.top/Article/details/gtddgitvpa.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daxiang520.top/Article/details/gtubhsrrod.html

[D20] 统计每个元素出现次数
来源：http://dali.sweek.top/Article/details/gtvqtwtxgi.html

Py:   Counter(arr)
来源：http://dali.sweek.top/Article/details/gtpwfviogi.html

PHP:  array_count_values($arr);
来源：http://dali.yuxming.cn/Article/details/gtwiydoryg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xylfe.cn/Article/details/gtwnmfanmm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gtioubiwml.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.meibo888.top/Article/details/gttzxukvrb.html

Go:   // 手写 map[T]int
来源：http://dali.cashguo.top/Article/details/gtdltgtxgw.html

Ruby: arr.tally
来源：http://dali.sweek.top/Article/details/gtoglczdhv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yvedp.cn/Article/details/gtzxgdortd.html

[D21] 判断是否包含某元素
来源：http://dali.c1oappe.top/Article/details/gtpvwcrmwg.html

Py:   x in arr
来源：http://dali.nwbrower.top/Article/details/gtjgdrkuky.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jqgfzy.top/Article/details/gtnfvxozrx.html

JS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtnqpaebqa.html

TS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtaianogtv.html

Java: list.contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gthvacjomm.html

Go:   slices.Contains(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtqnuzlakt.html

Ruby: arr.include?(x)
来源：http://dali.kuanghao11.cn/Article/details/gtcsmoomuj.html

C#:   list.Contains(x)
来源：http://dali.guannengcc.top/Article/details/gtbtlsvhke.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdcoihdwu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.pycfn.com/Article/details/gtnwgwvxek.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gtkthgxyfr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtnfyuwigr.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gtiexowgww.html

Java: new ArrayList<>(list);
来源：http://dali.yueranfly.top/Article/details/gtrqpkndrq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.iojbl.cn/Article/details/gtoxtshfez.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yueranfly.top/Article/details/gtafuddwiq.html

C#:   new List<int>(list);
来源：http://dali.birdmap.top/Article/details/gtsfpcfyrw.html

[D23] reduce 累积计算
来源：http://dali.iojbl.cn/Article/details/gtjjzkbizd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shuidangran.top/Article/details/gtqscnyxly.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgfzy.top/Article/details/gtfkyvtila.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtvcjpjgrr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gtsliqrsnn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.havefunace.top/Article/details/gterardysx.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gtueefaavx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yongpay.top/Article/details/gtcemvyxzd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.bjfxy.top/Article/details/gttndcwxmw.html

[D24] 字典 / Map 基本操作
来源：http://dali.kuanghao11.cn/Article/details/gtccizjzcm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigfzy.top/Article/details/gtgxjpjkcw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dashuyun.cn/Article/details/gtphvkxcze.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtlbeynwih.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gttbgqreew.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigfzy.top/Article/details/gtmgnemdoz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nwbrower.top/Article/details/gtoleaounb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ppjwa.cn/Article/details/gtimntcdpy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hongshengwenyu.top/Article/details/gthklwuivo.html

[D25] Set 集合去重与交并差
来源：http://dali.zhengqikj.top/Article/details/gtiigmedtn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigfzy.top/Article/details/gtcfrjnpuo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aizwys.cn/Article/details/gtrotrgqqe.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj202588.top/Article/details/gtkjwvgrkk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cqqwz.cn/Article/details/gtjptinhne.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gtjjqwlopq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pengpengdd.cyou/Article/details/gtwlstvjgz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sufxvd.cn/Article/details/gtoyrfxblt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuizbmpil.html

[D26] 数组转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gttrjlgskf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtofaopnfb.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtmdtqzsuj.html

JS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtbrkguoll.html

TS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtcugjkgnu.html

Java: String.join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gtwvvpztye.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tanke756.top/Article/details/gtqfitpkqi.html

Ruby: arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gtvwnhnygc.html

C#:   string.Join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gtbsrjetwe.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtxzpbxssr.html

E. 字符串处理
来源：http://dali.gogol.net.cn/Article/details/gtghbdmefx.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsitwibru.html

[E01] 拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtmafgetze.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tian-w.cn/Article/details/gtyqdvezjm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhongyouzk.top/Article/details/gtpxrhaofh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxgrsqpn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gtbxevyfgr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hywenlv.cn/Article/details/gtcabaoayd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ybcxt.top/Article/details/gtgexvgshd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fzhhl.top/Article/details/gtkxemugeu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tanke756.top/Article/details/gtxgkutsvr.html

[E02] 重复字符串
来源：http://dali.birdmap.top/Article/details/gtttewaugg.html

Py:   "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyshdaua.html

PHP:  str_repeat("ab", 3);
来源：http://dali.andypj.xyz/Article/details/gtjnjbfzng.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gthxuhvwpk.html

TS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gtwhmibfty.html

Java: "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtsbdhdsoz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guowangkeji.top/Article/details/gtjrzshomc.html

Ruby: "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gtxanpqsci.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ppjwa.cn/Article/details/gtqamjsbbz.html

[E03] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gtzhtqivog.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuxming.cn/Article/details/gtcxywyobn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtskjhsgka.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtlejvptgz.html

TS:   s.slice(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtixvrysyj.html

Java: s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtrxvxzsyb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.redwolf501.top/Article/details/gtwtojcbem.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcyilzer.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigufen.top/Article/details/gtvhpvorvh.html

[E04] 查找子串位置
来源：http://dali.jinghuilouyu.cn/Article/details/gthcjvtvyz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gtlfshclxk.html

PHP:  strpos($s, "x");
来源：http://dali.yonumen.top/Article/details/gtqdgdpsdx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jyoumei.cn/Article/details/gtfeidnetv.html

TS:   s.indexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtiblxckyv.html

Java: s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gttbxjqbsk.html

Go:   strings.Index(s, "x")
来源：http://dali.yueranfly.top/Article/details/gtjlchcgur.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfgjddku.html

C#:   s.IndexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gthrdxrpzj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xylfe.cn/Article/details/gtocezbbtu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.smart0.xyz/Article/details/gtvbylzpds.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.bjfxy.top/Article/details/gttbbmjlel.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtsctmbtxf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinqigufen.top/Article/details/gtkqqxmbya.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtnyqslvrv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jlsjyb.cn/Article/details/gtrqdagujd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guannengcc.top/Article/details/gtmcytffkd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.wangdashe.top/Article/details/gthblkmzjz.html

[E06] 替换子串
来源：http://dali.ppjwa.cn/Article/details/gtnwwqtrav.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtedstbjxg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yueranfly.top/Article/details/gtwwtxfxly.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtoyuanhoj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtpdbvezes.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtzvurvigo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gtzmzbzidm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtbvsuhxdg.html

C#:   s.Replace("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtqmrjdknk.html

[E07] 按分隔符拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtdpcvldau.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.iojbl.cn/Article/details/gtnlcctpod.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj20258888.top/Article/details/gtqzqlizkd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sweek.top/Article/details/gtgtmpxmdy.html

TS:   s.split(",")
来源：http://dali.cashguo.top/Article/details/gtnmjgijej.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.316326.xyz/Article/details/gtjemkhdlm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxuanxn.top/Article/details/gtuqveiomf.html

Ruby: s.split(",");  s.split
来源：http://dali.yongpay.top/Article/details/gtbfnxyvaz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yueranfly.top/Article/details/gtqckglolf.html

[E08] 数组按分隔符合并
来源：http://dali.vqdsnc.cn/Article/details/gtpfhgbigx.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gtsbrzayco.html

PHP:  implode(",", $items);
来源：http://dali.hongshengwenyu.top/Article/details/gtswdhpaat.html

JS:   items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gtrcptodor.html

TS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gtdrnteetx.html

Java: String.join(",", items)
来源：http://dali.sweek.top/Article/details/gtvbagriys.html

Go:   strings.Join(items, ",")
来源：http://dali.hywenlv.cn/Article/details/gtiprjobgh.html

Ruby: items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtujqvvner.html

C#:   string.Join(",", items)
来源：http://dali.haohaochexian.top/Article/details/gthcjviocw.html

[E09] 去除所有空白字符
来源：http://dali.hammf.cn/Article/details/gtazrbpooc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtuaahjzik.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.daxiang520.top/Article/details/gtiulvapdx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gtaiuldhly.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gtpqxpgkue.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sysykeji.top/Article/details/gtedgnxill.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pycfn.com/Article/details/gtxifdzxzt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ybcxt.top/Article/details/gtsapwmahq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.bjfxy.top/Article/details/gtxxzxnapw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xziqi.cn/Article/details/gtuwohrmau.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtypnrwbkg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hfpthk.cn/Article/details/gtqkjgwwns.html

JS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtqasrrcys.html

TS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gthkmrszwn.html

Java: String.format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtewyycvui.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtzzxwidpc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gtzlalmdlu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangtech.top/Article/details/gtsthrtayd.html

[E11] 反转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtvbqswrzq.html

Py:   s[::-1]
来源：http://dali.hammf.cn/Article/details/gtrfsxsfok.html

PHP:  strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gtdgjmzofu.html

JS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtlydpsied.html

TS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtfxynnvmx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gaohongyu789.top/Article/details/gtojvhbvfb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gttkmzqeym.html

Ruby: s.reverse
来源：http://dali.ybcxt.top/Article/details/gtlqzaebds.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gtmlpeqhpu.html

[E12] 统计某字符出现次数
来源：http://dali.smart0.xyz/Article/details/gttwnjgojw.html

Py:   s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gtxuiqassk.html


<!-- 参考信息 -->