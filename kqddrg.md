代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nanxinkj.top/Article/details/gtlfhfasvr.html

TS:   arr.splice(0, 1);
来源：http://dali.jinqigfzy.top/Article/details/gtmsjpzeor.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nanxinkj.top/Article/details/gtrmgojijj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnxiangtu.top/Article/details/gtattbmzew.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.snrcjt.cn/Article/details/gtshurrvvg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zdqjudy.top/Article/details/gtcaeltrib.html

[D05] 访问与修改元素
来源：http://dali.xylfe.cn/Article/details/gtpgyqnlxq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gtsacgztqo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gtqbbskdvz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sxryk.cn/Article/details/gtnfizlkma.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nwbrower.top/Article/details/gtijijwknf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sufxvd.cn/Article/details/gtpoktcwhj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtpwqlyomq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gttimyzwpu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gtfbxlmlxr.html

[D06] 数组长度
来源：http://dali.yonumen.top/Article/details/gtggpzangm.html

Py:   len(arr)
来源：http://dali.havefunace.top/Article/details/gtrsoazhce.html

PHP:  count($arr);
来源：http://dali.jyoumei.cn/Article/details/gtwcnnextd.html

JS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjdpolen.html

TS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftjrcxtb.html

Java: list.size();
来源：http://dali.9152youxi.cn/Article/details/gtfzpgurzc.html

Go:   len(arr)
来源：http://dali.hammf.cn/Article/details/gtnbqagfln.html

Ruby: arr.length; arr.size
来源：http://dali.jianghu66.top/Article/details/gtwfnyajdc.html

C#:   list.Count;
来源：http://dali.zhoulong.xyz/Article/details/gtznqifwlq.html

[D07] 切片 / 取子数组
来源：http://dali.cheryme.top/Article/details/gthsztqbxs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jianghu66.top/Article/details/gtcrvgzber.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtfjoqheck.html

JS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtwoqzwumu.html

TS:   arr.slice(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gtbqffzanc.html

Java: list.subList(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtydskvzej.html

Go:   arr[1:4]
来源：http://dali.dianchejie.cn/Article/details/gtfaqwcenl.html

Ruby: arr[1, 3]
来源：http://dali.hywenlv.cn/Article/details/gtkpmifdbn.html

C#:   list.GetRange(1, 3);
来源：http://dali.yvedp.cn/Article/details/gtdeprfhvq.html

[D08] 合并两个数组
来源：http://dali.cqqwz.cn/Article/details/gtdllzvtwi.html

Py:   a + b;  a.extend(b)
来源：http://dali.fzhhl.top/Article/details/gtsbgrofgz.html

PHP:  array_merge($a, $b);
来源：http://dali.birdmap.top/Article/details/gtrwptclro.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hysaishi.cn/Article/details/gtcozzajvy.html

TS:   [...a, ...b];
来源：http://dali.xylfe.cn/Article/details/gtufmpnbmz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtmevozeuh.html

Go:   append(a, b...)
来源：http://dali.cqqwz.cn/Article/details/gtvapdzqxh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtaxhkjrsc.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258888.top/Article/details/gttmlnhyxe.html

[D09] 排序（升序）
来源：http://dali.gogol.net.cn/Article/details/gtutkyvmvk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gtjgtatops.html

PHP:  sort($arr);
来源：http://dali.316326.xyz/Article/details/gtyczcliwm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gotoacloud.top/Article/details/gtfekutumy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yvedp.cn/Article/details/gtiqvpkxxb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenzaomai.com/Article/details/gtwkrtghpz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gtkuavhjli.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gttqasxdha.html

C#:   list.Sort();
来源：http://dali.yvedp.cn/Article/details/gtjjwtsfgx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yvedp.cn/Article/details/gtvrzfhmyf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvvbqlla.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenzaomai.com/Article/details/gtullovfqn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gtlekimqrr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gtcpfeshiw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.iojbl.cn/Article/details/gtfqyavvmt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenlongwang.top/Article/details/gtujebtccl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gaohongyu789.top/Article/details/gtxpwntsgj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yvedp.cn/Article/details/gtfyrlivun.html

[D11] 反转数组
来源：http://dali.chenlongwang.top/Article/details/gtftrtehrt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfmzldhj.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtllkejnoa.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yanxiufei.cn/Article/details/gtqvpfjgkg.html

TS:   [...arr].reverse();
来源：http://dali.jqgufenzy.top/Article/details/gtbktjbago.html

Java: Collections.reverse(list);
来源：http://dali.gogol.net.cn/Article/details/gtkzvuyouw.html

Go:   slices.Reverse(arr)
来源：http://dali.fzhhl.top/Article/details/gtnznkhjwv.html

Ruby: arr.reverse
来源：http://dali.0kj1m.cn/Article/details/gtysrbjhtn.html

C#:   list.Reverse();
来源：http://dali.yuanzhike.top/Article/details/gtkqghgqmy.html

[D12] 查找元素下标
来源：http://dali.xylfe.cn/Article/details/gtgqzyevzm.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj202588.top/Article/details/gtqhumuahf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtdjoqftwf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gtvljucgdu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtuoueuytm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ivvv.top/Article/details/gtrajvvaes.html

Go:   slices.Index(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtkbhqwxun.html

Ruby: arr.index(x)
来源：http://dali.jiagoushi.top/Article/details/gtykgcckta.html

C#:   list.IndexOf(x);
来源：http://dali.ybcxt.top/Article/details/gtgsggbzmr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yangfankeji.com/Article/details/gtewzgofaa.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gtwtnxvtea.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.redwolf501.top/Article/details/gtgibayrfa.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtucxpvgzf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gtffmejwfr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.snrcjt.cn/Article/details/gthxazflro.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdlbjrrn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhengqikj.top/Article/details/gtgvelooti.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtvkquymxj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtyxxlas.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258888.top/Article/details/gtftvouhgv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jiagoushi.top/Article/details/gtfidevlkc.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtuuyijjgk.html

TS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gtjtoejqnd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtjxlyonjy.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtzmbaxtgd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtqmjqjdhc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.iojbl.cn/Article/details/gtxfdmbinc.html

[D15] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gtvmdqjcvx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjbqxuuv.html

PHP:  array_unique($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtfcmfyulw.html

JS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtgpvtgzoj.html

TS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gtazrscxaf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sweek.top/Article/details/gtrwfwlsvt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigufen.top/Article/details/gtesftkehb.html

Ruby: arr.uniq
来源：http://dali.yonumen.top/Article/details/gtcjbdjyfk.html

C#:   list.Distinct().ToList()
来源：http://dali.yonumen.top/Article/details/gtsdpweqqw.html

[D16] 求和与平均值
来源：http://dali.zhixingplan.top/Article/details/gtrwzehbsr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtntaukhjc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.smart0.xyz/Article/details/gtjgvpygmy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gtnsnodgfp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gtagvaceuo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gtrqfvxqcb.html

Go:   // 手写循环累加
来源：http://dali.iojbl.cn/Article/details/gtobhhpuwt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gtiosjzbxy.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgfzy.top/Article/details/gtxtsagtyb.html

[D17] 最大值与最小值
来源：http://dali.chenjidiqi.icu/Article/details/gtkandnuwr.html

Py:   max(arr);  min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlpyqbsv.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtcqcuxpzq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dashuyun.cn/Article/details/gtynshbzyj.html

TS:   Math.max(...arr);
来源：http://dali.c1oappe.top/Article/details/gtksxwsdav.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinqigufen.top/Article/details/gtvrhlqvwb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtyqpsecrd.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjklpniwo.html

C#:   list.Max();  list.Min()
来源：http://dali.gzhubu.top/Article/details/gtqkevemgm.html

[D18] 扁平化嵌套数组
来源：http://dali.zycfv.cn/Article/details/gtfercbgpu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnqzz.top/Article/details/gtjhutmreo.html

PHP:  array_merge(...$nested);
来源：http://dali.yuxming.cn/Article/details/gtpbjjnvwo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shangyingyoupin.top/Article/details/gtavkodxxh.html

TS:   nested.flat();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanurbpfi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.0kj1m.cn/Article/details/gtdhmxbcnp.html

Go:   // 手写双层循环
来源：http://dali.snrcjt.cn/Article/details/gtdmtetcla.html

Ruby: nested.flatten
来源：http://dali.shzxlz.cn/Article/details/gtwkzavhwu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtyjdsommb.html

[D19] 按字段分组
来源：http://dali.mhx1999.top/Article/details/gtemhxwzwg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aizwys.cn/Article/details/gtfclearte.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dianchejie.cn/Article/details/gthdipwdlu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tian-w.cn/Article/details/gtkiatxjhm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdifbgetv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenlongwang.top/Article/details/gtrfgjfvqg.html

Go:   // 手写 map[string][]T
来源：http://dali.pycfn.com/Article/details/gtmawedqja.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hysaishi.cn/Article/details/gtapfnfwrs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gtuyebcnde.html

[D20] 统计每个元素出现次数
来源：http://dali.vqdsnc.cn/Article/details/gtjepekqkz.html

Py:   Counter(arr)
来源：http://dali.sxryk.cn/Article/details/gtojysxyui.html

PHP:  array_count_values($arr);
来源：http://dali.zdqjudy.top/Article/details/gtlmdxuvwy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gtjiwdqplx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hongshengwenyu.top/Article/details/gthlscvslj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.vqdsnc.cn/Article/details/gtycztusus.html

Go:   // 手写 map[T]int
来源：http://dali.jqgfzy.top/Article/details/gtpdwzgtrt.html

Ruby: arr.tally
来源：http://dali.yonumen.top/Article/details/gtjggqujms.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.haohaochexian.top/Article/details/gtwoaurlaz.html

[D21] 判断是否包含某元素
来源：http://dali.chenjidiqi.icu/Article/details/gtnagqlhbc.html

Py:   x in arr
来源：http://dali.aibaodan.cn/Article/details/gtlzvvohaa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sysykeji.top/Article/details/gtwgxkhhfi.html

JS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gtlwilmbzo.html

TS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gtzgvtutvi.html

Java: list.contains(x)
来源：http://dali.gzhubu.top/Article/details/gtrfnogkuf.html

Go:   slices.Contains(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtjtrcsbvu.html

Ruby: arr.include?(x)
来源：http://dali.haohaochexian.top/Article/details/gtywoxcviz.html

C#:   list.Contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtonlqpyry.html

[D22] 复制数组（避免共享引用）
来源：http://dali.smart0.xyz/Article/details/gtaqvolvge.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigufen.top/Article/details/gtlanebwnc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yangfankeji.com/Article/details/gtgyabgpfk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtvzwonxgj.html

TS:   [...arr];
来源：http://dali.quarkkingdee.top/Article/details/gtugobnoea.html

Java: new ArrayList<>(list);
来源：http://dali.ivvv.top/Article/details/gtnkjhelht.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenlongwang.top/Article/details/gtodbwdaky.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fzhhl.top/Article/details/gttthobeml.html

C#:   new List<int>(list);
来源：http://dali.yonumen.top/Article/details/gtmmorzxiu.html

[D23] reduce 累积计算
来源：http://dali.yongpay.top/Article/details/gteeazxetn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.havefunace.top/Article/details/gtfcozebzi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tanke756.top/Article/details/gtnalvqzbl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtahmlpykd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gtgloqupxo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ydzc1.top/Article/details/gtjtnpossy.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gtlyicwnbn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yongpay.top/Article/details/gtkaybkfpq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guannengcc.top/Article/details/gtjgensoej.html

[D24] 字典 / Map 基本操作
来源：http://dali.yonumen.top/Article/details/gtwemyjpcq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jiagoushi.top/Article/details/gtwezbiefb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtdccielvr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ehwqpu.com/Article/details/gtuojmymej.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pycfn.com/Article/details/gtxujjoiee.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnqzz.top/Article/details/gtzxpuzdqk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj202588.top/Article/details/gtnlijjtpc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnyafkboc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cheryme.top/Article/details/gtiklxymvl.html

[D25] Set 集合去重与交并差
来源：http://dali.cdnleiting.top/Article/details/gtrqzygbzh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.mhx1999.top/Article/details/gtiwfoctho.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hongshengwenyu.top/Article/details/gtipoqtjqv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tian-w.cn/Article/details/gtvabnrdkf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tanke756.top/Article/details/gtpvsiuaff.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuanzhike.top/Article/details/gtmiucdrby.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shuidangran.top/Article/details/gthuiwttet.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fzhhl.top/Article/details/gtbpccroww.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hammf.cn/Article/details/gtdymzjsjt.html

[D26] 数组转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtsbsxarnz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yongpay.top/Article/details/gtycpyeogn.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigufen.top/Article/details/gtolphsksr.html

JS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gtbghgadiv.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqcawdahk.html

Java: String.join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gtltdgcqnb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.iojbl.cn/Article/details/gtmgdjiile.html

Ruby: arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gthynyhowb.html

C#:   string.Join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gtzmtwugbs.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtmropekdw.html

E. 字符串处理
来源：http://dali.gotoacloud.top/Article/details/gtxmkdvoqn.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtcctwqokk.html

[E01] 拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtlrnzpvtx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.wangshuangyany.cn/Article/details/gtjikeadsk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yangfankeji.com/Article/details/gtruughlno.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hywenlv.cn/Article/details/gtmvnmudej.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gthkuyczft.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhongyouzk.top/Article/details/gtnubfpnal.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnqzz.top/Article/details/gtmlnxqvfv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ydzc1.top/Article/details/gtyvmslsnx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtyqltxbjw.html

[E02] 重复字符串
来源：http://dali.bjfxy.top/Article/details/gtrpnnjzvo.html

Py:   "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gtznkemkjj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhixingplan.top/Article/details/gtvdkzozdx.html

JS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtwkyczuws.html

TS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gtyftizpfm.html

Java: "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtaaxehcsk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.svipenyu.cn/Article/details/gtbmadmwck.html

Ruby: "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gtsyytqnbb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zdqjudy.top/Article/details/gtkgiqbtwm.html

[E03] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gtqrzywuxb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.mhx1999.top/Article/details/gtzfiwfcxo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtaqwnmoxl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gtdsihpzpw.html

TS:   s.slice(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtqtywmlgw.html

Java: s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtjqskoyhp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gzhubu.top/Article/details/gtjaibydqr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenlongwang.top/Article/details/gtcacxmlju.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258.top/Article/details/gtlxumntna.html

[E04] 查找子串位置
来源：http://dali.zycfv.cn/Article/details/gthlportjh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvuncybge.html

PHP:  strpos($s, "x");
来源：http://dali.ehwqpu.com/Article/details/gtattppojl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigufen.top/Article/details/gtwsjsiual.html

TS:   s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gtgevmrvcc.html

Java: s.indexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtbsxemugn.html

Go:   strings.Index(s, "x")
来源：http://dali.fzhhl.top/Article/details/gtdpcogjnh.html

Ruby: s.index("x")
来源：http://dali.sxryk.cn/Article/details/gtfraiwcej.html

C#:   s.IndexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshuyllet.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.birdmap.top/Article/details/gtbpidonef.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xuanzx.com/Article/details/gtcdwmcflx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.quarkkingdee.top/Article/details/gtqgtwzfue.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtjupxjbkt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhoulong.xyz/Article/details/gthzbpwrkg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtioykzqhl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258.top/Article/details/gtmsgqnygk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuanzx.com/Article/details/gtzthlfjck.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtusremwsy.html

[E06] 替换子串
来源：http://dali.gzhubu.top/Article/details/gtspectwnx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxuanxn.top/Article/details/gtxgumbrla.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.9152youxi.cn/Article/details/gtxowvhaqc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtqiccishm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtghizqdsr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtkhnoqlhn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gtzzfrbjlu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtcmgxfxnu.html

C#:   s.Replace("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtvxtrnnux.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gtidvtdtoy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.quarkkingdee.top/Article/details/gtqtcponjy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cashguo.top/Article/details/gtkdmnsxqz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guowangkeji.top/Article/details/gthodzxptv.html

TS:   s.split(",")
来源：http://dali.wangdashe.top/Article/details/gtjfucsiya.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.iojbl.cn/Article/details/gtgvnjdgud.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258.top/Article/details/gtqeybtozu.html

Ruby: s.split(",");  s.split
来源：http://dali.fengsongda.top/Article/details/gtzksrxwuh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxuanxn.top/Article/details/gtrqrzycmq.html

[E08] 数组按分隔符合并
来源：http://dali.havefunace.top/Article/details/gtwphdxijp.html

Py:   ",".join(items)
来源：http://dali.cdnleiting.top/Article/details/gtpyhbgqvx.html

PHP:  implode(",", $items);
来源：http://dali.cucudq.cn/Article/details/gtoisycqth.html

JS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gtnrmpxrzn.html

TS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtmmncghxd.html

Java: String.join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gtllzvsksg.html

Go:   strings.Join(items, ",")
来源：http://dali.0kj1m.cn/Article/details/gtjpspkqxp.html

Ruby: items.join(",")
来源：http://dali.tanke756.top/Article/details/gtofghwazb.html

C#:   string.Join(",", items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvnpibcn.html

[E09] 去除所有空白字符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfgeimsy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.quarkkingdee.top/Article/details/gtmbivwbak.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gogol.net.cn/Article/details/gtrvqdtaji.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gttqjjotyi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtxhqyytrf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.smart0.xyz/Article/details/gttzlrkiod.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.meibo888.top/Article/details/gtfpymvczl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gotoacloud.top/Article/details/gtumzwjces.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gtmolargpy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhixingplan.top/Article/details/gtiumisuwo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtbwdyxtfy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.svipenyu.cn/Article/details/gtnlkxkbjb.html

JS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbspidoh.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtgcfzhgeq.html

Java: String.format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gttfljnnrd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtqeqsessr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtgxmeypta.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgfzy.top/Article/details/gtldhlzzrt.html

[E11] 反转字符串
来源：http://dali.guannengcc.top/Article/details/gtymetsvfg.html

Py:   s[::-1]
来源：http://dali.cucudq.cn/Article/details/gtnzryjwyc.html

PHP:  strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gtycryxttm.html


<!-- 参考信息 -->