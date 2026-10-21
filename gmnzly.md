代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.snrcjt.cn/Article/details/gtjiwqjlth.html

TS:   arr.splice(0, 1);
来源：http://dali.ydzc1.top/Article/details/gtlcfccvht.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shzxlz.cn/Article/details/gtipzrlmaq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.quarkkingdee.top/Article/details/gtnnpupzqn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gtoilejrlx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenlongwang.top/Article/details/gtnwpvehzt.html

[D05] 访问与修改元素
来源：http://dali.tianlin.xyz/Article/details/gtkoeehaet.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtouibnbbt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gtrzbpgzwp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gterkfkatv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhixingplan.top/Article/details/gtgwtixoiu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shzxlz.cn/Article/details/gtucorrbom.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gtecsuaryw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtdbkcndxd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtnmaoklkk.html

[D06] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gtlutppbpn.html

Py:   len(arr)
来源：http://dali.zdqjudy.top/Article/details/gtpnbtkunv.html

PHP:  count($arr);
来源：http://dali.smart0.xyz/Article/details/gtxuixglix.html

JS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gtfmybcizw.html

TS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gtzipnpadv.html

Java: list.size();
来源：http://dali.yvedp.cn/Article/details/gtfamxrntu.html

Go:   len(arr)
来源：http://dali.nwbrower.top/Article/details/gtrtftamib.html

Ruby: arr.length; arr.size
来源：http://dali.iojbl.cn/Article/details/gtzpbfwukm.html

C#:   list.Count;
来源：http://dali.jyoumei.cn/Article/details/gtkgbjmnbj.html

[D07] 切片 / 取子数组
来源：http://dali.jlsjyb.cn/Article/details/gtoaroumpi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.havefunace.top/Article/details/gtzlihtanj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenlongwang.top/Article/details/gtlihteboj.html

JS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtrqenazmv.html

TS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gtcikzueju.html

Java: list.subList(1, 4);
来源：http://dali.yj202588.top/Article/details/gtvxbuxxev.html

Go:   arr[1:4]
来源：http://dali.c1oappe.top/Article/details/gtnkgjklja.html

Ruby: arr[1, 3]
来源：http://dali.cucudq.cn/Article/details/gtvstzjpox.html

C#:   list.GetRange(1, 3);
来源：http://dali.tanke756.top/Article/details/gtvvolefme.html

[D08] 合并两个数组
来源：http://dali.9152youxi.cn/Article/details/gtpkcepekc.html

Py:   a + b;  a.extend(b)
来源：http://dali.yvedp.cn/Article/details/gtfrfxxrwc.html

PHP:  array_merge($a, $b);
来源：http://dali.cdnleiting.top/Article/details/gtvnyibroz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gzhubu.top/Article/details/gtpvpsztem.html

TS:   [...a, ...b];
来源：http://dali.mhx1999.top/Article/details/gtrqqgbsyj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.redwolf501.top/Article/details/gtaxkjiqfn.html

Go:   append(a, b...)
来源：http://dali.xylfe.cn/Article/details/gtxnapqqte.html

Ruby: a + b;  a.concat(b)
来源：http://dali.redwolf501.top/Article/details/gtgqgxpnrs.html

C#:   a.Concat(b).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtcgyhvivl.html

[D09] 排序（升序）
来源：http://dali.zhongyouzk.top/Article/details/gtqrfqtzmz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gtrundxgbc.html

PHP:  sort($arr);
来源：http://dali.yueranfly.top/Article/details/gtbwbbfybg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yueranfly.top/Article/details/gtwuwsivvb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yueranfly.top/Article/details/gtuiovntgn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.birdmap.top/Article/details/gtmpfytyim.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtqgmnzppa.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gtcrdduxqi.html

C#:   list.Sort();
来源：http://dali.cheryme.top/Article/details/gtqdgymfpd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jqgfzy.top/Article/details/gthknupxkq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthrbyvckj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gtbrlwfzlv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gtuvxbcrzi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gtdsmktiry.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aibaodan.cn/Article/details/gtvbzjgwuy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuanzx.com/Article/details/gtsrgwpacr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.redwolf501.top/Article/details/gtlijmlpls.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ppjwa.cn/Article/details/gtwsfilayw.html

[D11] 反转数组
来源：http://dali.xuanzx.com/Article/details/gtronjxell.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pengpengdd.cyou/Article/details/gtldisruxe.html

PHP:  array_reverse($arr);
来源：http://dali.jiagoushi.top/Article/details/gtxonmqsec.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yvedp.cn/Article/details/gtgmkcwqit.html

TS:   [...arr].reverse();
来源：http://dali.hammf.cn/Article/details/gtjpttksks.html

Java: Collections.reverse(list);
来源：http://dali.yanxiufei.cn/Article/details/gtjiljdupk.html

Go:   slices.Reverse(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gteytdyzxn.html

Ruby: arr.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuljgdjjf.html

C#:   list.Reverse();
来源：http://dali.nwbrower.top/Article/details/gtmvxzmrbd.html

[D12] 查找元素下标
来源：http://dali.zhongyouzk.top/Article/details/gtclamtmxv.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhengqikj.top/Article/details/gtxhbzjvgk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jiagoushi.top/Article/details/gtpfaggqsc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtticsdmea.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gtrnvvjmts.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.aizwys.cn/Article/details/gtycnemubw.html

Go:   slices.Index(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtmwahhigx.html

Ruby: arr.index(x)
来源：http://dali.xinyue.icu/Article/details/gtxvlsosfb.html

C#:   list.IndexOf(x);
来源：http://dali.zycfv.cn/Article/details/gtamgjstcd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gtkyqpsopd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtildrcnca.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hfpthk.cn/Article/details/gtwjyydkfv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gtrlleyilj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fengsongda.top/Article/details/gtnafuxpgv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hywenlv.cn/Article/details/gtxkhndcdt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xylfe.cn/Article/details/gtrxnlwpno.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hongshengwenyu.top/Article/details/gtafdnmdqg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtjhsxhhoa.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gtcfultnyw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nwbrower.top/Article/details/gtqdkgvccy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhengqikj.top/Article/details/gtfhagijeb.html

JS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gtkcwwbfgt.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gtuhunfuaq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtvqhgqhpx.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gtybfmdibq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmsevvjkd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnqzz.top/Article/details/gtraiijtbc.html

[D15] 去重
来源：http://dali.zhongyouzk.top/Article/details/gtbitlfdpm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daria6918.cn/Article/details/gtuvekeflw.html

PHP:  array_unique($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtnmhdwdrg.html

JS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gtbqnrfqlj.html

TS:   [...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gtdvdvdevo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cdnleiting.top/Article/details/gtltcuapbo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hywenlv.cn/Article/details/gtvdsmxvat.html

Ruby: arr.uniq
来源：http://dali.9152youxi.cn/Article/details/gtnquotsrk.html

C#:   list.Distinct().ToList()
来源：http://dali.tianlin.xyz/Article/details/gtlvhnghlz.html

[D16] 求和与平均值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdlbbvmt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtrkchmrjl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gotoacloud.top/Article/details/gtfuxmumnn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gtdmjjhhnn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gtjgdydeey.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.feifeiyinyue.top/Article/details/gtzlxfwlvv.html

Go:   // 手写循环累加
来源：http://dali.shuidangran.top/Article/details/gtxkvzcegf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gzhubu.top/Article/details/gtwqztjftk.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhiwuduotai.top/Article/details/gtdhcujxog.html

[D17] 最大值与最小值
来源：http://dali.ydzc1.top/Article/details/gtzhilniaq.html

Py:   max(arr);  min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtrpshcbtt.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuanzhike.top/Article/details/gtvperlhrn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtcomzgseh.html

TS:   Math.max(...arr);
来源：http://dali.yj20258.top/Article/details/gtagxfhzik.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aizwys.cn/Article/details/gtcffteyxq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtxrzubdbr.html

Ruby: arr.max;  arr.min
来源：http://dali.hnxiangtu.top/Article/details/gtyjktejzl.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgufenzy.top/Article/details/gtwfsjgfzn.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxuanxn.top/Article/details/gtujrnyyuc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cashguo.top/Article/details/gtbdvxuvca.html

PHP:  array_merge(...$nested);
来源：http://dali.daria6918.cn/Article/details/gtdsdsrgbt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tanke756.top/Article/details/gtyvwwalav.html

TS:   nested.flat();
来源：http://dali.tian-w.cn/Article/details/gtqzaignlf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cheryme.top/Article/details/gtpsxdahjw.html

Go:   // 手写双层循环
来源：http://dali.jinqigufen.top/Article/details/gtynmqqqhe.html

Ruby: nested.flatten
来源：http://dali.havefunace.top/Article/details/gtxhekmwlb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtshfsaeta.html

[D19] 按字段分组
来源：http://dali.yongpay.top/Article/details/gtciublucs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jlsjyb.cn/Article/details/gtydlsfuel.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxuanxn.top/Article/details/gtsjfsazci.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sxryk.cn/Article/details/gtpjhtewbq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gtnxusjwmj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daria6918.cn/Article/details/gtvonyreqs.html

Go:   // 手写 map[string][]T
来源：http://dali.fengsongda.top/Article/details/gtpfyacgug.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hammf.cn/Article/details/gtsjwausuj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jyoumei.cn/Article/details/gtdhsnraqp.html

[D20] 统计每个元素出现次数
来源：http://dali.jlsjyb.cn/Article/details/gtearfzmwl.html

Py:   Counter(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtxthkmiwt.html

PHP:  array_count_values($arr);
来源：http://dali.yuxming.cn/Article/details/gtfnhmjsjc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gtvvnxxxlm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtvuvueyvk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.aibaodan.cn/Article/details/gtibiqfnjv.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigfzy.top/Article/details/gtejkrfdwi.html

Ruby: arr.tally
来源：http://dali.kuanghao11.cn/Article/details/gtgazlxwvd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xinyue.icu/Article/details/gtdihkvqzn.html

[D21] 判断是否包含某元素
来源：http://dali.gzhubu.top/Article/details/gtajzngixe.html

Py:   x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gtcgqfktah.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tanke756.top/Article/details/gtbzarqjsc.html

JS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtyleeixkj.html

TS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtqlammafp.html

Java: list.contains(x)
来源：http://dali.xylfe.cn/Article/details/gtbfdbsbxa.html

Go:   slices.Contains(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmeawdovh.html

Ruby: arr.include?(x)
来源：http://dali.jinqigufen.top/Article/details/gttoosopic.html

C#:   list.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpyveqgyw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gzhubu.top/Article/details/gtjjbmhtvv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aibaodan.cn/Article/details/gtsgrllaqb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ybcxt.top/Article/details/gtcwnjglts.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xziqi.cn/Article/details/gtnkmcwaed.html

TS:   [...arr];
来源：http://dali.yangfankeji.com/Article/details/gtvprswohd.html

Java: new ArrayList<>(list);
来源：http://dali.ybcxt.top/Article/details/gtznltibbc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gtmnksnlri.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cqqwz.cn/Article/details/gtfivlmqmi.html

C#:   new List<int>(list);
来源：http://dali.yuxming.cn/Article/details/gtigwzatys.html

[D23] reduce 累积计算
来源：http://dali.zhoulong.xyz/Article/details/gtkhnkdjia.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhixingplan.top/Article/details/gtumxuxtea.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xylfe.cn/Article/details/gtxpjmdnbj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gtdnycgjzc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjhptbou.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhiwuduotai.top/Article/details/gtpqogijfm.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gtoyrqmtrl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yonumen.top/Article/details/gtzhjsewkj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nwbrower.top/Article/details/gtbbqrjrih.html

[D24] 字典 / Map 基本操作
来源：http://dali.aizwys.cn/Article/details/gtjtxlpsbt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xinyue.icu/Article/details/gttjypsbbw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxinkj.top/Article/details/gtfxgyjzef.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cqqwz.cn/Article/details/gtwterdeuk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.havefunace.top/Article/details/gtmjixfljq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nanxuanxn.top/Article/details/gtxwwyunsn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj202588.top/Article/details/gtgpkvocgp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhixingplan.top/Article/details/gtadtnwoml.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj20258888.top/Article/details/gtiabqhbnr.html

[D25] Set 集合去重与交并差
来源：http://dali.yvedp.cn/Article/details/gtggwqrspg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj20258.top/Article/details/gtxpixjcnm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenzaomai.com/Article/details/gtelvmclim.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jiagoushi.top/Article/details/gtslkwvwbx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xuanzx.com/Article/details/gtviuscrbf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.c1oappe.top/Article/details/gtlttfsjcz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.snrcjt.cn/Article/details/gttfcejpdy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.c1oappe.top/Article/details/gtklbhwuyn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.vqdsnc.cn/Article/details/gtxfxuiicw.html

[D26] 数组转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtfhuzzoxb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknpajgct.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258.top/Article/details/gtjricnsaa.html

JS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtcqoigwgw.html

TS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtwnivqawn.html

Java: String.join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gtalnryent.html

Go:   strings.Join(strs, ", ")
来源：http://dali.haohaochexian.top/Article/details/gtrvxxeslv.html

Ruby: arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gtnmzirguo.html

C#:   string.Join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gtewapaldv.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtheomnbjk.html

E. 字符串处理
来源：http://dali.gaohongyu789.top/Article/details/gtvjzxwutn.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtedmjeqcz.html

[E01] 拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtcbdhlwbg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jiagoushi.top/Article/details/gtmsarykvl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxsxppfsj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gtabxlprsr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gtcnjjthqh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daxiang520.top/Article/details/gtpjwzvbmn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guannengcc.top/Article/details/gtzlpnhfri.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.316326.xyz/Article/details/gtazdbapei.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtldnkeqjn.html

[E02] 重复字符串
来源：http://dali.fengsongda.top/Article/details/gtmxbzqeza.html

Py:   "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gtvzhxiggx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jqgufenzy.top/Article/details/gtdemhrybr.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtuvehzpqj.html

TS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtydlzfkwr.html

Java: "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqntqyaya.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nwbrower.top/Article/details/gtaqbmpbeb.html

Ruby: "ab" * 3
来源：http://dali.pycfn.com/Article/details/gtemaaoqkv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gtaszkljau.html

[E03] 截取子串
来源：http://dali.hammf.cn/Article/details/gtjkocaddb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zdqjudy.top/Article/details/gtskoacqxd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtzvtdyglj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gteflvksdd.html

TS:   s.slice(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtixwzcapq.html

Java: s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtizdrmxlj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtsihaoezp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hnxiangtu.top/Article/details/gtxqnyadbm.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxinkj.top/Article/details/gtbshxofiz.html

[E04] 查找子串位置
来源：http://dali.zhoulong.xyz/Article/details/gtvulilvgr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shuidangran.top/Article/details/gtvptbvjbj.html

PHP:  strpos($s, "x");
来源：http://dali.aibaodan.cn/Article/details/gtoepitbea.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.aibaodan.cn/Article/details/gtbnxofqwz.html

TS:   s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gthogokfvy.html

Java: s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gtceyfrwej.html

Go:   strings.Index(s, "x")
来源：http://dali.zycfv.cn/Article/details/gtchexvyge.html

Ruby: s.index("x")
来源：http://dali.xuanzx.com/Article/details/gtlcfvysec.html

C#:   s.IndexOf("x")
来源：http://dali.redwolf501.top/Article/details/gthvyswfqg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cucudq.cn/Article/details/gtdcvxnpja.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtvbpfeoxx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenjidiqi.icu/Article/details/gtuwcnunes.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtltkckquw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangdashe.top/Article/details/gttvrhgkbd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gtyplfgdpc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dashuyun.cn/Article/details/gtgyektkuy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jlsjyb.cn/Article/details/gtytpznwux.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtkcjftpms.html

[E06] 替换子串
来源：http://dali.jqgfzy.top/Article/details/gtjdfyfwoa.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gtlglglnlw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.9152youxi.cn/Article/details/gtyvsjrzmo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtfjqmbkij.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtcqfvocve.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtlrjxlxdd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigufen.top/Article/details/gtvnxcenir.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj202588.top/Article/details/gtbvoznlzc.html

C#:   s.Replace("a", "b")
来源：http://dali.yongpay.top/Article/details/gtczknmqad.html

[E07] 按分隔符拆分
来源：http://dali.birdmap.top/Article/details/gtwodzhmbw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.meibo888.top/Article/details/gtkffzgrvt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtpooswowe.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258888.top/Article/details/gtkcgccbhl.html

TS:   s.split(",")
来源：http://dali.chenlongwang.top/Article/details/gtxzddcrcz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zdqjudy.top/Article/details/gtnvzgnxgp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgufenzy.top/Article/details/gtoxsbchuw.html

Ruby: s.split(",");  s.split
来源：http://dali.guannengcc.top/Article/details/gtjusqxceq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofbwidkr.html

[E08] 数组按分隔符合并
来源：http://dali.hysaishi.cn/Article/details/gtcmrsystk.html

Py:   ",".join(items)
来源：http://dali.zhongyouzk.top/Article/details/gtsugctceb.html

PHP:  implode(",", $items);
来源：http://dali.yvedp.cn/Article/details/gtrhlvtplq.html

JS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtjrmelmpa.html

TS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gtdxoiwxsb.html

Java: String.join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gtfohkibrg.html

Go:   strings.Join(items, ",")
来源：http://dali.zycfv.cn/Article/details/gtmxkxujfo.html

Ruby: items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtksjccwbk.html

C#:   string.Join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gtzanosaqz.html

[E09] 去除所有空白字符
来源：http://dali.yongpay.top/Article/details/gthdwhfidl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fzhhl.top/Article/details/gtnkwxwomn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yangfankeji.com/Article/details/gtihyxdpwu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gaohongyu789.top/Article/details/gttmokvkkv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtliopvupa.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxoxyldar.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gttymategm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpswsohyl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gtadnyevxq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nwbrower.top/Article/details/gtfyhqhatt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtkxhxdlyr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cqqwz.cn/Article/details/gtlskqdcgi.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtbbftmgoe.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gtzxjolzrq.html

Java: String.format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtopiqhfso.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtuyivjmec.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtrqfuabuj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnqzz.top/Article/details/gttlwxczaz.html

[E11] 反转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtpjmnuyex.html

Py:   s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gtbeiwxqex.html

PHP:  strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gtrshhppju.html


<!-- 参考信息 -->