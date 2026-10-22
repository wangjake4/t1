代发 wailian999

PHP:  (function () { echo "run"; })();
来源：http://dali.guannengcc.top/Article/details/gt2bwjjnise.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gt2hdgsflgc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ydzc1.top/Article/details/gt2rwldhaos.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.vqdsnc.cn/Article/details/gt2jmmpqhzw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhengqikj.top/Article/details/gt2pqydabag.html

Ruby: -> { puts "run" }.call
来源：http://dali.gzhubu.top/Article/details/gt2ywaangjv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cqqwz.cn/Article/details/gt2svdrfggk.html

[C13] 类型声明 / 类型注解
来源：http://dali.svipenyu.cn/Article/details/gt2lflxubbd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cheryme.top/Article/details/gt2pqzriark.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2phlyogze.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ivvv.top/Article/details/gt2qfbmujeo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yonumen.top/Article/details/gt2nqrnroaq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2luvovjis.html

Go:   func add(a, b int) int
来源：http://dali.yuanzhike.top/Article/details/gt2clnrsttw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.snrcjt.cn/Article/details/gt2yiqqpchw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hysaishi.cn/Article/details/gt2lnthycch.html

[C14] 泛型函数
来源：http://dali.aizwys.cn/Article/details/gt2wplcxgqi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ystglesa.html

PHP:  // 无泛型
来源：http://dali.yj202588.top/Article/details/gt2gznmilkn.html

JS:   // 无泛型
来源：http://dali.shuidangran.top/Article/details/gt2mlpixcey.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ybcxt.top/Article/details/gt2ddylleml.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tian-w.cn/Article/details/gt2phejpxhl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuanzhike.top/Article/details/gt2tqhzdsel.html

Ruby: # 无泛型
来源：http://dali.hammf.cn/Article/details/gt2foxqiuxq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.svipenyu.cn/Article/details/gt2kpfacoca.html

[C15] 解构 / 展开参数
来源：http://dali.hfpthk.cn/Article/details/gt2ctlriuwx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2yijhxwax.html

PHP:  [$a, $b] = $pair;
来源：http://dali.iojbl.cn/Article/details/gt2kvhoipta.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2gixhnhqe.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2dkcgqfgn.html

Java: // 无解构
来源：http://dali.iojbl.cn/Article/details/gt2kwxnikck.html

Go:   // 无解构
来源：http://dali.jinqigufen.top/Article/details/gt2ppguggnx.html

Ruby: a, b = pair
来源：http://dali.jinghuilouyu.cn/Article/details/gt2avqxweuk.html

C#:   var (a, b) = pair;
来源：http://dali.meibo888.top/Article/details/gt2fzgyyxod.html

[C16] 函数 / 方法重载
来源：http://dali.cashguo.top/Article/details/gt2krxgpywm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.snrcjt.cn/Article/details/gt2axeaguxk.html

PHP:  // 无重载
来源：http://dali.cdnleiting.top/Article/details/gt2onqauvqm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xylfe.cn/Article/details/gt2ienbleyy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258.top/Article/details/gt2gmyeoalu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yvedp.cn/Article/details/gt2quwvmvpu.html

Go:   // 无重载：用不同函数名
来源：http://dali.yuxming.cn/Article/details/gt2kdoezjut.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uflesppb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj20258.top/Article/details/gt2oolpjuhv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2nooowgnx.html

D. 数组 / 列表 / 集合
来源：http://dali.ydzc1.top/Article/details/gt2fxnejvsb.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2jyielbjx.html

[D01] 创建数组 / 列表
来源：http://dali.yuxming.cn/Article/details/gt2msrxrvns.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jyoumei.cn/Article/details/gt2oyqlrrxv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sweek.top/Article/details/gt2vikrsdsd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.birdmap.top/Article/details/gt2jhjcptom.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jiagoushi.top/Article/details/gt2pbgkznem.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangshuangyany.cn/Article/details/gt2dyxctmxg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jlsjyb.cn/Article/details/gt2xoajxlmy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.smart0.xyz/Article/details/gt2slbrjema.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pengpengdd.cyou/Article/details/gt2qckcwqdo.html

[D02] 追加元素到末尾
来源：http://dali.birdmap.top/Article/details/gt2juhajlzk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hnqzz.top/Article/details/gt2ysjihvkm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jbxoiime.html

JS:   arr.push(4);
来源：http://dali.gotoacloud.top/Article/details/gt2rgkpcmbs.html

TS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gt2luekntic.html

Java: list.add(4);
来源：http://dali.fzhhl.top/Article/details/gt2ilkmfwej.html

Go:   arr = append(arr, 4)
来源：http://dali.havefunace.top/Article/details/gt2uhipphgr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.316326.xyz/Article/details/gt2rirwasyb.html

C#:   list.Add(4);
来源：http://dali.yangfankeji.com/Article/details/gt2ypcdyaxy.html

[D03] 在指定位置插入元素
来源：http://dali.tianlin.xyz/Article/details/gt2qfhfalra.html

Py:   arr.insert(0, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2fvngxqqi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.quarkkingdee.top/Article/details/gt2rukwywfq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jyoumei.cn/Article/details/gt2wuotyhgz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hfpthk.cn/Article/details/gt2khjsplgg.html

Java: list.add(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cvohcupp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hysaishi.cn/Article/details/gt2fbmvylll.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dianchejie.cn/Article/details/gt2hdkadwei.html

C#:   list.Insert(0, 0);
来源：http://dali.fengsongda.top/Article/details/gt2mauipexk.html

[D04] 删除元素
来源：http://dali.redwolf501.top/Article/details/gt2wghdzmzs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2vfrcoxyd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2katrvgfr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.feifeiyinyue.top/Article/details/gt2ryiyjmnl.html

TS:   arr.splice(0, 1);
来源：http://dali.xinyue.icu/Article/details/gt2cspamtok.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sbkkpujh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gzhubu.top/Article/details/gt2sewqxgiy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yvedp.cn/Article/details/gt2fbnuqntd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aibaodan.cn/Article/details/gt2mwigrurc.html

[D05] 访问与修改元素
来源：http://dali.nanxinkj.top/Article/details/gt2goiatehu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gt2cjozolwi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gt2xpwrlsqv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyckatcm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenlongwang.top/Article/details/gt2lotekzwh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tianlin.xyz/Article/details/gt2znaahkly.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gt2njbvkkck.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gt2nqdzsyra.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gt2tdkheunf.html

[D06] 数组长度
来源：http://dali.yj202588.top/Article/details/gt2igiipvfl.html

Py:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2bpphxtqo.html

PHP:  count($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2kkhcqnlv.html

JS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gt2zihcxpra.html

TS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gt2dhfixquv.html

Java: list.size();
来源：http://dali.pengpengdd.cyou/Article/details/gt2wcwjjanq.html

Go:   len(arr)
来源：http://dali.cashguo.top/Article/details/gt2tgksvsch.html

Ruby: arr.length; arr.size
来源：http://dali.meibo888.top/Article/details/gt2ntimqatc.html

C#:   list.Count;
来源：http://dali.kuanghao11.cn/Article/details/gt2rgsmlfhg.html

[D07] 切片 / 取子数组
来源：http://dali.pycfn.com/Article/details/gt2vyuaniax.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.kuanghao11.cn/Article/details/gt2yelplarn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2rvxypgqa.html

JS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gt2skwxhcjr.html

TS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gt2hgxqzblp.html

Java: list.subList(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gt2ohrckpxp.html

Go:   arr[1:4]
来源：http://dali.jyoumei.cn/Article/details/gt2psxpjlay.html

Ruby: arr[1, 3]
来源：http://dali.vqdsnc.cn/Article/details/gt2sioyigfy.html

C#:   list.GetRange(1, 3);
来源：http://dali.yangfankeji.com/Article/details/gt2kohrzzoq.html

[D08] 合并两个数组
来源：http://dali.0kj1m.cn/Article/details/gt2qmjporvf.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gdqqgxou.html

PHP:  array_merge($a, $b);
来源：http://dali.c1oappe.top/Article/details/gt2huflqzhj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnqzz.top/Article/details/gt2hmumsrcd.html

TS:   [...a, ...b];
来源：http://dali.nanxinkj.top/Article/details/gt2yjfsnnyi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ppjwa.cn/Article/details/gt2uqinbfmj.html

Go:   append(a, b...)
来源：http://dali.mhx1999.top/Article/details/gt2tqrhmvjt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhixingplan.top/Article/details/gt2dfnxfrzc.html

C#:   a.Concat(b).ToList()
来源：http://dali.ivvv.top/Article/details/gt2npchspvl.html

[D09] 排序（升序）
来源：http://dali.nwbrower.top/Article/details/gt2nzdehjlk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gt2hiawakyj.html

PHP:  sort($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ggkfsrxc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.bjfxy.top/Article/details/gt2egrmlbsy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xuanzx.com/Article/details/gt2cnsxirte.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xziqi.cn/Article/details/gt2vqoxkuju.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2dnzdrbjk.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gt2hfgnjwxr.html

C#:   list.Sort();
来源：http://dali.chenzaomai.com/Article/details/gt2chvovpem.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.iojbl.cn/Article/details/gt2zcwbkssd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gotoacloud.top/Article/details/gt2ajdwzisk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gt2ficibiyr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2okcgjffj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gt2gapjglyf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.mhx1999.top/Article/details/gt2dvbyeyyu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hysaishi.cn/Article/details/gt2oziwcolh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sufxvd.cn/Article/details/gt2xbefcaxv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhoulong.xyz/Article/details/gt2oiohgknj.html

[D11] 反转数组
来源：http://dali.hnxiangtu.top/Article/details/gt2evckzhlx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj20258888.top/Article/details/gt2ifxolhfb.html

PHP:  array_reverse($arr);
来源：http://dali.xziqi.cn/Article/details/gt2cybicfvi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.quarkkingdee.top/Article/details/gt2xptmgxsd.html

TS:   [...arr].reverse();
来源：http://dali.nanxinkj.top/Article/details/gt2pthgrfaj.html

Java: Collections.reverse(list);
来源：http://dali.jqgfzy.top/Article/details/gt2xojinlcv.html

Go:   slices.Reverse(arr)
来源：http://dali.fengsongda.top/Article/details/gt2gldfuysn.html

Ruby: arr.reverse
来源：http://dali.zycfv.cn/Article/details/gt2qtnifarp.html

C#:   list.Reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gt2mhrevwfa.html

[D12] 查找元素下标
来源：http://dali.shuidangran.top/Article/details/gt2xifjffpy.html

Py:   arr.index(x);  x in arr
来源：http://dali.ppjwa.cn/Article/details/gt2piiiexnn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2txkvjojz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.redwolf501.top/Article/details/gt2qehzrvef.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mkxcnxks.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xinyue.icu/Article/details/gt2ruvmious.html

Go:   slices.Index(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2wppzwudb.html

Ruby: arr.index(x)
来源：http://dali.daxiang520.top/Article/details/gt2vakrxnqi.html

C#:   list.IndexOf(x);
来源：http://dali.zhiwuduotai.top/Article/details/gt2qzfuvvrn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.feifeiyinyue.top/Article/details/gt2xghqzdcm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vkypjjqk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daria6918.cn/Article/details/gt2zfekwdzu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gt2ynktuhyf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gt2ilciccoj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.316326.xyz/Article/details/gt2ntwzupjw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhongyouzk.top/Article/details/gt2dwipwytf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnqzz.top/Article/details/gt2lyzxvunt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guannengcc.top/Article/details/gt2eaxxjfjv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aizwys.cn/Article/details/gt2fctyzbpt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.c1oappe.top/Article/details/gt2ijfxskye.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dianchejie.cn/Article/details/gt2pcvyvwjo.html

JS:   arr.map(x => x * 2)
来源：http://dali.guowangkeji.top/Article/details/gt2coburlge.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2rbtdhglr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yuxming.cn/Article/details/gt2sxmadubx.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gpugteca.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yongpay.top/Article/details/gt2wbwnkzeq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2kgclskgv.html

[D15] 去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cqnqcfmr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxinkj.top/Article/details/gt2vwefodvu.html

PHP:  array_unique($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2jvmrsemq.html

JS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gt2jcweewgk.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gt2pjgnaeqd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jiagoushi.top/Article/details/gt2ikbrmedk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daxiang520.top/Article/details/gt2ccnuylwq.html

Ruby: arr.uniq
来源：http://dali.xylfe.cn/Article/details/gt2iqcrojdd.html

C#:   list.Distinct().ToList()
来源：http://dali.tian-w.cn/Article/details/gt2ukkengpf.html

[D16] 求和与平均值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ocantuoj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2lmfjapez.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.andypj.xyz/Article/details/gt2wiedcyjk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gt2hkyhmbkd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gt2xzfehuph.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhoulong.xyz/Article/details/gt2kekxulzj.html

Go:   // 手写循环累加
来源：http://dali.andypj.xyz/Article/details/gt2mlgiczwl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.vqdsnc.cn/Article/details/gt2dshzaiea.html

C#:   list.Sum();  list.Average()
来源：http://dali.nwbrower.top/Article/details/gt2debenipf.html

[D17] 最大值与最小值
来源：http://dali.cdnleiting.top/Article/details/gt2cocdvtkl.html

Py:   max(arr);  min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2gaeisayk.html

PHP:  max($arr);  min($arr);
来源：http://dali.fzhhl.top/Article/details/gt2efbfbnry.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuanzx.com/Article/details/gt2mposrmut.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2thnqaofp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guowangkeji.top/Article/details/gt2zdojwjgm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guannengcc.top/Article/details/gt2rmtswcbx.html

Ruby: arr.max;  arr.min
来源：http://dali.fengsongda.top/Article/details/gt2pavrhcqq.html

C#:   list.Max();  list.Min()
来源：http://dali.0kj1m.cn/Article/details/gt2xycvoeqw.html

[D18] 扁平化嵌套数组
来源：http://dali.sweek.top/Article/details/gt2hogjicbv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sysykeji.top/Article/details/gt2akmeomfv.html

PHP:  array_merge(...$nested);
来源：http://dali.yonumen.top/Article/details/gt2tiybogtc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hywenlv.cn/Article/details/gt2mjakymzd.html

TS:   nested.flat();
来源：http://dali.ppjwa.cn/Article/details/gt2gwoxedms.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2aididgya.html

Go:   // 手写双层循环
来源：http://dali.hywenlv.cn/Article/details/gt2ksusfrqf.html

Ruby: nested.flatten
来源：http://dali.shangyingyoupin.top/Article/details/gt2oyxwrjjx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2bigycolj.html

[D19] 按字段分组
来源：http://dali.hnxiangtu.top/Article/details/gt2xalazmgp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fstvovvp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenzaomai.com/Article/details/gt2niztojwc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dianchejie.cn/Article/details/gt2crcefyhw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xziqi.cn/Article/details/gt2xobsqrri.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigfzy.top/Article/details/gt2snfsnlpg.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgfzy.top/Article/details/gt2eadmxliy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ivvv.top/Article/details/gt2vyjjwqkx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.redwolf501.top/Article/details/gt2llotcloh.html

[D20] 统计每个元素出现次数
来源：http://dali.cdnleiting.top/Article/details/gt2qtcfxijm.html

Py:   Counter(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2raebedpl.html

PHP:  array_count_values($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2pcaztyay.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gt2pckmyape.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gt2vjgffeqv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tianlin.xyz/Article/details/gt2wbxspzku.html

Go:   // 手写 map[T]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vdpskbup.html

Ruby: arr.tally
来源：http://dali.haohaochexian.top/Article/details/gt2cwdzteyz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pycfn.com/Article/details/gt2enlyfhkh.html

[D21] 判断是否包含某元素
来源：http://dali.ydzc1.top/Article/details/gt2dportsba.html

Py:   x in arr
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mwhzewmx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhiwuduotai.top/Article/details/gt2oqybzprx.html

JS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2qnncjzwr.html

TS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nevwplas.html

Java: list.contains(x)
来源：http://dali.jyoumei.cn/Article/details/gt2nwpoxdow.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2xzyusumg.html

Ruby: arr.include?(x)
来源：http://dali.haohaochexian.top/Article/details/gt2vcyxbjsh.html

C#:   list.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gt2wrovrcbw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tianlin.xyz/Article/details/gt2rsbzlxbs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2viwlikfo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuanzx.com/Article/details/gt2srueidkl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gcpmmart.html

TS:   [...arr];
来源：http://dali.sweek.top/Article/details/gt2mboypzlk.html

Java: new ArrayList<>(list);
来源：http://dali.xuanzx.com/Article/details/gt2aqdfrcet.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yvedp.cn/Article/details/gt2fdsrdtjk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yvedp.cn/Article/details/gt2ssnavpsx.html

C#:   new List<int>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njglcjlm.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxtpkmd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2bflchkbq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zdqjudy.top/Article/details/gt2ihjhulio.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gt2icnkgcjm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gt2zkwuxhmq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cashguo.top/Article/details/gt2febtflyu.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gt2qgedjple.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ybcxt.top/Article/details/gt2ymxicsya.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zycfv.cn/Article/details/gt2zuwhjgtn.html

[D24] 字典 / Map 基本操作
来源：http://dali.0kj1m.cn/Article/details/gt2ybqkthwd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tianlin.xyz/Article/details/gt2qhqlydgp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zycfv.cn/Article/details/gt2uzisirby.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nwbrower.top/Article/details/gt2sridzuar.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2eepeqjfx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hoagyowi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ydzc1.top/Article/details/gt2posvxpdt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cdnleiting.top/Article/details/gt2tgntzkhy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gogol.net.cn/Article/details/gt2erjsafhc.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxuanxn.top/Article/details/gt2oifxhhtw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yanxiufei.cn/Article/details/gt2mmtqdsej.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangdashe.top/Article/details/gt2jlooqxdx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2laohyhlv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cheryme.top/Article/details/gt2oqquzgqa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gogol.net.cn/Article/details/gt2pqnpvdxz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jianghu66.top/Article/details/gt2zxdfvhhr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2pupuqhhq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jianghu66.top/Article/details/gt2qmyrbhet.html

[D26] 数组转字符串
来源：http://dali.yonumen.top/Article/details/gt2xppxoyai.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnqzz.top/Article/details/gt2hipatpvm.html

PHP:  implode(", ", $arr);
来源：http://dali.guowangkeji.top/Article/details/gt2nhjglavh.html

JS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gt2uuddndeg.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lnjqnrjv.html

Java: String.join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2doyzjpmw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zdqjudy.top/Article/details/gt2nacflpmk.html

Ruby: arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gt2rkrwbafx.html

C#:   string.Join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gt2ghabssbp.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2ahwaprtt.html

E. 字符串处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2dgaglzpa.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2qdrccuhp.html

[E01] 拼接字符串
来源：http://dali.tanke756.top/Article/details/gt2cewobrnl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.haohaochexian.top/Article/details/gt2ilmfvnhq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj202588.top/Article/details/gt2uubnnhrn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2uinwcesg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gt2jyhcnbfv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tianlin.xyz/Article/details/gt2tqwndhlx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.svipenyu.cn/Article/details/gt2lkxeiftr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.aibaodan.cn/Article/details/gt2hqnzjrjy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2zpvlcxxq.html

[E02] 重复字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2tcisffcq.html

Py:   "ab" * 3
来源：http://dali.yongpay.top/Article/details/gt2icquwjkv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuanzhike.top/Article/details/gt2nhddwfxf.html

JS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gt2oscedzkn.html

TS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gt2araqlyzc.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eilufddp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2ssfqzfyt.html

Ruby: "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gt2hyyktexc.html


<!-- 参考信息 -->