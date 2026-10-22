代发 wailian999

PHP:  // 无重载
来源：http://dali.jinqigfzy.top/Article/details/gt2araxbmav.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gogol.net.cn/Article/details/gt2gsqnhffk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhongyouzk.top/Article/details/gt2viiudfxn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ppjwa.cn/Article/details/gt2hsekqadz.html

Go:   // 无重载：用不同函数名
来源：http://dali.bjfxy.top/Article/details/gt2nmhydylx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fzhhl.top/Article/details/gt2mfjxbtqk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.316326.xyz/Article/details/gt2refrijgu.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2aumidszv.html

D. 数组 / 列表 / 集合
来源：http://dali.jlsjyb.cn/Article/details/gt2uudxnvhf.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bnodhihs.html

[D01] 创建数组 / 列表
来源：http://dali.mhx1999.top/Article/details/gt2uwiadspq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxbgmcos.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.316326.xyz/Article/details/gt2tyxpupeg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.iojbl.cn/Article/details/gt2rkmhrvep.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.dashuyun.cn/Article/details/gt2ulkmdanp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nanxuanxn.top/Article/details/gt2eoiwtgfn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ehwqpu.com/Article/details/gt2vbwlcnxn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zlekcubu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cashguo.top/Article/details/gt2pubyvpok.html

[D02] 追加元素到末尾
来源：http://dali.jiagoushi.top/Article/details/gt2fhcshqan.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhoulong.xyz/Article/details/gt2fawqynbf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jianghu66.top/Article/details/gt2bvlcfjmj.html

JS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gt2zplxqarm.html

TS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gt2uluujozw.html

Java: list.add(4);
来源：http://dali.cdnleiting.top/Article/details/gt2vddptxhm.html

Go:   arr = append(arr, 4)
来源：http://dali.sysykeji.top/Article/details/gt2bixfmilb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nanxuanxn.top/Article/details/gt2dviqpdud.html

C#:   list.Add(4);
来源：http://dali.hammf.cn/Article/details/gt2ursmqjnp.html

[D03] 在指定位置插入元素
来源：http://dali.c1oappe.top/Article/details/gt2wkambozr.html

Py:   arr.insert(0, 0)
来源：http://dali.yueranfly.top/Article/details/gt2vwkgiojn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jlsjyb.cn/Article/details/gt2idjwwdss.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ydzc1.top/Article/details/gt2knavvyie.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.aibaodan.cn/Article/details/gt2eygvmeot.html

Java: list.add(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gt2tfjnywmx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.vqdsnc.cn/Article/details/gt2ktdyghlv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gogol.net.cn/Article/details/gt2dkuceydv.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gt2asksumuq.html

[D04] 删除元素
来源：http://dali.gogol.net.cn/Article/details/gt2qpvmfway.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.bjfxy.top/Article/details/gt2zmvmpmoe.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xylfe.cn/Article/details/gt2syuhongc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhiwuduotai.top/Article/details/gt2dxzpozux.html

TS:   arr.splice(0, 1);
来源：http://dali.tianlin.xyz/Article/details/gt2dlhbyehz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pnvwwwac.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shuidangran.top/Article/details/gt2uauzimvy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvrambm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xinyue.icu/Article/details/gt2hgisvwom.html

[D05] 访问与修改元素
来源：http://dali.birdmap.top/Article/details/gt2sybqmzpt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zdgifvsd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cheryme.top/Article/details/gt2yzdwdovt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gt2ikhxmlgw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jlsjyb.cn/Article/details/gt2tjcaserx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.vqdsnc.cn/Article/details/gt2rnrnimjo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gt2fznbxtkr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gt2jilstybc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gt2kutgxcsi.html

[D06] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gt2dvfpmzte.html

Py:   len(arr)
来源：http://dali.wangdashe.top/Article/details/gt2dpsqqozu.html

PHP:  count($arr);
来源：http://dali.yj20258.top/Article/details/gt2rbmmiavl.html

JS:   arr.length
来源：http://dali.zycfv.cn/Article/details/gt2ubhuggtd.html

TS:   arr.length
来源：http://dali.cashguo.top/Article/details/gt2sqdmfbhv.html

Java: list.size();
来源：http://dali.haohaochexian.top/Article/details/gt2zagwhoje.html

Go:   len(arr)
来源：http://dali.redwolf501.top/Article/details/gt2lxbdrzku.html

Ruby: arr.length; arr.size
来源：http://dali.gaohongyu789.top/Article/details/gt2hvjtgsrq.html

C#:   list.Count;
来源：http://dali.kuanghao11.cn/Article/details/gt2dovizgbb.html

[D07] 切片 / 取子数组
来源：http://dali.dashuyun.cn/Article/details/gt2mtfeptxh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xinyue.icu/Article/details/gt2gownnmzk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2cbqjxccq.html

JS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gt2qjvxwssz.html

TS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gt2syturenr.html

Java: list.subList(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gt2jygsoeig.html

Go:   arr[1:4]
来源：http://dali.yj202588.top/Article/details/gt2bfirpoqj.html

Ruby: arr[1, 3]
来源：http://dali.zhoulong.xyz/Article/details/gt2auweftfp.html

C#:   list.GetRange(1, 3);
来源：http://dali.tian-w.cn/Article/details/gt2xgwskgke.html

[D08] 合并两个数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rvvtcpta.html

Py:   a + b;  a.extend(b)
来源：http://dali.dashuyun.cn/Article/details/gt2vkglhggs.html

PHP:  array_merge($a, $b);
来源：http://dali.daria6918.cn/Article/details/gt2nxoonyfg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.0kj1m.cn/Article/details/gt2tnxjmpdl.html

TS:   [...a, ...b];
来源：http://dali.chenlongwang.top/Article/details/gt2olvqbbje.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2zcntyvvm.html

Go:   append(a, b...)
来源：http://dali.hfpthk.cn/Article/details/gt2xfogkjxh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lhvjbffn.html

C#:   a.Concat(b).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2fmnmzxyu.html

[D09] 排序（升序）
来源：http://dali.daxiang520.top/Article/details/gt2gwkkizvq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gt2jnpyaaof.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqnycuw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fengsongda.top/Article/details/gt2xewthbnw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.0kj1m.cn/Article/details/gt2tuuvgyrj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yangfankeji.com/Article/details/gt2nirylxjs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2snoepjor.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gt2usqhqwzg.html

C#:   list.Sort();
来源：http://dali.iojbl.cn/Article/details/gt2pmnzyblk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenzaomai.com/Article/details/gt2ommwwali.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.316326.xyz/Article/details/gt2kzqfdtqz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.havefunace.top/Article/details/gt2licomjii.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenzaomai.com/Article/details/gt2kkfsdglz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovabnrik.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangdashe.top/Article/details/gt2wclhdjrp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhiwuduotai.top/Article/details/gt2rekwkhvt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.kuanghao11.cn/Article/details/gt2zzzsiiwa.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhongyouzk.top/Article/details/gt2tgtvejyi.html

[D11] 反转数组
来源：http://dali.yongpay.top/Article/details/gt2sqihfkgu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shuidangran.top/Article/details/gt2iztqidvr.html

PHP:  array_reverse($arr);
来源：http://dali.tanke756.top/Article/details/gt2njhvdqks.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gaohongyu789.top/Article/details/gt2pdtfxpqj.html

TS:   [...arr].reverse();
来源：http://dali.cashguo.top/Article/details/gt2ugdutxtz.html

Java: Collections.reverse(list);
来源：http://dali.havefunace.top/Article/details/gt2bsoqhvjb.html

Go:   slices.Reverse(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2alchdbmm.html

Ruby: arr.reverse
来源：http://dali.smart0.xyz/Article/details/gt2lpfkmmwz.html

C#:   list.Reverse();
来源：http://dali.fengsongda.top/Article/details/gt2amkfbguu.html

[D12] 查找元素下标
来源：http://dali.zhixingplan.top/Article/details/gt2jjbkcubn.html

Py:   arr.index(x);  x in arr
来源：http://dali.hammf.cn/Article/details/gt2znuuenzq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.iojbl.cn/Article/details/gt2uzuyfuas.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gt2fxrxusbt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gt2ylsfjhjq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.bjfxy.top/Article/details/gt2caxzcmkg.html

Go:   slices.Index(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qnofhmvl.html

Ruby: arr.index(x)
来源：http://dali.zycfv.cn/Article/details/gt2juuycdfp.html

C#:   list.IndexOf(x);
来源：http://dali.haohaochexian.top/Article/details/gt2acjdnyqd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fzhhl.top/Article/details/gt2gyqpxync.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnqzz.top/Article/details/gt2dqoohuhq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.redwolf501.top/Article/details/gt2uzghpitf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gt2dcmwrfpz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gt2gnibzmpl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jianghu66.top/Article/details/gt2nhzzdner.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yongpay.top/Article/details/gt2quymrgew.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj202588.top/Article/details/gt2gmiakvam.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jianghu66.top/Article/details/gt2jdweoiin.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ydzc1.top/Article/details/gt2syvrtqei.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2bfagzmny.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ivvv.top/Article/details/gt2smmatois.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gt2ckletkcw.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2fyxsewnl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.smart0.xyz/Article/details/gt2ruzljlep.html

Go:   // 手写循环
来源：http://dali.zhengqikj.top/Article/details/gt2thfrhleh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gt2ayvbubnq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.meibo888.top/Article/details/gt2mfqurief.html

[D15] 去重
来源：http://dali.jianghu66.top/Article/details/gt2plidglzx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gt2rtiphmdb.html

PHP:  array_unique($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2pbqsurtv.html

JS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gt2aagorvuh.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gt2qsryeobg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gaohongyu789.top/Article/details/gt2lhxvqjcz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daxiang520.top/Article/details/gt2xbblxjfk.html

Ruby: arr.uniq
来源：http://dali.jinghuilouyu.cn/Article/details/gt2chfjtsie.html

C#:   list.Distinct().ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2bovjargr.html

[D16] 求和与平均值
来源：http://dali.hongshengwenyu.top/Article/details/gt2atuihmjn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guannengcc.top/Article/details/gt2qwouehti.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aizwys.cn/Article/details/gt2tdyadubd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2qnumlrnf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2ukezetoh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guannengcc.top/Article/details/gt2nevnczdz.html

Go:   // 手写循环累加
来源：http://dali.jqgufenzy.top/Article/details/gt2owdjjpbo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhoulong.xyz/Article/details/gt2itymwbyc.html

C#:   list.Sum();  list.Average()
来源：http://dali.svipenyu.cn/Article/details/gt2ufxirygb.html

[D17] 最大值与最小值
来源：http://dali.yj202588.top/Article/details/gt2exjilxdk.html

Py:   max(arr);  min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2cmjiyuyo.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vsxceqth.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.0kj1m.cn/Article/details/gt2bfsoflbb.html

TS:   Math.max(...arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2wbwkcmsl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuxming.cn/Article/details/gt2gtadyiaf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2ejbvwnyh.html

Ruby: arr.max;  arr.min
来源：http://dali.gogol.net.cn/Article/details/gt2nagjkyur.html

C#:   list.Max();  list.Min()
来源：http://dali.nwbrower.top/Article/details/gt2khxuzbif.html

[D18] 扁平化嵌套数组
来源：http://dali.sufxvd.cn/Article/details/gt2nybyyjgq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sxryk.cn/Article/details/gt2qwrftdli.html

PHP:  array_merge(...$nested);
来源：http://dali.mhx1999.top/Article/details/gt2zjtozxkk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhengqikj.top/Article/details/gt2sopjyrih.html

TS:   nested.flat();
来源：http://dali.9152youxi.cn/Article/details/gt2gcooxdee.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxinkj.top/Article/details/gt2xsjpgbsg.html

Go:   // 手写双层循环
来源：http://dali.yueranfly.top/Article/details/gt2gdrwrrsf.html

Ruby: nested.flatten
来源：http://dali.cheryme.top/Article/details/gt2zlythkbf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhixingplan.top/Article/details/gt2xhpyxryx.html

[D19] 按字段分组
来源：http://dali.316326.xyz/Article/details/gt2gniiegro.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yongpay.top/Article/details/gt2omemsxtp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hysaishi.cn/Article/details/gt2hmdvqgna.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.havefunace.top/Article/details/gt2bnfoxkwm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gt2uypabwxp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ivvv.top/Article/details/gt2jizzntgs.html

Go:   // 手写 map[string][]T
来源：http://dali.cheryme.top/Article/details/gt2hpzzpjza.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gaohongyu789.top/Article/details/gt2vlfpazws.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhoulong.xyz/Article/details/gt2senittxk.html

[D20] 统计每个元素出现次数
来源：http://dali.chenzaomai.com/Article/details/gt2gzjcweyj.html

Py:   Counter(arr)
来源：http://dali.hnqzz.top/Article/details/gt2rllcnhyt.html

PHP:  array_count_values($arr);
来源：http://dali.yongpay.top/Article/details/gt2qzmbmgvw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gt2kllnhlkw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gt2ledeeezo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shangyingyoupin.top/Article/details/gt2sagzdozg.html

Go:   // 手写 map[T]int
来源：http://dali.dashuyun.cn/Article/details/gt2qywcezmu.html

Ruby: arr.tally
来源：http://dali.yanxiufei.cn/Article/details/gt2hhvglytt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgufenzy.top/Article/details/gt2isvavcqk.html

[D21] 判断是否包含某元素
来源：http://dali.yuxming.cn/Article/details/gt2ngbgnsgy.html

Py:   x in arr
来源：http://dali.zhongyouzk.top/Article/details/gt2luxfxbua.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gogol.net.cn/Article/details/gt2yxrhxpql.html

JS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gt2sjwwgphu.html

TS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2xuovason.html

Java: list.contains(x)
来源：http://dali.cheryme.top/Article/details/gt2jpjofqpk.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2smlsohrz.html

Ruby: arr.include?(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2vwygrpyk.html

C#:   list.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gt2vucldhmo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenlongwang.top/Article/details/gt2ebozxiqa.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangdashe.top/Article/details/gt2nerghrjx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2piffjhqd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258.top/Article/details/gt2iazwexfe.html

TS:   [...arr];
来源：http://dali.c1oappe.top/Article/details/gt2tgvvifwf.html

Java: new ArrayList<>(list);
来源：http://dali.chenzaomai.com/Article/details/gt2odwgkibr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cdnleiting.top/Article/details/gt2rlnnlkql.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cdnleiting.top/Article/details/gt2laqhlmpx.html

C#:   new List<int>(list);
来源：http://dali.tian-w.cn/Article/details/gt2xikomevb.html

[D23] reduce 累积计算
来源：http://dali.hysaishi.cn/Article/details/gt2vfmuglqj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.316326.xyz/Article/details/gt2pyuvumtq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hywenlv.cn/Article/details/gt2depruxid.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2ivwtemtb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2rklofnec.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.iojbl.cn/Article/details/gt2dwuuwtew.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qvyabnkp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.bjfxy.top/Article/details/gt2guayzfbs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sufxvd.cn/Article/details/gt2jnhraegp.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenlongwang.top/Article/details/gt2dqwdpbfu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gt2ghwivyjg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jyoumei.cn/Article/details/gt2nqrxxjvv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigufen.top/Article/details/gt2iprpxkwe.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnqzz.top/Article/details/gt2imizhwwp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zycfv.cn/Article/details/gt2ayzxscmu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ghfvlwoa.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.iojbl.cn/Article/details/gt2jzojsdfv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenlongwang.top/Article/details/gt2qwqogiwn.html

[D25] Set 集合去重与交并差
来源：http://dali.xylfe.cn/Article/details/gt2ytkleknf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.smart0.xyz/Article/details/gt2dhnwduwz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.kuanghao11.cn/Article/details/gt2zpdqnzxu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sysykeji.top/Article/details/gt2oohaikrf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jianghu66.top/Article/details/gt2hnvhaxlt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xinyue.icu/Article/details/gt2zcbeirjw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ybcxt.top/Article/details/gt2fdiwasyn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shuidangran.top/Article/details/gt2xvslmxya.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gomlvtxk.html

[D26] 数组转字符串
来源：http://dali.guannengcc.top/Article/details/gt2lrurplpe.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenzaomai.com/Article/details/gt2zofbubgn.html

PHP:  implode(", ", $arr);
来源：http://dali.jianghu66.top/Article/details/gt2kngrugwf.html

JS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gt2tkfniluq.html

TS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ffudpsti.html

Java: String.join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gt2uewsziwi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gotoacloud.top/Article/details/gt2gmtsgvwk.html

Ruby: arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ggpiyneo.html

C#:   string.Join(", ", list)
来源：http://dali.fengsongda.top/Article/details/gt2hktuzeua.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2nuhtwvlz.html

E. 字符串处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2jhslolhc.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2zhfztqzl.html

[E01] 拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gt2gnauwwpz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yonumen.top/Article/details/gt2toxecifp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.iojbl.cn/Article/details/gt2hkcqvpnl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xylfe.cn/Article/details/gt2gpeeweat.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gt2rpxusiry.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.316326.xyz/Article/details/gt2tcrtjpvq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxuanxn.top/Article/details/gt2ztpjvzxz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgfzy.top/Article/details/gt2ibibdomg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gt2fxcozsep.html

[E02] 重复字符串
来源：http://dali.cdnleiting.top/Article/details/gt2runkuiml.html

Py:   "ab" * 3
来源：http://dali.bjfxy.top/Article/details/gt2szwkdauh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gyueajok.html

JS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gt2mymeupwt.html

TS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gt2uzdpjoud.html

Java: "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gt2xeiktkjp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ybcxt.top/Article/details/gt2ebjeramj.html

Ruby: "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gt2lmixalxr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.kuanghao11.cn/Article/details/gt2xtwraabz.html

[E03] 截取子串
来源：http://dali.smart0.xyz/Article/details/gt2snxwfnij.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2czlsuuav.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2jxascnuy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gt2okgkwywx.html

TS:   s.slice(1, 4)
来源：http://dali.yj202588.top/Article/details/gt2mtrquend.html

Java: s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gt2yahorkws.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cdnleiting.top/Article/details/gt2uofjezmd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ivvv.top/Article/details/gt2abastukn.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2ejpohitb.html

[E04] 查找子串位置
来源：http://dali.fengsongda.top/Article/details/gt2nivtszce.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dnuguoyu.html

PHP:  strpos($s, "x");
来源：http://dali.shuidangran.top/Article/details/gt2cfqgqpmu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.9152youxi.cn/Article/details/gt2zccvnkkt.html

TS:   s.indexOf("x")
来源：http://dali.c1oappe.top/Article/details/gt2xwbtxfzj.html

Java: s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gt2bekgllax.html

Go:   strings.Index(s, "x")
来源：http://dali.daria6918.cn/Article/details/gt2bvdmgohs.html

Ruby: s.index("x")
来源：http://dali.tanke756.top/Article/details/gt2zmsqkkxb.html

C#:   s.IndexOf("x")
来源：http://dali.tanke756.top/Article/details/gt2hmczfvrm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnxiangtu.top/Article/details/gt2xfzfhnoo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgfzy.top/Article/details/gt2yahjpldi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhongyouzk.top/Article/details/gt2zanbjyor.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gt2aapzmsqy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.redwolf501.top/Article/details/gt2lrbgijrz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gt2gvxulzja.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.havefunace.top/Article/details/gt2hnmptlpf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cdnleiting.top/Article/details/gt2wiskdcac.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gt2opfegvre.html

[E06] 替换子串
来源：http://dali.guowangkeji.top/Article/details/gt2fkeauvtc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gt2ofzoupaa.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daria6918.cn/Article/details/gt2smetbzbv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2jmoozebh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gt2rwejtgud.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2rbvytlla.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yuanzhike.top/Article/details/gt2txiuybkh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2roihjoau.html


<!-- 参考信息 -->