代发 wailian999

PHP:  (function () { echo "run"; })();
来源：http://dali.aizwys.cn/Article/details/gtewxnamfh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gtzqkybkxh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zycfv.cn/Article/details/gtednuohon.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.redwolf501.top/Article/details/gtrrqyltxi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ppjwa.cn/Article/details/gtktrzplvk.html

Ruby: -> { puts "run" }.call
来源：http://dali.meibo888.top/Article/details/gthahuhzov.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtkjcexvqh.html

[C13] 类型声明 / 类型注解
来源：http://dali.shangyingyoupin.top/Article/details/gtxuxcatkq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangdashe.top/Article/details/gtjzbbpfnj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtjcxstgwj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ppjwa.cn/Article/details/gtqwysrvos.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtnjdyhzxn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gthghogjka.html

Go:   func add(a, b int) int
来源：http://dali.ywan-chungtsiang.top/Article/details/gttahigeod.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guannengcc.top/Article/details/gtmlgyopnj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tian-w.cn/Article/details/gtcmvofobq.html

[C14] 泛型函数
来源：http://dali.feifeiyinyue.top/Article/details/gtzaqwkxxw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ivvv.top/Article/details/gtyublbbtw.html

PHP:  // 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gtlxnrlkll.html

JS:   // 无泛型
来源：http://dali.chenlongwang.top/Article/details/gtiupxflwm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtuuihbqpt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yvedp.cn/Article/details/gtzpbkkwyj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.redwolf501.top/Article/details/gtqntjdrwc.html

Ruby: # 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqanqbqtq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenzaomai.com/Article/details/gtslqscfee.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gtweqrfzsh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.svipenyu.cn/Article/details/gtddidqbok.html

PHP:  [$a, $b] = $pair;
来源：http://dali.wangshuangyany.cn/Article/details/gtwsekxhmb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gtkqlvtixv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.c1oappe.top/Article/details/gtbzgupnnb.html

Java: // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gtcxfpgpwj.html

Go:   // 无解构
来源：http://dali.bjfxy.top/Article/details/gtrsmsbgyz.html

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gtjkmwhhzg.html

C#:   var (a, b) = pair;
来源：http://dali.bjfxy.top/Article/details/gtltqdtapl.html

[C16] 函数 / 方法重载
来源：http://dali.yj202588.top/Article/details/gtszlzsbkp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.snrcjt.cn/Article/details/gtopohbegp.html

PHP:  // 无重载
来源：http://dali.nwbrower.top/Article/details/gtigndxszs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gogol.net.cn/Article/details/gtrckaamzl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yueranfly.top/Article/details/gtaqttmdlv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nwbrower.top/Article/details/gtylqwibex.html

Go:   // 无重载：用不同函数名
来源：http://dali.zdqjudy.top/Article/details/gtjhrclyqq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.meibo888.top/Article/details/gtxggjpbsq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tian-w.cn/Article/details/gtznjeahyv.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtinaacdxf.html

D. 数组 / 列表 / 集合
来源：http://dali.0kj1m.cn/Article/details/gtabqtwasi.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtjzuvyhyi.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258.top/Article/details/gtuvzasvwq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.snrcjt.cn/Article/details/gticlwqern.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aizwys.cn/Article/details/gtaikgkani.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ppjwa.cn/Article/details/gthcojtopm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aizwys.cn/Article/details/gtkboisvas.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.andypj.xyz/Article/details/gtvicvibkr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sysykeji.top/Article/details/gtkjskvffw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.svipenyu.cn/Article/details/gthtykllxt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yuxming.cn/Article/details/gttiobvjke.html

[D02] 追加元素到末尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbhdadlj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cqqwz.cn/Article/details/gthapvofxl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhoulong.xyz/Article/details/gtwyrridwu.html

JS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gtxmmyexrd.html

TS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gtgytgimja.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gtsosnjxqc.html

Go:   arr = append(arr, 4)
来源：http://dali.gzhubu.top/Article/details/gtxozhxloi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuanzx.com/Article/details/gtagdzodrz.html

C#:   list.Add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtwovefazb.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gtmdvfbatx.html

Py:   arr.insert(0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtepyfstup.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sweek.top/Article/details/gtghzdfgbq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdglxhab.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtnccvlibc.html

Java: list.add(0, 0);
来源：http://dali.meibo888.top/Article/details/gtftphbipx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xziqi.cn/Article/details/gtbyriolrt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zdqjudy.top/Article/details/gtansenzjc.html

C#:   list.Insert(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtkcnlkmll.html

[D04] 删除元素
来源：http://dali.dashuyun.cn/Article/details/gtwmtwjgtu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxinkj.top/Article/details/gtkfbrkemf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuanzhike.top/Article/details/gterjozrvd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hfpthk.cn/Article/details/gtjrxqelyu.html

TS:   arr.splice(0, 1);
来源：http://dali.gaohongyu789.top/Article/details/gtfflsfvsl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hywenlv.cn/Article/details/gttvqjxzth.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cheryme.top/Article/details/gtprmxhnzb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hammf.cn/Article/details/gtzkdangnj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhiwuduotai.top/Article/details/gtnyvdbkni.html

[D05] 访问与修改元素
来源：http://dali.guowangkeji.top/Article/details/gtrqcwcauu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gtyigdgpvb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtxhlvtgwo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtljojodxr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aibaodan.cn/Article/details/gtgiqfmrso.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhiwuduotai.top/Article/details/gtxhcsrnie.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gtpomsdtkh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gthyhdfqze.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtvlglbdcd.html

[D06] 数组长度
来源：http://dali.ydzc1.top/Article/details/gtydncubvm.html

Py:   len(arr)
来源：http://dali.gotoacloud.top/Article/details/gtoksaibfa.html

PHP:  count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtzbnoatuz.html

JS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtdddiudku.html

TS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gttqlxbzrh.html

Java: list.size();
来源：http://dali.yangfankeji.com/Article/details/gtliegpxpd.html

Go:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtzrceiiuh.html

Ruby: arr.length; arr.size
来源：http://dali.hfpthk.cn/Article/details/gtelahhzuj.html

C#:   list.Count;
来源：http://dali.jiagoushi.top/Article/details/gtqkjgxfgp.html

[D07] 切片 / 取子数组
来源：http://dali.guannengcc.top/Article/details/gtzkymhncq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.iojbl.cn/Article/details/gttdqboegw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwmhnxxn.html

JS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gttibogvhu.html

TS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtunzdickc.html

Java: list.subList(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gthtdinxhg.html

Go:   arr[1:4]
来源：http://dali.316326.xyz/Article/details/gtwpqhnala.html

Ruby: arr[1, 3]
来源：http://dali.haohaochexian.top/Article/details/gtatmdrwbj.html

C#:   list.GetRange(1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtrckuknrs.html

[D08] 合并两个数组
来源：http://dali.zycfv.cn/Article/details/gtplktprqw.html

Py:   a + b;  a.extend(b)
来源：http://dali.yonumen.top/Article/details/gtksbtajhe.html

PHP:  array_merge($a, $b);
来源：http://dali.hammf.cn/Article/details/gtniazgkyp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.snrcjt.cn/Article/details/gtxqjdlpfx.html

TS:   [...a, ...b];
来源：http://dali.cdnleiting.top/Article/details/gtqrohpqpr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zycfv.cn/Article/details/gtdwcrmcus.html

Go:   append(a, b...)
来源：http://dali.aibaodan.cn/Article/details/gtuqpqqtxp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xinyue.icu/Article/details/gtscsqdlgh.html

C#:   a.Concat(b).ToList()
来源：http://dali.xylfe.cn/Article/details/gtysjgdvyf.html

[D09] 排序（升序）
来源：http://dali.hysaishi.cn/Article/details/gtphcjgkkm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtvhdwuveg.html

PHP:  sort($arr);
来源：http://dali.nanxinkj.top/Article/details/gtnmyvcmsx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tianlin.xyz/Article/details/gtgziepopq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yonumen.top/Article/details/gttdsnkedd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cashguo.top/Article/details/gtyhyjdoov.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gtpicylsus.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gtllfxdgrz.html

C#:   list.Sort();
来源：http://dali.shangyingyoupin.top/Article/details/gtsxkhoawt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jlsjyb.cn/Article/details/gtvylamhmc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj20258888.top/Article/details/gthhxgpdkk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtwjlkrrcm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ivvv.top/Article/details/gtbbgyixfx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cheryme.top/Article/details/gticiwwxjy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhongyouzk.top/Article/details/gtmsjyhnud.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.quarkkingdee.top/Article/details/gtlguzbhkl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgfzy.top/Article/details/gtyvtwrhlb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.9152youxi.cn/Article/details/gtecmoxahy.html

[D11] 反转数组
来源：http://dali.jinqigufen.top/Article/details/gtlvixuknn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sysykeji.top/Article/details/gtizcggqwb.html

PHP:  array_reverse($arr);
来源：http://dali.mhx1999.top/Article/details/gtkszplxet.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sufxvd.cn/Article/details/gtzbcpncub.html

TS:   [...arr].reverse();
来源：http://dali.zhoulong.xyz/Article/details/gtwflveksy.html

Java: Collections.reverse(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtrbtqekpb.html

Go:   slices.Reverse(arr)
来源：http://dali.yuxming.cn/Article/details/gtwcxwfsnq.html

Ruby: arr.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtlxygtpfg.html

C#:   list.Reverse();
来源：http://dali.sufxvd.cn/Article/details/gtqhvlsbjj.html

[D12] 查找元素下标
来源：http://dali.wangshuangyany.cn/Article/details/gtjzwdelcr.html

Py:   arr.index(x);  x in arr
来源：http://dali.nanxinkj.top/Article/details/gtbvqzkbqd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zycfv.cn/Article/details/gtagkyqdwd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtlyjurufl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakxqvhdw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhengqikj.top/Article/details/gtsghojbee.html

Go:   slices.Index(arr, x)
来源：http://dali.yj20258.top/Article/details/gtndlkzoyg.html

Ruby: arr.index(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqbuucgn.html

C#:   list.IndexOf(x);
来源：http://dali.jqgufenzy.top/Article/details/gtgerolkjl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cdnleiting.top/Article/details/gtqgmqnphd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ydzc1.top/Article/details/gtgpikhcqb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jqgfzy.top/Article/details/gtjefvocvi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtwirfnccj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gttibhrsxs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtxvgeodvc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tanke756.top/Article/details/gtauufcena.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhixingplan.top/Article/details/gtfmtjpyzb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ybcxt.top/Article/details/gtlcnpgein.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xylfe.cn/Article/details/gthvzaftab.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cdnleiting.top/Article/details/gtflofcdaz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sxryk.cn/Article/details/gtalzeolcz.html

JS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gtmwykgbxr.html

TS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gtevsfcpze.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.havefunace.top/Article/details/gtuhkhyrll.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gtgstbozyz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtqhoecusy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtjsstcijk.html

[D15] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gturskebfx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjlwcdbo.html

PHP:  array_unique($arr);
来源：http://dali.yj20258.top/Article/details/gtfzujgsxn.html

JS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gtcfgizuxd.html

TS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gtyfmjpbyd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cashguo.top/Article/details/gtswyivzrl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangtech.top/Article/details/gturdmrzoz.html

Ruby: arr.uniq
来源：http://dali.daria6918.cn/Article/details/gtbzmcczdq.html

C#:   list.Distinct().ToList()
来源：http://dali.yangfankeji.com/Article/details/gtplrxxogw.html

[D16] 求和与平均值
来源：http://dali.feifeiyinyue.top/Article/details/gtzgdpxosw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xinyue.icu/Article/details/gtkztbcqqk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dashuyun.cn/Article/details/gtpuydyzld.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gttgekbzoa.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gtknsnrekn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gtbhjgipam.html

Go:   // 手写循环累加
来源：http://dali.hysaishi.cn/Article/details/gttquwzwxd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.snrcjt.cn/Article/details/gtpmzuoisu.html

C#:   list.Sum();  list.Average()
来源：http://dali.gotoacloud.top/Article/details/gtzrxvswcm.html

[D17] 最大值与最小值
来源：http://dali.guannengcc.top/Article/details/gtwbqdjzel.html

Py:   max(arr);  min(arr)
来源：http://dali.sysykeji.top/Article/details/gtazswbqsf.html

PHP:  max($arr);  min($arr);
来源：http://dali.redwolf501.top/Article/details/gtpuilzvqk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gthmrqdlvi.html

TS:   Math.max(...arr);
来源：http://dali.mhx1999.top/Article/details/gtsvjpikxw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dashuyun.cn/Article/details/gteuwycxco.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtzordrpaa.html

Ruby: arr.max;  arr.min
来源：http://dali.yuanzhike.top/Article/details/gtwreinson.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258888.top/Article/details/gtymbdlptx.html

[D18] 扁平化嵌套数组
来源：http://dali.wangshuangyany.cn/Article/details/gtyhaoefqt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.smart0.xyz/Article/details/gtygrhwkde.html

PHP:  array_merge(...$nested);
来源：http://dali.hongshengwenyu.top/Article/details/gtyjgfvnct.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvjhfmzp.html

TS:   nested.flat();
来源：http://dali.zhongyouzk.top/Article/details/gtmpxwsyzj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yonumen.top/Article/details/gtlrtwympc.html

Go:   // 手写双层循环
来源：http://dali.aizwys.cn/Article/details/gtfhmpjugm.html

Ruby: nested.flatten
来源：http://dali.zhiwuduotai.top/Article/details/gtwjzpkhif.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zycfv.cn/Article/details/gtewdkmwws.html

[D19] 按字段分组
来源：http://dali.xuetiantiany.cn/Article/details/gtxxkiikvr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daxiang520.top/Article/details/gtchyewtob.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dianchejie.cn/Article/details/gtvekrlsct.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shzxlz.cn/Article/details/gtqnzentpo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tanke756.top/Article/details/gtnlftuuzj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guannengcc.top/Article/details/gtssbbuxfs.html

Go:   // 手写 map[string][]T
来源：http://dali.jiagoushi.top/Article/details/gtlwkomlih.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.c1oappe.top/Article/details/gtgwvrnhqr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aizwys.cn/Article/details/gtuiugculw.html

[D20] 统计每个元素出现次数
来源：http://dali.zycfv.cn/Article/details/gtothfczvw.html

Py:   Counter(arr)
来源：http://dali.yvedp.cn/Article/details/gtukvalnrj.html

PHP:  array_count_values($arr);
来源：http://dali.cucudq.cn/Article/details/gtccwlsnya.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gtnvlzsyfw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.svipenyu.cn/Article/details/gtpafvxrqg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jianghu66.top/Article/details/gtgvrdngao.html

Go:   // 手写 map[T]int
来源：http://dali.redwolf501.top/Article/details/gtlklxbdbu.html

Ruby: arr.tally
来源：http://dali.xinyue.icu/Article/details/gthwhcvuvu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqauqcnxp.html

[D21] 判断是否包含某元素
来源：http://dali.guannengcc.top/Article/details/gteyceekst.html

Py:   x in arr
来源：http://dali.smart0.xyz/Article/details/gtfcdmejzg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yonumen.top/Article/details/gtyjxzwgwu.html

JS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtsdnrjizt.html

TS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gtnfnhakxs.html

Java: list.contains(x)
来源：http://dali.ydzc1.top/Article/details/gtywwgfxvs.html

Go:   slices.Contains(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtjrwvtwqp.html

Ruby: arr.include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gtaclhodkz.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gttmmabwno.html

[D22] 复制数组（避免共享引用）
来源：http://dali.mhx1999.top/Article/details/gtvzbeyqhp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gotoacloud.top/Article/details/gtqefljqfv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenlongwang.top/Article/details/gtjjamcikg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tian-w.cn/Article/details/gthmeljwvs.html

TS:   [...arr];
来源：http://dali.ydzc1.top/Article/details/gtnsxdgcyd.html

Java: new ArrayList<>(list);
来源：http://dali.shuidangran.top/Article/details/gtkchtmtvq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jyoumei.cn/Article/details/gtppiccjtr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ehwqpu.com/Article/details/gtabxmbnmt.html

C#:   new List<int>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtyeeoknie.html

[D23] reduce 累积计算
来源：http://dali.wangdashe.top/Article/details/gtornkafzo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cqqwz.cn/Article/details/gtgrihajih.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gzhubu.top/Article/details/gtgruytjxk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cucudq.cn/Article/details/gtunqltack.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gtdzdbuoqp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhengqikj.top/Article/details/gtvpubvfyg.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gtbwxwbsol.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tian-w.cn/Article/details/gthecuirqa.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gogol.net.cn/Article/details/gturclhvgc.html

[D24] 字典 / Map 基本操作
来源：http://dali.fzhhl.top/Article/details/gtrpnmrdvh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xziqi.cn/Article/details/gtvitwlmwx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sysykeji.top/Article/details/gttrvbedek.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtonntdvvm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtyglmvhhg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yangfankeji.com/Article/details/gtuahatbif.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fzhhl.top/Article/details/gtnwwhpfxf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqsvwgug.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.kuanghao11.cn/Article/details/gtuwfyychj.html

[D25] Set 集合去重与交并差
来源：http://dali.andypj.xyz/Article/details/gtduyaqoxi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yongpay.top/Article/details/gtfwdsbmke.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zycfv.cn/Article/details/gtizegfavk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ybcxt.top/Article/details/gtxmlmpnup.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shzxlz.cn/Article/details/gtozpfswws.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.smart0.xyz/Article/details/gtmtajqngh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuanzx.com/Article/details/gtnzjtbtzf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jlsjyb.cn/Article/details/gtezbmrpol.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aizwys.cn/Article/details/gtthcfkdfa.html

[D26] 数组转字符串
来源：http://dali.zdqjudy.top/Article/details/gtigzrowyo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.bjfxy.top/Article/details/gtfxosykqh.html

PHP:  implode(", ", $arr);
来源：http://dali.zdqjudy.top/Article/details/gtpajgsszy.html

JS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtfaiwwvnd.html

TS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtfmnxiuho.html

Java: String.join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gtbnqmbzxq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.redwolf501.top/Article/details/gtprrcngng.html

Ruby: arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtzntjovxj.html

C#:   string.Join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gtsfphnozm.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtvvcptdfh.html

E. 字符串处理
来源：http://dali.zdqjudy.top/Article/details/gtdwfpbbbw.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtwqapixld.html

[E01] 拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtqaulenta.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenzaomai.com/Article/details/gtihsphahd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gogol.net.cn/Article/details/gtwgmhvfyr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtzdbraatk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gtzekbdrfr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj202588.top/Article/details/gtgqojncny.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuanzhike.top/Article/details/gtbxxmyqgb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzptjqgo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtwrizyxjg.html

[E02] 重复字符串
来源：http://dali.zycfv.cn/Article/details/gtetokcexo.html

Py:   "ab" * 3
来源：http://dali.yonumen.top/Article/details/gtclpyovxd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtrniuvymm.html

JS:   "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gtwxnvhlta.html

TS:   "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gtcxiurind.html

Java: "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtbanmjrvg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zycfv.cn/Article/details/gtzasikano.html

Ruby: "ab" * 3
来源：http://dali.yj20258888.top/Article/details/gthlcitkro.html


<!-- 参考信息 -->