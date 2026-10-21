代发 wailian999

Ruby: require "json"; require_relative "./util"
来源：http://dali.aizwys.cn/Article/details/gtexjaymcn.html

C#:   using System.Text;
来源：http://dali.nanxinkj.top/Article/details/gtrxbamdji.html

[C12] 立即执行函数 IIFE
来源：http://dali.yangfankeji.com/Article/details/gtkznkzmhs.html

Py:   (lambda: print("run"))()
来源：http://dali.hywenlv.cn/Article/details/gtgzhmohfp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.daria6918.cn/Article/details/gtmooprkwg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ivvv.top/Article/details/gtezprbsbj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gzhubu.top/Article/details/gtbgnnjibf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hfpthk.cn/Article/details/gtybprakpu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ppjwa.cn/Article/details/gtrmbxeido.html

Ruby: -> { puts "run" }.call
来源：http://dali.shzxlz.cn/Article/details/gtovydjxug.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jiagoushi.top/Article/details/gtgmthujsq.html

[C13] 类型声明 / 类型注解
来源：http://dali.jqgfzy.top/Article/details/gtrkgxezxk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtjxdciomy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gtfrrforbh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ppjwa.cn/Article/details/gtjzgigghl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtiwgjjtjs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtueofwjzk.html

Go:   func add(a, b int) int
来源：http://dali.zycfv.cn/Article/details/gtvwuoxrpp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xziqi.cn/Article/details/gtlvvzvlhy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yonumen.top/Article/details/gtmtmgrdme.html

[C14] 泛型函数
来源：http://dali.smart0.xyz/Article/details/gtjqkkwzom.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.vqdsnc.cn/Article/details/gtyvsjrvwn.html

PHP:  // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtoxbnxlac.html

JS:   // 无泛型
来源：http://dali.sweek.top/Article/details/gtyzmaxuct.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.316326.xyz/Article/details/gtiewtkwdp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.svipenyu.cn/Article/details/gtstyrumqd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dashuyun.cn/Article/details/gtznbtgbuj.html

Ruby: # 无泛型
来源：http://dali.pycfn.com/Article/details/gtqttjktae.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yanxiufei.cn/Article/details/gtexiozfjc.html

[C15] 解构 / 展开参数
来源：http://dali.yanxiufei.cn/Article/details/gthagnhgoh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yanxiufei.cn/Article/details/gtqdzwmbmx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.snrcjt.cn/Article/details/gtkqewgcko.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sxryk.cn/Article/details/gtqnsimtjv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj202588.top/Article/details/gtezoseims.html

Java: // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtaixisfjs.html

Go:   // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gtccijvzhd.html

Ruby: a, b = pair
来源：http://dali.andypj.xyz/Article/details/gtnaatxydj.html

C#:   var (a, b) = pair;
来源：http://dali.gaohongyu789.top/Article/details/gtlmuhrohr.html

[C16] 函数 / 方法重载
来源：http://dali.yonumen.top/Article/details/gteppooemj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.iojbl.cn/Article/details/gtnlqhvmuz.html

PHP:  // 无重载
来源：http://dali.zhixingplan.top/Article/details/gtufvnpevk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmphqyuoe.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pengpengdd.cyou/Article/details/gtadirgwqu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pycfn.com/Article/details/gtccsuddjm.html

Go:   // 无重载：用不同函数名
来源：http://dali.nwbrower.top/Article/details/gtcghtypbg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jiagoushi.top/Article/details/gtohszfuia.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.c1oappe.top/Article/details/gtknouspwv.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtqmekkcic.html

D. 数组 / 列表 / 集合
来源：http://dali.sweek.top/Article/details/gtednuvjuv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmowsviqv.html

[D01] 创建数组 / 列表
来源：http://dali.yangfankeji.com/Article/details/gtaradzaax.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvdgbtvl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.iojbl.cn/Article/details/gtchchkttg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.haohaochexian.top/Article/details/gtpdrunmxd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhengqikj.top/Article/details/gtggscvegn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fzhhl.top/Article/details/gtgxyotrru.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xuanzx.com/Article/details/gtagdyoots.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gogol.net.cn/Article/details/gtgnsnhsec.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhgtycly.html

[D02] 追加元素到末尾
来源：http://dali.ydzc1.top/Article/details/gtvilchezn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shangyingyoupin.top/Article/details/gthlaxnqab.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xinyue.icu/Article/details/gtqpoiozbx.html

JS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gtuwzyvony.html

TS:   arr.push(4);
来源：http://dali.yj202588.top/Article/details/gtijuazwbe.html

Java: list.add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtmxxiioun.html

Go:   arr = append(arr, 4)
来源：http://dali.daria6918.cn/Article/details/gtjfmzigsd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.0kj1m.cn/Article/details/gttbarctzw.html

C#:   list.Add(4);
来源：http://dali.mhx1999.top/Article/details/gtkxxcttle.html

[D03] 在指定位置插入元素
来源：http://dali.jqgfzy.top/Article/details/gtvrqlfekd.html

Py:   arr.insert(0, 0)
来源：http://dali.redwolf501.top/Article/details/gtqmfdlkyr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hfpthk.cn/Article/details/gtewoifdko.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.mhx1999.top/Article/details/gtqwntimnc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yueranfly.top/Article/details/gtqptarhib.html

Java: list.add(0, 0);
来源：http://dali.iojbl.cn/Article/details/gtltbnmqnb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hysaishi.cn/Article/details/gtnckfdjre.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.iojbl.cn/Article/details/gtikcnjina.html

C#:   list.Insert(0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtsrwhdvmp.html

[D04] 删除元素
来源：http://dali.yanxiufei.cn/Article/details/gttxmlhndo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.daxiang520.top/Article/details/gtdnpkzmxs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yangfankeji.com/Article/details/gtbreyetty.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgufenzy.top/Article/details/gtoksluueh.html

TS:   arr.splice(0, 1);
来源：http://dali.yj202588.top/Article/details/gtjgqsbfia.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtdciaqitx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dashuyun.cn/Article/details/gtsorpqoik.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.haohaochexian.top/Article/details/gtgpzgogxh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yongpay.top/Article/details/gtsjkpnhfg.html

[D05] 访问与修改元素
来源：http://dali.daria6918.cn/Article/details/gtwcsxcyyf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gtgtoydiyw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtjnxlkylf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cheryme.top/Article/details/gtupwrnzcg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gaohongyu789.top/Article/details/gtxdwamxie.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtlztxeo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gtwvjngana.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmvtcsqw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gtdyujfxjm.html

[D06] 数组长度
来源：http://dali.sxryk.cn/Article/details/gtwfhqaoxs.html

Py:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqaraqxg.html

PHP:  count($arr);
来源：http://dali.hammf.cn/Article/details/gtttyiryvn.html

JS:   arr.length
来源：http://dali.c1oappe.top/Article/details/gtfttdhwvf.html

TS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gtkisubrmz.html

Java: list.size();
来源：http://dali.hnqzz.top/Article/details/gtzdognjqu.html

Go:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgltrthir.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258.top/Article/details/gtykumbxst.html

C#:   list.Count;
来源：http://dali.tanke756.top/Article/details/gtyksvnaxq.html

[D07] 切片 / 取子数组
来源：http://dali.yj20258.top/Article/details/gtehdygwqe.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhixingplan.top/Article/details/gtialyhbdo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtcudigbdj.html

JS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtdzzwezob.html

TS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtpsdugqeu.html

Java: list.subList(1, 4);
来源：http://dali.tian-w.cn/Article/details/gtruaiprwm.html

Go:   arr[1:4]
来源：http://dali.gotoacloud.top/Article/details/gthwgyatfo.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtqgqavfsd.html

C#:   list.GetRange(1, 3);
来源：http://dali.shuidangran.top/Article/details/gtzamnrfpj.html

[D08] 合并两个数组
来源：http://dali.mhx1999.top/Article/details/gtpivkcqgx.html

Py:   a + b;  a.extend(b)
来源：http://dali.havefunace.top/Article/details/gtqxknblqn.html

PHP:  array_merge($a, $b);
来源：http://dali.guowangkeji.top/Article/details/gtrpyfpwaq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.kuanghao11.cn/Article/details/gtsyzvhsvk.html

TS:   [...a, ...b];
来源：http://dali.guowangkeji.top/Article/details/gttdoggajj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sxryk.cn/Article/details/gtzuqmsqlo.html

Go:   append(a, b...)
来源：http://dali.jqgfzy.top/Article/details/gtzoamlcsj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fzhhl.top/Article/details/gtjipnnelq.html

C#:   a.Concat(b).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtfzjqqotf.html

[D09] 排序（升序）
来源：http://dali.guannengcc.top/Article/details/gtnrbdropy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gtrgshwxfa.html

PHP:  sort($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtyylxuffw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fzhhl.top/Article/details/gtmcwnnles.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrmteoxq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jiagoushi.top/Article/details/gtqmvrsbll.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gtjhszerna.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gtqtjgzztz.html

C#:   list.Sort();
来源：http://dali.jinqigufen.top/Article/details/gtpddcexxh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jyoumei.cn/Article/details/gtwxapddwf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yuxming.cn/Article/details/gtxyqrylus.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jianghu66.top/Article/details/gthaqkdsre.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xinyue.icu/Article/details/gtsdsadvyw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgfzy.top/Article/details/gtupfahcei.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yvedp.cn/Article/details/gtmzkpgzvo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yongpay.top/Article/details/gtxsrzxsla.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhongyouzk.top/Article/details/gtifwwgkjy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tianlin.xyz/Article/details/gthxdvnsry.html

[D11] 反转数组
来源：http://dali.sufxvd.cn/Article/details/gthykrrqnk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.guowangkeji.top/Article/details/gtsampydhu.html

PHP:  array_reverse($arr);
来源：http://dali.yj20258.top/Article/details/gtymuxopny.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cashguo.top/Article/details/gtxthcdtuy.html

TS:   [...arr].reverse();
来源：http://dali.yj202588.top/Article/details/gtcxtckcka.html

Java: Collections.reverse(list);
来源：http://dali.hywenlv.cn/Article/details/gtlpgsqkkx.html

Go:   slices.Reverse(arr)
来源：http://dali.yangfankeji.com/Article/details/gtunwgjiqi.html

Ruby: arr.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtsyaoeuof.html

C#:   list.Reverse();
来源：http://dali.yonumen.top/Article/details/gttauyjvpo.html

[D12] 查找元素下标
来源：http://dali.xylfe.cn/Article/details/gtefqogjfa.html

Py:   arr.index(x);  x in arr
来源：http://dali.aibaodan.cn/Article/details/gtbpabwufr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yongpay.top/Article/details/gtgeejnnxw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdtvwkxs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtulujvdeg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ivvv.top/Article/details/gtffvglxae.html

Go:   slices.Index(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtvpyxiddb.html

Ruby: arr.index(x)
来源：http://dali.smart0.xyz/Article/details/gtteetevuu.html

C#:   list.IndexOf(x);
来源：http://dali.mhx1999.top/Article/details/gtjmfgptai.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gogol.net.cn/Article/details/gtvwnvfaaw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ydzc1.top/Article/details/gtpswpogzn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258.top/Article/details/gtnzsfomdy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtwxfptglr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xuanzx.com/Article/details/gtvrvwgrft.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xylfe.cn/Article/details/gttjtwtapb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shzxlz.cn/Article/details/gtroizrqym.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenzaomai.com/Article/details/gtfujesfpx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtjzkybtts.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dashuyun.cn/Article/details/gttegxfnfl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangdashe.top/Article/details/gtjwfdcqjc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cqqwz.cn/Article/details/gtsdzqikow.html

JS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gtalckejjg.html

TS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtavfkdnjj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtftqefahy.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gtmoztxnko.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtxjcwwyvh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtooaaudon.html

[D15] 去重
来源：http://dali.sweek.top/Article/details/gtvhmtsnrg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sxryk.cn/Article/details/gtkqineylv.html

PHP:  array_unique($arr);
来源：http://dali.daxiang520.top/Article/details/gtcavmefvy.html

JS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtvescwkje.html

TS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gtckmwbdhr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dianchejie.cn/Article/details/gtajfnmzbo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shuidangran.top/Article/details/gtjnailhia.html

Ruby: arr.uniq
来源：http://dali.xylfe.cn/Article/details/gtngjkgetn.html

C#:   list.Distinct().ToList()
来源：http://dali.yj202588.top/Article/details/gthhzygmlp.html

[D16] 求和与平均值
来源：http://dali.jiagoushi.top/Article/details/gtukhdumff.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenlongwang.top/Article/details/gtsbdhgqjj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.9152youxi.cn/Article/details/gtqevmybfy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gtgueyuzmz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtpvfrjuos.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hfpthk.cn/Article/details/gttzinucji.html

Go:   // 手写循环累加
来源：http://dali.pycfn.com/Article/details/gturdsyuxo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hywenlv.cn/Article/details/gtkivqkovn.html

C#:   list.Sum();  list.Average()
来源：http://dali.aizwys.cn/Article/details/gtysepukvs.html

[D17] 最大值与最小值
来源：http://dali.yj20258.top/Article/details/gtlyqhsbfx.html

Py:   max(arr);  min(arr)
来源：http://dali.hywenlv.cn/Article/details/gtmcnqdghe.html

PHP:  max($arr);  min($arr);
来源：http://dali.quarkkingdee.top/Article/details/gthxjjysls.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxuanxn.top/Article/details/gtkhzlkguc.html

TS:   Math.max(...arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtanknlovn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sysykeji.top/Article/details/gtzqktdjoe.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiftwobds.html

Ruby: arr.max;  arr.min
来源：http://dali.guannengcc.top/Article/details/gtowennjme.html

C#:   list.Max();  list.Min()
来源：http://dali.316326.xyz/Article/details/gtyzetrrza.html

[D18] 扁平化嵌套数组
来源：http://dali.hnqzz.top/Article/details/gtxaljooex.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aizwys.cn/Article/details/gtmnlfwrwe.html

PHP:  array_merge(...$nested);
来源：http://dali.gzhubu.top/Article/details/gtuqmfcgvf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gtlaniuois.html

TS:   nested.flat();
来源：http://dali.cashguo.top/Article/details/gteyxmvlzy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gzhubu.top/Article/details/gtheechgko.html

Go:   // 手写双层循环
来源：http://dali.hysaishi.cn/Article/details/gtgbfjhuxv.html

Ruby: nested.flatten
来源：http://dali.xuetiantiany.cn/Article/details/gtiyfufmxf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtcrfkoank.html

[D19] 按字段分组
来源：http://dali.jyoumei.cn/Article/details/gtcsppcgnt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daria6918.cn/Article/details/gtxrfsqhrk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj202588.top/Article/details/gtehzupyyf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyxzwxvh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gtavhptxfg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hfpthk.cn/Article/details/gtspfrralx.html

Go:   // 手写 map[string][]T
来源：http://dali.tanke756.top/Article/details/gtynakzhtk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258888.top/Article/details/gtrkunkdbj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.feifeiyinyue.top/Article/details/gtedhvoulu.html

[D20] 统计每个元素出现次数
来源：http://dali.hnqzz.top/Article/details/gtqohqdbht.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gtryuokjxu.html

PHP:  array_count_values($arr);
来源：http://dali.tianlin.xyz/Article/details/gtplmoquxm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gtkdxdytin.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gtloyryynh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yueranfly.top/Article/details/gtlxugdswe.html

Go:   // 手写 map[T]int
来源：http://dali.yj20258.top/Article/details/gtweoghhlb.html

Ruby: arr.tally
来源：http://dali.ivvv.top/Article/details/gtgsweeddy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hammf.cn/Article/details/gtysjvtlha.html

[D21] 判断是否包含某元素
来源：http://dali.xinyue.icu/Article/details/gtyeznyktz.html

Py:   x in arr
来源：http://dali.jqgfzy.top/Article/details/gtikjkliou.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hammf.cn/Article/details/gtetqoupiw.html

JS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtuohbckpc.html

TS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gtcerpmhxf.html

Java: list.contains(x)
来源：http://dali.hnqzz.top/Article/details/gtosufmluh.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtslnoycjh.html

Ruby: arr.include?(x)
来源：http://dali.yvedp.cn/Article/details/gtnhrznxzv.html

C#:   list.Contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtdduebwxt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gtidzuatfe.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.316326.xyz/Article/details/gtwolkdypm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tianlin.xyz/Article/details/gtitrtizbv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.0kj1m.cn/Article/details/gtlyqsnhyd.html

TS:   [...arr];
来源：http://dali.smart0.xyz/Article/details/gtivunzhuu.html

Java: new ArrayList<>(list);
来源：http://dali.jianghu66.top/Article/details/gtkpkjerqb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.mhx1999.top/Article/details/gtpfcvudkx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cqqwz.cn/Article/details/gtuijjzxso.html

C#:   new List<int>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbypxovyp.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gtmkizqhrn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.havefunace.top/Article/details/gttowkyuct.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tianlin.xyz/Article/details/gtlsltgbun.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gtpjxdtzcm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtnkkdodwb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jianghu66.top/Article/details/gtfexljdob.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gttmlfxmzm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tanke756.top/Article/details/gtfkgwobcp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.quarkkingdee.top/Article/details/gtqshmkzaa.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdvubfgo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daria6918.cn/Article/details/gtmtmcceag.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sweek.top/Article/details/gtwxrdruwf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hysaishi.cn/Article/details/gtigohhajf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtabbztcra.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cucudq.cn/Article/details/gtyivdotiu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuanzhike.top/Article/details/gtyahkakye.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yongpay.top/Article/details/gtpabltxak.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daria6918.cn/Article/details/gtyofepyxs.html

[D25] Set 集合去重与交并差
来源：http://dali.hywenlv.cn/Article/details/gtdriaprum.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpazqbubx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nwbrower.top/Article/details/gtbubgtiog.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.c1oappe.top/Article/details/gtvdepffkc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daria6918.cn/Article/details/gtuljiqrtg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtrzagmawt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.mhx1999.top/Article/details/gtxsujqffv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtnmuuvkti.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.redwolf501.top/Article/details/gtqnkqbtzw.html

[D26] 数组转字符串
来源：http://dali.xuanzx.com/Article/details/gtolgcntkg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yongpay.top/Article/details/gtrermiymu.html

PHP:  implode(", ", $arr);
来源：http://dali.daria6918.cn/Article/details/gtijxakrls.html

JS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtyjcgfexg.html

TS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtuyywqy.html

Java: String.join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gttvssgkwi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.smart0.xyz/Article/details/gtkkosbnbc.html

Ruby: arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegsirrxd.html

C#:   string.Join(", ", list)
来源：http://dali.yongpay.top/Article/details/gtmrnwnjgm.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtdwkdxltb.html

E. 字符串处理
来源：http://dali.andypj.xyz/Article/details/gthvtleaod.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gthizivjas.html

[E01] 拼接字符串
来源：http://dali.yj202588.top/Article/details/gtmletomke.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daria6918.cn/Article/details/gtnaznlqms.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dashuyun.cn/Article/details/gtywfgdfay.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gtsqbyrjha.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gtoltakrzr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yvedp.cn/Article/details/gtlqsedqrm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zdqjudy.top/Article/details/gttqndambg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jlsjyb.cn/Article/details/gtfpyctujt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtqajgrejw.html

[E02] 重复字符串
来源：http://dali.316326.xyz/Article/details/gtloptswzv.html

Py:   "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gtmaaupghb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.andypj.xyz/Article/details/gtgojargpv.html

JS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtifrvaglw.html


<!-- 参考信息 -->