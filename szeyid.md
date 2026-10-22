代发 wailian999

[D03] 在指定位置插入元素
来源：http://dali.nwbrower.top/Article/details/gtnxoqizou.html

Py:   arr.insert(0, 0)
来源：http://dali.pycfn.com/Article/details/gtqarbgnqm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sxryk.cn/Article/details/gtdwdozbwz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gtxwcckcpp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yuanzhike.top/Article/details/gtfpflotnq.html

Java: list.add(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gtoehdvqfc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.birdmap.top/Article/details/gtukdxhyyt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.feifeiyinyue.top/Article/details/gtrduhoriw.html

C#:   list.Insert(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpyxbgsvt.html

[D04] 删除元素
来源：http://dali.snrcjt.cn/Article/details/gtssecrwwz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqoqovazj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nwbrower.top/Article/details/gtmhqczkwt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ybcxt.top/Article/details/gthqsjlekw.html

TS:   arr.splice(0, 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskrewkui.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnqzz.top/Article/details/gtmuuaceoy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tianlin.xyz/Article/details/gtomjarztq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.wangdashe.top/Article/details/gtqbumevwn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guannengcc.top/Article/details/gtalpafisx.html

[D05] 访问与修改元素
来源：http://dali.zhongyouzk.top/Article/details/gteeduemnd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gtghfwgopf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtwzntukuw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtxlqfpqwg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehbqxvsv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.snrcjt.cn/Article/details/gtqonvuxhn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtwpmoihvk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtzgapizxw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtqjhwiadd.html

[D06] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gtmbhhefto.html

Py:   len(arr)
来源：http://dali.hysaishi.cn/Article/details/gtprcotpdx.html

PHP:  count($arr);
来源：http://dali.jqgfzy.top/Article/details/gtozinsirr.html

JS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gtxketscku.html

TS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gtloalehhj.html

Java: list.size();
来源：http://dali.jiagoushi.top/Article/details/gtmdmssfjb.html

Go:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpaobxmbh.html

Ruby: arr.length; arr.size
来源：http://dali.yongpay.top/Article/details/gtycqgatau.html

C#:   list.Count;
来源：http://dali.0kj1m.cn/Article/details/gtuuzbktcv.html

[D07] 切片 / 取子数组
来源：http://dali.xuanzx.com/Article/details/gtcuihvpkq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigfzy.top/Article/details/gtvjsnjmjt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sysykeji.top/Article/details/gthegklsaq.html

JS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gtlhwslgkl.html

TS:   arr.slice(1, 4);
来源：http://dali.aizwys.cn/Article/details/gtwwjxkzcl.html

Java: list.subList(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gtxqmeghsy.html

Go:   arr[1:4]
来源：http://dali.xinyue.icu/Article/details/gtjlkbkemk.html

Ruby: arr[1, 3]
来源：http://dali.gzhubu.top/Article/details/gtatfgjmte.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhixingplan.top/Article/details/gtbqfcpygr.html

[D08] 合并两个数组
来源：http://dali.daxiang520.top/Article/details/gtfigaxgfd.html

Py:   a + b;  a.extend(b)
来源：http://dali.smart0.xyz/Article/details/gthwkhmcvk.html

PHP:  array_merge($a, $b);
来源：http://dali.jiagoushi.top/Article/details/gtrshqonvm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yongpay.top/Article/details/gtfwsgnzar.html

TS:   [...a, ...b];
来源：http://dali.shuidangran.top/Article/details/gtrifnbmgf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.iojbl.cn/Article/details/gtqclgqknb.html

Go:   append(a, b...)
来源：http://dali.xinyue.icu/Article/details/gtzayzkwua.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fzhhl.top/Article/details/gtxezybzzv.html

C#:   a.Concat(b).ToList()
来源：http://dali.birdmap.top/Article/details/gtsjdrxevr.html

[D09] 排序（升序）
来源：http://dali.cheryme.top/Article/details/gturpjfynr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gtndfatayu.html

PHP:  sort($arr);
来源：http://dali.jyoumei.cn/Article/details/gtcoowodkz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258888.top/Article/details/gthajembdp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guowangkeji.top/Article/details/gtpnjgsuym.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.svipenyu.cn/Article/details/gtouiaflec.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guannengcc.top/Article/details/gtkjchmgyo.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gtgmodjfqt.html

C#:   list.Sort();
来源：http://dali.iojbl.cn/Article/details/gtsxpiphil.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nwbrower.top/Article/details/gtfafoljnl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.redwolf501.top/Article/details/gtbnsqodcx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gtfdpzercb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gtcpipests.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfifrups.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yangfankeji.com/Article/details/gtndhaqwvi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhongyouzk.top/Article/details/gtyxpyzhrg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenlongwang.top/Article/details/gtilwxfaen.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guannengcc.top/Article/details/gtnbeyjwqq.html

[D11] 反转数组
来源：http://dali.xuanzx.com/Article/details/gtqpqcimmw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.snrcjt.cn/Article/details/gtsxvuwuyv.html

PHP:  array_reverse($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtiorjheox.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jiagoushi.top/Article/details/gtjfsyifst.html

TS:   [...arr].reverse();
来源：http://dali.ybcxt.top/Article/details/gttvnffhov.html

Java: Collections.reverse(list);
来源：http://dali.bjfxy.top/Article/details/gtovbfvvcc.html

Go:   slices.Reverse(arr)
来源：http://dali.gogol.net.cn/Article/details/gtudkzamkz.html

Ruby: arr.reverse
来源：http://dali.dashuyun.cn/Article/details/gttemyahpx.html

C#:   list.Reverse();
来源：http://dali.cashguo.top/Article/details/gtjxttkkds.html

[D12] 查找元素下标
来源：http://dali.guannengcc.top/Article/details/gthwsrtxuk.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigfzy.top/Article/details/gtzuplisid.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daxiang520.top/Article/details/gtctquoish.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.mhx1999.top/Article/details/gtamiguymh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yueranfly.top/Article/details/gtqmsncldd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sysykeji.top/Article/details/gttxzbphqb.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtoyzutlgi.html

Ruby: arr.index(x)
来源：http://dali.snrcjt.cn/Article/details/gttpmnnbhj.html

C#:   list.IndexOf(x);
来源：http://dali.yongpay.top/Article/details/gtdbofncjy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258888.top/Article/details/gtpokgywgp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.svipenyu.cn/Article/details/gtcbjdfuod.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jyoumei.cn/Article/details/gtenfuufij.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtarusxams.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gtkgkmlpdj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.snrcjt.cn/Article/details/gtxizzijbl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.daxiang520.top/Article/details/gtgxpwawtn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.smart0.xyz/Article/details/gtkezodrms.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtzmsbqsik.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhixingplan.top/Article/details/gtvnsdzlbs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvriddckf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.andypj.xyz/Article/details/gtlralyzls.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gtjdhkclji.html

TS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gtvpyswyny.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sufxvd.cn/Article/details/gttlrgokje.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gtmplzdhmx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtuxapnpgt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtfnugxqsh.html

[D15] 去重
来源：http://dali.hongshengwenyu.top/Article/details/gtgywfdhph.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdausbxx.html

PHP:  array_unique($arr);
来源：http://dali.mhx1999.top/Article/details/gtoypwtvly.html

JS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtofkiqktn.html

TS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gtnxmedqwg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ppjwa.cn/Article/details/gtbxolyuyl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ivvv.top/Article/details/gtkjtjmnap.html

Ruby: arr.uniq
来源：http://dali.ivvv.top/Article/details/gtxxnmqdqy.html

C#:   list.Distinct().ToList()
来源：http://dali.cqqwz.cn/Article/details/gtxkkeymrq.html

[D16] 求和与平均值
来源：http://dali.gotoacloud.top/Article/details/gtnwbmcpdr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gotoacloud.top/Article/details/gtcsrpdgnq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtelvgqmas.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtsujuqbtt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtohaswbgy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenlongwang.top/Article/details/gtjkxssonr.html

Go:   // 手写循环累加
来源：http://dali.tianlin.xyz/Article/details/gtbkabfffu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tian-w.cn/Article/details/gtuodcpdyi.html

C#:   list.Sum();  list.Average()
来源：http://dali.0kj1m.cn/Article/details/gtouyelllt.html

[D17] 最大值与最小值
来源：http://dali.fzhhl.top/Article/details/gturldhdje.html

Py:   max(arr);  min(arr)
来源：http://dali.ppjwa.cn/Article/details/gtgupbdbdt.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuanzhike.top/Article/details/gtuanolinp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigfzy.top/Article/details/gtlutqodbd.html

TS:   Math.max(...arr);
来源：http://dali.yj20258.top/Article/details/gtkltuicsl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwnnptpq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtnoukaqyw.html

Ruby: arr.max;  arr.min
来源：http://dali.cashguo.top/Article/details/gtbfjtmzik.html

C#:   list.Max();  list.Min()
来源：http://dali.tian-w.cn/Article/details/gtwoeiijbd.html

[D18] 扁平化嵌套数组
来源：http://dali.feifeiyinyue.top/Article/details/gtfeoqwzlv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xylfe.cn/Article/details/gtqyngkrlq.html

PHP:  array_merge(...$nested);
来源：http://dali.zhoulong.xyz/Article/details/gtllwmlgbd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuanzhike.top/Article/details/gttphhuznh.html

TS:   nested.flat();
来源：http://dali.meibo888.top/Article/details/gtuhytkjnn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.mhx1999.top/Article/details/gtdoevnuwv.html

Go:   // 手写双层循环
来源：http://dali.ivvv.top/Article/details/gtmecqxxhm.html

Ruby: nested.flatten
来源：http://dali.fengsongda.top/Article/details/gtccmfopub.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cucudq.cn/Article/details/gttxwtukey.html

[D19] 按字段分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmatqmfky.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.bjfxy.top/Article/details/gtuheubcmb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ppjwa.cn/Article/details/gtlqwbiovo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fzhhl.top/Article/details/gterhanyqb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.birdmap.top/Article/details/gtoqzmqawy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shuidangran.top/Article/details/gtemrftxnq.html

Go:   // 手写 map[string][]T
来源：http://dali.316326.xyz/Article/details/gtppbfygub.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxinkj.top/Article/details/gtaiktuahh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shuidangran.top/Article/details/gtbtypmazh.html

[D20] 统计每个元素出现次数
来源：http://dali.snrcjt.cn/Article/details/gtxrorpxuy.html

Py:   Counter(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovjrotzm.html

PHP:  array_count_values($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtsadykgik.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gtjqhuxnqk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gtrqwftwff.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jlsjyb.cn/Article/details/gtepfmsdvj.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigufen.top/Article/details/gtrpvlennd.html

Ruby: arr.tally
来源：http://dali.sxryk.cn/Article/details/gtdtshuvay.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gogol.net.cn/Article/details/gtcvdcfhlp.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gtnroktwax.html

Py:   x in arr
来源：http://dali.gzhubu.top/Article/details/gtdkpxdlle.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jiagoushi.top/Article/details/gtgwfcgssa.html

JS:   arr.includes(x)
来源：http://dali.ppjwa.cn/Article/details/gtwkmrnokd.html

TS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshbgwolq.html

Java: list.contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtglmpgxds.html

Go:   slices.Contains(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtfxsbcwbl.html

Ruby: arr.include?(x)
来源：http://dali.nwbrower.top/Article/details/gtxdbadtie.html

C#:   list.Contains(x)
来源：http://dali.xylfe.cn/Article/details/gtxgkdzvjv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenjidiqi.icu/Article/details/gtwqqitelv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.birdmap.top/Article/details/gtowvudjld.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.havefunace.top/Article/details/gtbdkfxrer.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtjzpmiyje.html

TS:   [...arr];
来源：http://dali.yj20258888.top/Article/details/gtpogbbcbj.html

Java: new ArrayList<>(list);
来源：http://dali.daria6918.cn/Article/details/gtqpbopkdq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hfpthk.cn/Article/details/gtvddhyuze.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigfzy.top/Article/details/gtzswvzncp.html

C#:   new List<int>(list);
来源：http://dali.andypj.xyz/Article/details/gtgljxhsay.html

[D23] reduce 累积计算
来源：http://dali.zhiwuduotai.top/Article/details/gtiztstkei.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yongpay.top/Article/details/gtdhrxaorm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtfuyuusul.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gtqujctzgw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gtdfkvcjwr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.meibo888.top/Article/details/gtgbsswwqh.html

Go:   // 手写循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswgswvfl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jianghu66.top/Article/details/gtibrvkbjk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jlsjyb.cn/Article/details/gtutaunals.html

[D24] 字典 / Map 基本操作
来源：http://dali.dianchejie.cn/Article/details/gthkzaxref.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangdashe.top/Article/details/gtwjfafllx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtvybtxdpr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hysaishi.cn/Article/details/gtgeoenfak.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtnhmgkxtn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dianchejie.cn/Article/details/gthpymsymi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxuanxn.top/Article/details/gtkxzecspj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gotoacloud.top/Article/details/gtjxpgfyhq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhixingplan.top/Article/details/gtbkytlwek.html

[D25] Set 集合去重与交并差
来源：http://dali.hammf.cn/Article/details/gtikoeyzjk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ehwqpu.com/Article/details/gtdytqwhgs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgufenzy.top/Article/details/gtyvjhvbkq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ehwqpu.com/Article/details/gtbbyypmnb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jiagoushi.top/Article/details/gtwoseveyn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daxiang520.top/Article/details/gtbxjnsuez.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.316326.xyz/Article/details/gtsqcqioyh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cqqwz.cn/Article/details/gtvgytoahr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hammf.cn/Article/details/gtzseelhod.html

[D26] 数组转字符串
来源：http://dali.bjfxy.top/Article/details/gtkhubtyha.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yueranfly.top/Article/details/gtlvoiprgb.html

PHP:  implode(", ", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtnulzdepr.html

JS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtunmwcorb.html

TS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtdomlfcdl.html

Java: String.join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gtmodaupjt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.0kj1m.cn/Article/details/gtdynhvlfb.html

Ruby: arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gtlhwozgdc.html

C#:   string.Join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gthrwlbmpz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtqygmxcbo.html

E. 字符串处理
来源：http://dali.cqqwz.cn/Article/details/gtiyaiaitn.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtwwlcfngv.html

[E01] 拼接字符串
来源：http://dali.iojbl.cn/Article/details/gtdsalihfm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuanzx.com/Article/details/gtabmotjwo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hfpthk.cn/Article/details/gtrtihlhuq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtxkbeqhbh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gtvktooukf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ybcxt.top/Article/details/gtwfvhsspk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yvedp.cn/Article/details/gtqyyarzod.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj20258888.top/Article/details/gtewepqqdx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtanhyscek.html

[E02] 重复字符串
来源：http://dali.jqgufenzy.top/Article/details/gtlltwpjja.html

Py:   "ab" * 3
来源：http://dali.yj20258.top/Article/details/gtcvcegrtc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cqqwz.cn/Article/details/gtbofxxfka.html

JS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtvfnxfwmd.html

TS:   "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gtyesrbywn.html

Java: "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gtwxjsxder.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtqmwmtbkf.html

Ruby: "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gtuelkqljn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangshuangyany.cn/Article/details/gtfrcdfelv.html

[E03] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gtofhwblrj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxuanxn.top/Article/details/gtxxqdcygm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhnwnyxs.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gteyhmefch.html

TS:   s.slice(1, 4)
来源：http://dali.yj202588.top/Article/details/gtqweybymy.html

Java: s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtygvbxcnn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtangftenk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhiwuduotai.top/Article/details/gtihnkpkfb.html

C#:   s.Substring(1, 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxbilsuv.html

[E04] 查找子串位置
来源：http://dali.zhixingplan.top/Article/details/gthnekqlnb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gttwvwhsus.html

PHP:  strpos($s, "x");
来源：http://dali.dashuyun.cn/Article/details/gtgaqryuxr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gogol.net.cn/Article/details/gtumjpatmk.html

TS:   s.indexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gtnxzrtfjx.html

Java: s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gtyucymman.html

Go:   strings.Index(s, "x")
来源：http://dali.cashguo.top/Article/details/gtvsywksbk.html

Ruby: s.index("x")
来源：http://dali.feifeiyinyue.top/Article/details/gttlvlsgik.html

C#:   s.IndexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtkhrcniir.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangdashe.top/Article/details/gtkqfcyild.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zdqjudy.top/Article/details/gthamtzseb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifgyrfbq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daria6918.cn/Article/details/gtpdtgwfcm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258.top/Article/details/gteqhlffvz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtrrdbkvzs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.snrcjt.cn/Article/details/gtdfgodckn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aibaodan.cn/Article/details/gtpvegfsrn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tanke756.top/Article/details/gtkfunplvq.html

[E06] 替换子串
来源：http://dali.yanxiufei.cn/Article/details/gtlgxdejur.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gtejubfwht.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hfpthk.cn/Article/details/gttpastegy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtnjcvppip.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtmfjeossf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibjtxarm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guannengcc.top/Article/details/gtspdarmkf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtvvkopyul.html

C#:   s.Replace("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtxwtcolhn.html

[E07] 按分隔符拆分
来源：http://dali.nanxinkj.top/Article/details/gtjhosngsf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbozqogd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtqjeyvjge.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ppjwa.cn/Article/details/gtemijubxi.html

TS:   s.split(",")
来源：http://dali.ivvv.top/Article/details/gtqjaggwub.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgufenzy.top/Article/details/gtlzillcrb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtltanpbrs.html

Ruby: s.split(",");  s.split
来源：http://dali.sweek.top/Article/details/gtdasnpozf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zycfv.cn/Article/details/gtbjdzsbdn.html

[E08] 数组按分隔符合并
来源：http://dali.cqqwz.cn/Article/details/gtwqmhqehr.html

Py:   ",".join(items)
来源：http://dali.zhixingplan.top/Article/details/gtvhwsnkfh.html

PHP:  implode(",", $items);
来源：http://dali.hammf.cn/Article/details/gtcnninuki.html

JS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gtdqdeyczj.html

TS:   items.join(",")
来源：http://dali.bjfxy.top/Article/details/gtledmidcv.html

Java: String.join(",", items)
来源：http://dali.hywenlv.cn/Article/details/gtmfqcgttn.html

Go:   strings.Join(items, ",")
来源：http://dali.sufxvd.cn/Article/details/gtocyretuh.html

Ruby: items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqnxxuxe.html

C#:   string.Join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gtiuwvxuvc.html

[E09] 去除所有空白字符
来源：http://dali.gotoacloud.top/Article/details/gterjlmmkk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aibaodan.cn/Article/details/gtppoikwag.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtsbzmsvss.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gthebkhlhy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gtfhtqfnos.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtljaqdryo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cheryme.top/Article/details/gtlulnestw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daria6918.cn/Article/details/gtumvttykv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gtalwefgcp.html


<!-- 参考信息 -->