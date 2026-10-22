代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.feifeiyinyue.top/Article/details/gt2ggwmwrdw.html

[C15] 解构 / 展开参数
来源：http://dali.jiagoushi.top/Article/details/gt2bacmhooj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxuanxn.top/Article/details/gt2ezunofrq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shzxlz.cn/Article/details/gt2tquzkwgk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gt2ylucsagn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dianchejie.cn/Article/details/gt2acwqsnqf.html

Java: // 无解构
来源：http://dali.cashguo.top/Article/details/gt2vjgfiqxt.html

Go:   // 无解构
来源：http://dali.yueranfly.top/Article/details/gt2lbzwlqaz.html

Ruby: a, b = pair
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lazjamya.html

C#:   var (a, b) = pair;
来源：http://dali.0kj1m.cn/Article/details/gt2gvzwvtez.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigfzy.top/Article/details/gt2jqmlmcyr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.svipenyu.cn/Article/details/gt2ufaydxnu.html

PHP:  // 无重载
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2grfvbktv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhiwuduotai.top/Article/details/gt2sssrrcau.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tian-w.cn/Article/details/gt2nlvzfpbs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgfzy.top/Article/details/gt2vikdvwwn.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinqigfzy.top/Article/details/gt2qtasnfiu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fqncnqac.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ybcxt.top/Article/details/gt2qhcrbcjx.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2fpfihjul.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2xptnlkqm.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ilesoexo.html

[D01] 创建数组 / 列表
来源：http://dali.zhiwuduotai.top/Article/details/gt2jhhihvhy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.kuanghao11.cn/Article/details/gt2gusbpzbo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.daria6918.cn/Article/details/gt2cpcefytp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj202588.top/Article/details/gt2fvtcwzjh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ydzc1.top/Article/details/gt2obhtisij.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ehwqpu.com/Article/details/gt2lnianbqc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ppjwa.cn/Article/details/gt2ditqajax.html

Ruby: arr = [1, 2, 3]
来源：http://dali.andypj.xyz/Article/details/gt2pcocrmxd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yrctxfng.html

[D02] 追加元素到末尾
来源：http://dali.zhixingplan.top/Article/details/gt2qlhjcfkd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.smart0.xyz/Article/details/gt2qdgjcxpt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ydzc1.top/Article/details/gt2ttqypegz.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gxrwixiv.html

TS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gt2shqenupe.html

Java: list.add(4);
来源：http://dali.tian-w.cn/Article/details/gt2qdevjtbj.html

Go:   arr = append(arr, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2devvzdln.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hfpthk.cn/Article/details/gt2byoyfilm.html

C#:   list.Add(4);
来源：http://dali.gogol.net.cn/Article/details/gt2ekhymkch.html

[D03] 在指定位置插入元素
来源：http://dali.ppjwa.cn/Article/details/gt2xpbawrpo.html

Py:   arr.insert(0, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2mrgnsqll.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xvlwpkye.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.svipenyu.cn/Article/details/gt2eggntkmb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gzhubu.top/Article/details/gt2mreuazvs.html

Java: list.add(0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2mpaultnz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnxiangtu.top/Article/details/gt2rskqirkk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tianlin.xyz/Article/details/gt2wcyprnvp.html

C#:   list.Insert(0, 0);
来源：http://dali.yvedp.cn/Article/details/gt2kmenpact.html

[D04] 删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2nkwniaox.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gaohongyu789.top/Article/details/gt2wrnczklm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2cyrrrusw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgufenzy.top/Article/details/gt2yqhhwnyt.html

TS:   arr.splice(0, 1);
来源：http://dali.yonumen.top/Article/details/gt2fwsfsttb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tian-w.cn/Article/details/gt2tqsvypyz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuanzhike.top/Article/details/gt2wwpgqzwb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ybcxt.top/Article/details/gt2hzohqdwi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhongyouzk.top/Article/details/gt2fozydznr.html

[D05] 访问与修改元素
来源：http://dali.hammf.cn/Article/details/gt2yxvppwdb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gt2yklcdjji.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gt2rccejjqv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gt2qfugcnkk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ivvv.top/Article/details/gt2fyzexeqp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jiagoushi.top/Article/details/gt2dghisfpf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gt2ahgyyffi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gt2kwmuzpaa.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gt2dflhpspj.html

[D06] 数组长度
来源：http://dali.sxryk.cn/Article/details/gt2fgehiecv.html

Py:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2whxrdfkl.html

PHP:  count($arr);
来源：http://dali.aizwys.cn/Article/details/gt2bohuikss.html

JS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gt2nquodxqu.html

TS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gt2dofrktgd.html

Java: list.size();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kekqqbvg.html

Go:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sdwqarso.html

Ruby: arr.length; arr.size
来源：http://dali.sufxvd.cn/Article/details/gt2hafgzokn.html

C#:   list.Count;
来源：http://dali.tianlin.xyz/Article/details/gt2tqrrmuly.html

[D07] 切片 / 取子数组
来源：http://dali.hysaishi.cn/Article/details/gt2pbyplwkg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.mhx1999.top/Article/details/gt2nkjfcqbr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.bjfxy.top/Article/details/gt2znamjiiu.html

JS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gt2uftihhzz.html

TS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gt2laozvbtk.html

Java: list.subList(1, 4);
来源：http://dali.ybcxt.top/Article/details/gt2uuogeyru.html

Go:   arr[1:4]
来源：http://dali.yj202588.top/Article/details/gt2jyuordcn.html

Ruby: arr[1, 3]
来源：http://dali.cqqwz.cn/Article/details/gt2bbipsumv.html

C#:   list.GetRange(1, 3);
来源：http://dali.316326.xyz/Article/details/gt2oxpvfjoa.html

[D08] 合并两个数组
来源：http://dali.xziqi.cn/Article/details/gt2qlzaojdz.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ydhsnprb.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258888.top/Article/details/gt2smxwutch.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.meibo888.top/Article/details/gt2uqbdfrcy.html

TS:   [...a, ...b];
来源：http://dali.snrcjt.cn/Article/details/gt2yokthzxr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.bjfxy.top/Article/details/gt2nzqmjsch.html

Go:   append(a, b...)
来源：http://dali.yueranfly.top/Article/details/gt2ifpnqtei.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zvmgchsf.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ajggxhfj.html

[D09] 排序（升序）
来源：http://dali.kuanghao11.cn/Article/details/gt2qmeafyzr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gt2gurfcwps.html

PHP:  sort($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2rypfpwqy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.vqdsnc.cn/Article/details/gt2fruhcdvn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.316326.xyz/Article/details/gt2pfdxujgd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.kuanghao11.cn/Article/details/gt2nztwjkdq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2ftvrpfgj.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gt2oxihsmuy.html

C#:   list.Sort();
来源：http://dali.cheryme.top/Article/details/gt2vvpkulmd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2llfaqbbc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgfzy.top/Article/details/gt2ltrppzsm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sweek.top/Article/details/gt2kwueovdn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgfzy.top/Article/details/gt2jhzlnkbi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gt2tywfdjse.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hysaishi.cn/Article/details/gt2tvbghcqo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dashuyun.cn/Article/details/gt2wroybbzp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.daria6918.cn/Article/details/gt2fnsmfoia.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.havefunace.top/Article/details/gt2foxeqozr.html

[D11] 反转数组
来源：http://dali.daria6918.cn/Article/details/gt2cjpzlzpn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xylfe.cn/Article/details/gt2qwjcvkqe.html

PHP:  array_reverse($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2galodwzr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.haohaochexian.top/Article/details/gt2xhraccwf.html

TS:   [...arr].reverse();
来源：http://dali.chenzaomai.com/Article/details/gt2nsliiuri.html

Java: Collections.reverse(list);
来源：http://dali.c1oappe.top/Article/details/gt2rwfufrws.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2qwateviz.html

Ruby: arr.reverse
来源：http://dali.yanxiufei.cn/Article/details/gt2qsajaxnr.html

C#:   list.Reverse();
来源：http://dali.nanxinkj.top/Article/details/gt2bducpdec.html

[D12] 查找元素下标
来源：http://dali.svipenyu.cn/Article/details/gt2qqdoysck.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhixingplan.top/Article/details/gt2ltoxvypo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ybcxt.top/Article/details/gt2czadawhn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gt2utclhsfr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gt2xnwqhgpo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rwbprcyg.html

Go:   slices.Index(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kqzruerh.html

Ruby: arr.index(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2yykhkqgh.html

C#:   list.IndexOf(x);
来源：http://dali.ivvv.top/Article/details/gt2xmdkqovg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.haohaochexian.top/Article/details/gt2xsllwzmo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tanke756.top/Article/details/gt2dzlkzlfr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hfpthk.cn/Article/details/gt2smjfwzaa.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zjajjyiq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gkcgwcsv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhixingplan.top/Article/details/gt2frmzzwlv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangdashe.top/Article/details/gt2lapmkjhy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zycfv.cn/Article/details/gt2gyaigkye.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2trsxmiid.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ppjwa.cn/Article/details/gt2ppxzxhko.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.mhx1999.top/Article/details/gt2cagdidzu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dashuyun.cn/Article/details/gt2hofoamdb.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gt2wyunuxhm.html

TS:   arr.map(x => x * 2)
来源：http://dali.birdmap.top/Article/details/gt2plcsarog.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuanzx.com/Article/details/gt2uasrkevf.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gt2jpmnbxuq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.c1oappe.top/Article/details/gt2fosgxxil.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.316326.xyz/Article/details/gt2xnrwhkzo.html

[D15] 去重
来源：http://dali.cheryme.top/Article/details/gt2aopaxvyn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuetiantiany.cn/Article/details/gt2tixwkrpq.html

PHP:  array_unique($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2dmornywf.html

JS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gt2vqhycnve.html

TS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gt2fpbwoglr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.daxiang520.top/Article/details/gt2psrvgkem.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fengsongda.top/Article/details/gt2tnidjcym.html

Ruby: arr.uniq
来源：http://dali.zhoulong.xyz/Article/details/gt2cubzwgvb.html

C#:   list.Distinct().ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2opcnjcoh.html

[D16] 求和与平均值
来源：http://dali.daria6918.cn/Article/details/gt2kjugnblh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2svfvperv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2vvocupgy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2imhugqje.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gt2kxcwqggx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ybusyigz.html

Go:   // 手写循环累加
来源：http://dali.andypj.xyz/Article/details/gt2ecbegvvw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.snrcjt.cn/Article/details/gt2bjfwctpq.html

C#:   list.Sum();  list.Average()
来源：http://dali.cashguo.top/Article/details/gt2knzxergv.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pmunxrkv.html

Py:   max(arr);  min(arr)
来源：http://dali.ydzc1.top/Article/details/gt2cobtzfur.html

PHP:  max($arr);  min($arr);
来源：http://dali.cheryme.top/Article/details/gt2rvmnmfue.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yangfankeji.com/Article/details/gt2ahtugfvj.html

TS:   Math.max(...arr);
来源：http://dali.sufxvd.cn/Article/details/gt2axkrhvmk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.kuanghao11.cn/Article/details/gt2lcvzsync.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2kngmxbze.html

Ruby: arr.max;  arr.min
来源：http://dali.tanke756.top/Article/details/gt2glxgbvfz.html

C#:   list.Max();  list.Min()
来源：http://dali.0kj1m.cn/Article/details/gt2zaswcguw.html

[D18] 扁平化嵌套数组
来源：http://dali.chenzaomai.com/Article/details/gt2aonrotgg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuanzx.com/Article/details/gt2cpbembcf.html

PHP:  array_merge(...$nested);
来源：http://dali.0kj1m.cn/Article/details/gt2hnynktax.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj202588.top/Article/details/gt2jtlftigw.html

TS:   nested.flat();
来源：http://dali.sysykeji.top/Article/details/gt2uujijgpz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.fzhhl.top/Article/details/gt2vnyxnqfu.html

Go:   // 手写双层循环
来源：http://dali.yueranfly.top/Article/details/gt2bhpygstc.html

Ruby: nested.flatten
来源：http://dali.xuetiantiany.cn/Article/details/gt2phikxotk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2hzkjuaff.html

[D19] 按字段分组
来源：http://dali.guowangkeji.top/Article/details/gt2exsibowt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yueranfly.top/Article/details/gt2wqxfkyfp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgfzy.top/Article/details/gt2mduefasq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzhvoma.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jqgfzy.top/Article/details/gt2prdvnhmd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yongpay.top/Article/details/gt2cdetrmsm.html

Go:   // 手写 map[string][]T
来源：http://dali.ppjwa.cn/Article/details/gt2zbjdsmmb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgfzy.top/Article/details/gt2ezwwfptc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.smart0.xyz/Article/details/gt2tdtdfgdt.html

[D20] 统计每个元素出现次数
来源：http://dali.gogol.net.cn/Article/details/gt2qxindkdq.html

Py:   Counter(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2kkemoebr.html

PHP:  array_count_values($arr);
来源：http://dali.andypj.xyz/Article/details/gt2swijwzap.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gt2hxzlzadi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gt2lwmypgcu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ydzc1.top/Article/details/gt2rcamljch.html

Go:   // 手写 map[T]int
来源：http://dali.jlsjyb.cn/Article/details/gt2opooatdn.html

Ruby: arr.tally
来源：http://dali.yonumen.top/Article/details/gt2vvnvzbmd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.316326.xyz/Article/details/gt2hsewrmug.html

[D21] 判断是否包含某元素
来源：http://dali.xziqi.cn/Article/details/gt2lhladnxk.html

Py:   x in arr
来源：http://dali.0kj1m.cn/Article/details/gt2bcjgievv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.havefunace.top/Article/details/gt2gnxychgg.html

JS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gt2sydbrlbk.html

TS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gt2kjdeeoqx.html

Java: list.contains(x)
来源：http://dali.daria6918.cn/Article/details/gt2xgfekrmb.html

Go:   slices.Contains(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2pfbiuexs.html

Ruby: arr.include?(x)
来源：http://dali.hnqzz.top/Article/details/gt2ljlnbpkw.html

C#:   list.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gt2jvhbedbm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yanxiufei.cn/Article/details/gt2nhgzzatb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.meibo888.top/Article/details/gt2geqrbctc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cashguo.top/Article/details/gt2hfydqxer.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yonumen.top/Article/details/gt2wfrxzugd.html

TS:   [...arr];
来源：http://dali.daxiang520.top/Article/details/gt2vlnpifqu.html

Java: new ArrayList<>(list);
来源：http://dali.aibaodan.cn/Article/details/gt2bctttlgn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xvmrhdsn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tian-w.cn/Article/details/gt2etgsjwuv.html

C#:   new List<int>(list);
来源：http://dali.chenlongwang.top/Article/details/gt2znsqegbc.html

[D23] reduce 累积计算
来源：http://dali.jinghuilouyu.cn/Article/details/gt2quyyqxag.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2swrbmfav.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sufxvd.cn/Article/details/gt2cquiriib.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gt2juqvvues.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2crfsfyna.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jyoumei.cn/Article/details/gt2elpkeade.html

Go:   // 手写循环
来源：http://dali.cdnleiting.top/Article/details/gt2vrcrkkso.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nqcedsjq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xziqi.cn/Article/details/gt2ggmzawhm.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenzaomai.com/Article/details/gt2hvjjyazx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jnfcgnvn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xylfe.cn/Article/details/gt2gpyyvxdr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2koscasus.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dqkejnqg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gotoacloud.top/Article/details/gt2sxhqmfhn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vxsnqyws.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yonumen.top/Article/details/gt2ljkjlmtz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhiwuduotai.top/Article/details/gt2sgjbioec.html

[D25] Set 集合去重与交并差
来源：http://dali.ybcxt.top/Article/details/gt2puxtclbe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.quarkkingdee.top/Article/details/gt2fuxpvlxl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.meibo888.top/Article/details/gt2mfhwjrvq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258.top/Article/details/gt2qlimvzoy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.iojbl.cn/Article/details/gt2qsldmice.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aizwys.cn/Article/details/gt2aqsqdosa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hfpthk.cn/Article/details/gt2joztixbz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sweek.top/Article/details/gt2jzfnsyex.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guowangkeji.top/Article/details/gt2bgajspmw.html

[D26] 数组转字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2alkfiixa.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2yxikxvch.html

PHP:  implode(", ", $arr);
来源：http://dali.yj202588.top/Article/details/gt2ktbmatsj.html

JS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2vbqjxrzt.html

TS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gt2bcvzljul.html

Java: String.join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gt2xuqqnfqh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guowangkeji.top/Article/details/gt2hltwziub.html

Ruby: arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gt2vjktdywo.html

C#:   string.Join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gt2waltupgz.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2epvjrcdp.html

E. 字符串处理
来源：http://dali.cqqwz.cn/Article/details/gt2zyotzijj.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2hnmrgdml.html

[E01] 拼接字符串
来源：http://dali.ybcxt.top/Article/details/gt2ftadiebw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj202588.top/Article/details/gt2owubgrkq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.9152youxi.cn/Article/details/gt2fmggbyil.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sweek.top/Article/details/gt2vdiwzalv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gt2bfoheirt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xinyue.icu/Article/details/gt2vsshxiom.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zycfv.cn/Article/details/gt2xviuzaex.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.mhx1999.top/Article/details/gt2ubbksxsc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2ogouhtup.html

[E02] 重复字符串
来源：http://dali.wangdashe.top/Article/details/gt2armlralu.html

Py:   "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aneubhvz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangdashe.top/Article/details/gt2vpzngjsc.html

JS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gt2meeyfvjk.html

TS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gt2ffnlvmde.html

Java: "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gt2sazbdjye.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.vqdsnc.cn/Article/details/gt2teuwwbve.html

Ruby: "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gt2fcndyojg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gzhubu.top/Article/details/gt2byrpzlwv.html

[E03] 截取子串
来源：http://dali.tian-w.cn/Article/details/gt2uidzqiyi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tanke756.top/Article/details/gt2mxjctxsq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gt2gjuehskn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.smart0.xyz/Article/details/gt2zwzwwsjc.html

TS:   s.slice(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gt2blclfmfr.html

Java: s.substring(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gt2pxhtehlk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gt2yjpejxmk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fengsongda.top/Article/details/gt2rfikyvna.html

C#:   s.Substring(1, 3)
来源：http://dali.guowangkeji.top/Article/details/gt2dguqexkm.html

[E04] 查找子串位置
来源：http://dali.gaohongyu789.top/Article/details/gt2rndgvfnv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qsrofudq.html

PHP:  strpos($s, "x");
来源：http://dali.xylfe.cn/Article/details/gt2mstbwcfa.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yangfankeji.com/Article/details/gt2ypoouixd.html

TS:   s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gt2fecazvah.html

Java: s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2euuduchl.html

Go:   strings.Index(s, "x")
来源：http://dali.jinqigufen.top/Article/details/gt2kjhpkltz.html

Ruby: s.index("x")
来源：http://dali.sweek.top/Article/details/gt2stdmdcjv.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gt2ayfiuosk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nwbrower.top/Article/details/gt2jlytmgte.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangdashe.top/Article/details/gt2rmrshxxn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyetvlr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gt2nxkytlxp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gaohongyu789.top/Article/details/gt2zhvruezo.html


<!-- 参考信息 -->