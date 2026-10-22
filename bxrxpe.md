代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swcjjgnu.html

TS:   arr.splice(0, 1);
来源：http://dali.ppjwa.cn/Article/details/gt2qlfghxgo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.svipenyu.cn/Article/details/gt2dmxglash.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.fzhhl.top/Article/details/gt2slzitsfy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hammf.cn/Article/details/gt2zvfpbvgu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hysaishi.cn/Article/details/gt2fqtrxygm.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gt2hxmfapgx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gt2ybpzmgjb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gt2eiukqukq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gt2qsxzjtzu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gzhubu.top/Article/details/gt2aqsrmmaf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hywenlv.cn/Article/details/gt2fgejdmuf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gt2jyifpvxt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gt2pqltkayl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gt2qlvdmixc.html

[D06] 数组长度
来源：http://dali.daxiang520.top/Article/details/gt2rwifzlaq.html

Py:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2bfnzhmuz.html

PHP:  count($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2rcbdqgur.html

JS:   arr.length
来源：http://dali.cheryme.top/Article/details/gt2jcqkeijc.html

TS:   arr.length
来源：http://dali.yongpay.top/Article/details/gt2sfxggmwv.html

Java: list.size();
来源：http://dali.yj20258.top/Article/details/gt2tgrquijn.html

Go:   len(arr)
来源：http://dali.yj202588.top/Article/details/gt2vukefoqp.html

Ruby: arr.length; arr.size
来源：http://dali.jiagoushi.top/Article/details/gt2rbwsvqun.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsumxgu.html

[D07] 切片 / 取子数组
来源：http://dali.cheryme.top/Article/details/gt2mnuanbsb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xziqi.cn/Article/details/gt2ujzodqgq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zdqjudy.top/Article/details/gt2qiocffhg.html

JS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gt2naxqadjk.html

TS:   arr.slice(1, 4);
来源：http://dali.zycfv.cn/Article/details/gt2xsqsgawz.html

Java: list.subList(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lutkhdkw.html

Go:   arr[1:4]
来源：http://dali.tianlin.xyz/Article/details/gt2gjaftzyg.html

Ruby: arr[1, 3]
来源：http://dali.zhixingplan.top/Article/details/gt2ikuzafza.html

C#:   list.GetRange(1, 3);
来源：http://dali.nwbrower.top/Article/details/gt2zznrjjzg.html

[D08] 合并两个数组
来源：http://dali.meibo888.top/Article/details/gt2dzgrosqe.html

Py:   a + b;  a.extend(b)
来源：http://dali.guowangkeji.top/Article/details/gt2lxexhyqs.html

PHP:  array_merge($a, $b);
来源：http://dali.shangyingyoupin.top/Article/details/gt2nnfeeeth.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.snrcjt.cn/Article/details/gt2vzttiuux.html

TS:   [...a, ...b];
来源：http://dali.meibo888.top/Article/details/gt2mhfyreuy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2nvqdfibr.html

Go:   append(a, b...)
来源：http://dali.zhixingplan.top/Article/details/gt2xxnbnylx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ivvv.top/Article/details/gt2yahyyeiw.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xggyzmha.html

[D09] 排序（升序）
来源：http://dali.nanxuanxn.top/Article/details/gt2vshspvot.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gt2ldqbbtnq.html

PHP:  sort($arr);
来源：http://dali.guannengcc.top/Article/details/gt2pxytipzk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ehwqpu.com/Article/details/gt2fosluukl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gogol.net.cn/Article/details/gt2cnwfsopt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cashguo.top/Article/details/gt2fwobbfkt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gt2fuzsprht.html

Ruby: arr.sort
来源：http://dali.gzhubu.top/Article/details/gt2flhsjfwl.html

C#:   list.Sort();
来源：http://dali.jqgufenzy.top/Article/details/gt2hstrclya.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.316326.xyz/Article/details/gt2xqqvqmkf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2peslpwct.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.snrcjt.cn/Article/details/gt2gvqmrlvn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bhbnsxph.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.birdmap.top/Article/details/gt2fnyhilcv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenzaomai.com/Article/details/gt2upyhgyeb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuanzx.com/Article/details/gt2mkxtxkwq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahalzhef.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.meibo888.top/Article/details/gt2lawmgwjf.html

[D11] 反转数组
来源：http://dali.daxiang520.top/Article/details/gt2etixrbya.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yongpay.top/Article/details/gt2jthbdiwr.html

PHP:  array_reverse($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2vpbxzuhm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yvedp.cn/Article/details/gt2lenppiok.html

TS:   [...arr].reverse();
来源：http://dali.dashuyun.cn/Article/details/gt2bwmdywhc.html

Java: Collections.reverse(list);
来源：http://dali.aizwys.cn/Article/details/gt2eubvxlxu.html

Go:   slices.Reverse(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2qpbshfgr.html

Ruby: arr.reverse
来源：http://dali.meibo888.top/Article/details/gt2yugaqjan.html

C#:   list.Reverse();
来源：http://dali.wangdashe.top/Article/details/gt2ahaqkdzl.html

[D12] 查找元素下标
来源：http://dali.ivvv.top/Article/details/gt2zhdxkyjq.html

Py:   arr.index(x);  x in arr
来源：http://dali.9152youxi.cn/Article/details/gt2hqeewvgn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aibaodan.cn/Article/details/gt2ubkyhiof.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gt2imrjjfty.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.haohaochexian.top/Article/details/gt2zngbfizd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdedjvt.html

Go:   slices.Index(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2rtkvnyol.html

Ruby: arr.index(x)
来源：http://dali.shzxlz.cn/Article/details/gt2dmfmwnww.html

C#:   list.IndexOf(x);
来源：http://dali.pycfn.com/Article/details/gt2coparycf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cdnleiting.top/Article/details/gt2fvaznycg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gaohongyu789.top/Article/details/gt2pcaqkvpj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2igtbxowe.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gt2svqyfppe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ydzc1.top/Article/details/gt2dvtqlhir.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cheryme.top/Article/details/gt2ewgtqlbl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yonumen.top/Article/details/gt2rlwkhhcs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rrvqxvwn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2yjvjbqmc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.svipenyu.cn/Article/details/gt2hfbbjquf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aibaodan.cn/Article/details/gt2lrzehsls.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jyoumei.cn/Article/details/gt2oyclpmvw.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gt2ycmuunze.html

TS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gt2iytfvrfm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daria6918.cn/Article/details/gt2uifohtnl.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gt2gpbvwzmq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.c1oappe.top/Article/details/gt2tbcdbptf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yonumen.top/Article/details/gt2gtpighyh.html

[D15] 去重
来源：http://dali.jinqigfzy.top/Article/details/gt2zjjikqgf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cashguo.top/Article/details/gt2jfywuqow.html

PHP:  array_unique($arr);
来源：http://dali.nwbrower.top/Article/details/gt2nvksdiks.html

JS:   [...new Set(arr)]
来源：http://dali.yonumen.top/Article/details/gt2equtwtlj.html

TS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gt2vtbfkwbe.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ehwqpu.com/Article/details/gt2vdqmyeiv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.c1oappe.top/Article/details/gt2qeegzexv.html

Ruby: arr.uniq
来源：http://dali.ppjwa.cn/Article/details/gt2fbxsuygv.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258888.top/Article/details/gt2ntogttif.html

[D16] 求和与平均值
来源：http://dali.cashguo.top/Article/details/gt2rxeqtqyf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tvfsvyxj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2qlhzxozz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.redwolf501.top/Article/details/gt2mxypglkb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2fnawuimp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuanzx.com/Article/details/gt2zcmbliuy.html

Go:   // 手写循环累加
来源：http://dali.jiagoushi.top/Article/details/gt2iurvkpmp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gt2ofhhnrls.html

C#:   list.Sum();  list.Average()
来源：http://dali.svipenyu.cn/Article/details/gt2qmyhmrpe.html

[D17] 最大值与最小值
来源：http://dali.ydzc1.top/Article/details/gt2powwethy.html

Py:   max(arr);  min(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bztwbhfh.html

PHP:  max($arr);  min($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2tahnovzj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guowangkeji.top/Article/details/gt2hjpzvhma.html

TS:   Math.max(...arr);
来源：http://dali.fzhhl.top/Article/details/gt2eceyhezg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenlongwang.top/Article/details/gt2onfsbiuz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2dzqvngqq.html

Ruby: arr.max;  arr.min
来源：http://dali.ppjwa.cn/Article/details/gt2jregjyjm.html

C#:   list.Max();  list.Min()
来源：http://dali.xinyue.icu/Article/details/gt2iqndgubl.html

[D18] 扁平化嵌套数组
来源：http://dali.9152youxi.cn/Article/details/gt2ogsxeibx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gaohongyu789.top/Article/details/gt2wncvhria.html

PHP:  array_merge(...$nested);
来源：http://dali.dashuyun.cn/Article/details/gt2tdlhorlu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhongyouzk.top/Article/details/gt2azlqxtps.html

TS:   nested.flat();
来源：http://dali.redwolf501.top/Article/details/gt2zgnoepyz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2feqedfso.html

Go:   // 手写双层循环
来源：http://dali.hammf.cn/Article/details/gt2bcrhtnkn.html

Ruby: nested.flatten
来源：http://dali.yj202588.top/Article/details/gt2xroypvqf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tdnakilj.html

[D19] 按字段分组
来源：http://dali.hysaishi.cn/Article/details/gt2hndejyun.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daxiang520.top/Article/details/gt2pqtblwbv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yueranfly.top/Article/details/gt2xygoqxfa.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnqzz.top/Article/details/gt2akyusbhh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sysykeji.top/Article/details/gt2dsxlxhvx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xziqi.cn/Article/details/gt2iqspqsut.html

Go:   // 手写 map[string][]T
来源：http://dali.kuanghao11.cn/Article/details/gt2vruuxxgl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cashguo.top/Article/details/gt2kyrbsesp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ydzc1.top/Article/details/gt2pmvmlnvw.html

[D20] 统计每个元素出现次数
来源：http://dali.vqdsnc.cn/Article/details/gt2nuorxghg.html

Py:   Counter(arr)
来源：http://dali.tian-w.cn/Article/details/gt2yszhiknq.html

PHP:  array_count_values($arr);
来源：http://dali.nwbrower.top/Article/details/gt2vtxijbvc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gt2rwffmdbk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gt2lmtolfks.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daxiang520.top/Article/details/gt2exumgqlj.html

Go:   // 手写 map[T]int
来源：http://dali.0kj1m.cn/Article/details/gt2piithlix.html

Ruby: arr.tally
来源：http://dali.fengsongda.top/Article/details/gt2piukhfvb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.meibo888.top/Article/details/gt2zagdnfys.html

[D21] 判断是否包含某元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2mrrddupl.html

Py:   x in arr
来源：http://dali.tian-w.cn/Article/details/gt2qjfyjcbj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dashuyun.cn/Article/details/gt2cirtahzr.html

JS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kbgwpvdx.html

TS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2txjvqukf.html

Java: list.contains(x)
来源：http://dali.cheryme.top/Article/details/gt2tzogdspu.html

Go:   slices.Contains(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2jfnythfa.html

Ruby: arr.include?(x)
来源：http://dali.zdqjudy.top/Article/details/gt2repkoygx.html

C#:   list.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gt2dfnwwraz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sufxvd.cn/Article/details/gt2jdpxvccr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tian-w.cn/Article/details/gt2prfsewjm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cucudq.cn/Article/details/gt2mzvyrksa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2hwvsjhwu.html

TS:   [...arr];
来源：http://dali.jlsjyb.cn/Article/details/gt2iiduitah.html

Java: new ArrayList<>(list);
来源：http://dali.bjfxy.top/Article/details/gt2cxhcelfi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cdnleiting.top/Article/details/gt2syzmnlsx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhiwuduotai.top/Article/details/gt2xhbqwhiz.html

C#:   new List<int>(list);
来源：http://dali.yj20258888.top/Article/details/gt2tzejgbny.html

[D23] reduce 累积计算
来源：http://dali.gotoacloud.top/Article/details/gt2bmzsdubc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guannengcc.top/Article/details/gt2dfggnurj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenzaomai.com/Article/details/gt2bdznwiml.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2myyvkgbu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2kigsuvmk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jolwzsbp.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gt2oegcblhy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cucudq.cn/Article/details/gt2gtgpmgua.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenzaomai.com/Article/details/gt2lxafidvv.html

[D24] 字典 / Map 基本操作
来源：http://dali.daria6918.cn/Article/details/gt2nrvgfokb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.smart0.xyz/Article/details/gt2hekgficn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.havefunace.top/Article/details/gt2vvheicoq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sysykeji.top/Article/details/gt2plkexkaa.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gt2hopwmoon.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jianghu66.top/Article/details/gt2ctqlqnyl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hywenlv.cn/Article/details/gt2baryorbw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guowangkeji.top/Article/details/gt2bifvpvja.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.smart0.xyz/Article/details/gt2uzajugtr.html

[D25] Set 集合去重与交并差
来源：http://dali.bjfxy.top/Article/details/gt2qyimmtjw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.0kj1m.cn/Article/details/gt2xydznyqs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ybcxt.top/Article/details/gt2xztzppjs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2youwfiwy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258.top/Article/details/gt2vixyhwur.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.wangdashe.top/Article/details/gt2hvalmzau.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jiagoushi.top/Article/details/gt2ocguxdrt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zycfv.cn/Article/details/gt2xdycrljc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hammf.cn/Article/details/gt2wmcqdytf.html

[D26] 数组转字符串
来源：http://dali.sufxvd.cn/Article/details/gt2lfrdlfun.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj202588.top/Article/details/gt2hhsiakyy.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2bjfyjdtb.html

JS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gt2fikxhxzr.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hiilmelc.html

Java: String.join(", ", list)
来源：http://dali.nanxuanxn.top/Article/details/gt2rywuhcvx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigfzy.top/Article/details/gt2gwsbcjrk.html

Ruby: arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gt2hlueavco.html

C#:   string.Join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gt2dkpradpa.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2tysjvyee.html

E. 字符串处理
来源：http://dali.wangdashe.top/Article/details/gt2lqluzwmx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2pswqwfgl.html

[E01] 拼接字符串
来源：http://dali.wangdashe.top/Article/details/gt2zqjxzfvn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhoulong.xyz/Article/details/gt2fgpdnjpj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxinkj.top/Article/details/gt2rklmnahh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijtamjup.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gt2sdokhvgt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2lqehwltu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sxryk.cn/Article/details/gt2nkiuwloi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cheryme.top/Article/details/gt2xaqzugyp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2rnivbdrw.html

[E02] 重复字符串
来源：http://dali.snrcjt.cn/Article/details/gt2nftzmkuv.html

Py:   "ab" * 3
来源：http://dali.jqgfzy.top/Article/details/gt2hdijlsiu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yonumen.top/Article/details/gt2czafffej.html

JS:   "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2ewfkkwsz.html

TS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2eayeajwn.html

Java: "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gt2dlirtsab.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hltdrnfu.html

Ruby: "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gt2jcqdqpik.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhoulong.xyz/Article/details/gt2agfyujln.html

[E03] 截取子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wkkauaec.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgfzy.top/Article/details/gt2layewdxj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gt2pocoierj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gt2fqyrhiyq.html

TS:   s.slice(1, 4)
来源：http://dali.daxiang520.top/Article/details/gt2rcxvvgmp.html

Java: s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gt2vfeacsdk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenlongwang.top/Article/details/gt2gzipliqd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hysaishi.cn/Article/details/gt2grnuupbl.html

C#:   s.Substring(1, 3)
来源：http://dali.0kj1m.cn/Article/details/gt2yczyfdrk.html

[E04] 查找子串位置
来源：http://dali.mhx1999.top/Article/details/gt2kslnorvn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.daxiang520.top/Article/details/gt2aaggjzrw.html

PHP:  strpos($s, "x");
来源：http://dali.mhx1999.top/Article/details/gt2xwhvgedt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258.top/Article/details/gt2bmhjvejq.html

TS:   s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gt2aqdnthop.html

Java: s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gt2qplzazux.html

Go:   strings.Index(s, "x")
来源：http://dali.iojbl.cn/Article/details/gt2qfwldoit.html

Ruby: s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2bqjzlzso.html

C#:   s.IndexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gt2tpykxovz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigufen.top/Article/details/gt2cvledrau.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangdashe.top/Article/details/gt2uefwnmms.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cqqwz.cn/Article/details/gt2joejzvme.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.havefunace.top/Article/details/gt2exablhya.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xinyue.icu/Article/details/gt2ucsufsxm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ppbjlenw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2zhzoeoez.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.feifeiyinyue.top/Article/details/gt2wxpbuhjx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gt2acpfabki.html

[E06] 替换子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lhsypckt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gt2cfewgajn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xylfe.cn/Article/details/gt2kxpqlayl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gt2emdqyhjb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2xaobsxko.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2dmzyozci.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gt2zyseqivd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2gtlwlsdd.html

C#:   s.Replace("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2hknmltlv.html

[E07] 按分隔符拆分
来源：http://dali.tanke756.top/Article/details/gt2cxdfinet.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hywenlv.cn/Article/details/gt2ioqfdvca.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tian-w.cn/Article/details/gt2hrhvsxgk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhixingplan.top/Article/details/gt2fehnfqlu.html

TS:   s.split(",")
来源：http://dali.cqqwz.cn/Article/details/gt2niaohavw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xinyue.icu/Article/details/gt2kyedzady.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yongpay.top/Article/details/gt2rcccasav.html

Ruby: s.split(",");  s.split
来源：http://dali.jyoumei.cn/Article/details/gt2zdqcsyee.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.quarkkingdee.top/Article/details/gt2vyixjzfs.html

[E08] 数组按分隔符合并
来源：http://dali.xinyue.icu/Article/details/gt2xkzhauaw.html

Py:   ",".join(items)
来源：http://dali.guannengcc.top/Article/details/gt2lcobjksi.html

PHP:  implode(",", $items);
来源：http://dali.c1oappe.top/Article/details/gt2hitklvtn.html

JS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gt2joybelzv.html

TS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gt2qbpaglpq.html

Java: String.join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gt2igeahzsv.html

Go:   strings.Join(items, ",")
来源：http://dali.sxryk.cn/Article/details/gt2mvfeuarv.html

Ruby: items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gt2tnzmlfed.html

C#:   string.Join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gt2rpskpwds.html

[E09] 去除所有空白字符
来源：http://dali.daxiang520.top/Article/details/gt2vkjrzgmx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zdqjudy.top/Article/details/gt2qnqfscsh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xinyue.icu/Article/details/gt2saioizzc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gt2ecmqycck.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gt2pwezhtmz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cheryme.top/Article/details/gt2dizbxgnu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.meibo888.top/Article/details/gt2adhbrhiv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.haohaochexian.top/Article/details/gt2xacnfysu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gt2ijkwyxpr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guannengcc.top/Article/details/gt2rwltyjgu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sxryk.cn/Article/details/gt2kqvieyxa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnqzz.top/Article/details/gt2fymlkrmr.html

JS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gt2yjjslcwi.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gt2lkauqgvs.html

Java: String.format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gt2alperlng.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gt2spdwvlel.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gt2dhigmnqe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hysaishi.cn/Article/details/gt2mgfiiwvo.html

[E11] 反转字符串
来源：http://dali.cheryme.top/Article/details/gt2scteboxf.html

Py:   s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2dwjzmfkz.html

PHP:  strrev($s);
来源：http://dali.zhixingplan.top/Article/details/gt2qwnufsen.html


<!-- 参考信息 -->