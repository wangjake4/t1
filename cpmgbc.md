代发 wailian999

Go:   // 无重载：用不同函数名
来源：http://dali.cqqwz.cn/Article/details/gt2znsqwjhe.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hfpthk.cn/Article/details/gt2enozyrpn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenlongwang.top/Article/details/gt2fyvbxlno.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2tfvntfnl.html

D. 数组 / 列表 / 集合
来源：http://dali.kuanghao11.cn/Article/details/gt2jfzouhjs.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2kgxhbowb.html

[D01] 创建数组 / 列表
来源：http://dali.gaohongyu789.top/Article/details/gt2dgufmetr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangshuangyany.cn/Article/details/gt2mqwzyqdu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gt2unmrudma.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gt2rdxttbdn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.meibo888.top/Article/details/gt2mozddkdz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mklrcujo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.316326.xyz/Article/details/gt2rbrsdhsi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ivvv.top/Article/details/gt2krlhigah.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.bjfxy.top/Article/details/gt2yciiapst.html

[D02] 追加元素到末尾
来源：http://dali.cashguo.top/Article/details/gt2jyffzxly.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fengsongda.top/Article/details/gt2qynfimip.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.iojbl.cn/Article/details/gt2oxazmoxp.html

JS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gt2cihjfrcg.html

TS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gt2yxbzfbhs.html

Java: list.add(4);
来源：http://dali.yvedp.cn/Article/details/gt2asazkujk.html

Go:   arr = append(arr, 4)
来源：http://dali.daria6918.cn/Article/details/gt2gmhqixbv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dashuyun.cn/Article/details/gt2xygdmjqq.html

C#:   list.Add(4);
来源：http://dali.gotoacloud.top/Article/details/gt2xnmnkdvm.html

[D03] 在指定位置插入元素
来源：http://dali.jyoumei.cn/Article/details/gt2lbofteep.html

Py:   arr.insert(0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2kupxxscx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gogol.net.cn/Article/details/gt2vhmzhuop.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenzaomai.com/Article/details/gt2uubnmbqv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shzxlz.cn/Article/details/gt2oeagxftg.html

Java: list.add(0, 0);
来源：http://dali.ivvv.top/Article/details/gt2zuevswpu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nanxuanxn.top/Article/details/gt2lhblykln.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xylfe.cn/Article/details/gt2xqugmhld.html

C#:   list.Insert(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2atymewjl.html

[D04] 删除元素
来源：http://dali.hfpthk.cn/Article/details/gt2lwhvspfo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nprehtod.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2rjesfgtz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2strlhpko.html

TS:   arr.splice(0, 1);
来源：http://dali.yueranfly.top/Article/details/gt2nmpurcnb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hywenlv.cn/Article/details/gt2ifsyytpk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sfrpvvif.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.316326.xyz/Article/details/gt2ououzipa.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgufenzy.top/Article/details/gt2mimxuefv.html

[D05] 访问与修改元素
来源：http://dali.birdmap.top/Article/details/gt2qostzicj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gt2togkrulj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.316326.xyz/Article/details/gt2xrahcliq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sdlxcnzj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.316326.xyz/Article/details/gt2nzfhxhfm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gotoacloud.top/Article/details/gt2pentgaac.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gt2ufvugope.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gt2vxercepe.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gt2ccbflswf.html

[D06] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gt2okuezarp.html

Py:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gt2cenulzcf.html

PHP:  count($arr);
来源：http://dali.sxryk.cn/Article/details/gt2srlvuols.html

JS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gt2bdxlsbgx.html

TS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gt2vlsbcojg.html

Java: list.size();
来源：http://dali.cheryme.top/Article/details/gt2zpovtarl.html

Go:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2kiqathwi.html

Ruby: arr.length; arr.size
来源：http://dali.jinqigfzy.top/Article/details/gt2fbqgccaj.html

C#:   list.Count;
来源：http://dali.shuidangran.top/Article/details/gt2wymxqwbe.html

[D07] 切片 / 取子数组
来源：http://dali.fzhhl.top/Article/details/gt2blncfvkb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nwbrower.top/Article/details/gt2ashkwbww.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sweek.top/Article/details/gt2pnlahkvg.html

JS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gt2qdhfcwfh.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gt2aiqncczz.html

Java: list.subList(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gt2wojbpgds.html

Go:   arr[1:4]
来源：http://dali.jqgfzy.top/Article/details/gt2mbvoewfh.html

Ruby: arr[1, 3]
来源：http://dali.guannengcc.top/Article/details/gt2gaxsnmgu.html

C#:   list.GetRange(1, 3);
来源：http://dali.meibo888.top/Article/details/gt2smnaucif.html

[D08] 合并两个数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2ldikegmv.html

Py:   a + b;  a.extend(b)
来源：http://dali.hammf.cn/Article/details/gt2defldukw.html

PHP:  array_merge($a, $b);
来源：http://dali.daria6918.cn/Article/details/gt2atfgutbr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.snrcjt.cn/Article/details/gt2ahxyqmra.html

TS:   [...a, ...b];
来源：http://dali.xinyue.icu/Article/details/gt2vjtngbjq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkeigrh.html

Go:   append(a, b...)
来源：http://dali.jyoumei.cn/Article/details/gt2wcufeikf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2asdpundx.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ockgccvw.html

[D09] 排序（升序）
来源：http://dali.pycfn.com/Article/details/gt2tsmswjcy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gt2shkdnmrk.html

PHP:  sort($arr);
来源：http://dali.gzhubu.top/Article/details/gt2stunbvpq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.meibo888.top/Article/details/gt2ejdyhkio.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gaohongyu789.top/Article/details/gt2rzsnwrag.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yanxiufei.cn/Article/details/gt2opzxbrrs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2ssjaekbf.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vpelkeat.html

C#:   list.Sort();
来源：http://dali.tianlin.xyz/Article/details/gt2uzsgfluj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aibaodan.cn/Article/details/gt2ektskiyj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhongyouzk.top/Article/details/gt2wixqacnt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2azcorntl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gt2ezojztks.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qpmtdgex.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ehwqpu.com/Article/details/gt2udakpbso.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuxming.cn/Article/details/gt2lcbjjjqb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fengsongda.top/Article/details/gt2cwdcxxgo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.quarkkingdee.top/Article/details/gt2ocdfpddm.html

[D11] 反转数组
来源：http://dali.yj20258.top/Article/details/gt2tmhynwyf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jlsjyb.cn/Article/details/gt2dbebqohc.html

PHP:  array_reverse($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2tkimjjfv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhoulong.xyz/Article/details/gt2fsmptywm.html

TS:   [...arr].reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gt2zxlxrgka.html

Java: Collections.reverse(list);
来源：http://dali.andypj.xyz/Article/details/gt2hgkfapic.html

Go:   slices.Reverse(arr)
来源：http://dali.yuxming.cn/Article/details/gt2zcybnbbk.html

Ruby: arr.reverse
来源：http://dali.c1oappe.top/Article/details/gt2fkvlifxh.html

C#:   list.Reverse();
来源：http://dali.yj20258888.top/Article/details/gt2lxhpeseb.html

[D12] 查找元素下标
来源：http://dali.zhongyouzk.top/Article/details/gt2sjeuqdbw.html

Py:   arr.index(x);  x in arr
来源：http://dali.zycfv.cn/Article/details/gt2iccxgbyz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2ygudoidx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gt2engpkppv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gt2kqekkqaj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gogol.net.cn/Article/details/gt2zirqcxje.html

Go:   slices.Index(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2abkqgrey.html

Ruby: arr.index(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2ubnfgbon.html

C#:   list.IndexOf(x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vxjlwaxv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangdashe.top/Article/details/gt2shbrobdz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj202588.top/Article/details/gt2osmqnxsv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.svipenyu.cn/Article/details/gt2pmygtdno.html

JS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gt2zqoxnsvb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gt2rthknpgn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2wuapkkxq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhongyouzk.top/Article/details/gt2ziyfgrvo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fengsongda.top/Article/details/gt2wxavhgwk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cxuayxiz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zycfv.cn/Article/details/gt2bbpiyxti.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nwbrower.top/Article/details/gt2uembetcn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2rdwjzybz.html

JS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gt2zusprajn.html

TS:   arr.map(x => x * 2)
来源：http://dali.dianchejie.cn/Article/details/gt2bqhsfpef.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shzxlz.cn/Article/details/gt2jgpzjbvf.html

Go:   // 手写循环
来源：http://dali.vqdsnc.cn/Article/details/gt2sxtxfjas.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cucudq.cn/Article/details/gt2xrfncdfy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2yhcaejcd.html

[D15] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqsgomen.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gt2lpupjvfo.html

PHP:  array_unique($arr);
来源：http://dali.xziqi.cn/Article/details/gt2cmpstitg.html

JS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gt2zhigwqrn.html

TS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gt2fxsxzoml.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hfpthk.cn/Article/details/gt2qpwyzckg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangdashe.top/Article/details/gt2yvogixnc.html

Ruby: arr.uniq
来源：http://dali.yongpay.top/Article/details/gt2yzaidaaw.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2howkimgp.html

[D16] 求和与平均值
来源：http://dali.zhengqikj.top/Article/details/gt2krwadwwz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xylfe.cn/Article/details/gt2cobpimie.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.bjfxy.top/Article/details/gt2lacxpkzb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2ajekhsod.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gt2sqjwvoxn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yanxiufei.cn/Article/details/gt2eaeazukn.html

Go:   // 手写循环累加
来源：http://dali.chenjidiqi.icu/Article/details/gt2ncnntyjs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ydzc1.top/Article/details/gt2bxsxtgaj.html

C#:   list.Sum();  list.Average()
来源：http://dali.quarkkingdee.top/Article/details/gt2qsruvwnt.html

[D17] 最大值与最小值
来源：http://dali.birdmap.top/Article/details/gt2rioolaut.html

Py:   max(arr);  min(arr)
来源：http://dali.tanke756.top/Article/details/gt2twakcdth.html

PHP:  max($arr);  min($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2zgstibam.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj202588.top/Article/details/gt2umvbncxs.html

TS:   Math.max(...arr);
来源：http://dali.iojbl.cn/Article/details/gt2nnxbnsji.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yueranfly.top/Article/details/gt2dpmoalzt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2tqupawaw.html

Ruby: arr.max;  arr.min
来源：http://dali.gogol.net.cn/Article/details/gt2nlvlklms.html

C#:   list.Max();  list.Min()
来源：http://dali.cheryme.top/Article/details/gt2hkquzhlg.html

[D18] 扁平化嵌套数组
来源：http://dali.pycfn.com/Article/details/gt2nqqbnyuf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zycfv.cn/Article/details/gt2sgggijhq.html

PHP:  array_merge(...$nested);
来源：http://dali.wangdashe.top/Article/details/gt2abtxazoa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhoulong.xyz/Article/details/gt2gxunznpp.html

TS:   nested.flat();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uwsdtgbx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guannengcc.top/Article/details/gt2knyoxnay.html

Go:   // 手写双层循环
来源：http://dali.pycfn.com/Article/details/gt2edphmcmn.html

Ruby: nested.flatten
来源：http://dali.gogol.net.cn/Article/details/gt2uzdxrjiw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2bpppciaa.html

[D19] 按字段分组
来源：http://dali.zhoulong.xyz/Article/details/gt2aonrbhhw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yongpay.top/Article/details/gt2urdiuthj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.0kj1m.cn/Article/details/gt2cfseqxfk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.redwolf501.top/Article/details/gt2gdnnpzpq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gt2wgswhgxx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shangyingyoupin.top/Article/details/gt2rphazpwe.html

Go:   // 手写 map[string][]T
来源：http://dali.zhengqikj.top/Article/details/gt2xwetgrpk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xinyue.icu/Article/details/gt2zqyhxvmv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.andypj.xyz/Article/details/gt2wqoglwwh.html

[D20] 统计每个元素出现次数
来源：http://dali.316326.xyz/Article/details/gt2eqsjtyef.html

Py:   Counter(arr)
来源：http://dali.fengsongda.top/Article/details/gt2dhzxhhdq.html

PHP:  array_count_values($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2dbjjqnkl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gt2adpwzwno.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hongshengwenyu.top/Article/details/gt2zqwohigb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigfzy.top/Article/details/gt2nchzgqbd.html

Go:   // 手写 map[T]int
来源：http://dali.gogol.net.cn/Article/details/gt2gskpgrqa.html

Ruby: arr.tally
来源：http://dali.chenjidiqi.icu/Article/details/gt2blfckaat.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hywenlv.cn/Article/details/gt2cvhgsvsu.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258.top/Article/details/gt2sfcufxqk.html

Py:   x in arr
来源：http://dali.hammf.cn/Article/details/gt2ahqlogkl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.0kj1m.cn/Article/details/gt2jtqyyzjv.html

JS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gt2cskmerxp.html

TS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2prmkmhqg.html

Java: list.contains(x)
来源：http://dali.cdnleiting.top/Article/details/gt2ixiilzcd.html

Go:   slices.Contains(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2nbhlikpj.html

Ruby: arr.include?(x)
来源：http://dali.cucudq.cn/Article/details/gt2xeifrzsh.html

C#:   list.Contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2xxfgfjkq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sweek.top/Article/details/gt2rbqtncqy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2dfmonqky.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.kuanghao11.cn/Article/details/gt2nioffdal.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.smart0.xyz/Article/details/gt2xhcrspgs.html

TS:   [...arr];
来源：http://dali.cucudq.cn/Article/details/gt2bzffzwns.html

Java: new ArrayList<>(list);
来源：http://dali.snrcjt.cn/Article/details/gt2ivlniuyo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hnxiangtu.top/Article/details/gt2shyjrrvg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sysykeji.top/Article/details/gt2akwmdkah.html

C#:   new List<int>(list);
来源：http://dali.xylfe.cn/Article/details/gt2vjmizosi.html

[D23] reduce 累积计算
来源：http://dali.guowangkeji.top/Article/details/gt2wjbljyha.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2xwpxbytp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gzhubu.top/Article/details/gt2ijancrls.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2zuhieiyc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2nmlgwoxu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daria6918.cn/Article/details/gt2vnalsnmu.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gt2fwpvpbav.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jianghu66.top/Article/details/gt2gghobymz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2avzajsce.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuanzhike.top/Article/details/gt2oydvyrqo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zycfv.cn/Article/details/gt2ljpbbgfm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hammf.cn/Article/details/gt2owapfhbq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fengsongda.top/Article/details/gt2ufxulmpa.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2reytkryh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tian-w.cn/Article/details/gt2cjkmmors.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zdqjudy.top/Article/details/gt2tzgnavfz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yuxming.cn/Article/details/gt2emcubsyv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yangfankeji.com/Article/details/gt2ttbzkezv.html

[D25] Set 集合去重与交并差
来源：http://dali.kuanghao11.cn/Article/details/gt2ehargour.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.havefunace.top/Article/details/gt2rjhoagij.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.c1oappe.top/Article/details/gt2xafrtbja.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzqwgpob.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.redwolf501.top/Article/details/gt2eovqjfzi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2cqnotdlx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yanxiufei.cn/Article/details/gt2zazwtygn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenlongwang.top/Article/details/gt2ugqljbbj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gzhubu.top/Article/details/gt2kmydrtsf.html

[D26] 数组转字符串
来源：http://dali.gzhubu.top/Article/details/gt2ztxwdjds.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guowangkeji.top/Article/details/gt2lkdekhue.html

PHP:  implode(", ", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ldiqgtcs.html

JS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gt2tfizcdmi.html

TS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gt2ywsbokgs.html

Java: String.join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gt2yhanvsen.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qqzwyxdh.html

Ruby: arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gt2ohmxgvdz.html

C#:   string.Join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gt2kixauaun.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ieicmzvj.html

E. 字符串处理
来源：http://dali.xziqi.cn/Article/details/gt2gudazicm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2jguvywmu.html

[E01] 拼接字符串
来源：http://dali.yonumen.top/Article/details/gt2nddqqmxu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hongshengwenyu.top/Article/details/gt2loguwzoa.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qmtlsdbb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gt2xkitqnsz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gt2misuggvz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2tcvilemt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dianchejie.cn/Article/details/gt2tnqmygxn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigufen.top/Article/details/gt2pamknlpq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2qrhfqbyf.html

[E02] 重复字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2juppborl.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2elomctho.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2bluwqstk.html

JS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gt2nviqgrie.html

TS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cyhtiokv.html

Java: "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uecrphmf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xziqi.cn/Article/details/gt2lcbmpbdd.html

Ruby: "ab" * 3
来源：http://dali.meibo888.top/Article/details/gt2mgxgevny.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ivvv.top/Article/details/gt2advdenxc.html

[E03] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gt2hartoyna.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ivvv.top/Article/details/gt2isaaozmm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gt2gqvurbct.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gt2mxpyabxt.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258.top/Article/details/gt2twklczud.html

Java: s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gt2wpuiqmdx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258.top/Article/details/gt2afxzxirl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hpqkmhdb.html

C#:   s.Substring(1, 3)
来源：http://dali.sxryk.cn/Article/details/gt2stqvnzva.html

[E04] 查找子串位置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wmjmdfwa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gt2lrdwouyz.html

PHP:  strpos($s, "x");
来源：http://dali.yvedp.cn/Article/details/gt2jcplrsqc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lxfguywq.html

TS:   s.indexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gt2fmvrlhmf.html

Java: s.indexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vnofeftc.html

Go:   strings.Index(s, "x")
来源：http://dali.quarkkingdee.top/Article/details/gt2hubnkmqt.html

Ruby: s.index("x")
来源：http://dali.xziqi.cn/Article/details/gt2qlqoeedj.html

C#:   s.IndexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2nmwnzkao.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ppjwa.cn/Article/details/gt2zjhclbhk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgfzy.top/Article/details/gt2byfrfepp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yvedp.cn/Article/details/gt2xyjsldgq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gt2fopdlyvo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yongpay.top/Article/details/gt2qoneflgz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gt2iivldxuh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hgzjtvgr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jvutlfkw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.meibo888.top/Article/details/gt2uimhdrtm.html

[E06] 替换子串
来源：http://dali.yj20258888.top/Article/details/gt2sccosejk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gt2qufnlqvc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dianchejie.cn/Article/details/gt2nqywonfb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2uxmqivuc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2lksanteb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2xxqobggy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gt2lullnuyw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2rcgkqkwp.html

C#:   s.Replace("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2qniivgch.html

[E07] 按分隔符拆分
来源：http://dali.jinqigfzy.top/Article/details/gt2dxpixukz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.havefunace.top/Article/details/gt2mpnoenuf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2ldzajwwe.html


<!-- 参考信息 -->