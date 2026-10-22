代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hongshengwenyu.top/Article/details/gt2lekfzntw.html

[C15] 解构 / 展开参数
来源：http://dali.ivvv.top/Article/details/gt2sygkutzp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhengqikj.top/Article/details/gt2wfkbdirw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhengqikj.top/Article/details/gt2ktaqshur.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fzhhl.top/Article/details/gt2giudgyfp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2vbigqpkm.html

Java: // 无解构
来源：http://dali.nwbrower.top/Article/details/gt2czqhhzoz.html

Go:   // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wzjvrsmw.html

Ruby: a, b = pair
来源：http://dali.guannengcc.top/Article/details/gt2nnxemwjs.html

C#:   var (a, b) = pair;
来源：http://dali.chenjidiqi.icu/Article/details/gt2orpyxtxz.html

[C16] 函数 / 方法重载
来源：http://dali.cashguo.top/Article/details/gt2qmlmpisl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jiagoushi.top/Article/details/gt2zeafutcd.html

PHP:  // 无重载
来源：http://dali.jqgfzy.top/Article/details/gt2kftpjvlh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhixingplan.top/Article/details/gt2yvstqjnp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhixingplan.top/Article/details/gt2hedaqgdx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2npftmhfm.html

Go:   // 无重载：用不同函数名
来源：http://dali.sxryk.cn/Article/details/gt2gtmuknbj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jiagoushi.top/Article/details/gt2ghykavzz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2kujjobao.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2urnnrlyq.html

D. 数组 / 列表 / 集合
来源：http://dali.havefunace.top/Article/details/gt2ztjbhwsw.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2ptsapude.html

[D01] 创建数组 / 列表
来源：http://dali.quarkkingdee.top/Article/details/gt2hkznqzxf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.svipenyu.cn/Article/details/gt2qzbouljr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ydzc1.top/Article/details/gt2nuggyids.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xuanzx.com/Article/details/gt2tqdbicmz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxinkj.top/Article/details/gt2zqusvrsl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cqqwz.cn/Article/details/gt2ufrjpltf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sweek.top/Article/details/gt2cewnnwol.html

Ruby: arr = [1, 2, 3]
来源：http://dali.bjfxy.top/Article/details/gt2hfshjbqd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.feifeiyinyue.top/Article/details/gt2etywgddn.html

[D02] 追加元素到末尾
来源：http://dali.haohaochexian.top/Article/details/gt2iaxkxiez.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sxryk.cn/Article/details/gt2bklutyuh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangdashe.top/Article/details/gt2hazqknic.html

JS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gt2dtlfadis.html

TS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gvkcmodm.html

Java: list.add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2sxhdkmdn.html

Go:   arr = append(arr, 4)
来源：http://dali.wangdashe.top/Article/details/gt2aabqhnku.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.bjfxy.top/Article/details/gt2vjxuuwfr.html

C#:   list.Add(4);
来源：http://dali.yj20258.top/Article/details/gt2petqauvx.html

[D03] 在指定位置插入元素
来源：http://dali.hysaishi.cn/Article/details/gt2xtvvgilc.html

Py:   arr.insert(0, 0)
来源：http://dali.daria6918.cn/Article/details/gt2ugdgkbrx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jlsjyb.cn/Article/details/gt2jrdiizuo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigufen.top/Article/details/gt2wmfvjguf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ydzc1.top/Article/details/gt2olfnetrr.html

Java: list.add(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gt2tolpgynq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.meibo888.top/Article/details/gt2ebpksomw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sufxvd.cn/Article/details/gt2zpfajcfg.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gt2pqdfumsp.html

[D04] 删除元素
来源：http://dali.c1oappe.top/Article/details/gt2uanxbcbv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yonumen.top/Article/details/gt2ivnudhyx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uicgivsu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yuanzhike.top/Article/details/gt2nlcgvaax.html

TS:   arr.splice(0, 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yuxlmwsx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhengqikj.top/Article/details/gt2qpvgbkse.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yongpay.top/Article/details/gt2hsqbksbx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hfpthk.cn/Article/details/gt2hyhihxeh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nanxinkj.top/Article/details/gt2vaffaamv.html

[D05] 访问与修改元素
来源：http://dali.hammf.cn/Article/details/gt2tzddgnke.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rifbxdhb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gt2cxaduanl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gt2cdnqdbix.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.dianchejie.cn/Article/details/gt2sbdyxyku.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gckwqycz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gt2dmiimtac.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gt2rhwytojz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gt2yubwisth.html

[D06] 数组长度
来源：http://dali.bjfxy.top/Article/details/gt2pqoxrngm.html

Py:   len(arr)
来源：http://dali.meibo888.top/Article/details/gt2mrsfacow.html

PHP:  count($arr);
来源：http://dali.guannengcc.top/Article/details/gt2jlaruthr.html

JS:   arr.length
来源：http://dali.cheryme.top/Article/details/gt2xrxnrsdz.html

TS:   arr.length
来源：http://dali.havefunace.top/Article/details/gt2ljmvxdsb.html

Java: list.size();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2avdcuccx.html

Go:   len(arr)
来源：http://dali.havefunace.top/Article/details/gt2dkhvmvct.html

Ruby: arr.length; arr.size
来源：http://dali.xinyue.icu/Article/details/gt2ksgwbmpg.html

C#:   list.Count;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fywmojrx.html

[D07] 切片 / 取子数组
来源：http://dali.yvedp.cn/Article/details/gt2xgentgvf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shangyingyoupin.top/Article/details/gt2joyhfeyp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fzhhl.top/Article/details/gt2yuqcwcjt.html

JS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gt2omvvepbz.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qkxbgkrj.html

Java: list.subList(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gt2kmvawujm.html

Go:   arr[1:4]
来源：http://dali.nwbrower.top/Article/details/gt2mrzmrumh.html

Ruby: arr[1, 3]
来源：http://dali.zhoulong.xyz/Article/details/gt2ygvukvhm.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj20258888.top/Article/details/gt2renxcbvn.html

[D08] 合并两个数组
来源：http://dali.hywenlv.cn/Article/details/gt2ebfvlprc.html

Py:   a + b;  a.extend(b)
来源：http://dali.9152youxi.cn/Article/details/gt2nkmpmzkd.html

PHP:  array_merge($a, $b);
来源：http://dali.dianchejie.cn/Article/details/gt2aavucvwl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dianchejie.cn/Article/details/gt2gwdfaslh.html

TS:   [...a, ...b];
来源：http://dali.gotoacloud.top/Article/details/gt2zcneseqh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2kekrypil.html

Go:   append(a, b...)
来源：http://dali.yanxiufei.cn/Article/details/gt2jskghohl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gaohongyu789.top/Article/details/gt2qmmldrvu.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2sbzoemqc.html

[D09] 排序（升序）
来源：http://dali.svipenyu.cn/Article/details/gt2imagwdtn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gt2gqzrpfie.html

PHP:  sort($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2qbxmmgpc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hfpthk.cn/Article/details/gt2bajvozhq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.svipenyu.cn/Article/details/gt2bvdxzopl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigufen.top/Article/details/gt2khuptdzz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gt2rpybikwu.html

Ruby: arr.sort
来源：http://dali.c1oappe.top/Article/details/gt2jbkcevls.html

C#:   list.Sort();
来源：http://dali.wangshuangyany.cn/Article/details/gt2shqggpsu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.guannengcc.top/Article/details/gt2ljstipxg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2ukdtwptx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenzaomai.com/Article/details/gt2ijztsxcl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gt2vbbdqrmz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gt2impmivqq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigfzy.top/Article/details/gt2xtzaacps.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gaohongyu789.top/Article/details/gt2lvorcpaf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gaohongyu789.top/Article/details/gt2vnokcfli.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhongyouzk.top/Article/details/gt2waheloit.html

[D11] 反转数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2relgefpv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.meibo888.top/Article/details/gt2cunaedjr.html

PHP:  array_reverse($arr);
来源：http://dali.xylfe.cn/Article/details/gt2xfoolowf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cqqwz.cn/Article/details/gt2dwpyrctg.html

TS:   [...arr].reverse();
来源：http://dali.dashuyun.cn/Article/details/gt2nuiqgqwn.html

Java: Collections.reverse(list);
来源：http://dali.gzhubu.top/Article/details/gt2gpntxykr.html

Go:   slices.Reverse(arr)
来源：http://dali.shuidangran.top/Article/details/gt2bxxdvfge.html

Ruby: arr.reverse
来源：http://dali.sweek.top/Article/details/gt2wkxfpsuv.html

C#:   list.Reverse();
来源：http://dali.guannengcc.top/Article/details/gt2qbzfnkud.html

[D12] 查找元素下标
来源：http://dali.wangdashe.top/Article/details/gt2fjdamdsz.html

Py:   arr.index(x);  x in arr
来源：http://dali.bjfxy.top/Article/details/gt2yrwpwmjw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cucudq.cn/Article/details/gt2mnjnhdbc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gt2zaqnroyf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gt2gldkcpjt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhoulong.xyz/Article/details/gt2pnakslcz.html

Go:   slices.Index(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2tssnckyk.html

Ruby: arr.index(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uwigixqw.html

C#:   list.IndexOf(x);
来源：http://dali.yonumen.top/Article/details/gt2alinvywn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xylfe.cn/Article/details/gt2xqzygbia.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhoulong.xyz/Article/details/gt2qkoagphl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.meibo888.top/Article/details/gt2fmewtghr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gt2mvgmpsdj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tian-w.cn/Article/details/gt2tmijadfj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2lmiksvdo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gogol.net.cn/Article/details/gt2tiiyjtoa.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kixiuwyq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2ibdjdegu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pycfn.com/Article/details/gt2fgafohzz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinqigfzy.top/Article/details/gt2hruifbmk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2gzcktgzv.html

JS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gt2rcwsjdwy.html

TS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gt2yqzkgdpb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2wgyrtptj.html

Go:   // 手写循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2odmijtjr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sysykeji.top/Article/details/gt2hjedzxkx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2tmhdcexc.html

[D15] 去重
来源：http://dali.hongshengwenyu.top/Article/details/gt2jiperpak.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenzaomai.com/Article/details/gt2ptdhlyph.html

PHP:  array_unique($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2secdaqwj.html

JS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gt2ypsuiiek.html

TS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gt2uhqpwzeh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aizwys.cn/Article/details/gt2mchuxwza.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hywenlv.cn/Article/details/gt2wbxydcyd.html

Ruby: arr.uniq
来源：http://dali.nanxuanxn.top/Article/details/gt2yfdvfgqe.html

C#:   list.Distinct().ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2nghjvtjx.html

[D16] 求和与平均值
来源：http://dali.jinqigfzy.top/Article/details/gt2fsfcbegr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2adsabpsh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2pjigywjy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2mkzbjnty.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2xhzumbdn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gt2grusrwef.html

Go:   // 手写循环累加
来源：http://dali.zhoulong.xyz/Article/details/gt2usnbytvc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.bjfxy.top/Article/details/gt2dvmieuni.html

C#:   list.Sum();  list.Average()
来源：http://dali.c1oappe.top/Article/details/gt2bbsnzklb.html

[D17] 最大值与最小值
来源：http://dali.hnxiangtu.top/Article/details/gt2vtertjie.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2yxucnaul.html

PHP:  max($arr);  min($arr);
来源：http://dali.sweek.top/Article/details/gt2gkkbnnkm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenzaomai.com/Article/details/gt2iviqxgpo.html

TS:   Math.max(...arr);
来源：http://dali.shzxlz.cn/Article/details/gt2zqhybseo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.redwolf501.top/Article/details/gt2spbqxxzc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj202588.top/Article/details/gt2suaidjhs.html

Ruby: arr.max;  arr.min
来源：http://dali.ydzc1.top/Article/details/gt2vopncgga.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mxhkdars.html

[D18] 扁平化嵌套数组
来源：http://dali.hywenlv.cn/Article/details/gt2dsycpyzc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.0kj1m.cn/Article/details/gt2mzicnkkj.html

PHP:  array_merge(...$nested);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kvrnbtpn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yangfankeji.com/Article/details/gt2igpskqtd.html

TS:   nested.flat();
来源：http://dali.snrcjt.cn/Article/details/gt2mpawthai.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenzaomai.com/Article/details/gt2zabcfyzp.html

Go:   // 手写双层循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2ztnlxobs.html

Ruby: nested.flatten
来源：http://dali.guannengcc.top/Article/details/gt2jdadhpng.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.mhx1999.top/Article/details/gt2yhbpxklc.html

[D19] 按字段分组
来源：http://dali.dianchejie.cn/Article/details/gt2aigtjkwz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guannengcc.top/Article/details/gt2avrztyny.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fzhhl.top/Article/details/gt2lezmtzdl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fzhhl.top/Article/details/gt2zvcuukqf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ydzc1.top/Article/details/gt2ixxxlsye.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sufxvd.cn/Article/details/gt2ocomhzpc.html

Go:   // 手写 map[string][]T
来源：http://dali.yanxiufei.cn/Article/details/gt2cedmuech.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kxvnncfg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zycfv.cn/Article/details/gt2mjbxaeym.html

[D20] 统计每个元素出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mkeypibx.html

Py:   Counter(arr)
来源：http://dali.shuidangran.top/Article/details/gt2gshgeyyx.html

PHP:  array_count_values($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2eithmnuq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gt2sldjjlfh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gt2alkpyysp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cqqwz.cn/Article/details/gt2ezqemgal.html

Go:   // 手写 map[T]int
来源：http://dali.tanke756.top/Article/details/gt2wowlvarl.html

Ruby: arr.tally
来源：http://dali.xuanzx.com/Article/details/gt2ytttlcky.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tian-w.cn/Article/details/gt2sbobamlq.html

[D21] 判断是否包含某元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cwqqllte.html

Py:   x in arr
来源：http://dali.hammf.cn/Article/details/gt2yxfacrut.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxinkj.top/Article/details/gt2esehbkfm.html

JS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gt2xdlihzyw.html

TS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2gykiiqbd.html

Java: list.contains(x)
来源：http://dali.ydzc1.top/Article/details/gt2hmgjjfcs.html

Go:   slices.Contains(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2mfuweziu.html

Ruby: arr.include?(x)
来源：http://dali.yj20258.top/Article/details/gt2sfyrrnka.html

C#:   list.Contains(x)
来源：http://dali.cdnleiting.top/Article/details/gt2biyvzisy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tanke756.top/Article/details/gt2lfapfibh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2ybkzujqg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuanzhike.top/Article/details/gt2fdmvyhyn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2ezghmqaf.html

TS:   [...arr];
来源：http://dali.aizwys.cn/Article/details/gt2ovkuowaw.html

Java: new ArrayList<>(list);
来源：http://dali.fzhhl.top/Article/details/gt2wqgbkyir.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuanzx.com/Article/details/gt2fnhabkvj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yongpay.top/Article/details/gt2ldwktxvc.html

C#:   new List<int>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ojjxbcyd.html

[D23] reduce 累积计算
来源：http://dali.cqqwz.cn/Article/details/gt2ohzvecgq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2nqgvusxe.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guannengcc.top/Article/details/gt2taekxula.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qfcwqexs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2xjnvtboi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nanxinkj.top/Article/details/gt2zokjxdnm.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gt2itgsfqnt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxinkj.top/Article/details/gt2hqywaqfs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.wangdashe.top/Article/details/gt2fukkorte.html

[D24] 字典 / Map 基本操作
来源：http://dali.ppjwa.cn/Article/details/gt2hmzmviuf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xylfe.cn/Article/details/gt2dxlksfjq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yongpay.top/Article/details/gt2oazjrvft.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2snhsjssl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2mgwajaqg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fengsongda.top/Article/details/gt2nofitcjx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.havefunace.top/Article/details/gt2kzwxhqfu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shzxlz.cn/Article/details/gt2brvxteen.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigufen.top/Article/details/gt2zftfytiy.html

[D25] Set 集合去重与交并差
来源：http://dali.ybcxt.top/Article/details/gt2aaefwmbf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sxryk.cn/Article/details/gt2oiawbweh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hongshengwenyu.top/Article/details/gt2opezwbxp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2apncjmmx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gt2jytiigvf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cheryme.top/Article/details/gt2zkzpubwl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigufen.top/Article/details/gt2bbfzljka.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daria6918.cn/Article/details/gt2nfdgavnc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2fabsrxtj.html

[D26] 数组转字符串
来源：http://dali.cdnleiting.top/Article/details/gt2dmkzuejt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fengsongda.top/Article/details/gt2vlgmkzvu.html

PHP:  implode(", ", $arr);
来源：http://dali.haohaochexian.top/Article/details/gt2xrrwrnbu.html

JS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gt2iovcdxjj.html

TS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gt2somursqf.html

Java: String.join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gt2ptgzeyyj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.svipenyu.cn/Article/details/gt2qdfsstqu.html

Ruby: arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gt2yisolhao.html

C#:   string.Join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cyzcinmh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2tkfodsxt.html

E. 字符串处理
来源：http://dali.chenlongwang.top/Article/details/gt2jbxmmson.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2mllqqlrx.html

[E01] 拼接字符串
来源：http://dali.shuidangran.top/Article/details/gt2gmoxohkr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daxiang520.top/Article/details/gt2dfpttwyt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fzhhl.top/Article/details/gt2opxdnzcz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yvedp.cn/Article/details/gt2niscrofa.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gt2mhffdvmk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yueranfly.top/Article/details/gt2egqkfqzv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cashguo.top/Article/details/gt2kslgubua.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.vqdsnc.cn/Article/details/gt2yafayhsa.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2ydbjjwtf.html

[E02] 重复字符串
来源：http://dali.ppjwa.cn/Article/details/gt2kngvtenn.html

Py:   "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gt2hymfhjcw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dianchejie.cn/Article/details/gt2brqhpowm.html

JS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wqydodbe.html

TS:   "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gt2uraqckip.html

Java: "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gt2dpeghsde.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbmlvuf.html

Ruby: "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gt2mdhtqzqn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangshuangyany.cn/Article/details/gt2eqpvutoz.html

[E03] 截取子串
来源：http://dali.bjfxy.top/Article/details/gt2fbmgukvx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.svipenyu.cn/Article/details/gt2nbwtvtil.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gt2ldhqehyn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gt2kozbqvst.html

TS:   s.slice(1, 4)
来源：http://dali.guannengcc.top/Article/details/gt2pfuaepww.html

Java: s.substring(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gt2glnktjfp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daria6918.cn/Article/details/gt2oahprtvk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eesdauro.html

C#:   s.Substring(1, 3)
来源：http://dali.sweek.top/Article/details/gt2mgjgqskv.html

[E04] 查找子串位置
来源：http://dali.jianghu66.top/Article/details/gt2uzkmkvvi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gt2wrwefjuo.html

PHP:  strpos($s, "x");
来源：http://dali.zhongyouzk.top/Article/details/gt2shuahyyz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gzhubu.top/Article/details/gt2eozlcomz.html

TS:   s.indexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gt2ylcvmmrj.html

Java: s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gt2zktxyolv.html

Go:   strings.Index(s, "x")
来源：http://dali.tian-w.cn/Article/details/gt2biuyfxuv.html

Ruby: s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gt2rwxgmwrv.html

C#:   s.IndexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gt2xlkcvgpq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigfzy.top/Article/details/gt2ypqdtaal.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yanxiufei.cn/Article/details/gt2agyitbzv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnxiangtu.top/Article/details/gt2nuwewxaa.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ixpsxeab.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2tffxsqyh.html


<!-- 参考信息 -->