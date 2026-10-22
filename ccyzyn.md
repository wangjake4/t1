代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhendqjr.html

TS:   arr.splice(0, 1);
来源：http://dali.zdqjudy.top/Article/details/gtbsujbuzj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtwevjejto.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258.top/Article/details/gtjvobytyk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjpvgofy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangshuangyany.cn/Article/details/gtzmmdemoz.html

[D05] 访问与修改元素
来源：http://dali.cashguo.top/Article/details/gtibwbvaup.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gteqdmgvet.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gthcoarrcv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gtxfbxlfod.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.316326.xyz/Article/details/gtphtzgkjh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ehwqpu.com/Article/details/gtgasaatkf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtbcupgflm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gttffztvyz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gtfcahwrdy.html

[D06] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gtgnrctdkw.html

Py:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtmzhhcrgj.html

PHP:  count($arr);
来源：http://dali.fengsongda.top/Article/details/gtqhsmahmy.html

JS:   arr.length
来源：http://dali.birdmap.top/Article/details/gtbfojoqir.html

TS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gtymsjqqxx.html

Java: list.size();
来源：http://dali.xuanzx.com/Article/details/gtctsewwni.html

Go:   len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtcowllaqq.html

Ruby: arr.length; arr.size
来源：http://dali.haohaochexian.top/Article/details/gtrewkcspm.html

C#:   list.Count;
来源：http://dali.tian-w.cn/Article/details/gtqqinflkl.html

[D07] 切片 / 取子数组
来源：http://dali.bjfxy.top/Article/details/gttatajouk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.andypj.xyz/Article/details/gtmlmevecw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.9152youxi.cn/Article/details/gtzreqszeh.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gtvkgdxphn.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtyzhyuphd.html

Java: list.subList(1, 4);
来源：http://dali.sweek.top/Article/details/gtxtandihf.html

Go:   arr[1:4]
来源：http://dali.dashuyun.cn/Article/details/gtonxnwodi.html

Ruby: arr[1, 3]
来源：http://dali.ppjwa.cn/Article/details/gtoaplrtpa.html

C#:   list.GetRange(1, 3);
来源：http://dali.316326.xyz/Article/details/gtxiluugnz.html

[D08] 合并两个数组
来源：http://dali.daxiang520.top/Article/details/gtqyoxrwzt.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj202588.top/Article/details/gtievalgdd.html

PHP:  array_merge($a, $b);
来源：http://dali.zhiwuduotai.top/Article/details/gtprfqguff.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenlongwang.top/Article/details/gtgbpfkjow.html

TS:   [...a, ...b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgwasxkm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yvedp.cn/Article/details/gtiyjbsoeg.html

Go:   append(a, b...)
来源：http://dali.yj20258.top/Article/details/gtpofoeoqt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtubrghiff.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnqzz.top/Article/details/gtfeoiavld.html

[D09] 排序（升序）
来源：http://dali.cashguo.top/Article/details/gtbcikbjgg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gteexkvhze.html

PHP:  sort($arr);
来源：http://dali.tianlin.xyz/Article/details/gtlzctedcn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jianghu66.top/Article/details/gtuqxmvyym.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenlongwang.top/Article/details/gttbxfoduh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hnxiangtu.top/Article/details/gtscqvdyxq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzvexrmi.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gtonwdjsxs.html

C#:   list.Sort();
来源：http://dali.yuanzhike.top/Article/details/gtinogwcoq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gogol.net.cn/Article/details/gtpisljzxg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtycfjfboe.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ehwqpu.com/Article/details/gtjedgwpvg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hywenlv.cn/Article/details/gtdujmmvkh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yvedp.cn/Article/details/gtgrbcthtr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.snrcjt.cn/Article/details/gtusuqogrz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangdashe.top/Article/details/gtexjioiqp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cqqwz.cn/Article/details/gtaxywlufw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxywsvhm.html

[D11] 反转数组
来源：http://dali.yueranfly.top/Article/details/gtvxbxlkbq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.guannengcc.top/Article/details/gtpufcyynx.html

PHP:  array_reverse($arr);
来源：http://dali.redwolf501.top/Article/details/gtaqwsprdd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ivvv.top/Article/details/gtdgoeraae.html

TS:   [...arr].reverse();
来源：http://dali.cashguo.top/Article/details/gtdutdscgs.html

Java: Collections.reverse(list);
来源：http://dali.cashguo.top/Article/details/gtbmfzxhhp.html

Go:   slices.Reverse(arr)
来源：http://dali.shuidangran.top/Article/details/gtxtxphvye.html

Ruby: arr.reverse
来源：http://dali.ehwqpu.com/Article/details/gtyfhsyjzk.html

C#:   list.Reverse();
来源：http://dali.guannengcc.top/Article/details/gtlihgnhuf.html

[D12] 查找元素下标
来源：http://dali.feifeiyinyue.top/Article/details/gtrhzeeshf.html

Py:   arr.index(x);  x in arr
来源：http://dali.c1oappe.top/Article/details/gtezmrgyvt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sufxvd.cn/Article/details/gtuytyfsrb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gtphaybrdp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yvedp.cn/Article/details/gtlvtuflhj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ehwqpu.com/Article/details/gtqvcmdjah.html

Go:   slices.Index(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtxzmbohai.html

Ruby: arr.index(x)
来源：http://dali.nanxuanxn.top/Article/details/gtengwbvgt.html

C#:   list.IndexOf(x);
来源：http://dali.dianchejie.cn/Article/details/gtzusmmiti.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinqigufen.top/Article/details/gtprwnlmhc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xziqi.cn/Article/details/gtmqmwwwle.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtxfhohbbo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtjxiwlmet.html

TS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtlpruyymb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtrgsqzqty.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shzxlz.cn/Article/details/gtuijwzxbp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxuanxn.top/Article/details/gtrqcyhhpk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtelkxnwea.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gzhubu.top/Article/details/gtlvklmits.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgfzy.top/Article/details/gtomxxdood.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tianlin.xyz/Article/details/gtexyqbqtq.html

JS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gtsiilcrjw.html

TS:   arr.map(x => x * 2)
来源：http://dali.birdmap.top/Article/details/gtkxfchbos.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ivvv.top/Article/details/gtuwmqcvpt.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gtwehenmlf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhixingplan.top/Article/details/gtlqsoqwud.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtfhwoextr.html

[D15] 去重
来源：http://dali.gotoacloud.top/Article/details/gtabyqzqig.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cheryme.top/Article/details/gtjnzkilsg.html

PHP:  array_unique($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehjkdcwu.html

JS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtteysulmt.html

TS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gtgawzlwqb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.havefunace.top/Article/details/gtrwrolnjx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jlsjyb.cn/Article/details/gtpmniuqqc.html

Ruby: arr.uniq
来源：http://dali.ehwqpu.com/Article/details/gttijnxnqn.html

C#:   list.Distinct().ToList()
来源：http://dali.sysykeji.top/Article/details/gtlugeutap.html

[D16] 求和与平均值
来源：http://dali.jinqigfzy.top/Article/details/gtvparutjj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.bjfxy.top/Article/details/gtmkkyltvy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtfchhdvbr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gtlljickhy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gtxdngxcgs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258888.top/Article/details/gtcmkhyhfr.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucaaxvdu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnqzz.top/Article/details/gtwjdmowpu.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258.top/Article/details/gtynleorhf.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gtfqxiqgze.html

Py:   max(arr);  min(arr)
来源：http://dali.shzxlz.cn/Article/details/gtpfkepfvt.html

PHP:  max($arr);  min($arr);
来源：http://dali.hywenlv.cn/Article/details/gtzshblmzp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.bjfxy.top/Article/details/gtiybikywj.html

TS:   Math.max(...arr);
来源：http://dali.yangfankeji.com/Article/details/gtxeoorfey.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ppjwa.cn/Article/details/gtxkkdjvdf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuxming.cn/Article/details/gtbtmlaqhs.html

Ruby: arr.max;  arr.min
来源：http://dali.dianchejie.cn/Article/details/gtucpbsppb.html

C#:   list.Max();  list.Min()
来源：http://dali.sweek.top/Article/details/gttrbnyvfu.html

[D18] 扁平化嵌套数组
来源：http://dali.shzxlz.cn/Article/details/gtziovigpk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guowangkeji.top/Article/details/gtvpqsnzfr.html

PHP:  array_merge(...$nested);
来源：http://dali.yanxiufei.cn/Article/details/gtbofrbmmy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuetiantiany.cn/Article/details/gtscbgmkcc.html

TS:   nested.flat();
来源：http://dali.xuanzx.com/Article/details/gtgobhydqn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtnzgqlhfx.html

Go:   // 手写双层循环
来源：http://dali.hysaishi.cn/Article/details/gtnhqewqnc.html

Ruby: nested.flatten
来源：http://dali.shangyingyoupin.top/Article/details/gtgavzetji.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtbzpgzxdu.html

[D19] 按字段分组
来源：http://dali.hammf.cn/Article/details/gtnravdrqb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj202588.top/Article/details/gtgtcqhznn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gotoacloud.top/Article/details/gtmjqeilgz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.vqdsnc.cn/Article/details/gtculxoinh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcfrosha.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jiagoushi.top/Article/details/gtwhbkexdy.html

Go:   // 手写 map[string][]T
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhboqdwf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tianlin.xyz/Article/details/gtywtrfodl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhengqikj.top/Article/details/gtimuceyiq.html

[D20] 统计每个元素出现次数
来源：http://dali.gotoacloud.top/Article/details/gtgiokupfs.html

Py:   Counter(arr)
来源：http://dali.sysykeji.top/Article/details/gtzvfbyiuf.html

PHP:  array_count_values($arr);
来源：http://dali.nwbrower.top/Article/details/gttcthfqpc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gtoncxzcft.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gtarisqmws.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.aibaodan.cn/Article/details/gtfegheyea.html

Go:   // 手写 map[T]int
来源：http://dali.hongshengwenyu.top/Article/details/gtxoycggeu.html

Ruby: arr.tally
来源：http://dali.jianghu66.top/Article/details/gtqlpxrzsv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jlsjyb.cn/Article/details/gtpuqfeekn.html

[D21] 判断是否包含某元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwjvxjnd.html

Py:   x in arr
来源：http://dali.tian-w.cn/Article/details/gtqsumhemk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jqgfzy.top/Article/details/gthgtodhva.html

JS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gtocdsgabd.html

TS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gtxqyosxel.html

Java: list.contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtqjdcmvdr.html

Go:   slices.Contains(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtgfdadqlo.html

Ruby: arr.include?(x)
来源：http://dali.redwolf501.top/Article/details/gtwukuufjm.html

C#:   list.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gtoyakulfn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gotoacloud.top/Article/details/gtyotaqotu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.meibo888.top/Article/details/gtfuairvae.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxuanxn.top/Article/details/gtolehtqdp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.birdmap.top/Article/details/gtecabxkts.html

TS:   [...arr];
来源：http://dali.ivvv.top/Article/details/gtngzneszs.html

Java: new ArrayList<>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtgzdrjabd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.redwolf501.top/Article/details/gtlycmbgho.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zdqjudy.top/Article/details/gtwxabxfyz.html

C#:   new List<int>(list);
来源：http://dali.gotoacloud.top/Article/details/gtbsrsivyv.html

[D23] reduce 累积计算
来源：http://dali.pengpengdd.cyou/Article/details/gtwglvhupg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shzxlz.cn/Article/details/gtfcdikgwb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258888.top/Article/details/gtclbsnzxo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gtawkzslbz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtxkhcpkzh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hywenlv.cn/Article/details/gtoplazvua.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gtuublzddv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuanzx.com/Article/details/gtltgsyuel.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinqigufen.top/Article/details/gtcawwtxbs.html

[D24] 字典 / Map 基本操作
来源：http://dali.ydzc1.top/Article/details/gtvvqezlze.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cheryme.top/Article/details/gtqmeerass.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangdashe.top/Article/details/gtateeywmq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aizwys.cn/Article/details/gtcqdhpxyh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtadhtvebh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zycfv.cn/Article/details/gtjnjsfvza.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.316326.xyz/Article/details/gtbzwuzals.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhoulong.xyz/Article/details/gtudhpasrg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cucudq.cn/Article/details/gtxhdozacl.html

[D25] Set 集合去重与交并差
来源：http://dali.0kj1m.cn/Article/details/gtgrifaifh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shangyingyoupin.top/Article/details/gtmgjchucr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yueranfly.top/Article/details/gtesntlxsb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ybcxt.top/Article/details/gtdcenrlba.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hongshengwenyu.top/Article/details/gtmselwjxb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.c1oappe.top/Article/details/gtzfqoious.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxuanxn.top/Article/details/gthqibjzah.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhoulong.xyz/Article/details/gteeslwzkj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhhjezes.html

[D26] 数组转字符串
来源：http://dali.bjfxy.top/Article/details/gtjdfdovwh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cucudq.cn/Article/details/gtqcthyscm.html

PHP:  implode(", ", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtqtfmcafi.html

JS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtnvbvqgbc.html

TS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtsyuucscn.html

Java: String.join(", ", list)
来源：http://dali.jiagoushi.top/Article/details/gtlbmsnfrc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daria6918.cn/Article/details/gtabkojrio.html

Ruby: arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gtginectgb.html

C#:   string.Join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gttltinisa.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtibiqznpi.html

E. 字符串处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmpofups.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtjquswwmm.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutcxrzvl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daxiang520.top/Article/details/gtmhanlmyx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gotoacloud.top/Article/details/gtoansjosr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gtdhcfnnml.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gtidxpbqsf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.guannengcc.top/Article/details/gtyfzkjlne.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gotoacloud.top/Article/details/gtldnkvjqc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sufxvd.cn/Article/details/gtrodcsgxw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtzntxppzo.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gtssgtgwqh.html

Py:   "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gtrfdsxmqe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgurtabj.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdiakncl.html

TS:   "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gtjjcitecf.html

Java: "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtoqidcvot.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gtiooayrle.html

Ruby: "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gtiugcudju.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhixingplan.top/Article/details/gtoizhtoas.html

[E03] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gtnyjcvmsj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daxiang520.top/Article/details/gtzbszcjgt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtkocwflaq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtutilxsnk.html

TS:   s.slice(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtdlazvupn.html

Java: s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gtzrdjpdtk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daria6918.cn/Article/details/gtywdjssmw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpielkxdt.html

C#:   s.Substring(1, 3)
来源：http://dali.shzxlz.cn/Article/details/gtpbhyvjhh.html

[E04] 查找子串位置
来源：http://dali.ppjwa.cn/Article/details/gtvismouvu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gteojcghia.html

PHP:  strpos($s, "x");
来源：http://dali.hongshengwenyu.top/Article/details/gtsjecgmmx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tanke756.top/Article/details/gtqihudbxp.html

TS:   s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtthaorvay.html

Java: s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtahdltxtv.html

Go:   strings.Index(s, "x")
来源：http://dali.wangshuangyany.cn/Article/details/gtrudyizfs.html

Ruby: s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gtahllicfp.html

C#:   s.IndexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gtbjecjieb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guowangkeji.top/Article/details/gtegwsljjx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtkpndmjxr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gzhubu.top/Article/details/gtqklojcvf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cheryme.top/Article/details/gtgajrwfhp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nanxinkj.top/Article/details/gtegnmybkl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtsltywvcy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tianlin.xyz/Article/details/gtzuqcgpzn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hfpthk.cn/Article/details/gtjqxcdpkn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj202588.top/Article/details/gtuppslber.html

[E06] 替换子串
来源：http://dali.cdnleiting.top/Article/details/gtbgemmaav.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gtkbbxqovu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pycfn.com/Article/details/gtxpsmmwcj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtvffnvjtf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gthlnhhrio.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtzkriwkgm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cheryme.top/Article/details/gtdynwdvqf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtyieufuoy.html

C#:   s.Replace("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtteetpeqb.html

[E07] 按分隔符拆分
来源：http://dali.ydzc1.top/Article/details/gtxfczadvv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.0kj1m.cn/Article/details/gttcvobrnk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tian-w.cn/Article/details/gtjsntibea.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.svipenyu.cn/Article/details/gtmlevkxrr.html

TS:   s.split(",")
来源：http://dali.gzhubu.top/Article/details/gtvpsgcyhe.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hammf.cn/Article/details/gtrzrkdopj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuukqjkyk.html

Ruby: s.split(",");  s.split
来源：http://dali.yangfankeji.com/Article/details/gtysgzbzqm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cdnleiting.top/Article/details/gtdsnmkmmp.html

[E08] 数组按分隔符合并
来源：http://dali.daria6918.cn/Article/details/gtryogqfeo.html

Py:   ",".join(items)
来源：http://dali.ybcxt.top/Article/details/gturnothxt.html

PHP:  implode(",", $items);
来源：http://dali.xuetiantiany.cn/Article/details/gtzsnwjloh.html

JS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzfpvujb.html

TS:   items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gtvojotbpc.html

Java: String.join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gtpmxqhtey.html

Go:   strings.Join(items, ",")
来源：http://dali.tianlin.xyz/Article/details/gthcrftybs.html

Ruby: items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gttbiuctbx.html

C#:   string.Join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gtdxysowmq.html

[E09] 去除所有空白字符
来源：http://dali.birdmap.top/Article/details/gtvliuvmup.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jlsjyb.cn/Article/details/gttflawlyr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dashuyun.cn/Article/details/gtyppudqlm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgejkopr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtvwxvwijp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gtsjjdtcca.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sxryk.cn/Article/details/gtcndzobqk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.quarkkingdee.top/Article/details/gtkdfqkdpe.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daria6918.cn/Article/details/gtsgikmraz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhengqikj.top/Article/details/gteqtcxkny.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtapovepvm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shuidangran.top/Article/details/gtwoseqxwa.html

JS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtzkafzujw.html

TS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtkcbquuex.html

Java: String.format("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gtkisazzwj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gtboklisaf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtpkgmwpwm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jyoumei.cn/Article/details/gtoiuwtvek.html

[E11] 反转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtymzuivwl.html

Py:   s[::-1]
来源：http://dali.cashguo.top/Article/details/gthuhaavvz.html

PHP:  strrev($s);
来源：http://dali.daria6918.cn/Article/details/gtbmdiumfs.html


<!-- 参考信息 -->