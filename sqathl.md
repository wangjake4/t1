代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.birdmap.top/Article/details/gtzdxonzor.html

Ruby: -> { puts "run" }.call
来源：http://dali.shzxlz.cn/Article/details/gtnkapgmck.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gtryequuzt.html

[C13] 类型声明 / 类型注解
来源：http://dali.snrcjt.cn/Article/details/gtyahoblgb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258.top/Article/details/gtotqusydx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtxifihkci.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.mhx1999.top/Article/details/gtficasxew.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtjbqxfjrt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtoxnbfnco.html

Go:   func add(a, b int) int
来源：http://dali.xuetiantiany.cn/Article/details/gtudwqbyef.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gotoacloud.top/Article/details/gtktttiwxu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenlongwang.top/Article/details/gtpcdujnph.html

[C14] 泛型函数
来源：http://dali.shangyingyoupin.top/Article/details/gtfczkhxpu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xziqi.cn/Article/details/gtmexzzjty.html

PHP:  // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtckyiljsw.html

JS:   // 无泛型
来源：http://dali.yvedp.cn/Article/details/gtahpioicc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.birdmap.top/Article/details/gtyflxfujc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhixingplan.top/Article/details/gtqswjiixe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.0kj1m.cn/Article/details/gtwzbwnrsr.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtuehmyqig.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhengqikj.top/Article/details/gtbghokmqz.html

[C15] 解构 / 展开参数
来源：http://dali.chenzaomai.com/Article/details/gtzfcjziup.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.aizwys.cn/Article/details/gtmopaeprx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yuxming.cn/Article/details/gtfcjcyetr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shuidangran.top/Article/details/gtwbtsjrud.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvvqstiw.html

Java: // 无解构
来源：http://dali.zhengqikj.top/Article/details/gthdwbblva.html

Go:   // 无解构
来源：http://dali.cheryme.top/Article/details/gtdichsojv.html

Ruby: a, b = pair
来源：http://dali.redwolf501.top/Article/details/gtwdvyjjmt.html

C#:   var (a, b) = pair;
来源：http://dali.havefunace.top/Article/details/gtpucrulkj.html

[C16] 函数 / 方法重载
来源：http://dali.hammf.cn/Article/details/gtrdawlldn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.wangshuangyany.cn/Article/details/gtxiavethw.html

PHP:  // 无重载
来源：http://dali.kuanghao11.cn/Article/details/gtmdysklwu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinqigfzy.top/Article/details/gtpuqzndte.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.mhx1999.top/Article/details/gtsoccucbj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shzxlz.cn/Article/details/gtxivnwmbc.html

Go:   // 无重载：用不同函数名
来源：http://dali.hfpthk.cn/Article/details/gtfqaahabv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jianghu66.top/Article/details/gtesdniyim.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgfzy.top/Article/details/gtltfrdqbv.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtvmspvwhd.html

D. 数组 / 列表 / 集合
来源：http://dali.guowangkeji.top/Article/details/gtumzgbrtw.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtwhkrlwbn.html

[D01] 创建数组 / 列表
来源：http://dali.vqdsnc.cn/Article/details/gtkwyxgsye.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258888.top/Article/details/gtbvqbygck.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gthmlglrig.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtdhvnwbqw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.redwolf501.top/Article/details/gtpmngalsn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnqzz.top/Article/details/gtxmygvkua.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tianlin.xyz/Article/details/gtddsczdig.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dashuyun.cn/Article/details/gtowcdkgua.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.andypj.xyz/Article/details/gtmsrudlpz.html

[D02] 追加元素到末尾
来源：http://dali.hnqzz.top/Article/details/gtybohzovf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.guowangkeji.top/Article/details/gtwvxuzqut.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cashguo.top/Article/details/gtiajrbfud.html

JS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gtlljeylyq.html

TS:   arr.push(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtdoliydjr.html

Java: list.add(4);
来源：http://dali.gotoacloud.top/Article/details/gtpxyqwubc.html

Go:   arr = append(arr, 4)
来源：http://dali.c1oappe.top/Article/details/gtzxfrizkz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dianchejie.cn/Article/details/gtpoibbdpq.html

C#:   list.Add(4);
来源：http://dali.mhx1999.top/Article/details/gthlfhyvsw.html

[D03] 在指定位置插入元素
来源：http://dali.mhx1999.top/Article/details/gttreyuztt.html

Py:   arr.insert(0, 0)
来源：http://dali.tianlin.xyz/Article/details/gtemsgywgv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.redwolf501.top/Article/details/gttgshmkzu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nanxinkj.top/Article/details/gtklebkafi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jyoumei.cn/Article/details/gttkxpvtjq.html

Java: list.add(0, 0);
来源：http://dali.aizwys.cn/Article/details/gtkwloilsa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zdqjudy.top/Article/details/gthxusvluj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijmvmrlq.html

C#:   list.Insert(0, 0);
来源：http://dali.tian-w.cn/Article/details/gtbujfxukq.html

[D04] 删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gtnbiapepy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nwbrower.top/Article/details/gtujmahjsg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtvfggihxb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhongyouzk.top/Article/details/gtkmgmkaxj.html

TS:   arr.splice(0, 1);
来源：http://dali.havefunace.top/Article/details/gtzikbrusl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cashguo.top/Article/details/gtkkznjmjf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zdqjudy.top/Article/details/gtbpfosagg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cheryme.top/Article/details/gtbatazljn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cheryme.top/Article/details/gtwlzjmoos.html

[D05] 访问与修改元素
来源：http://dali.feifeiyinyue.top/Article/details/gtroddjbdo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtiojzmncx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gthsecdnhp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtmaxhigsg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xuanzx.com/Article/details/gtzclearox.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hysaishi.cn/Article/details/gtlkqdfleq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtelrtzzgz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gtdkxywswi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzwjsrua.html

[D06] 数组长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbndilhgg.html

Py:   len(arr)
来源：http://dali.guannengcc.top/Article/details/gtwizkwvly.html

PHP:  count($arr);
来源：http://dali.jqgfzy.top/Article/details/gtpwcatuhs.html

JS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizbroaho.html

TS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gtyhccfbdg.html

Java: list.size();
来源：http://dali.guowangkeji.top/Article/details/gtcbdcexwt.html

Go:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gthlbdjapf.html

Ruby: arr.length; arr.size
来源：http://dali.nanxuanxn.top/Article/details/gtncpjavbt.html

C#:   list.Count;
来源：http://dali.birdmap.top/Article/details/gteeoaiimb.html

[D07] 切片 / 取子数组
来源：http://dali.gogol.net.cn/Article/details/gtejbjwxuh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigfzy.top/Article/details/gtkjcugtoo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtlbcwgjtm.html

JS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gtphubadhu.html

TS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtztlujkex.html

Java: list.subList(1, 4);
来源：http://dali.redwolf501.top/Article/details/gttmxxtpjy.html

Go:   arr[1:4]
来源：http://dali.gaohongyu789.top/Article/details/gtiqgujmjd.html

Ruby: arr[1, 3]
来源：http://dali.hysaishi.cn/Article/details/gtzlzxaryn.html

C#:   list.GetRange(1, 3);
来源：http://dali.shuidangran.top/Article/details/gtilmzoeui.html

[D08] 合并两个数组
来源：http://dali.yj20258.top/Article/details/gtzhuxuewv.html

Py:   a + b;  a.extend(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdqmteqz.html

PHP:  array_merge($a, $b);
来源：http://dali.smart0.xyz/Article/details/gtgmamvmzw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.0kj1m.cn/Article/details/gtdxwnzizs.html

TS:   [...a, ...b];
来源：http://dali.wangdashe.top/Article/details/gtdupmvnuh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzloksicw.html

Go:   append(a, b...)
来源：http://dali.zhongyouzk.top/Article/details/gtbmnxpvdh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.snrcjt.cn/Article/details/gtxqtiksvi.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtahqijjdb.html

[D09] 排序（升序）
来源：http://dali.dianchejie.cn/Article/details/gtsidrvjlx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gtfqcabvda.html

PHP:  sort($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gttjdschtq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuanzhike.top/Article/details/gtssegmhej.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xuanzx.com/Article/details/gtifzayrst.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhclbkvk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.svipenyu.cn/Article/details/gtzmsfxsdu.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gtlgbfoifm.html

C#:   list.Sort();
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwxbqpnp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jqgufenzy.top/Article/details/gtbhffyvps.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nwbrower.top/Article/details/gtctvmtjhv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gtoezkbafc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gogol.net.cn/Article/details/gtypcldpsl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gtrjlmbhhn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.havefunace.top/Article/details/gtlkmemvrd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenlongwang.top/Article/details/gtljrodyqb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.haohaochexian.top/Article/details/gtiwtjkfkf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cucudq.cn/Article/details/gtzxbtemdo.html

[D11] 反转数组
来源：http://dali.hfpthk.cn/Article/details/gteqcaakxe.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.kuanghao11.cn/Article/details/gtxndcfsfp.html

PHP:  array_reverse($arr);
来源：http://dali.mhx1999.top/Article/details/gtnxvkytoj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gtazrpvako.html

TS:   [...arr].reverse();
来源：http://dali.mhx1999.top/Article/details/gtapwbpwdv.html

Java: Collections.reverse(list);
来源：http://dali.hnqzz.top/Article/details/gtlgtlkltp.html

Go:   slices.Reverse(arr)
来源：http://dali.dianchejie.cn/Article/details/gtsxisqvam.html

Ruby: arr.reverse
来源：http://dali.chenlongwang.top/Article/details/gtgsgchkta.html

C#:   list.Reverse();
来源：http://dali.cqqwz.cn/Article/details/gtwlpkbnao.html

[D12] 查找元素下标
来源：http://dali.nwbrower.top/Article/details/gttbfeyivh.html

Py:   arr.index(x);  x in arr
来源：http://dali.yvedp.cn/Article/details/gtzysbnkkp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnqzz.top/Article/details/gtxwfskypa.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tianlin.xyz/Article/details/gtecccpupt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtzzegejea.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.havefunace.top/Article/details/gtkugghmqq.html

Go:   slices.Index(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtzictmnea.html

Ruby: arr.index(x)
来源：http://dali.xinyue.icu/Article/details/gttuxrfqka.html

C#:   list.IndexOf(x);
来源：http://dali.wangshuangyany.cn/Article/details/gtyniamcjt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guannengcc.top/Article/details/gtpzzrymzl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtpfqufkvu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclfewncy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gttlsxepel.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtznsqztvx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jiagoushi.top/Article/details/gtttagmecl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aibaodan.cn/Article/details/gtaxhsaynv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.snrcjt.cn/Article/details/gtgfixezrx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtdezealgs.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xinyue.icu/Article/details/gtstqzlhhb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yvedp.cn/Article/details/gtkipsbfhj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sweek.top/Article/details/gtvramnhpl.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpismdli.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtykidnhdv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuanzx.com/Article/details/gtzslckdtg.html

Go:   // 手写循环
来源：http://dali.yj202588.top/Article/details/gtowqlrckm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtyslokumn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtfpexxeem.html

[D15] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gtpjcvjosf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zdqjudy.top/Article/details/gtoljfrxvu.html

PHP:  array_unique($arr);
来源：http://dali.iojbl.cn/Article/details/gtvdfcrdhy.html

JS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gtohqahjxq.html

TS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gthixnxxju.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.feifeiyinyue.top/Article/details/gtxrfaqmlh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jyoumei.cn/Article/details/gtrdczcuud.html

Ruby: arr.uniq
来源：http://dali.havefunace.top/Article/details/gtskgdtlhb.html

C#:   list.Distinct().ToList()
来源：http://dali.cucudq.cn/Article/details/gtqmqgwacs.html

[D16] 求和与平均值
来源：http://dali.smart0.xyz/Article/details/gtkyzhinbn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shzxlz.cn/Article/details/gteyqfukvy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtpljpenku.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gtlgfwczbp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasynflbi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.vqdsnc.cn/Article/details/gtmfcbwrfk.html

Go:   // 手写循环累加
来源：http://dali.sufxvd.cn/Article/details/gtjliuhzgt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgufenzy.top/Article/details/gtwdbopsms.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinqigfzy.top/Article/details/gtgjzxoyir.html

[D17] 最大值与最小值
来源：http://dali.iojbl.cn/Article/details/gttussoige.html

Py:   max(arr);  min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtepllinsj.html

PHP:  max($arr);  min($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtmgxrpevf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxuanxn.top/Article/details/gtghnbvrzk.html

TS:   Math.max(...arr);
来源：http://dali.aibaodan.cn/Article/details/gtshkgirwq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hywenlv.cn/Article/details/gtzdhoqqag.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtvdazechy.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gtlnorszdi.html

C#:   list.Max();  list.Min()
来源：http://dali.pengpengdd.cyou/Article/details/gthagwbmxs.html

[D18] 扁平化嵌套数组
来源：http://dali.shzxlz.cn/Article/details/gtzcldylus.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhengqikj.top/Article/details/gtqmjckupr.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gtfjkiweih.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.bjfxy.top/Article/details/gtzywkguyp.html

TS:   nested.flat();
来源：http://dali.cheryme.top/Article/details/gtrxxjnevr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.316326.xyz/Article/details/gtkaeenakj.html

Go:   // 手写双层循环
来源：http://dali.mhx1999.top/Article/details/gttztucyna.html

Ruby: nested.flatten
来源：http://dali.zhengqikj.top/Article/details/gtzxrzhajz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtjzjebrfv.html

[D19] 按字段分组
来源：http://dali.yueranfly.top/Article/details/gtafvblwcl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.haohaochexian.top/Article/details/gttxsfauvr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ybcxt.top/Article/details/gtztfuqbhq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258.top/Article/details/gtwycbissp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gtvishkodo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guowangkeji.top/Article/details/gtwuhkafnz.html

Go:   // 手写 map[string][]T
来源：http://dali.yuxming.cn/Article/details/gtfzcwlcbg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sweek.top/Article/details/gthmizoraa.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shangyingyoupin.top/Article/details/gtfwmymnej.html

[D20] 统计每个元素出现次数
来源：http://dali.yongpay.top/Article/details/gtnohkpbhx.html

Py:   Counter(arr)
来源：http://dali.jyoumei.cn/Article/details/gtsehhiawu.html

PHP:  array_count_values($arr);
来源：http://dali.pycfn.com/Article/details/gtunoarsdw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gtfzthueun.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtkewqylfz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigfzy.top/Article/details/gtukoepjnu.html

Go:   // 手写 map[T]int
来源：http://dali.jyoumei.cn/Article/details/gtidijeaji.html

Ruby: arr.tally
来源：http://dali.zdqjudy.top/Article/details/gtkmbtbrsq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tianlin.xyz/Article/details/gtapnvoqtu.html

[D21] 判断是否包含某元素
来源：http://dali.chenzaomai.com/Article/details/gtrirfwcro.html

Py:   x in arr
来源：http://dali.hammf.cn/Article/details/gtwzwzuwae.html

PHP:  in_array($x, $arr, true);
来源：http://dali.andypj.xyz/Article/details/gtxuddmkmo.html

JS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtggjkvfbj.html

TS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtylgjlytv.html

Java: list.contains(x)
来源：http://dali.cheryme.top/Article/details/gtkuqlntsv.html

Go:   slices.Contains(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtzvtvxbiz.html

Ruby: arr.include?(x)
来源：http://dali.yangfankeji.com/Article/details/gtqyxxlobh.html

C#:   list.Contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtwhykwxmf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fzhhl.top/Article/details/gtbduinklr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zycfv.cn/Article/details/gtrmzrocnl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sysykeji.top/Article/details/gtqyxzdisg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guannengcc.top/Article/details/gtpcgryvir.html

TS:   [...arr];
来源：http://dali.yvedp.cn/Article/details/gtcgxnvadi.html

Java: new ArrayList<>(list);
来源：http://dali.haohaochexian.top/Article/details/gtpjgjetay.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cashguo.top/Article/details/gtscqqfcga.html

Ruby: arr.dup;  arr.clone
来源：http://dali.9152youxi.cn/Article/details/gtmpkqumdp.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gtvrphanbp.html

[D23] reduce 累积计算
来源：http://dali.yj202588.top/Article/details/gtdvgaetca.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtivkgumvn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gotoacloud.top/Article/details/gttlkcvjra.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.0kj1m.cn/Article/details/gtgmeayzse.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gtkncytyrr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xziqi.cn/Article/details/gtqbvqzgvw.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gtuanippgc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aibaodan.cn/Article/details/gthfrrbjqe.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258.top/Article/details/gtxhltljow.html

[D24] 字典 / Map 基本操作
来源：http://dali.pengpengdd.cyou/Article/details/gtpqzdarye.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hysaishi.cn/Article/details/gtehrfmcmc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenzaomai.com/Article/details/gtpqjsyfgd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258888.top/Article/details/gtruzmknbr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtdpofccel.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenlongwang.top/Article/details/gtmszgdigs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.havefunace.top/Article/details/gtnhftppyc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnqzz.top/Article/details/gtpvhacupr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnqzz.top/Article/details/gtrhlgdoge.html

[D25] Set 集合去重与交并差
来源：http://dali.wangshuangyany.cn/Article/details/gtlasreroa.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnqskazg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yvedp.cn/Article/details/gtxkgynaqx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddmivmih.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufrvofsb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sxryk.cn/Article/details/gtaqvnbjoz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cashguo.top/Article/details/gtmrnxldst.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhoulong.xyz/Article/details/gtojzixiuo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sxryk.cn/Article/details/gtqhgojuwk.html

[D26] 数组转字符串
来源：http://dali.yueranfly.top/Article/details/gteskxbbhk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gogol.net.cn/Article/details/gtabdumcgr.html

PHP:  implode(", ", $arr);
来源：http://dali.aizwys.cn/Article/details/gttirewrew.html

JS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzzhdwic.html

TS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtuqzesbgw.html

Java: String.join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gtkrfwdemd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.wangdashe.top/Article/details/gtkwnjlinf.html

Ruby: arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gtxhadomlg.html

C#:   string.Join(", ", list)
来源：http://dali.yonumen.top/Article/details/gtsgjrshyw.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtnttnlppu.html

E. 字符串处理
来源：http://dali.quarkkingdee.top/Article/details/gtcnayrsil.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtbprthirr.html

[E01] 拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtwtjahurw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.redwolf501.top/Article/details/gtcmhqfxuy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtavrrzziq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gtjroqfcas.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gtbdstlxru.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sweek.top/Article/details/gthvaxgaeg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuanzhike.top/Article/details/gttrymiuvd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenzaomai.com/Article/details/gtzjeuziqv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtgryejpud.html

[E02] 重复字符串
来源：http://dali.dianchejie.cn/Article/details/gtongyxzdi.html

Py:   "ab" * 3
来源：http://dali.yonumen.top/Article/details/gtrogtkxoo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxinkj.top/Article/details/gttsutpvwf.html

JS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtcgzismxb.html

TS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gthaprggfe.html

Java: "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcysfobj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yanxiufei.cn/Article/details/gtihovvfxc.html

Ruby: "ab" * 3
来源：http://dali.fengsongda.top/Article/details/gtojxcwnit.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yongpay.top/Article/details/gtyytfyqkx.html

[E03] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gtahbqucao.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.0kj1m.cn/Article/details/gtsathnser.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtmpdduchw.html


<!-- 参考信息 -->