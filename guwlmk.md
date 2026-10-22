代发 wailian999

D. 数组 / 列表 / 集合
来源：http://dali.0kj1m.cn/Article/details/gtwwyhboqv.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtcqyvtmxk.html

[D01] 创建数组 / 列表
来源：http://dali.cucudq.cn/Article/details/gtjvrympoa.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.guowangkeji.top/Article/details/gtkhztewny.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ybcxt.top/Article/details/gtqutcyhva.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shzxlz.cn/Article/details/gtdqoxxmpg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cqqwz.cn/Article/details/gtqxqyibet.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zycfv.cn/Article/details/gtzebtzvzp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tanke756.top/Article/details/gtytrhzcus.html

Ruby: arr = [1, 2, 3]
来源：http://dali.wangshuangyany.cn/Article/details/gtnmrqwgbt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigufen.top/Article/details/gtjzeqrynv.html

[D02] 追加元素到末尾
来源：http://dali.xuanzx.com/Article/details/gtbuvkbkqm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cqqwz.cn/Article/details/gtyjublmya.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cheryme.top/Article/details/gthlypaxov.html

JS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gtjxukpepj.html

TS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gttgsvhlcd.html

Java: list.add(4);
来源：http://dali.ivvv.top/Article/details/gtfhtblpii.html

Go:   arr = append(arr, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtylrfcfqp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gaohongyu789.top/Article/details/gtmbfsgqli.html

C#:   list.Add(4);
来源：http://dali.chenlongwang.top/Article/details/gtgkpeivxe.html

[D03] 在指定位置插入元素
来源：http://dali.cqqwz.cn/Article/details/gtisrwqhfs.html

Py:   arr.insert(0, 0)
来源：http://dali.jianghu66.top/Article/details/gtqqbivkrt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sweek.top/Article/details/gtebgzoihl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangdashe.top/Article/details/gtikdblmni.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.aibaodan.cn/Article/details/gttxeuizlx.html

Java: list.add(0, 0);
来源：http://dali.sysykeji.top/Article/details/gtjbqdorhu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yonumen.top/Article/details/gtrjrhypoy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xinyue.icu/Article/details/gthowykjkf.html

C#:   list.Insert(0, 0);
来源：http://dali.yuxming.cn/Article/details/gtcchfpiym.html

[D04] 删除元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhtdjvfc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fzhhl.top/Article/details/gthrzmzfvn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hnqzz.top/Article/details/gtnsdbdmrp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guannengcc.top/Article/details/gtoklbqxck.html

TS:   arr.splice(0, 1);
来源：http://dali.shuidangran.top/Article/details/gtfbxeyfad.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgfzy.top/Article/details/gtrhydlrli.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nwbrower.top/Article/details/gttjmyfrxb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hysaishi.cn/Article/details/gtuwrcoutc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hywenlv.cn/Article/details/gtqnfimxuf.html

[D05] 访问与修改元素
来源：http://dali.guowangkeji.top/Article/details/gtyjwrnagl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfyhxzsv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtbaybhegm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cheryme.top/Article/details/gtvcscboat.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pengpengdd.cyou/Article/details/gtkmvooydn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sxryk.cn/Article/details/gtavadbiqw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gtbaqmczae.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gtvffteykt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtsmgocfgm.html

[D06] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gtmfkcwqzy.html

Py:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gtgkysxasg.html

PHP:  count($arr);
来源：http://dali.yvedp.cn/Article/details/gtfmlomhmp.html

JS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugzvbiqr.html

TS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gtaxdihxsc.html

Java: list.size();
来源：http://dali.yongpay.top/Article/details/gtvizstnjk.html

Go:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtimabzhym.html

Ruby: arr.length; arr.size
来源：http://dali.chenlongwang.top/Article/details/gtpqusuewi.html

C#:   list.Count;
来源：http://dali.aibaodan.cn/Article/details/gtdwruyxbp.html

[D07] 切片 / 取子数组
来源：http://dali.svipenyu.cn/Article/details/gtmiioqnex.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.c1oappe.top/Article/details/gtixkuyply.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gttebueohn.html

JS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtxwbibxqr.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtkjgjjtay.html

Java: list.subList(1, 4);
来源：http://dali.havefunace.top/Article/details/gtupuljyzt.html

Go:   arr[1:4]
来源：http://dali.yj20258.top/Article/details/gtcedlyays.html

Ruby: arr[1, 3]
来源：http://dali.sufxvd.cn/Article/details/gtxrzejfpt.html

C#:   list.GetRange(1, 3);
来源：http://dali.cdnleiting.top/Article/details/gtehzwqiqv.html

[D08] 合并两个数组
来源：http://dali.jyoumei.cn/Article/details/gtoiixnglf.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnxiangtu.top/Article/details/gtphmkgetx.html

PHP:  array_merge($a, $b);
来源：http://dali.bjfxy.top/Article/details/gtwduephnm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daxiang520.top/Article/details/gteioggkcy.html

TS:   [...a, ...b];
来源：http://dali.zhoulong.xyz/Article/details/gtxnvrunpr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hysaishi.cn/Article/details/gtahrgxjqq.html

Go:   append(a, b...)
来源：http://dali.gotoacloud.top/Article/details/gtbdiequxc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hnqzz.top/Article/details/gtumnuidbx.html

C#:   a.Concat(b).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtmlstksqu.html

[D09] 排序（升序）
来源：http://dali.guannengcc.top/Article/details/gtdtsgramp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gtswcyysoh.html

PHP:  sort($arr);
来源：http://dali.ybcxt.top/Article/details/gtsuqounjd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gogol.net.cn/Article/details/gtughmdima.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guannengcc.top/Article/details/gtpeqivpdq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.wangshuangyany.cn/Article/details/gtaojhrhzv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gtbbpbxytu.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gtdzlsepfl.html

C#:   list.Sort();
来源：http://dali.yj20258.top/Article/details/gtizpigwsk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sufxvd.cn/Article/details/gtbvmxuqjg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.redwolf501.top/Article/details/gtvekzqssr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cashguo.top/Article/details/gtplmchbov.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gtmtsbirbv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gtmhweyxvk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fzhhl.top/Article/details/gtfksjgbld.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuanzhike.top/Article/details/gtmrhxemou.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgfzy.top/Article/details/gttxzctglm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxuanxn.top/Article/details/gtusaestgu.html

[D11] 反转数组
来源：http://dali.wangshuangyany.cn/Article/details/gtbdarygzi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hysaishi.cn/Article/details/gtugtdjyml.html

PHP:  array_reverse($arr);
来源：http://dali.chenlongwang.top/Article/details/gtfoonuizv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hfpthk.cn/Article/details/gtaalmkwcf.html

TS:   [...arr].reverse();
来源：http://dali.sxryk.cn/Article/details/gtivqaeipg.html

Java: Collections.reverse(list);
来源：http://dali.bjfxy.top/Article/details/gtepucdzjl.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtutaaxkhl.html

Ruby: arr.reverse
来源：http://dali.andypj.xyz/Article/details/gthheexflb.html

C#:   list.Reverse();
来源：http://dali.redwolf501.top/Article/details/gtjdzuxoht.html

[D12] 查找元素下标
来源：http://dali.xylfe.cn/Article/details/gtkhkszklh.html

Py:   arr.index(x);  x in arr
来源：http://dali.sysykeji.top/Article/details/gtrmaiyoge.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yueranfly.top/Article/details/gtpqjgtdqr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gtjczjwjyk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtwrnkvgsw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gaohongyu789.top/Article/details/gtsifxoonu.html

Go:   slices.Index(arr, x)
来源：http://dali.sxryk.cn/Article/details/gttxgnxmhc.html

Ruby: arr.index(x)
来源：http://dali.aibaodan.cn/Article/details/gtzqohmgjw.html

C#:   list.IndexOf(x);
来源：http://dali.yuxming.cn/Article/details/gteombxcit.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jqgfzy.top/Article/details/gtmchtpdcz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sxryk.cn/Article/details/gtqvzijulk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtvwtftjtq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gtcvtipuzr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtuxfcadxl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sweek.top/Article/details/gtftcetmrk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258.top/Article/details/gtnzehqgvv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhiwuduotai.top/Article/details/gtyrvanpqs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.snrcjt.cn/Article/details/gthewnvktq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhengqikj.top/Article/details/gtcjsxyizf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtsvicgvls.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtdbqvjkmk.html

JS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gtteugecjy.html

TS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtbrbzszma.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hammf.cn/Article/details/gtikfcbnii.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gtfmsvikns.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtwykcufjc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtouaroxcl.html

[D15] 去重
来源：http://dali.sweek.top/Article/details/gtxnqiylrs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigufen.top/Article/details/gtgcofwmie.html

PHP:  array_unique($arr);
来源：http://dali.sweek.top/Article/details/gtreccafge.html

JS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtrqrmrkwb.html

TS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtnwpdldud.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sxryk.cn/Article/details/gtnhwfddsu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.feifeiyinyue.top/Article/details/gtsivngazz.html

Ruby: arr.uniq
来源：http://dali.316326.xyz/Article/details/gtigrwxccd.html

C#:   list.Distinct().ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttjibqgb.html

[D16] 求和与平均值
来源：http://dali.sweek.top/Article/details/gtgdvyroif.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sysykeji.top/Article/details/gtcnhycojx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nwbrower.top/Article/details/gtjuggsljg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtixtgxokk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtokljafft.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gthsqvolmw.html

Go:   // 手写循环累加
来源：http://dali.jlsjyb.cn/Article/details/gtgzywfpfk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yangfankeji.com/Article/details/gtmpsbcdei.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuanzhike.top/Article/details/gttknqguvw.html

[D17] 最大值与最小值
来源：http://dali.shangyingyoupin.top/Article/details/gtdnaoeorl.html

Py:   max(arr);  min(arr)
来源：http://dali.hywenlv.cn/Article/details/gttjzwneaq.html

PHP:  max($arr);  min($arr);
来源：http://dali.9152youxi.cn/Article/details/gtafcqiixu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gtqnvunmjm.html

TS:   Math.max(...arr);
来源：http://dali.ehwqpu.com/Article/details/gtlzzbzxto.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cucudq.cn/Article/details/gttwofzyov.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shuidangran.top/Article/details/gtvdgdvksy.html

Ruby: arr.max;  arr.min
来源：http://dali.yueranfly.top/Article/details/gtwxpdcspt.html

C#:   list.Max();  list.Min()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphhkbqbm.html

[D18] 扁平化嵌套数组
来源：http://dali.yj202588.top/Article/details/gtabbyesne.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jianghu66.top/Article/details/gtnpuhkeyj.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigfzy.top/Article/details/gthagqzocx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zycfv.cn/Article/details/gtuqdjxzkk.html

TS:   nested.flat();
来源：http://dali.yj202588.top/Article/details/gttjdjaovc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yvedp.cn/Article/details/gtbfesgkwe.html

Go:   // 手写双层循环
来源：http://dali.jqgfzy.top/Article/details/gtdwipptyr.html

Ruby: nested.flatten
来源：http://dali.cqqwz.cn/Article/details/gtifrrppww.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtvbkyfjwc.html

[D19] 按字段分组
来源：http://dali.nanxinkj.top/Article/details/gteztgzgcl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.haohaochexian.top/Article/details/gtpvnfnkzw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guowangkeji.top/Article/details/gtijjglzzp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258.top/Article/details/gtokanubok.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gtfsjapfdk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.316326.xyz/Article/details/gtzehewmeh.html

Go:   // 手写 map[string][]T
来源：http://dali.ivvv.top/Article/details/gtpkkmpyuf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cdnleiting.top/Article/details/gtiwexjmqv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxuanxn.top/Article/details/gtzddmziqk.html

[D20] 统计每个元素出现次数
来源：http://dali.gzhubu.top/Article/details/gtphndbctw.html

Py:   Counter(arr)
来源：http://dali.yuanzhike.top/Article/details/gtihcxdfgl.html

PHP:  array_count_values($arr);
来源：http://dali.c1oappe.top/Article/details/gtgaqclmxz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gtympfktlw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gtbavhunde.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnxiangtu.top/Article/details/gtewtzbxoi.html

Go:   // 手写 map[T]int
来源：http://dali.yanxiufei.cn/Article/details/gtxefskmvo.html

Ruby: arr.tally
来源：http://dali.0kj1m.cn/Article/details/gtvcrwlkfg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hnxiangtu.top/Article/details/gtkmsorezy.html

[D21] 判断是否包含某元素
来源：http://dali.jiagoushi.top/Article/details/gtaviloscr.html

Py:   x in arr
来源：http://dali.iojbl.cn/Article/details/gticojmupq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xylfe.cn/Article/details/gteujtyaok.html

JS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gtcvhzbwmm.html

TS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gtrqjeyytk.html

Java: list.contains(x)
来源：http://dali.316326.xyz/Article/details/gtrfnkkshn.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtkpumiezh.html

Ruby: arr.include?(x)
来源：http://dali.wangdashe.top/Article/details/gtldppfupv.html

C#:   list.Contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtjkksahql.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shangyingyoupin.top/Article/details/gtkvkzkjuc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhixingplan.top/Article/details/gtwkjzoqsj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.vqdsnc.cn/Article/details/gtyjdzpakt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.daxiang520.top/Article/details/gtclfbondc.html

TS:   [...arr];
来源：http://dali.yueranfly.top/Article/details/gtaylhypgl.html

Java: new ArrayList<>(list);
来源：http://dali.svipenyu.cn/Article/details/gtrngkwaxn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.kuanghao11.cn/Article/details/gtppswcxym.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnxiangtu.top/Article/details/gtsordakep.html

C#:   new List<int>(list);
来源：http://dali.hnxiangtu.top/Article/details/gtckcjrgqj.html

[D23] reduce 累积计算
来源：http://dali.iojbl.cn/Article/details/gthdmbcyjz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenzaomai.com/Article/details/gtthcpiapa.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nwbrower.top/Article/details/gttjsglhaz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gtuemsxmlu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtmnxaclke.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gzhubu.top/Article/details/gtsxdhflot.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gtnbraklen.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tanke756.top/Article/details/gtvtvsdyir.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.wangdashe.top/Article/details/gtoiryajiz.html

[D24] 字典 / Map 基本操作
来源：http://dali.daxiang520.top/Article/details/gtqimdatvw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sweek.top/Article/details/gthizqytqc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hnxiangtu.top/Article/details/gtsggtaebq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dianchejie.cn/Article/details/gthphuybst.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtziudcmuj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvzmpyaq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gogol.net.cn/Article/details/gtdnjbjnlk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aibaodan.cn/Article/details/gtjytibxra.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ybcxt.top/Article/details/gtfknwipya.html

[D25] Set 集合去重与交并差
来源：http://dali.ybcxt.top/Article/details/gtzszvhdmg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gotoacloud.top/Article/details/gtheecofpd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shzxlz.cn/Article/details/gtzotxwawv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.havefunace.top/Article/details/gtekcohfgy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tanke756.top/Article/details/gtgyrxxchs.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gtxnpwnmml.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhengqikj.top/Article/details/gtghejgipm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.iojbl.cn/Article/details/gtucqvhqgd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhixingplan.top/Article/details/gtbsvdsjqo.html

[D26] 数组转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtrwxtrdlm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxinkj.top/Article/details/gtvujzmbxn.html

PHP:  implode(", ", $arr);
来源：http://dali.shzxlz.cn/Article/details/gtfkvjurhb.html

JS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtzrtibknf.html

TS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gtftmmfhfz.html

Java: String.join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gtczredgpc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.andypj.xyz/Article/details/gtmgzevpdn.html

Ruby: arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtuknwujbb.html

C#:   string.Join(", ", list)
来源：http://dali.c1oappe.top/Article/details/gtsmjcqqwt.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtigzsffqb.html

E. 字符串处理
来源：http://dali.xuetiantiany.cn/Article/details/gtkihzhtnt.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtxmoyusss.html

[E01] 拼接字符串
来源：http://dali.cheryme.top/Article/details/gtkiiftxbu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigufen.top/Article/details/gtgfvdqgvu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guannengcc.top/Article/details/gtxednsqdh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gtcyeutbbm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gtkkytqjvj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dianchejie.cn/Article/details/gtowirgzhg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxuanxn.top/Article/details/gtrvjukezq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dianchejie.cn/Article/details/gtyprclcft.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtmnamxusg.html

[E02] 重复字符串
来源：http://dali.9152youxi.cn/Article/details/gtfulhqprc.html

Py:   "ab" * 3
来源：http://dali.andypj.xyz/Article/details/gtogeffkvk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtziehsgzr.html

JS:   "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtrbcliipd.html

TS:   "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gtdacnqlzy.html

Java: "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtkjlvnwnj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yvedp.cn/Article/details/gthzklzryk.html

Ruby: "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gtdiqsfhkx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sufxvd.cn/Article/details/gtsekmtrdw.html

[E03] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gtvhhakble.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nwbrower.top/Article/details/gtplwivtuw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmceotygs.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gtlfaizadm.html

TS:   s.slice(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gtswluykqw.html

Java: s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gteonvshej.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yueranfly.top/Article/details/gtyqvbxxbq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuanzhike.top/Article/details/gtdnommoxc.html

C#:   s.Substring(1, 3)
来源：http://dali.yuxming.cn/Article/details/gtcpwrrvth.html

[E04] 查找子串位置
来源：http://dali.tanke756.top/Article/details/gtytrkmoom.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtsdymtdkp.html

PHP:  strpos($s, "x");
来源：http://dali.birdmap.top/Article/details/gtrqlxzgtf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yueranfly.top/Article/details/gtgqvriadh.html

TS:   s.indexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gtuqohgxym.html

Java: s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtqtonkaci.html

Go:   strings.Index(s, "x")
来源：http://dali.yj202588.top/Article/details/gtnptlhkdn.html

Ruby: s.index("x")
来源：http://dali.yangfankeji.com/Article/details/gtfngocrja.html

C#:   s.IndexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gtlooiamhx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhengqikj.top/Article/details/gtaqkqehwl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.andypj.xyz/Article/details/gtzuvbughj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nwbrower.top/Article/details/gtsvuguwfd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtwwdzdqrf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yongpay.top/Article/details/gtjrfivnwu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gtruonoiie.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.pycfn.com/Article/details/gtydzsmotx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yanxiufei.cn/Article/details/gtfgehwzxl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtoljimumw.html

[E06] 替换子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswnofrjg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gtyqbirewd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj202588.top/Article/details/gtkmwevvwo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtwbtxgyjk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtfdkzqwal.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteurdrbsh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gthfolricn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamhqzgqd.html

C#:   s.Replace("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gttocxxpxp.html

[E07] 按分隔符拆分
来源：http://dali.cucudq.cn/Article/details/gtgqimtwuj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shzxlz.cn/Article/details/gthzwbayvv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gttaolmisb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenjidiqi.icu/Article/details/gtcuxikucg.html

TS:   s.split(",")
来源：http://dali.smart0.xyz/Article/details/gtepicvcsl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ehwqpu.com/Article/details/gtvwncdfnw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gaohongyu789.top/Article/details/gtoecbybxx.html


<!-- 参考信息 -->