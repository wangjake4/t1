代发 wailian999

PHP:  // 无重载
来源：http://dali.bjfxy.top/Article/details/gt2bnlgpuyi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenlongwang.top/Article/details/gt2dkbxlrks.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.aizwys.cn/Article/details/gt2emzaawkh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2qoyychag.html

Go:   // 无重载：用不同函数名
来源：http://dali.yonumen.top/Article/details/gt2nimhihgh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jqgfzy.top/Article/details/gt2avstbvab.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tanke756.top/Article/details/gt2swvscknp.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2kkiqltbl.html

D. 数组 / 列表 / 集合
来源：http://dali.c1oappe.top/Article/details/gt2rmqxkvzh.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2itzvjuwq.html

[D01] 创建数组 / 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jknzbsof.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.pengpengdd.cyou/Article/details/gt2olhrbybb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.316326.xyz/Article/details/gt2kgmhnwas.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shzxlz.cn/Article/details/gt2iemtwwxr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fengsongda.top/Article/details/gt2kvofkpwe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hongshengwenyu.top/Article/details/gt2nqkykrob.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.kuanghao11.cn/Article/details/gt2qyqzfpny.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jqgufenzy.top/Article/details/gt2inbcyflb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.bjfxy.top/Article/details/gt2dqkadxpb.html

[D02] 追加元素到末尾
来源：http://dali.quarkkingdee.top/Article/details/gt2xyakygeb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhiwuduotai.top/Article/details/gt2vfuravpa.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.havefunace.top/Article/details/gt2vtyytmmi.html

JS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gt2trfypoqw.html

TS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gt2ojabjdso.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyamptp.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258888.top/Article/details/gt2cuyyover.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258888.top/Article/details/gt2xbltzcjl.html

C#:   list.Add(4);
来源：http://dali.xuanzx.com/Article/details/gt2pfdlsxei.html

[D03] 在指定位置插入元素
来源：http://dali.ehwqpu.com/Article/details/gt2melfsdhu.html

Py:   arr.insert(0, 0)
来源：http://dali.sxryk.cn/Article/details/gt2urpyexlg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bfobmgfx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yangfankeji.com/Article/details/gt2vtixbvxb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.birdmap.top/Article/details/gt2gwmddzre.html

Java: list.add(0, 0);
来源：http://dali.daria6918.cn/Article/details/gt2bnljccjf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sxryk.cn/Article/details/gt2itlbtbsw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenzaomai.com/Article/details/gt2jhcyisfk.html

C#:   list.Insert(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gt2fvdcjyuv.html

[D04] 删除元素
来源：http://dali.kuanghao11.cn/Article/details/gt2smlnfelr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hammf.cn/Article/details/gt2hgkpimaj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2dxuvoeio.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yanxiufei.cn/Article/details/gt2cnboddyg.html

TS:   arr.splice(0, 1);
来源：http://dali.havefunace.top/Article/details/gt2rfyehqkl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gzhubu.top/Article/details/gt2jxfzvill.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cucudq.cn/Article/details/gt2ghvizjjz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2onyqfigr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tanke756.top/Article/details/gt2pizrpyox.html

[D05] 访问与修改元素
来源：http://dali.shuidangran.top/Article/details/gt2cvczdouc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gt2ntgjbliz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2afllicqn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gt2tuzebxag.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yvedp.cn/Article/details/gt2zrxjwzgu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ehwqpu.com/Article/details/gt2dbbcycwm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gt2oaizthva.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gt2mqdkcvjt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gt2irovxeyt.html

[D06] 数组长度
来源：http://dali.mhx1999.top/Article/details/gt2ecbojzlf.html

Py:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gt2qgixyeuw.html

PHP:  count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2irxmyzrw.html

JS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gt2shzdnxyv.html

TS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkhervnp.html

Java: list.size();
来源：http://dali.gogol.net.cn/Article/details/gt2cppbydhz.html

Go:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2txdmjxny.html

Ruby: arr.length; arr.size
来源：http://dali.svipenyu.cn/Article/details/gt2swywecqn.html

C#:   list.Count;
来源：http://dali.aizwys.cn/Article/details/gt2veoqltfw.html

[D07] 切片 / 取子数组
来源：http://dali.xinyue.icu/Article/details/gt2zqbayxfy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ppjwa.cn/Article/details/gt2aijujhnf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fengsongda.top/Article/details/gt2aldgltbt.html

JS:   arr.slice(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gt2nlubvjef.html

TS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjfbnbrf.html

Java: list.subList(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gt2brggyhnu.html

Go:   arr[1:4]
来源：http://dali.pengpengdd.cyou/Article/details/gt2dnnzyhvv.html

Ruby: arr[1, 3]
来源：http://dali.redwolf501.top/Article/details/gt2htcuxvdz.html

C#:   list.GetRange(1, 3);
来源：http://dali.yueranfly.top/Article/details/gt2aoxfeetn.html

[D08] 合并两个数组
来源：http://dali.sufxvd.cn/Article/details/gt2siszrwzn.html

Py:   a + b;  a.extend(b)
来源：http://dali.jianghu66.top/Article/details/gt2qaigiixj.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxinkj.top/Article/details/gt2sjknonym.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zycfv.cn/Article/details/gt2logghlpl.html

TS:   [...a, ...b];
来源：http://dali.hammf.cn/Article/details/gt2fhowzoat.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ivvv.top/Article/details/gt2aoujntoh.html

Go:   append(a, b...)
来源：http://dali.0kj1m.cn/Article/details/gt2ingeetyi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuanzhike.top/Article/details/gt2bwphhhkx.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2hmdbgtek.html

[D09] 排序（升序）
来源：http://dali.cashguo.top/Article/details/gt2oxbdjlgy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gt2jxkyqwcs.html

PHP:  sort($arr);
来源：http://dali.ybcxt.top/Article/details/gt2jentbucs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.mhx1999.top/Article/details/gt2fopgacxz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shzxlz.cn/Article/details/gt2bjnkdvif.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guannengcc.top/Article/details/gt2tsvysfrf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qjeogwzo.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gt2dpypmipg.html

C#:   list.Sort();
来源：http://dali.c1oappe.top/Article/details/gt2qbegyiaq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dianchejie.cn/Article/details/gt2qznjdzez.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2pzpjscrk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jianghu66.top/Article/details/gt2gvvrfvuf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangshuangyany.cn/Article/details/gt2shmkmjbr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gt2cugekemc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.havefunace.top/Article/details/gt2yhtcgcbu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yueranfly.top/Article/details/gt2vzqxnopv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yvedp.cn/Article/details/gt2bpsnavch.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yanxiufei.cn/Article/details/gt2bcwhgshw.html

[D11] 反转数组
来源：http://dali.hnqzz.top/Article/details/gt2zseuslyq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenlongwang.top/Article/details/gt2qtxzpfwc.html

PHP:  array_reverse($arr);
来源：http://dali.pycfn.com/Article/details/gt2poampjce.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tian-w.cn/Article/details/gt2cflhmmcb.html

TS:   [...arr].reverse();
来源：http://dali.xylfe.cn/Article/details/gt2yqdzyitc.html

Java: Collections.reverse(list);
来源：http://dali.zdqjudy.top/Article/details/gt2gboyyfix.html

Go:   slices.Reverse(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2vqpmjxev.html

Ruby: arr.reverse
来源：http://dali.xylfe.cn/Article/details/gt2gnfbdssw.html

C#:   list.Reverse();
来源：http://dali.zycfv.cn/Article/details/gt2lsgndwer.html

[D12] 查找元素下标
来源：http://dali.nanxinkj.top/Article/details/gt2wxwmscxf.html

Py:   arr.index(x);  x in arr
来源：http://dali.jianghu66.top/Article/details/gt2khhwepsk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ifnhoawj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gt2bidifvhq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gt2fvlazawc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yangfankeji.com/Article/details/gt2ucdqocno.html

Go:   slices.Index(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lervibzm.html

Ruby: arr.index(x)
来源：http://dali.daria6918.cn/Article/details/gt2lpowdtxl.html

C#:   list.IndexOf(x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fjnoaxtz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenjidiqi.icu/Article/details/gt2stbvfydk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.svipenyu.cn/Article/details/gt2sjrezegp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenzaomai.com/Article/details/gt2htgfbuaj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gt2pyuwshkt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vvtpueph.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guowangkeji.top/Article/details/gt2dsyihvut.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guannengcc.top/Article/details/gt2hpfduucl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhoulong.xyz/Article/details/gt2ozarfbqb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guannengcc.top/Article/details/gt2wrsgjibv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tian-w.cn/Article/details/gt2bdizuaef.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cqqwz.cn/Article/details/gt2lgmkviyl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ehwqpu.com/Article/details/gt2zalxvciu.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gt2ardhecck.html

TS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gt2sxmvzmax.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2vplvttun.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gt2sjzjpcem.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2uelxboja.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2hyuyctbs.html

[D15] 去重
来源：http://dali.hysaishi.cn/Article/details/gt2blfaswtv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gt2brdznpgj.html

PHP:  array_unique($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2vrzwvhkb.html

JS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gt2xgyfzgki.html

TS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gt2tlkboxri.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xylfe.cn/Article/details/gt2drhavrqm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.c1oappe.top/Article/details/gt2ojrznics.html

Ruby: arr.uniq
来源：http://dali.yuxming.cn/Article/details/gt2ksoxtkys.html

C#:   list.Distinct().ToList()
来源：http://dali.yvedp.cn/Article/details/gt2qwnjjqyw.html

[D16] 求和与平均值
来源：http://dali.xuanzx.com/Article/details/gt2qkgbudxp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wqmshwsg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2dnrfdqid.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gt2kbyysptj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gt2yaseidyw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxinkj.top/Article/details/gt2zyrztdid.html

Go:   // 手写循环累加
来源：http://dali.sxryk.cn/Article/details/gt2ekvycdui.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangtech.top/Article/details/gt2feaipfse.html

C#:   list.Sum();  list.Average()
来源：http://dali.yangfankeji.com/Article/details/gt2cetcvxgm.html

[D17] 最大值与最小值
来源：http://dali.meibo888.top/Article/details/gt2saxzrgly.html

Py:   max(arr);  min(arr)
来源：http://dali.fengsongda.top/Article/details/gt2irigjpgx.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuxming.cn/Article/details/gt2okbgixgt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mmhkqabk.html

TS:   Math.max(...arr);
来源：http://dali.shuidangran.top/Article/details/gt2sctohwac.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gotoacloud.top/Article/details/gt2ofoixbhi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jxhpujmx.html

Ruby: arr.max;  arr.min
来源：http://dali.kuanghao11.cn/Article/details/gt2bcckudyz.html

C#:   list.Max();  list.Min()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bkuhgulj.html

[D18] 扁平化嵌套数组
来源：http://dali.meibo888.top/Article/details/gt2sjonisup.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jianghu66.top/Article/details/gt2hfnhkjii.html

PHP:  array_merge(...$nested);
来源：http://dali.quarkkingdee.top/Article/details/gt2ptypvuae.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.bjfxy.top/Article/details/gt2rkzobjrs.html

TS:   nested.flat();
来源：http://dali.guannengcc.top/Article/details/gt2sjdpngsq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gzhubu.top/Article/details/gt2nvwvydve.html

Go:   // 手写双层循环
来源：http://dali.9152youxi.cn/Article/details/gt2uzlwwsst.html

Ruby: nested.flatten
来源：http://dali.ppjwa.cn/Article/details/gt2jiiawxtj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2auwyjrbp.html

[D19] 按字段分组
来源：http://dali.vqdsnc.cn/Article/details/gt2ttwkpnxc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2gaakqygx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258888.top/Article/details/gt2ifkrvbgp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gzhubu.top/Article/details/gt2hcrtbuae.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gt2ypiuoehn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aizwys.cn/Article/details/gt2ywmjbtnc.html

Go:   // 手写 map[string][]T
来源：http://dali.gotoacloud.top/Article/details/gt2shtujrqq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daxiang520.top/Article/details/gt2zelfzrzt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangdashe.top/Article/details/gt2tdqsrkup.html

[D20] 统计每个元素出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2blskzstk.html

Py:   Counter(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2xhcxqbxs.html

PHP:  array_count_values($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2segkgufm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gt2rycnqiuu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.snrcjt.cn/Article/details/gt2skavobsj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.vqdsnc.cn/Article/details/gt2ylupiawy.html

Go:   // 手写 map[T]int
来源：http://dali.snrcjt.cn/Article/details/gt2mptlbdfm.html

Ruby: arr.tally
来源：http://dali.tian-w.cn/Article/details/gt2hgtwzdej.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ehwqpu.com/Article/details/gt2kjcxmnxk.html

[D21] 判断是否包含某元素
来源：http://dali.jqgfzy.top/Article/details/gt2wzhwmiee.html

Py:   x in arr
来源：http://dali.redwolf501.top/Article/details/gt2ywwzgmbp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daria6918.cn/Article/details/gt2kmlciiua.html

JS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gt2zoxcnaoh.html

TS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gt2ltvrcbpl.html

Java: list.contains(x)
来源：http://dali.sufxvd.cn/Article/details/gt2hptnkrrz.html

Go:   slices.Contains(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2oaqpczfb.html

Ruby: arr.include?(x)
来源：http://dali.daria6918.cn/Article/details/gt2cgbygygt.html

C#:   list.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gt2fvurrjbu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhiwuduotai.top/Article/details/gt2tiwyawjl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gzhubu.top/Article/details/gt2vntkuoks.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sysykeji.top/Article/details/gt2oitpmgnx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.meibo888.top/Article/details/gt2hwhecymi.html

TS:   [...arr];
来源：http://dali.hongshengwenyu.top/Article/details/gt2uagulgnp.html

Java: new ArrayList<>(list);
来源：http://dali.haohaochexian.top/Article/details/gt2yjxflrge.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xziqi.cn/Article/details/gt2evyobbqn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zycfv.cn/Article/details/gt2vzcktvdh.html

C#:   new List<int>(list);
来源：http://dali.xziqi.cn/Article/details/gt2odmidlfj.html

[D23] reduce 累积计算
来源：http://dali.zycfv.cn/Article/details/gt2nuyurune.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.meibo888.top/Article/details/gt2hpezpmoc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shzxlz.cn/Article/details/gt2pmxobxui.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gt2zzkfsvdn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gt2tktlpxsw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2btbvawdd.html

Go:   // 手写循环
来源：http://dali.0kj1m.cn/Article/details/gt2kluvwnoc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxinkj.top/Article/details/gt2bblufnhe.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuxming.cn/Article/details/gt2puuwwifd.html

[D24] 字典 / Map 基本操作
来源：http://dali.dashuyun.cn/Article/details/gt2evkymgfp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yanxiufei.cn/Article/details/gt2nljhfwzd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shuidangran.top/Article/details/gt2mjjczzmr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guannengcc.top/Article/details/gt2aedbysyl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2sylavmyc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gzhubu.top/Article/details/gt2ejxkswwq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hongshengwenyu.top/Article/details/gt2yhisvtff.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uhrylnpc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.0kj1m.cn/Article/details/gt2jbesrljs.html

[D25] Set 集合去重与交并差
来源：http://dali.hywenlv.cn/Article/details/gt2ilpmznbi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ivvv.top/Article/details/gt2ymstbstk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgfzy.top/Article/details/gt2kiwsaama.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangdashe.top/Article/details/gt2xukmvubr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daria6918.cn/Article/details/gt2tufwyfsb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hfpthk.cn/Article/details/gt2lieksvjz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zdqjudy.top/Article/details/gt2fdxxesqt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gzhubu.top/Article/details/gt2kzdfsexp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hzfpkauc.html

[D26] 数组转字符串
来源：http://dali.andypj.xyz/Article/details/gt2ucyubfml.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cashguo.top/Article/details/gt2rupflpkn.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gt2zaqrceim.html

JS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gt2vqsdinlk.html

TS:   arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gt2dmkhdqzf.html

Java: String.join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gt2gvwvovtv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jlsjyb.cn/Article/details/gt2yzdoztsr.html

Ruby: arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gt2oyywpsth.html

C#:   string.Join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gt2qgdajtpu.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evgcfgqr.html

E. 字符串处理
来源：http://dali.9152youxi.cn/Article/details/gt2iycazbcd.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2daiggjub.html

[E01] 拼接字符串
来源：http://dali.316326.xyz/Article/details/gt2uyegvank.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pycfn.com/Article/details/gt2caeogedi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2waklbfto.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gt2llxqszse.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gt2tlrybfyn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2clgzxtci.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daria6918.cn/Article/details/gt2ggdndrds.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnqzz.top/Article/details/gt2cfdigjst.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2vrxnymsk.html

[E02] 重复字符串
来源：http://dali.aibaodan.cn/Article/details/gt2mkjbshdv.html

Py:   "ab" * 3
来源：http://dali.andypj.xyz/Article/details/gt2ndgemqdw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2jcbdsurn.html

JS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gt2jncjoamw.html

TS:   "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xygsoosb.html

Java: "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gt2ovinpjuu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.haohaochexian.top/Article/details/gt2fjgdfkwt.html

Ruby: "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gt2qjnmdkqm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxuanxn.top/Article/details/gt2aufmekuw.html

[E03] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gt2cpptvgmj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhoulong.xyz/Article/details/gt2nffvceml.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gt2kcihalsv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gt2yqgrlitz.html

TS:   s.slice(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gt2yivjasku.html

Java: s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gt2yipyrvzg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jyoumei.cn/Article/details/gt2zlrmolnb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dashuyun.cn/Article/details/gt2qxvlubda.html

C#:   s.Substring(1, 3)
来源：http://dali.zdqjudy.top/Article/details/gt2pvjjtbkc.html

[E04] 查找子串位置
来源：http://dali.c1oappe.top/Article/details/gt2jarxrxly.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sysykeji.top/Article/details/gt2siexsxii.html

PHP:  strpos($s, "x");
来源：http://dali.gotoacloud.top/Article/details/gt2vnfkvuvf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xinyue.icu/Article/details/gt2owouepqv.html

TS:   s.indexOf("x")
来源：http://dali.yuxming.cn/Article/details/gt2vvlkniho.html

Java: s.indexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gt2mafkqtlj.html

Go:   strings.Index(s, "x")
来源：http://dali.snrcjt.cn/Article/details/gt2itgdkycd.html

Ruby: s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xpgfpuvf.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gt2yzewyaqj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenjidiqi.icu/Article/details/gt2hehdhuzn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daxiang520.top/Article/details/gt2hfnpblgp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yongpay.top/Article/details/gt2nsojwvhc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gt2djqyudpo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hfpthk.cn/Article/details/gt2wcxlsclq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gt2axnibnju.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sysykeji.top/Article/details/gt2fnhzahxp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sysykeji.top/Article/details/gt2hwmyogcy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gt2isgyyyxi.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bpoypcjh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gt2rjvsfnmz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vgeuzymo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2dievcgwo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2jkzvelmj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2fzwrxqmn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gt2thcetzgk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2vxtmucli.html


<!-- 参考信息 -->