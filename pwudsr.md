代发 wailian999

Ruby: require "json"; require_relative "./util"
来源：http://dali.daxiang520.top/Article/details/gtwbgnplwp.html

C#:   using System.Text;
来源：http://dali.yanxiufei.cn/Article/details/gtfpeqdtkh.html

[C12] 立即执行函数 IIFE
来源：http://dali.cqqwz.cn/Article/details/gtpiucxlgr.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxuanxn.top/Article/details/gtqmrbbczh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangshuangyany.cn/Article/details/gtsznirgxg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fzhhl.top/Article/details/gtolsonxwd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ydzc1.top/Article/details/gtbqqbrgbp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aibaodan.cn/Article/details/gtrnpqdkxk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttptuvzdr.html

Ruby: -> { puts "run" }.call
来源：http://dali.9152youxi.cn/Article/details/gtranwnune.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daxiang520.top/Article/details/gttbnvmkwc.html

[C13] 类型声明 / 类型注解
来源：http://dali.hnqzz.top/Article/details/gtggzfdzhr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.andypj.xyz/Article/details/gtanxchdrx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcbasrnv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.redwolf501.top/Article/details/gtldonatou.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtwxumalgn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtwogmeatl.html

Go:   func add(a, b int) int
来源：http://dali.hongshengwenyu.top/Article/details/gtvfenurma.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cheryme.top/Article/details/gtzmjsglky.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xylfe.cn/Article/details/gtflxxabtz.html

[C14] 泛型函数
来源：http://dali.vqdsnc.cn/Article/details/gtjzqlxneo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkoqgiho.html

PHP:  // 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gtdnaoshxe.html

JS:   // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfggnnzhp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvtzgibew.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sweek.top/Article/details/gtyemvtstm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.svipenyu.cn/Article/details/gtllnauyba.html

Ruby: # 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gtjlxylnkx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpaqxashb.html

[C15] 解构 / 展开参数
来源：http://dali.nwbrower.top/Article/details/gtqqgvegop.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuanzx.com/Article/details/gtxbieydig.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dianchejie.cn/Article/details/gtxrvtdhid.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinqigfzy.top/Article/details/gtgrtjjwcp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yonumen.top/Article/details/gtdsistjjg.html

Java: // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtavejhnck.html

Go:   // 无解构
来源：http://dali.zhengqikj.top/Article/details/gtwjqhdynk.html

Ruby: a, b = pair
来源：http://dali.yanxiufei.cn/Article/details/gteubxnohb.html

C#:   var (a, b) = pair;
来源：http://dali.zhiwuduotai.top/Article/details/gtikyvyguj.html

[C16] 函数 / 方法重载
来源：http://dali.gaohongyu789.top/Article/details/gtmwyxduro.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jyoumei.cn/Article/details/gtvhitiwbs.html

PHP:  // 无重载
来源：http://dali.hammf.cn/Article/details/gtekvmldru.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jianghu66.top/Article/details/gtazyshwgg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jyoumei.cn/Article/details/gtszuqhqfh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jyoumei.cn/Article/details/gtdxgabrhb.html

Go:   // 无重载：用不同函数名
来源：http://dali.meibo888.top/Article/details/gtuakaqblg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigufen.top/Article/details/gtkmddvlkn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tianlin.xyz/Article/details/gtqxtschoi.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gteyeubyvq.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxuanxn.top/Article/details/gtzncucpbc.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtuotafall.html

[D01] 创建数组 / 列表
来源：http://dali.316326.xyz/Article/details/gtdimuajdo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuxming.cn/Article/details/gtxrbjplgt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.guowangkeji.top/Article/details/gthucyutht.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cashguo.top/Article/details/gtqsnxrjjt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhongyouzk.top/Article/details/gtolvvtgrc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnxiangtu.top/Article/details/gtuhmgbrxz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhongyouzk.top/Article/details/gtwprmnvuu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cashguo.top/Article/details/gtvmjbnbyv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pycfn.com/Article/details/gtgmsmeeay.html

[D02] 追加元素到末尾
来源：http://dali.sufxvd.cn/Article/details/gttmitpniw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hywenlv.cn/Article/details/gtwqvkbeoq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenlongwang.top/Article/details/gtqmqslpvi.html

JS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gteoebxuxp.html

TS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gttzfsrthm.html

Java: list.add(4);
来源：http://dali.svipenyu.cn/Article/details/gtplbaytha.html

Go:   arr = append(arr, 4)
来源：http://dali.zhixingplan.top/Article/details/gtcfozuygd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shangyingyoupin.top/Article/details/gtomieblyp.html

C#:   list.Add(4);
来源：http://dali.cucudq.cn/Article/details/gtcupsjxyj.html

[D03] 在指定位置插入元素
来源：http://dali.kuanghao11.cn/Article/details/gtclhwlzyf.html

Py:   arr.insert(0, 0)
来源：http://dali.xylfe.cn/Article/details/gtlhlhujwr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yueranfly.top/Article/details/gthmjwzsgo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hammf.cn/Article/details/gtdukgxtko.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhengqikj.top/Article/details/gtebejtfeu.html

Java: list.add(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtvavhkjky.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.birdmap.top/Article/details/gtybecaifz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxuelhhc.html

C#:   list.Insert(0, 0);
来源：http://dali.ppjwa.cn/Article/details/gtkbczxxto.html

[D04] 删除元素
来源：http://dali.sysykeji.top/Article/details/gtantdmint.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.redwolf501.top/Article/details/gtqdyjsrse.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shzxlz.cn/Article/details/gttrzwupeb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.snrcjt.cn/Article/details/gtqgvkhyho.html

TS:   arr.splice(0, 1);
来源：http://dali.yueranfly.top/Article/details/gtvsuxzxei.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.snrcjt.cn/Article/details/gtjwrbeoig.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhoulong.xyz/Article/details/gtxgioerlb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hysaishi.cn/Article/details/gtqqturcqq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yanxiufei.cn/Article/details/gtvgokmwxb.html

[D05] 访问与修改元素
来源：http://dali.aibaodan.cn/Article/details/gtswkrlnva.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gtwmlprami.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtyxoynpct.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtuadnwftv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gaohongyu789.top/Article/details/gtnllnzwiz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yangfankeji.com/Article/details/gtuwytalkc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gtmkffplva.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtulzchpyz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gtpldiqgta.html

[D06] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gtqkercdng.html

Py:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gtujiqnhqt.html

PHP:  count($arr);
来源：http://dali.sysykeji.top/Article/details/gtvahirzer.html

JS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gtdwxjkzji.html

TS:   arr.length
来源：http://dali.havefunace.top/Article/details/gthgdrjzbz.html

Java: list.size();
来源：http://dali.daria6918.cn/Article/details/gtbckpxalk.html

Go:   len(arr)
来源：http://dali.cashguo.top/Article/details/gtlkhetyma.html

Ruby: arr.length; arr.size
来源：http://dali.meibo888.top/Article/details/gtizwliefn.html

C#:   list.Count;
来源：http://dali.vqdsnc.cn/Article/details/gtqsbtkrew.html

[D07] 切片 / 取子数组
来源：http://dali.redwolf501.top/Article/details/gtpkucnvua.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dianchejie.cn/Article/details/gtfsdozquu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.birdmap.top/Article/details/gtfhtunmzb.html

JS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxltcflkx.html

TS:   arr.slice(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gtnooomzll.html

Java: list.subList(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvthjvwq.html

Go:   arr[1:4]
来源：http://dali.smart0.xyz/Article/details/gtxafsfbxm.html

Ruby: arr[1, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gtbnxkelkn.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigufen.top/Article/details/gtfdkztdsl.html

[D08] 合并两个数组
来源：http://dali.svipenyu.cn/Article/details/gtfgjdtirj.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxinkj.top/Article/details/gtrgnkcxqo.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigufen.top/Article/details/gtfsvcsexg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yueranfly.top/Article/details/gtuggskwtl.html

TS:   [...a, ...b];
来源：http://dali.cashguo.top/Article/details/gtwiwdyrgh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fzhhl.top/Article/details/gtozdojofo.html

Go:   append(a, b...)
来源：http://dali.nanxinkj.top/Article/details/gtckuvksqy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cheryme.top/Article/details/gtugeszanq.html

C#:   a.Concat(b).ToList()
来源：http://dali.xziqi.cn/Article/details/gtgfdwzfxx.html

[D09] 排序（升序）
来源：http://dali.xziqi.cn/Article/details/gtvwbaneuz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtzvrtghwh.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gtzecwcyvs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cashguo.top/Article/details/gtazsqvsht.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ehwqpu.com/Article/details/gtpfcdmyls.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zdqjudy.top/Article/details/gtascaeapu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gtqvakqefs.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gtpsejqwna.html

C#:   list.Sort();
来源：http://dali.zhixingplan.top/Article/details/gtwdliifpg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.feifeiyinyue.top/Article/details/gtfqstsizu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sysykeji.top/Article/details/gtzulfinyd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yongpay.top/Article/details/gtpfmlaeqa.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gtcymfnesu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtlcgtewal.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shuidangran.top/Article/details/gthxjtlqun.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cheryme.top/Article/details/gtkllvznpt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yvedp.cn/Article/details/gtalouwbjw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhoulong.xyz/Article/details/gtjfsgrnyo.html

[D11] 反转数组
来源：http://dali.c1oappe.top/Article/details/gtchihqjer.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gtfrfbvpun.html

PHP:  array_reverse($arr);
来源：http://dali.fzhhl.top/Article/details/gthmkvyble.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pengpengdd.cyou/Article/details/gtdovsxgwo.html

TS:   [...arr].reverse();
来源：http://dali.gogol.net.cn/Article/details/gtadcoxrjh.html

Java: Collections.reverse(list);
来源：http://dali.andypj.xyz/Article/details/gtiehbujhj.html

Go:   slices.Reverse(arr)
来源：http://dali.gogol.net.cn/Article/details/gtymwiclhw.html

Ruby: arr.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtdtoxjcxc.html

C#:   list.Reverse();
来源：http://dali.hnxiangtu.top/Article/details/gtzhkzhhxx.html

[D12] 查找元素下标
来源：http://dali.ydzc1.top/Article/details/gtczminrnm.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhoulong.xyz/Article/details/gtnaefzasx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.smart0.xyz/Article/details/gtwcltviis.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtkbqvqarh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gthtrtpvdm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daria6918.cn/Article/details/gtwsdwpqyr.html

Go:   slices.Index(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtujqgxptr.html

Ruby: arr.index(x)
来源：http://dali.hysaishi.cn/Article/details/gtxbkmfsve.html

C#:   list.IndexOf(x);
来源：http://dali.hfpthk.cn/Article/details/gtsjufessl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zdqjudy.top/Article/details/gtmpdtzqaw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtxirxktps.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pycfn.com/Article/details/gtuaakmznw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gtcdnrsvaw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gtrlhznxzy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ppjwa.cn/Article/details/gtkfhzbumb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhuxotrv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqmvhbon.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtfzczxbcn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tanke756.top/Article/details/gtonkbmccf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtrffyqkyc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtbzpoikro.html

JS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gtlcdaridn.html

TS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gtrjvjuoon.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.snrcjt.cn/Article/details/gthwtyciki.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gtiveneler.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sweek.top/Article/details/gtppvncfsk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258888.top/Article/details/gtmazxdviv.html

[D15] 去重
来源：http://dali.zdqjudy.top/Article/details/gtbhzhzvmb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvnxodkh.html

PHP:  array_unique($arr);
来源：http://dali.yonumen.top/Article/details/gtdspmhfkn.html

JS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gtxgxlzrxc.html

TS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtkdbhgowc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigufen.top/Article/details/gtrecplxei.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgfzy.top/Article/details/gtmotrzpgy.html

Ruby: arr.uniq
来源：http://dali.daxiang520.top/Article/details/gtcfdraccu.html

C#:   list.Distinct().ToList()
来源：http://dali.haohaochexian.top/Article/details/gtzytfbonb.html

[D16] 求和与平均值
来源：http://dali.ppjwa.cn/Article/details/gtweymoqii.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yvedp.cn/Article/details/gtjzjbrnpu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fzhhl.top/Article/details/gtwsqbaxvp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gtmveompzq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtoaajhdpy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yvedp.cn/Article/details/gtkubqymge.html

Go:   // 手写循环累加
来源：http://dali.nanxinkj.top/Article/details/gtzrjabawp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tanke756.top/Article/details/gtlkenbtnm.html

C#:   list.Sum();  list.Average()
来源：http://dali.haohaochexian.top/Article/details/gtndftjyvh.html

[D17] 最大值与最小值
来源：http://dali.yangfankeji.com/Article/details/gtsvpssieb.html

Py:   max(arr);  min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtopftrdgi.html

PHP:  max($arr);  min($arr);
来源：http://dali.shuidangran.top/Article/details/gtknykmksp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj202588.top/Article/details/gtxqaboknt.html

TS:   Math.max(...arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwslaodut.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.haohaochexian.top/Article/details/gtsrhfzmjt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dashuyun.cn/Article/details/gteicubvxp.html

Ruby: arr.max;  arr.min
来源：http://dali.xziqi.cn/Article/details/gtsftsefjt.html

C#:   list.Max();  list.Min()
来源：http://dali.ybcxt.top/Article/details/gtuipfznmf.html

[D18] 扁平化嵌套数组
来源：http://dali.shzxlz.cn/Article/details/gtyhcfabyh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.snrcjt.cn/Article/details/gtltbazbre.html

PHP:  array_merge(...$nested);
来源：http://dali.shangyingyoupin.top/Article/details/gtkoykgwbz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.mhx1999.top/Article/details/gteyzhkiow.html

TS:   nested.flat();
来源：http://dali.c1oappe.top/Article/details/gtuhtmatdx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yongpay.top/Article/details/gtitjixcdq.html

Go:   // 手写双层循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtowrhorwe.html

Ruby: nested.flatten
来源：http://dali.tianlin.xyz/Article/details/gtluzzjajx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sxryk.cn/Article/details/gtgyqfvjpn.html

[D19] 按字段分组
来源：http://dali.yj20258.top/Article/details/gteqlkekye.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yonumen.top/Article/details/gthkyprsmp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangdashe.top/Article/details/gtgzmsozll.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jqgfzy.top/Article/details/gtutockdvc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gtglkwjnqk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cqqwz.cn/Article/details/gtoihlwcpc.html

Go:   // 手写 map[string][]T
来源：http://dali.xinyue.icu/Article/details/gtcfolbwjm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.0kj1m.cn/Article/details/gtjciyziub.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhixingplan.top/Article/details/gtdcsbzffr.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258888.top/Article/details/gtnyidbpbr.html

Py:   Counter(arr)
来源：http://dali.jyoumei.cn/Article/details/gtvolcxoix.html

PHP:  array_count_values($arr);
来源：http://dali.hnqzz.top/Article/details/gtobebxonm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gttxhjjqrz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gtykjhlljt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yangfankeji.com/Article/details/gtdlgnmkiw.html

Go:   // 手写 map[T]int
来源：http://dali.gzhubu.top/Article/details/gtyeoyehxv.html

Ruby: arr.tally
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxachioob.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gteldoxiow.html

[D21] 判断是否包含某元素
来源：http://dali.snrcjt.cn/Article/details/gtocwboxby.html

Py:   x in arr
来源：http://dali.ydzc1.top/Article/details/gtywbkqqty.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gogol.net.cn/Article/details/gtyghfxvcc.html

JS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gtqmpcblpm.html

TS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtqdmqlvzy.html

Java: list.contains(x)
来源：http://dali.jianghu66.top/Article/details/gtvaddikvx.html

Go:   slices.Contains(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtnojoqjiz.html

Ruby: arr.include?(x)
来源：http://dali.zdqjudy.top/Article/details/gtqjbpotlf.html

C#:   list.Contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtnwjtaasi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hywenlv.cn/Article/details/gtkiateijc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aizwys.cn/Article/details/gttooultes.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cucudq.cn/Article/details/gtfbpkqyie.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nwbrower.top/Article/details/gtlcnegtnr.html

TS:   [...arr];
来源：http://dali.gzhubu.top/Article/details/gtioezgqju.html

Java: new ArrayList<>(list);
来源：http://dali.aibaodan.cn/Article/details/gtgttvqqzm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xylfe.cn/Article/details/gttcvwojce.html

Ruby: arr.dup;  arr.clone
来源：http://dali.svipenyu.cn/Article/details/gtqnudthoj.html

C#:   new List<int>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtxlrhhnlf.html

[D23] reduce 累积计算
来源：http://dali.yonumen.top/Article/details/gtknqkkuqv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jyoumei.cn/Article/details/gtxziugpet.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgufenzy.top/Article/details/gttayxkqks.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gtcpjkmhvc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtqcwauzrm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenlongwang.top/Article/details/gtmasbixzf.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gtplzmifup.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258888.top/Article/details/gttdbfetix.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guowangkeji.top/Article/details/gtcvixdpox.html

[D24] 字典 / Map 基本操作
来源：http://dali.bjfxy.top/Article/details/gtgivdggpv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.redwolf501.top/Article/details/gtimpljydy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ydzc1.top/Article/details/gtidzmvnoc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenzaomai.com/Article/details/gtlzvczvcf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cheryme.top/Article/details/gttltqranw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shangyingyoupin.top/Article/details/gtvfxjomey.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ydzc1.top/Article/details/gtpufwgsow.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.kuanghao11.cn/Article/details/gtvpzvnqju.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyrwtfop.html

[D25] Set 集合去重与交并差
来源：http://dali.gzhubu.top/Article/details/gtwzaiocah.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.mhx1999.top/Article/details/gtmdgkbfuf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hfpthk.cn/Article/details/gtrvmymtpv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aizwys.cn/Article/details/gtzfhgebya.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yanxiufei.cn/Article/details/gtsnfhtaxi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sxryk.cn/Article/details/gthhevcalf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shzxlz.cn/Article/details/gtzqtjyrwl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.9152youxi.cn/Article/details/gtfolchekh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.iojbl.cn/Article/details/gtsbqfqzvb.html

[D26] 数组转字符串
来源：http://dali.smart0.xyz/Article/details/gtvmsliyoi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sufxvd.cn/Article/details/gtzhysqgea.html

PHP:  implode(", ", $arr);
来源：http://dali.gzhubu.top/Article/details/gtvwpoqukx.html

JS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtfjzriyvm.html

TS:   arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gtrizlvubg.html

Java: String.join(", ", list)
来源：http://dali.jinqigfzy.top/Article/details/gtfemcufot.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yvedp.cn/Article/details/gtnqvggvwn.html

Ruby: arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtookfbmbl.html

C#:   string.Join(", ", list)
来源：http://dali.yonumen.top/Article/details/gtyioiinwd.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtvtnmwgnc.html

E. 字符串处理
来源：http://dali.wangshuangyany.cn/Article/details/gttgdwkwvz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtdcqozwta.html

[E01] 拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtgufrlpuv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj202588.top/Article/details/gtkzbrxwdd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yongpay.top/Article/details/gtyjoymqsr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gtaktczzoq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ehwqpu.com/Article/details/gtpxabylgt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tanke756.top/Article/details/gtmcjmczpi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenzaomai.com/Article/details/gtuylgqtga.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xinyue.icu/Article/details/gtgofrzazw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtfwlcibvp.html

[E02] 重复字符串
来源：http://dali.daria6918.cn/Article/details/gttzoptoal.html

Py:   "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gtwavcppii.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtvhbrajww.html

JS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtqpbcabnv.html


<!-- 参考信息 -->