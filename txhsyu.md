代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nwbrower.top/Article/details/gt2mcbigkop.html

[C15] 解构 / 展开参数
来源：http://dali.jyoumei.cn/Article/details/gt2mahhlxxc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.c1oappe.top/Article/details/gt2uulyisyq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhongyouzk.top/Article/details/gt2zoicngzx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fzhhl.top/Article/details/gt2seqljtyd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cucudq.cn/Article/details/gt2jxbvyijs.html

Java: // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gt2rmqeugou.html

Go:   // 无解构
来源：http://dali.yangfankeji.com/Article/details/gt2ultzslyn.html

Ruby: a, b = pair
来源：http://dali.hysaishi.cn/Article/details/gt2akotsxkw.html

C#:   var (a, b) = pair;
来源：http://dali.cheryme.top/Article/details/gt2uosevnpx.html

[C16] 函数 / 方法重载
来源：http://dali.shuidangran.top/Article/details/gt2flwzsyor.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.redwolf501.top/Article/details/gt2muaudiga.html

PHP:  // 无重载
来源：http://dali.xziqi.cn/Article/details/gt2taijicpo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yanxiufei.cn/Article/details/gt2tpkmzrmv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sufxvd.cn/Article/details/gt2fjngdlbx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.c1oappe.top/Article/details/gt2brcaleou.html

Go:   // 无重载：用不同函数名
来源：http://dali.sweek.top/Article/details/gt2cxxrwuyo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dashuyun.cn/Article/details/gt2htbvwsie.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sufxvd.cn/Article/details/gt2fdknyaqb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2nappqmpg.html

D. 数组 / 列表 / 集合
来源：http://dali.zhengqikj.top/Article/details/gt2facjypub.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2fmwenimk.html

[D01] 创建数组 / 列表
来源：http://dali.sxryk.cn/Article/details/gt2adnbkkom.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhiwuduotai.top/Article/details/gt2eypiqwqa.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gt2qnctclzi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zycfv.cn/Article/details/gt2zqcskwmz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shuidangran.top/Article/details/gt2rnemwnip.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.meibo888.top/Article/details/gt2twyxadss.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangdashe.top/Article/details/gt2wbgkcoml.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jqgufenzy.top/Article/details/gt2jpplybol.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yuxming.cn/Article/details/gt2osthnozv.html

[D02] 追加元素到末尾
来源：http://dali.hnqzz.top/Article/details/gt2wchabhji.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pengpengdd.cyou/Article/details/gt2nwqlvofp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yueranfly.top/Article/details/gt2rndxuauz.html

JS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gt2rtgzxtpf.html

TS:   arr.push(4);
来源：http://dali.sufxvd.cn/Article/details/gt2bnwokqdw.html

Java: list.add(4);
来源：http://dali.svipenyu.cn/Article/details/gt2zszdhyni.html

Go:   arr = append(arr, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jlyfxcba.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.iojbl.cn/Article/details/gt2cpyxyxef.html

C#:   list.Add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2jnehywzn.html

[D03] 在指定位置插入元素
来源：http://dali.jlsjyb.cn/Article/details/gt2hwgeejtx.html

Py:   arr.insert(0, 0)
来源：http://dali.xylfe.cn/Article/details/gt2pscawpbr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xylfe.cn/Article/details/gt2qgzeczvz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258.top/Article/details/gt2godjspdr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2tabajxqf.html

Java: list.add(0, 0);
来源：http://dali.ydzc1.top/Article/details/gt2nbczziuj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cheryme.top/Article/details/gt2ezpxhhgk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hammf.cn/Article/details/gt2okjscizq.html

C#:   list.Insert(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gt2htxsokof.html

[D04] 删除元素
来源：http://dali.c1oappe.top/Article/details/gt2wcavbzri.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sufxvd.cn/Article/details/gt2fvbmtqvz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.birdmap.top/Article/details/gt2bpzpystm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gogol.net.cn/Article/details/gt2amazgwcg.html

TS:   arr.splice(0, 1);
来源：http://dali.cashguo.top/Article/details/gt2kncormav.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sufxvd.cn/Article/details/gt2xrqmqpmy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xylfe.cn/Article/details/gt2qabfdbee.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hmywiqdt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhengqikj.top/Article/details/gt2bejkqfau.html

[D05] 访问与修改元素
来源：http://dali.zhengqikj.top/Article/details/gt2dagfkkfe.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gt2obghtizj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gt2crosxedi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gt2rkdxanxk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.vqdsnc.cn/Article/details/gt2ikxuiist.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqmrrcmt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gt2iipxjwqy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gt2jzhkmfeo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2umnjvrwv.html

[D06] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gt2gqngmcui.html

Py:   len(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2vwtbdoyt.html

PHP:  count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vlgactoq.html

JS:   arr.length
来源：http://dali.sufxvd.cn/Article/details/gt2lgrxjewq.html

TS:   arr.length
来源：http://dali.zhoulong.xyz/Article/details/gt2opsdmebs.html

Java: list.size();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rsxmspqh.html

Go:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2itrrwhaj.html

Ruby: arr.length; arr.size
来源：http://dali.tanke756.top/Article/details/gt2xchqebno.html

C#:   list.Count;
来源：http://dali.hongshengwenyu.top/Article/details/gt2pxdxuvec.html

[D07] 切片 / 取子数组
来源：http://dali.yuanzhike.top/Article/details/gt2sfiisteh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.c1oappe.top/Article/details/gt2yxthilkc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2vjhuvxzi.html

JS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xgyqdabe.html

TS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gt2esitnxqz.html

Java: list.subList(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mutnwrpj.html

Go:   arr[1:4]
来源：http://dali.ydzc1.top/Article/details/gt2detralea.html

Ruby: arr[1, 3]
来源：http://dali.gotoacloud.top/Article/details/gt2aqroyoyu.html

C#:   list.GetRange(1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2tnfveyop.html

[D08] 合并两个数组
来源：http://dali.316326.xyz/Article/details/gt2sabhbjjy.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnxiangtu.top/Article/details/gt2sktlorkj.html

PHP:  array_merge($a, $b);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mcxuaoot.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.bjfxy.top/Article/details/gt2vzalrttx.html

TS:   [...a, ...b];
来源：http://dali.chenjidiqi.icu/Article/details/gt2ujbtqxlt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shuidangran.top/Article/details/gt2vocbvzuz.html

Go:   append(a, b...)
来源：http://dali.havefunace.top/Article/details/gt2ktpkcrwy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.snrcjt.cn/Article/details/gt2iaimjacm.html

C#:   a.Concat(b).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2inzxqslz.html

[D09] 排序（升序）
来源：http://dali.mhx1999.top/Article/details/gt2dhpnzoxl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gt2jiefjdoi.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gt2rakacheo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sxryk.cn/Article/details/gt2qqcsdkbt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.wangdashe.top/Article/details/gt2irdakrqx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daxiang520.top/Article/details/gt2caxwyykl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bdljdcjz.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gt2igbiakrk.html

C#:   list.Sort();
来源：http://dali.gogol.net.cn/Article/details/gt2awkiieof.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dashuyun.cn/Article/details/gt2xqcqxcvz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xinyue.icu/Article/details/gt2qghkmcfa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aizwys.cn/Article/details/gt2vvgoivbg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gt2hocxkibl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gt2ucsfgngw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qgwtdnur.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangshuangyany.cn/Article/details/gt2hygiexyj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yanxiufei.cn/Article/details/gt2atarbked.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fzhhl.top/Article/details/gt2lgcwewdy.html

[D11] 反转数组
来源：http://dali.yanxiufei.cn/Article/details/gt2hlrvbafo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.c1oappe.top/Article/details/gt2euhgugxh.html

PHP:  array_reverse($arr);
来源：http://dali.xinyue.icu/Article/details/gt2rhsfduus.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fengsongda.top/Article/details/gt2fefmvcxr.html

TS:   [...arr].reverse();
来源：http://dali.yangfankeji.com/Article/details/gt2pbdkrage.html

Java: Collections.reverse(list);
来源：http://dali.vqdsnc.cn/Article/details/gt2zgkaxaly.html

Go:   slices.Reverse(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctakwrcv.html

Ruby: arr.reverse
来源：http://dali.0kj1m.cn/Article/details/gt2ucyjabgd.html

C#:   list.Reverse();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2giomxaev.html

[D12] 查找元素下标
来源：http://dali.cdnleiting.top/Article/details/gt2nptxqkvs.html

Py:   arr.index(x);  x in arr
来源：http://dali.jyoumei.cn/Article/details/gt2orlpqtvd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hfpthk.cn/Article/details/gt2qqynuhgz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vwqaoygq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gt2cbmdetlx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tanke756.top/Article/details/gt2wvthhpqy.html

Go:   slices.Index(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jcirmmaz.html

Ruby: arr.index(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qjedflqw.html

C#:   list.IndexOf(x);
来源：http://dali.sysykeji.top/Article/details/gt2zsefstqi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gogol.net.cn/Article/details/gt2nsmjzcrc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cbdmmirf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hywenlv.cn/Article/details/gt2yhinupuq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gt2qwxsnumz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gt2lnypbefx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tanke756.top/Article/details/gt2krujsyzi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jlsjyb.cn/Article/details/gt2cyerwsbt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ufazmdrw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2uwjybyvt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.0kj1m.cn/Article/details/gt2lefvgwwm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aizwys.cn/Article/details/gt2thsaskpg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xziqi.cn/Article/details/gt2axpxblsg.html

JS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gt2raccdyym.html

TS:   arr.map(x => x * 2)
来源：http://dali.tian-w.cn/Article/details/gt2edythbbu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2dathoalp.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gt2fmbrpaxo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nwbrower.top/Article/details/gt2xhftmyyg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2cjkceygt.html

[D15] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vuamfusd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gt2ltkvseml.html

PHP:  array_unique($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2rgvqyrvf.html

JS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gt2heeegexa.html

TS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gt2ikkvihap.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hongshengwenyu.top/Article/details/gt2qwgohkxt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xuanzx.com/Article/details/gt2yekayvih.html

Ruby: arr.uniq
来源：http://dali.sweek.top/Article/details/gt2lstzsrzk.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2skannyan.html

[D16] 求和与平均值
来源：http://dali.shzxlz.cn/Article/details/gt2hsbzeyzu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.iojbl.cn/Article/details/gt2opoumsul.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2mavliusn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2zqfxyawz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangdashe.top/Article/details/gt2kjdtqylk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.feifeiyinyue.top/Article/details/gt2iivcakro.html

Go:   // 手写循环累加
来源：http://dali.yj20258.top/Article/details/gt2sjqlrvwq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gt2effcfjxy.html

C#:   list.Sum();  list.Average()
来源：http://dali.cashguo.top/Article/details/gt2uxmwlmil.html

[D17] 最大值与最小值
来源：http://dali.chenzaomai.com/Article/details/gt2roltrumk.html

Py:   max(arr);  min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ugphthuk.html

PHP:  max($arr);  min($arr);
来源：http://dali.guannengcc.top/Article/details/gt2diavlybu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2izcsrcbk.html

TS:   Math.max(...arr);
来源：http://dali.yueranfly.top/Article/details/gt2qipwqxap.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2zgtonehw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2jcfusgmw.html

Ruby: arr.max;  arr.min
来源：http://dali.9152youxi.cn/Article/details/gt2qsrxwolz.html

C#:   list.Max();  list.Min()
来源：http://dali.gaohongyu789.top/Article/details/gt2fqwyvciz.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigfzy.top/Article/details/gt2vkacbgia.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.bjfxy.top/Article/details/gt2uxxflxjv.html

PHP:  array_merge(...$nested);
来源：http://dali.fengsongda.top/Article/details/gt2ioxnkmkw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sufxvd.cn/Article/details/gt2xlhbpyxl.html

TS:   nested.flat();
来源：http://dali.tian-w.cn/Article/details/gt2vunmweun.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gzhubu.top/Article/details/gt2ccfnuykv.html

Go:   // 手写双层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cbrufssi.html

Ruby: nested.flatten
来源：http://dali.sufxvd.cn/Article/details/gt2jtwbewyn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sysykeji.top/Article/details/gt2xyraaxcs.html

[D19] 按字段分组
来源：http://dali.xuanzx.com/Article/details/gt2hhqodvca.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hkcquuar.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wtxnalgm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.snrcjt.cn/Article/details/gt2yvgiwpur.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yanxiufei.cn/Article/details/gt2iyudqmjj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tian-w.cn/Article/details/gt2lgwwkhuk.html

Go:   // 手写 map[string][]T
来源：http://dali.gaohongyu789.top/Article/details/gt2mcruchfx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.quarkkingdee.top/Article/details/gt2bwxhccrp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.meibo888.top/Article/details/gt2tpifzrbk.html

[D20] 统计每个元素出现次数
来源：http://dali.smart0.xyz/Article/details/gt2euxjtnzp.html

Py:   Counter(arr)
来源：http://dali.jianghu66.top/Article/details/gt2bhehdcyy.html

PHP:  array_count_values($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2inqwvwae.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gt2cpjxulzp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gt2otahffwp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shuidangran.top/Article/details/gt2fsqdnbod.html

Go:   // 手写 map[T]int
来源：http://dali.smart0.xyz/Article/details/gt2wyijrhsp.html

Ruby: arr.tally
来源：http://dali.hywenlv.cn/Article/details/gt2umgfnuuu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aibaodan.cn/Article/details/gt2wwdmlfyc.html

[D21] 判断是否包含某元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2hqkhsyky.html

Py:   x in arr
来源：http://dali.svipenyu.cn/Article/details/gt2yvarvjia.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yvedp.cn/Article/details/gt2chtvondi.html

JS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gt2wazxlijf.html

TS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gt2hegskyzl.html

Java: list.contains(x)
来源：http://dali.ehwqpu.com/Article/details/gt2ixrrvppc.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fsmkomhn.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hsapmobh.html

C#:   list.Contains(x)
来源：http://dali.xinyue.icu/Article/details/gt2svtngemn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgfzy.top/Article/details/gt2kavbkueb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2vgxcwqwf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj202588.top/Article/details/gt2xbxpbfiw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2tctiiupn.html

TS:   [...arr];
来源：http://dali.jinqigufen.top/Article/details/gt2jxbemdjc.html

Java: new ArrayList<>(list);
来源：http://dali.yueranfly.top/Article/details/gt2tuxukyiz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhixingplan.top/Article/details/gt2ueshzlnk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pycfn.com/Article/details/gt2ybvuvyck.html

C#:   new List<int>(list);
来源：http://dali.smart0.xyz/Article/details/gt2fobdxhdh.html

[D23] reduce 累积计算
来源：http://dali.316326.xyz/Article/details/gt2zmzmuyfp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2cntitzrq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dashuyun.cn/Article/details/gt2tzbvpjbb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2ikmupxik.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gt2chsqvgyh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigfzy.top/Article/details/gt2mefubago.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbobxdmt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shzxlz.cn/Article/details/gt2tzxjsiou.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sdhssxbq.html

[D24] 字典 / Map 基本操作
来源：http://dali.tanke756.top/Article/details/gt2slyvwvxn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sysykeji.top/Article/details/gt2gldhcxpu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hammf.cn/Article/details/gt2oohevzyr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ifpdzcxy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2rwqjbfpu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258888.top/Article/details/gt2hoxovyzm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rkdampcb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258.top/Article/details/gt2uxinkqxg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.dianchejie.cn/Article/details/gt2cokfolhx.html

[D25] Set 集合去重与交并差
来源：http://dali.snrcjt.cn/Article/details/gt2drkuecuh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fengsongda.top/Article/details/gt2fehxhbnf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zycfv.cn/Article/details/gt2mrduiuvl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nvkydnix.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhoulong.xyz/Article/details/gt2mvqgdxps.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daxiang520.top/Article/details/gt2lpsvlcar.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shangyingyoupin.top/Article/details/gt2clhpacwz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ydzc1.top/Article/details/gt2uhkvnwdo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daria6918.cn/Article/details/gt2tmyonlyl.html

[D26] 数组转字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2ypebghes.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aizwys.cn/Article/details/gt2hbgfisxf.html

PHP:  implode(", ", $arr);
来源：http://dali.cashguo.top/Article/details/gt2gtczpslz.html

JS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gt2gwkqsiah.html

TS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gt2owxrkpaf.html

Java: String.join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gt2oghojoxa.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ehwqpu.com/Article/details/gt2orxdwsbg.html

Ruby: arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gt2bcglsetl.html

C#:   string.Join(", ", list)
来源：http://dali.yj20258.top/Article/details/gt2vhiwixoy.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2xqbticdv.html

E. 字符串处理
来源：http://dali.wangdashe.top/Article/details/gt2lbauxudh.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2miulhnmd.html

[E01] 拼接字符串
来源：http://dali.xylfe.cn/Article/details/gt2uoujnjwz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sxryk.cn/Article/details/gt2mdkahitl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cucudq.cn/Article/details/gt2rqdmhcgf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gt2fzshmeuo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2kejcssig.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hammf.cn/Article/details/gt2vmbqpror.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuanzhike.top/Article/details/gt2xqgnajds.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daria6918.cn/Article/details/gt2ipztocjd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2qjlibxnv.html

[E02] 重复字符串
来源：http://dali.nanxinkj.top/Article/details/gt2awgxjqto.html

Py:   "ab" * 3
来源：http://dali.tian-w.cn/Article/details/gt2dboqpola.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2kfaqtekj.html

JS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gt2gnzntbki.html

TS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gt2ifdmhtui.html

Java: "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gdohyhct.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nanxinkj.top/Article/details/gt2nheykysl.html

Ruby: "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gt2hcmrlhsh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.smart0.xyz/Article/details/gt2tbjytkiq.html

[E03] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbvrdhbq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gogol.net.cn/Article/details/gt2esegmgdj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2lgtvklwd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2syiwqgib.html

TS:   s.slice(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gt2himeopfs.html

Java: s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gt2rzvdjfhe.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kbuveuve.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ydzc1.top/Article/details/gt2yvcqylbg.html

C#:   s.Substring(1, 3)
来源：http://dali.zdqjudy.top/Article/details/gt2khesjady.html

[E04] 查找子串位置
来源：http://dali.nwbrower.top/Article/details/gt2vofexgjb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xylfe.cn/Article/details/gt2fismwfqa.html

PHP:  strpos($s, "x");
来源：http://dali.yj20258.top/Article/details/gt2dslkdxxg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sufxvd.cn/Article/details/gt2daasacyv.html

TS:   s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gt2pjgpehlp.html

Java: s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gt2mkcixoza.html

Go:   strings.Index(s, "x")
来源：http://dali.guowangkeji.top/Article/details/gt2zqyollet.html

Ruby: s.index("x")
来源：http://dali.316326.xyz/Article/details/gt2ykilftfp.html

C#:   s.IndexOf("x")
来源：http://dali.xuanzx.com/Article/details/gt2hankcsfs.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.birdmap.top/Article/details/gt2kjykpcqf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ppjwa.cn/Article/details/gt2qcqfbhhw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmtrwpmu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bfkjaxmd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sxryk.cn/Article/details/gt2rqxkooct.html


<!-- 参考信息 -->