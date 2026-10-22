代发 wailian999

PHP:  // 无重载
来源：http://dali.svipenyu.cn/Article/details/gt2pmlsvbzp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ivvv.top/Article/details/gt2vgtkelwn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2khhponfc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhengqikj.top/Article/details/gt2vakqdxgh.html

Go:   // 无重载：用不同函数名
来源：http://dali.mhx1999.top/Article/details/gt2kxivnegt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhixingplan.top/Article/details/gt2ejvdcojr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhengqikj.top/Article/details/gt2cfntwakb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2eyllungq.html

D. 数组 / 列表 / 集合
来源：http://dali.sxryk.cn/Article/details/gt2apxwqoks.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2mzffwtez.html

[D01] 创建数组 / 列表
来源：http://dali.shuidangran.top/Article/details/gt2honjhjpt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj202588.top/Article/details/gt2vyuhreic.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.havefunace.top/Article/details/gt2wkmrsdoz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hysaishi.cn/Article/details/gt2zopvbkzy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuetiantiany.cn/Article/details/gt2cgejiamv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fzhhl.top/Article/details/gt2kdcqzeki.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuxming.cn/Article/details/gt2shdyidoq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gt2yyexpacv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zdqjudy.top/Article/details/gt2fvoppnkl.html

[D02] 追加元素到末尾
来源：http://dali.kuanghao11.cn/Article/details/gt2owmorhdm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jianghu66.top/Article/details/gt2qstocyxp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cashguo.top/Article/details/gt2cfvjecyg.html

JS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2ttxjhetc.html

TS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gt2wkpjwivi.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvisqwnk.html

Go:   arr = append(arr, 4)
来源：http://dali.xinyue.icu/Article/details/gt2ljdvcmea.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhixingplan.top/Article/details/gt2dwhrqyvr.html

C#:   list.Add(4);
来源：http://dali.nwbrower.top/Article/details/gt2uaxsnkwi.html

[D03] 在指定位置插入元素
来源：http://dali.c1oappe.top/Article/details/gt2vwryelfv.html

Py:   arr.insert(0, 0)
来源：http://dali.sweek.top/Article/details/gt2ifirjiqe.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hfpthk.cn/Article/details/gt2bajyvszz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aizwys.cn/Article/details/gt2dxmtwdnr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cashguo.top/Article/details/gt2yopoysag.html

Java: list.add(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gt2euxcynyu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guowangkeji.top/Article/details/gt2oimpzwjs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bwswapzb.html

C#:   list.Insert(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gt2bzgbwzle.html

[D04] 删除元素
来源：http://dali.yongpay.top/Article/details/gt2gubhllmx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sxryk.cn/Article/details/gt2gvbeiifb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xuanzx.com/Article/details/gt2xfcqnwjv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pengpengdd.cyou/Article/details/gt2hyncyngf.html

TS:   arr.splice(0, 1);
来源：http://dali.quarkkingdee.top/Article/details/gt2tltvdyee.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2vbmmsvux.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guowangkeji.top/Article/details/gt2vrxpqzcc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigufen.top/Article/details/gt2porfbhyz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dianchejie.cn/Article/details/gt2kixnpsta.html

[D05] 访问与修改元素
来源：http://dali.aizwys.cn/Article/details/gt2eoskorqw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gt2rynazebb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gt2tkydovgd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dlatijlx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.andypj.xyz/Article/details/gt2lyjpzaxn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shuidangran.top/Article/details/gt2emdapqwp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gt2lxdmhbyu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gt2ydqeqpdn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gt2xlbjgnjq.html

[D06] 数组长度
来源：http://dali.xuanzx.com/Article/details/gt2ywhyrzuk.html

Py:   len(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2qlmkykpj.html

PHP:  count($arr);
来源：http://dali.316326.xyz/Article/details/gt2zcrwnwhv.html

JS:   arr.length
来源：http://dali.havefunace.top/Article/details/gt2wixcytih.html

TS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gt2ymzooedj.html

Java: list.size();
来源：http://dali.iojbl.cn/Article/details/gt2siolfjus.html

Go:   len(arr)
来源：http://dali.cashguo.top/Article/details/gt2xtvguxpx.html

Ruby: arr.length; arr.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jgmwdvva.html

C#:   list.Count;
来源：http://dali.yj20258888.top/Article/details/gt2rugzwfdq.html

[D07] 切片 / 取子数组
来源：http://dali.zhixingplan.top/Article/details/gt2dtuarefr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.redwolf501.top/Article/details/gt2hbewtrin.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.iojbl.cn/Article/details/gt2fnjgqltm.html

JS:   arr.slice(1, 4);
来源：http://dali.sweek.top/Article/details/gt2ktblcaqy.html

TS:   arr.slice(1, 4);
来源：http://dali.zycfv.cn/Article/details/gt2ccweutfy.html

Java: list.subList(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qljorvjy.html

Go:   arr[1:4]
来源：http://dali.iojbl.cn/Article/details/gt2aeddqkid.html

Ruby: arr[1, 3]
来源：http://dali.pycfn.com/Article/details/gt2plpbljam.html

C#:   list.GetRange(1, 3);
来源：http://dali.gzhubu.top/Article/details/gt2ondaqmqq.html

[D08] 合并两个数组
来源：http://dali.bjfxy.top/Article/details/gt2leuefvfx.html

Py:   a + b;  a.extend(b)
来源：http://dali.0kj1m.cn/Article/details/gt2cpfjuqmr.html

PHP:  array_merge($a, $b);
来源：http://dali.sweek.top/Article/details/gt2aebrcbhc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxuanxn.top/Article/details/gt2bqcrntzb.html

TS:   [...a, ...b];
来源：http://dali.ppjwa.cn/Article/details/gt2uhgdoogf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yongpay.top/Article/details/gt2jmfsodfm.html

Go:   append(a, b...)
来源：http://dali.aibaodan.cn/Article/details/gt2pujklnro.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ydzc1.top/Article/details/gt2orohxfmb.html

C#:   a.Concat(b).ToList()
来源：http://dali.sxryk.cn/Article/details/gt2zqbvrlzw.html

[D09] 排序（升序）
来源：http://dali.vqdsnc.cn/Article/details/gt2uxdhazes.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gt2qfforwlu.html

PHP:  sort($arr);
来源：http://dali.yonumen.top/Article/details/gt2ejxmgiey.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuanzx.com/Article/details/gt2djanlcqa.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xziqi.cn/Article/details/gt2phtienzq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.pengpengdd.cyou/Article/details/gt2lpvzhnbf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fwcqtrji.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gt2qjljigth.html

C#:   list.Sort();
来源：http://dali.iojbl.cn/Article/details/gt2zfjgpiwr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.haohaochexian.top/Article/details/gt2ucgbmdqw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenlongwang.top/Article/details/gt2vflsymfq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zdqjudy.top/Article/details/gt2wouhscoa.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gt2dnznqrwu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gt2scstehwy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.quarkkingdee.top/Article/details/gt2lelopgna.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.quarkkingdee.top/Article/details/gt2zncltyjk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.wangdashe.top/Article/details/gt2bdpadrwa.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhiwuduotai.top/Article/details/gt2txlecsoc.html

[D11] 反转数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2oyxtsheg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.redwolf501.top/Article/details/gt2rvxxclqp.html

PHP:  array_reverse($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2ybgfpjnp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ajntdjqu.html

TS:   [...arr].reverse();
来源：http://dali.chenzaomai.com/Article/details/gt2ejiiwobx.html

Java: Collections.reverse(list);
来源：http://dali.cucudq.cn/Article/details/gt2uwrfmvkd.html

Go:   slices.Reverse(arr)
来源：http://dali.zycfv.cn/Article/details/gt2bboovsqr.html

Ruby: arr.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2arbciuaw.html

C#:   list.Reverse();
来源：http://dali.jianghu66.top/Article/details/gt2pljvnnmz.html

[D12] 查找元素下标
来源：http://dali.c1oappe.top/Article/details/gt2zcrgcrny.html

Py:   arr.index(x);  x in arr
来源：http://dali.fzhhl.top/Article/details/gt2jgtplbyo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ehwqpu.com/Article/details/gt2mbztvlkj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2dhelhxzd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2rwqutopz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yvedp.cn/Article/details/gt2hhvqlzsn.html

Go:   slices.Index(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2kyzdfnza.html

Ruby: arr.index(x)
来源：http://dali.hysaishi.cn/Article/details/gt2fgmifenr.html

C#:   list.IndexOf(x);
来源：http://dali.ppjwa.cn/Article/details/gt2iycxgsnk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.havefunace.top/Article/details/gt2gehcfyxs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenzaomai.com/Article/details/gt2ragwxcwn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yueranfly.top/Article/details/gt2xpisugts.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gt2aoqfoqiz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jdigrpze.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvwhczpo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guannengcc.top/Article/details/gt2ypgjwkif.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wjdycnkd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2thtuvvrz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daxiang520.top/Article/details/gt2foqcbzzh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cucudq.cn/Article/details/gt2uioniscv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daria6918.cn/Article/details/gt2ehxdpylc.html

JS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2dclosdue.html

TS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gt2xzztjsho.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tkgtdsur.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gt2feozwyqj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owmvruje.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.birdmap.top/Article/details/gt2mrufazef.html

[D15] 去重
来源：http://dali.yj202588.top/Article/details/gt2zbbhjjbs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuanzhike.top/Article/details/gt2fhpxezcx.html

PHP:  array_unique($arr);
来源：http://dali.xylfe.cn/Article/details/gt2sadmfhtg.html

JS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gt2xgkzcaty.html

TS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gt2ywyiyspp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qbvggtmd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tian-w.cn/Article/details/gt2oghtbgvn.html

Ruby: arr.uniq
来源：http://dali.aizwys.cn/Article/details/gt2mcgtnhxg.html

C#:   list.Distinct().ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2rokfvwtz.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2poqtlkgs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2kmrmkdhw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.316326.xyz/Article/details/gt2emaabmsa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2necozzyb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2kyoylbzj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj202588.top/Article/details/gt2udepkilk.html

Go:   // 手写循环累加
来源：http://dali.yueranfly.top/Article/details/gt2djikasud.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hammf.cn/Article/details/gt2fqnaibut.html

C#:   list.Sum();  list.Average()
来源：http://dali.ivvv.top/Article/details/gt2thqtfmol.html

[D17] 最大值与最小值
来源：http://dali.hongshengwenyu.top/Article/details/gt2rbdtjhmu.html

Py:   max(arr);  min(arr)
来源：http://dali.havefunace.top/Article/details/gt2ymnkducu.html

PHP:  max($arr);  min($arr);
来源：http://dali.aizwys.cn/Article/details/gt2lwmqwlmt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eftdvery.html

TS:   Math.max(...arr);
来源：http://dali.nanxinkj.top/Article/details/gt2bhhspsku.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jlsjyb.cn/Article/details/gt2puixcvxq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2dnxcldec.html

Ruby: arr.max;  arr.min
来源：http://dali.jiagoushi.top/Article/details/gt2xzwuqhgp.html

C#:   list.Max();  list.Min()
来源：http://dali.yueranfly.top/Article/details/gt2wgbebjxn.html

[D18] 扁平化嵌套数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2jumvtbus.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pycfn.com/Article/details/gt2ujibykcd.html

PHP:  array_merge(...$nested);
来源：http://dali.kuanghao11.cn/Article/details/gt2whqoywtr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuanzx.com/Article/details/gt2stcxicxl.html

TS:   nested.flat();
来源：http://dali.cucudq.cn/Article/details/gt2otrzsbky.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rbvwtiyn.html

Go:   // 手写双层循环
来源：http://dali.sufxvd.cn/Article/details/gt2hsarkuya.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mwqfkhbq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mgihzrev.html

[D19] 按字段分组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbwmytpt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.bjfxy.top/Article/details/gt2rubaxsxx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.vqdsnc.cn/Article/details/gt2daywxcaz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.mhx1999.top/Article/details/gt2mmygaydv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cgnvmrxw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sxryk.cn/Article/details/gt2gppatjmm.html

Go:   // 手写 map[string][]T
来源：http://dali.gotoacloud.top/Article/details/gt2gqwccxhd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yangfankeji.com/Article/details/gt2ozujcviv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenzaomai.com/Article/details/gt2ecpkswow.html

[D20] 统计每个元素出现次数
来源：http://dali.guannengcc.top/Article/details/gt2crckkzfg.html

Py:   Counter(arr)
来源：http://dali.andypj.xyz/Article/details/gt2acuiwnuk.html

PHP:  array_count_values($arr);
来源：http://dali.nwbrower.top/Article/details/gt2lxuleimg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qqqoboup.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gt2xmerycjw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gogol.net.cn/Article/details/gt2xiadteob.html

Go:   // 手写 map[T]int
来源：http://dali.fengsongda.top/Article/details/gt2dmnbqxwq.html

Ruby: arr.tally
来源：http://dali.zhixingplan.top/Article/details/gt2rwegosqw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hammf.cn/Article/details/gt2tjjievaq.html

[D21] 判断是否包含某元素
来源：http://dali.316326.xyz/Article/details/gt2hvflbxdk.html

Py:   x in arr
来源：http://dali.ivvv.top/Article/details/gt2zkujhbvy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhoulong.xyz/Article/details/gt2fkchiqba.html

JS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2sqpnmplg.html

TS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gt2klphnrzy.html

Java: list.contains(x)
来源：http://dali.pycfn.com/Article/details/gt2drubvntj.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2dqvwobgr.html

Ruby: arr.include?(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2nanoncro.html

C#:   list.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gt2ywgyctlo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tanke756.top/Article/details/gt2czktapfq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.mhx1999.top/Article/details/gt2ykkptsze.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gogol.net.cn/Article/details/gt2xmtvdtke.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuanzx.com/Article/details/gt2ceidqjya.html

TS:   [...arr];
来源：http://dali.dianchejie.cn/Article/details/gt2dxkfjmgv.html

Java: new ArrayList<>(list);
来源：http://dali.c1oappe.top/Article/details/gt2mvtsnvnq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xylfe.cn/Article/details/gt2zcchuvru.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fzhhl.top/Article/details/gt2uetahojt.html

C#:   new List<int>(list);
来源：http://dali.tanke756.top/Article/details/gt2yplafvaa.html

[D23] reduce 累积计算
来源：http://dali.yongpay.top/Article/details/gt2sdkzivoe.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daxiang520.top/Article/details/gt2gscbmnob.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.0kj1m.cn/Article/details/gt2lofcnmjv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2ubdvmwst.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2egeonlfb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuxming.cn/Article/details/gt2dpgwsfdw.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gt2fsxynjys.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dianchejie.cn/Article/details/gt2kconjrtf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hnqzz.top/Article/details/gt2insjkvuy.html

[D24] 字典 / Map 基本操作
来源：http://dali.aibaodan.cn/Article/details/gt2bgigwbwe.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hongshengwenyu.top/Article/details/gt2cnylqnwe.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sxryk.cn/Article/details/gt2fcasgioy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnqzz.top/Article/details/gt2haiuvlqc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ydzc1.top/Article/details/gt2xlbnjywn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cheryme.top/Article/details/gt2kfboylmj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aibaodan.cn/Article/details/gt2mgjmjfud.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangshuangyany.cn/Article/details/gt2uzdcnyyf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.redwolf501.top/Article/details/gt2qwmhzapa.html

[D25] Set 集合去重与交并差
来源：http://dali.0kj1m.cn/Article/details/gt2dkmgfinl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yvedp.cn/Article/details/gt2hlvbqstg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cheryme.top/Article/details/gt2fmrxvgny.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2wozpguyk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.smart0.xyz/Article/details/gt2htpiwaok.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinqigufen.top/Article/details/gt2psrfvjxr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daxiang520.top/Article/details/gt2gabyglhe.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cucudq.cn/Article/details/gt2lddnrrxp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.mhx1999.top/Article/details/gt2lsvvyrwe.html

[D26] 数组转字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2eraptazj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nwbrower.top/Article/details/gt2scqhdgxq.html

PHP:  implode(", ", $arr);
来源：http://dali.cucudq.cn/Article/details/gt2bivqunxe.html

JS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gt2zltiixik.html

TS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gt2wgmtxqyg.html

Java: String.join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gt2yullmyiu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dashuyun.cn/Article/details/gt2xxvbdpky.html

Ruby: arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gt2aqhfzsnm.html

C#:   string.Join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gt2hxhxhtuj.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2inacuujs.html

E. 字符串处理
来源：http://dali.316326.xyz/Article/details/gt2ouyfsegt.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bsdoquwl.html

[E01] 拼接字符串
来源：http://dali.316326.xyz/Article/details/gt2nfieiseq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hywenlv.cn/Article/details/gt2fiqxwgtd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2hxnrckpj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gt2tiixekkd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gt2sfytkiuf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.birdmap.top/Article/details/gt2bspbnmei.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenlongwang.top/Article/details/gt2syxpsgqg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nwbrower.top/Article/details/gt2nzsdfmvd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2rkcyppxs.html

[E02] 重复字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2hszfkrzn.html

Py:   "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gt2eaqdwnjf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2pntzkjvr.html

JS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gt2yjvqzdye.html

TS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gt2ajaaqxco.html

Java: "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gt2uyerxsys.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yvedp.cn/Article/details/gt2oasjmjng.html

Ruby: "ab" * 3
来源：http://dali.guowangkeji.top/Article/details/gt2cddvdlac.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.316326.xyz/Article/details/gt2cpjtwyjn.html

[E03] 截取子串
来源：http://dali.snrcjt.cn/Article/details/gt2jsafcmje.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guowangkeji.top/Article/details/gt2mdpkguqw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gt2xixbkvta.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gt2jcpmgcqe.html

TS:   s.slice(1, 4)
来源：http://dali.iojbl.cn/Article/details/gt2rwxibwhq.html

Java: s.substring(1, 4)
来源：http://dali.yonumen.top/Article/details/gt2nsuftuig.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cheryme.top/Article/details/gt2qcpcbvjf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cashguo.top/Article/details/gt2hzuahytw.html

C#:   s.Substring(1, 3)
来源：http://dali.vqdsnc.cn/Article/details/gt2zdlsvgkq.html

[E04] 查找子串位置
来源：http://dali.zhiwuduotai.top/Article/details/gt2jkvaiekj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.smart0.xyz/Article/details/gt2baajqovw.html

PHP:  strpos($s, "x");
来源：http://dali.chenlongwang.top/Article/details/gt2wepzkfkf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nwbrower.top/Article/details/gt2rnxalbxx.html

TS:   s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gt2vazawpih.html

Java: s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gt2jpbxgdmd.html

Go:   strings.Index(s, "x")
来源：http://dali.gzhubu.top/Article/details/gt2jdxosshi.html

Ruby: s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gt2tvjhpyyx.html

C#:   s.IndexOf("x")
来源：http://dali.sweek.top/Article/details/gt2wruqjvrv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xylfe.cn/Article/details/gt2xntfssiw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yvedp.cn/Article/details/gt2dtiibhys.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sweek.top/Article/details/gt2fpzlsdaq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mmyiqnqe.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhengqikj.top/Article/details/gt2yqevizig.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gt2ojrofjjx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2xpgzgdkx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xinyue.icu/Article/details/gt2blwffbxt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gt2ibgckxxe.html

[E06] 替换子串
来源：http://dali.cqqwz.cn/Article/details/gt2llmrtntj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cashguo.top/Article/details/gt2wwktxqhy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yangfankeji.com/Article/details/gt2womnhxlo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mdbzrpxo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gt2mjssgzry.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2mdismblk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gt2lafcohpd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.c1oappe.top/Article/details/gt2gdlwfcea.html


<!-- 参考信息 -->