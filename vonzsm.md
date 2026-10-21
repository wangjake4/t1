代发 wailian999

Ruby: require "json"; require_relative "./util"
来源：http://dali.xylfe.cn/Article/details/gtdhvfkwpe.html

C#:   using System.Text;
来源：http://dali.tanke756.top/Article/details/gtpgqsnmfx.html

[C12] 立即执行函数 IIFE
来源：http://dali.aibaodan.cn/Article/details/gtypxqyzsj.html

Py:   (lambda: print("run"))()
来源：http://dali.fzhhl.top/Article/details/gthpkaalft.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pycfn.com/Article/details/gtjhkaixru.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gteaeayrpc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.quarkkingdee.top/Article/details/gtpcmbyfwy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigfzy.top/Article/details/gtebmdqaay.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.quarkkingdee.top/Article/details/gtnoawicey.html

Ruby: -> { puts "run" }.call
来源：http://dali.xylfe.cn/Article/details/gtfqdljbtu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shuidangran.top/Article/details/gtitjqcbco.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinqigufen.top/Article/details/gtjnujwcbu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sufxvd.cn/Article/details/gtmazlzwix.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gthmuisvyh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.svipenyu.cn/Article/details/gttoptaklh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gtbsvopzlx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtymyqhuto.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgdnjbwj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ybcxt.top/Article/details/gtcplllvei.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258.top/Article/details/gtqwursewj.html

[C14] 泛型函数
来源：http://dali.zhiwuduotai.top/Article/details/gtthvxhugf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmwvefzw.html

PHP:  // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gteekalxpo.html

JS:   // 无泛型
来源：http://dali.yongpay.top/Article/details/gtyswxurjb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yongpay.top/Article/details/gtlklilpwv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guannengcc.top/Article/details/gtrjfaitwg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gotoacloud.top/Article/details/gtjsfnfwgs.html

Ruby: # 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gtuvazjbla.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yangfankeji.com/Article/details/gtuufkgvgn.html

[C15] 解构 / 展开参数
来源：http://dali.hongshengwenyu.top/Article/details/gtbtxxhktu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258888.top/Article/details/gttxojydyc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daxiang520.top/Article/details/gtunhsshej.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fzhhl.top/Article/details/gtxzpaeicd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hfpthk.cn/Article/details/gtofnkoegb.html

Java: // 无解构
来源：http://dali.hysaishi.cn/Article/details/gtxfnpupuu.html

Go:   // 无解构
来源：http://dali.cqqwz.cn/Article/details/gttobxaxhe.html

Ruby: a, b = pair
来源：http://dali.nwbrower.top/Article/details/gtitfajhkf.html

C#:   var (a, b) = pair;
来源：http://dali.sxryk.cn/Article/details/gtchcjmnas.html

[C16] 函数 / 方法重载
来源：http://dali.redwolf501.top/Article/details/gtjuvkvaii.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.c1oappe.top/Article/details/gtilrstmei.html

PHP:  // 无重载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgahilvty.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tian-w.cn/Article/details/gtpjnicqew.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tanke756.top/Article/details/gtzwgwlfej.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgufenzy.top/Article/details/gtqvhmwxjm.html

Go:   // 无重载：用不同函数名
来源：http://dali.tianlin.xyz/Article/details/gtrowxlqyj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zycfv.cn/Article/details/gtvfasmerv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cashguo.top/Article/details/gtaxurrdxo.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtibmtpylk.html

D. 数组 / 列表 / 集合
来源：http://dali.jiagoushi.top/Article/details/gtvjyhsuha.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtblavvdjc.html

[D01] 创建数组 / 列表
来源：http://dali.zhoulong.xyz/Article/details/gtrjntfkka.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhengqikj.top/Article/details/gtocorxvhu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yuxming.cn/Article/details/gtrdcguswz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.9152youxi.cn/Article/details/gtkrwtgunn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pycfn.com/Article/details/gtzjzxtmyp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fzhhl.top/Article/details/gtlxaqqttu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yueranfly.top/Article/details/gtlgcvycst.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xziqi.cn/Article/details/gtrjpendhq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.quarkkingdee.top/Article/details/gtyjqlhvte.html

[D02] 追加元素到末尾
来源：http://dali.yonumen.top/Article/details/gtuoqlsrib.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxuanxn.top/Article/details/gtjbzauzhq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shzxlz.cn/Article/details/gtitihkukz.html

JS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gtomutpiix.html

TS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gtksznffth.html

Java: list.add(4);
来源：http://dali.zdqjudy.top/Article/details/gturyyoura.html

Go:   arr = append(arr, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtiuclxwfb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.9152youxi.cn/Article/details/gthbrbtrqc.html

C#:   list.Add(4);
来源：http://dali.havefunace.top/Article/details/gtgnuwoktd.html

[D03] 在指定位置插入元素
来源：http://dali.havefunace.top/Article/details/gtbhuedjfj.html

Py:   arr.insert(0, 0)
来源：http://dali.haohaochexian.top/Article/details/gttnjenxko.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zdqjudy.top/Article/details/gtgkoltnyx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xziqi.cn/Article/details/gtxfgdytfa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fzhhl.top/Article/details/gtlwfwtpsi.html

Java: list.add(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtluzyedxs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuanzhike.top/Article/details/gtvbhmhekb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhengqikj.top/Article/details/gthgqxhobp.html

C#:   list.Insert(0, 0);
来源：http://dali.xuanzx.com/Article/details/gtxmaiibbk.html

[D04] 删除元素
来源：http://dali.aibaodan.cn/Article/details/gtbxzwkgsj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcmwwict.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtdvkbozds.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigfzy.top/Article/details/gthtrbnxov.html

TS:   arr.splice(0, 1);
来源：http://dali.sweek.top/Article/details/gtxwzxudho.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnxiangtu.top/Article/details/gtbhqrjksm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteyrbjqhx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgufenzy.top/Article/details/gtowjvpysl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gzhubu.top/Article/details/gtkqacwcim.html

[D05] 访问与修改元素
来源：http://dali.yj20258888.top/Article/details/gtzlxdgsfi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtwjfcwibx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtekkimwvy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtuohpshqw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jianghu66.top/Article/details/gtbmgrlnsv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gogol.net.cn/Article/details/gtkoffltji.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gtufxzqeqv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gtnvehbfje.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gtindxocyw.html

[D06] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gtykrjzjqo.html

Py:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkecnitxd.html

PHP:  count($arr);
来源：http://dali.sxryk.cn/Article/details/gtfvbptpyd.html

JS:   arr.length
来源：http://dali.jyoumei.cn/Article/details/gtuigqfqcl.html

TS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gtkreyfkcw.html

Java: list.size();
来源：http://dali.sweek.top/Article/details/gtqkwioplw.html

Go:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmjforjd.html

Ruby: arr.length; arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gtxaulpusg.html

C#:   list.Count;
来源：http://dali.zdqjudy.top/Article/details/gtydhkyoao.html

[D07] 切片 / 取子数组
来源：http://dali.feifeiyinyue.top/Article/details/gthwfmsvfm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuanzhike.top/Article/details/gthcimllir.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daria6918.cn/Article/details/gteploroxp.html

JS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gttnvfzjzq.html

TS:   arr.slice(1, 4);
来源：http://dali.yuxming.cn/Article/details/gttgjzjzkk.html

Java: list.subList(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtvircpjcu.html

Go:   arr[1:4]
来源：http://dali.jlsjyb.cn/Article/details/gtikdstgnj.html

Ruby: arr[1, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gtvcbzxfdq.html

C#:   list.GetRange(1, 3);
来源：http://dali.0kj1m.cn/Article/details/gtikldghqe.html

[D08] 合并两个数组
来源：http://dali.havefunace.top/Article/details/gtzfwcreln.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthnapuezt.html

PHP:  array_merge($a, $b);
来源：http://dali.vqdsnc.cn/Article/details/gtucymrdfe.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenlongwang.top/Article/details/gtaksnxjyi.html

TS:   [...a, ...b];
来源：http://dali.gaohongyu789.top/Article/details/gtfzbfkwxh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.meibo888.top/Article/details/gtrlbnwiue.html

Go:   append(a, b...)
来源：http://dali.aibaodan.cn/Article/details/gtcxnnzxvc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xylfe.cn/Article/details/gtypsccrss.html

C#:   a.Concat(b).ToList()
来源：http://dali.daria6918.cn/Article/details/gtrtxqrbjh.html

[D09] 排序（升序）
来源：http://dali.haohaochexian.top/Article/details/gtwlsibsfj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtduybgiir.html

PHP:  sort($arr);
来源：http://dali.0kj1m.cn/Article/details/gtceqekttd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cucudq.cn/Article/details/gtyoznqzvx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gogol.net.cn/Article/details/gtvckhtlmx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cheryme.top/Article/details/gtwoeedtug.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtbiglapts.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gtwteboepy.html

C#:   list.Sort();
来源：http://dali.shzxlz.cn/Article/details/gtbyypgvcb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.0kj1m.cn/Article/details/gtcwnvcxcv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ehwqpu.com/Article/details/gtptusnmmz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gtfuhwmqjz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gtbnkrcfeq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gtigfmymfn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.316326.xyz/Article/details/gtoctbpjgv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cucudq.cn/Article/details/gttmqzvfbx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sysykeji.top/Article/details/gtebxhglau.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pengpengdd.cyou/Article/details/gtwhgopzws.html

[D11] 反转数组
来源：http://dali.andypj.xyz/Article/details/gtafszzleb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yangfankeji.com/Article/details/gtaifactyo.html

PHP:  array_reverse($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtgysvslse.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pengpengdd.cyou/Article/details/gtjvaltagq.html

TS:   [...arr].reverse();
来源：http://dali.zhoulong.xyz/Article/details/gtvfmcezoc.html

Java: Collections.reverse(list);
来源：http://dali.tian-w.cn/Article/details/gtntkntygg.html

Go:   slices.Reverse(arr)
来源：http://dali.xinyue.icu/Article/details/gtlfmlxwch.html

Ruby: arr.reverse
来源：http://dali.jinqigufen.top/Article/details/gtgkixyudz.html

C#:   list.Reverse();
来源：http://dali.sweek.top/Article/details/gtdefgphid.html

[D12] 查找元素下标
来源：http://dali.bjfxy.top/Article/details/gtycvgqmmz.html

Py:   arr.index(x);  x in arr
来源：http://dali.cheryme.top/Article/details/gtetdbpsen.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cdnleiting.top/Article/details/gtsvjkxjln.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gtgmhvxfgv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gtgfyblurf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.aizwys.cn/Article/details/gtgxceghwp.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtsmrkvrff.html

Ruby: arr.index(x)
来源：http://dali.svipenyu.cn/Article/details/gtiocyphgx.html

C#:   list.IndexOf(x);
来源：http://dali.havefunace.top/Article/details/gtanrnssvw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tanke756.top/Article/details/gtgkbrtxoc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtxzglrgdu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmwayvzo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gtblnyokvd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinqigufen.top/Article/details/gtbnvgipde.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shuidangran.top/Article/details/gtxadryaec.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fengsongda.top/Article/details/gtalulypmm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xylfe.cn/Article/details/gttkguhiah.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtycqrohre.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigfzy.top/Article/details/gtjgamdvfx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fzhhl.top/Article/details/gtcmwrmewu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hywenlv.cn/Article/details/gtqasiefbv.html

JS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gtnsftkddv.html

TS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gtcrjgpwkt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.smart0.xyz/Article/details/gtsmmgstqc.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gtrdroknge.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gthhquljbk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtffaprihx.html

[D15] 去重
来源：http://dali.xziqi.cn/Article/details/gtwxsjxwwt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gtxsljsaky.html

PHP:  array_unique($arr);
来源：http://dali.jyoumei.cn/Article/details/gthhklcjsl.html

JS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtoqnsbbcy.html

TS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtlssdasgp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigufen.top/Article/details/gtnvikqcya.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fengsongda.top/Article/details/gtwdhxtmej.html

Ruby: arr.uniq
来源：http://dali.jinghuilouyu.cn/Article/details/gtifzitfur.html

C#:   list.Distinct().ToList()
来源：http://dali.zycfv.cn/Article/details/gtfzzbfwgg.html

[D16] 求和与平均值
来源：http://dali.dianchejie.cn/Article/details/gtjbxlknud.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtyikalsll.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guannengcc.top/Article/details/gtevgonstp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gtdbverpfv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gtjtkaxuxe.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258.top/Article/details/gtzopxrynu.html

Go:   // 手写循环累加
来源：http://dali.jinqigfzy.top/Article/details/gtxvhaaubi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gotoacloud.top/Article/details/gtdqgyxicl.html

C#:   list.Sum();  list.Average()
来源：http://dali.dianchejie.cn/Article/details/gtjjufquiu.html

[D17] 最大值与最小值
来源：http://dali.wangdashe.top/Article/details/gtujfmkeik.html

Py:   max(arr);  min(arr)
来源：http://dali.yvedp.cn/Article/details/gtbxiazpif.html

PHP:  max($arr);  min($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaejkselp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ehwqpu.com/Article/details/gtmduyobel.html

TS:   Math.max(...arr);
来源：http://dali.cqqwz.cn/Article/details/gtcewuvzub.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yongpay.top/Article/details/gtjligoffu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtjyekmkov.html

Ruby: arr.max;  arr.min
来源：http://dali.yj202588.top/Article/details/gttwltwqvu.html

C#:   list.Max();  list.Min()
来源：http://dali.chenlongwang.top/Article/details/gtadpsvcuc.html

[D18] 扁平化嵌套数组
来源：http://dali.yj20258.top/Article/details/gtcrovpxfx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guannengcc.top/Article/details/gtygmrnzhf.html

PHP:  array_merge(...$nested);
来源：http://dali.guannengcc.top/Article/details/gtbjacgteh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.mhx1999.top/Article/details/gtvuthsknr.html

TS:   nested.flat();
来源：http://dali.wangdashe.top/Article/details/gtpflbcnxd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtdmpemwpx.html

Go:   // 手写双层循环
来源：http://dali.hywenlv.cn/Article/details/gtrevpppsj.html

Ruby: nested.flatten
来源：http://dali.nwbrower.top/Article/details/gtdoqxuqtr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yvedp.cn/Article/details/gtfykshhnt.html

[D19] 按字段分组
来源：http://dali.sweek.top/Article/details/gtnqfhbdct.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pycfn.com/Article/details/gtgzeeunmy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhoulong.xyz/Article/details/gtntenrbme.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shuidangran.top/Article/details/gtxsdiocdz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.vqdsnc.cn/Article/details/gtglstrnek.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuanzx.com/Article/details/gtngwarlft.html

Go:   // 手写 map[string][]T
来源：http://dali.wangshuangyany.cn/Article/details/gtlazjssxt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbjccewm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.quarkkingdee.top/Article/details/gtfwkjamly.html

[D20] 统计每个元素出现次数
来源：http://dali.zhongyouzk.top/Article/details/gtsmpsiwff.html

Py:   Counter(arr)
来源：http://dali.meibo888.top/Article/details/gttwjqnfgz.html

PHP:  array_count_values($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gttwsnzqzc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xylfe.cn/Article/details/gtttsoyevm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gtlntmquar.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenjidiqi.icu/Article/details/gthnozdcpr.html

Go:   // 手写 map[T]int
来源：http://dali.jiagoushi.top/Article/details/gtsgqfocvs.html

Ruby: arr.tally
来源：http://dali.nanxuanxn.top/Article/details/gtdsgaxlyd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cqqwz.cn/Article/details/gttvcnfkaq.html

[D21] 判断是否包含某元素
来源：http://dali.zhoulong.xyz/Article/details/gtlljszvxx.html

Py:   x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gttjxoarrb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.quarkkingdee.top/Article/details/gtddjqjoqi.html

JS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtzwjglirr.html

TS:   arr.includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gtbuyaykyf.html

Java: list.contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtixklxbub.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258.top/Article/details/gtmlggjgzn.html

Ruby: arr.include?(x)
来源：http://dali.jyoumei.cn/Article/details/gtzjnkwxvz.html

C#:   list.Contains(x)
来源：http://dali.meibo888.top/Article/details/gtvvurezvv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxinkj.top/Article/details/gthmklfeai.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtghrkhrzj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tianlin.xyz/Article/details/gtcsnkrucp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchuqbuix.html

TS:   [...arr];
来源：http://dali.daria6918.cn/Article/details/gtdyyxzhre.html

Java: new ArrayList<>(list);
来源：http://dali.yangfankeji.com/Article/details/gtwtqhmsjo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigfzy.top/Article/details/gthqsuwvfe.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fzhhl.top/Article/details/gtohxqlqwt.html

C#:   new List<int>(list);
来源：http://dali.chenzaomai.com/Article/details/gtgassjlfy.html

[D23] reduce 累积计算
来源：http://dali.cashguo.top/Article/details/gtirukzeii.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtdacdmoxh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cashguo.top/Article/details/gtskhmmgvp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqehsrabj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.316326.xyz/Article/details/gtakkiffuo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.iojbl.cn/Article/details/gtjxivdrxg.html

Go:   // 手写循环
来源：http://dali.yonumen.top/Article/details/gtfyqobrbx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sweek.top/Article/details/gtcgtlymua.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.wangshuangyany.cn/Article/details/gtjzkgpvek.html

[D24] 字典 / Map 基本操作
来源：http://dali.jiagoushi.top/Article/details/gtibqrbwwm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhixingplan.top/Article/details/gtzcrcxvfs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shzxlz.cn/Article/details/gtvwjefazw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258.top/Article/details/gtidzonkcp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtmzpsadas.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenlongwang.top/Article/details/gtkxykgjlo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fzhhl.top/Article/details/gtrhydrqzi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.mhx1999.top/Article/details/gtektiaidy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zdqjudy.top/Article/details/gtrmbfukdg.html

[D25] Set 集合去重与交并差
来源：http://dali.sysykeji.top/Article/details/gttnvaqlys.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sxryk.cn/Article/details/gtmoybyfxf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.haohaochexian.top/Article/details/gtrwipzagr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hfpthk.cn/Article/details/gtxeqmqutp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ydzc1.top/Article/details/gtwhkggrvq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.havefunace.top/Article/details/gtciuvckyv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.andypj.xyz/Article/details/gtcrevstwu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sysykeji.top/Article/details/gtnmqzqnsd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jianghu66.top/Article/details/gtyqvzchoa.html

[D26] 数组转字符串
来源：http://dali.cucudq.cn/Article/details/gtcszgaxcy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dashuyun.cn/Article/details/gtglwgohuq.html

PHP:  implode(", ", $arr);
来源：http://dali.snrcjt.cn/Article/details/gtuizifikr.html

JS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtywhvloum.html

TS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtjkwfkynl.html

Java: String.join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gtqrzzndjj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhoulong.xyz/Article/details/gtbbdzwolb.html

Ruby: arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtluptxsrd.html

C#:   string.Join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gtvikdrier.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtnlhbicbm.html

E. 字符串处理
来源：http://dali.yj202588.top/Article/details/gtuqliicts.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gthrymljgx.html

[E01] 拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtextafjsa.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.wangshuangyany.cn/Article/details/gtqkazbffo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cucudq.cn/Article/details/gtkwdoouln.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gtvtvsiyqb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtaijabzhz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.0kj1m.cn/Article/details/gtncucjhmq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cqqwz.cn/Article/details/gtssmjosag.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.vqdsnc.cn/Article/details/gtyaevtfxx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guannengcc.top/Article/details/gttsjocygu.html

[E02] 重复字符串
来源：http://dali.zhengqikj.top/Article/details/gtwishhjal.html

Py:   "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gtvcntetjv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtwxnxeltq.html

JS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtddyfswqi.html


<!-- 参考信息 -->