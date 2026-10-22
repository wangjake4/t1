代发 wailian999

Ruby: require "json"; require_relative "./util"
来源：http://dali.svipenyu.cn/Article/details/gt2zamlcxgj.html

C#:   using System.Text;
来源：http://dali.jlsjyb.cn/Article/details/gt2lznregxq.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhengqikj.top/Article/details/gt2lhckyhem.html

Py:   (lambda: print("run"))()
来源：http://dali.cqqwz.cn/Article/details/gt2ojxqfpoh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.bjfxy.top/Article/details/gt2liodhqet.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dianchejie.cn/Article/details/gt2uzfeixfq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gt2msnjkwfr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.guowangkeji.top/Article/details/gt2aexjgmvi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhoulong.xyz/Article/details/gt2xotgqsop.html

Ruby: -> { puts "run" }.call
来源：http://dali.daxiang520.top/Article/details/gt2atyhnnlk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhoulong.xyz/Article/details/gt2hpubfweo.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangshuangyany.cn/Article/details/gt2wopcywow.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nwbrower.top/Article/details/gt2ualhtroy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gt2jjtbagqa.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yueranfly.top/Article/details/gt2lfxjruen.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fuukeccs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2cqjcrhef.html

Go:   func add(a, b int) int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2thtxrdnf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hongshengwenyu.top/Article/details/gt2qnrftsqw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.c1oappe.top/Article/details/gt2ehkxtpnh.html

[C14] 泛型函数
来源：http://dali.jlsjyb.cn/Article/details/gt2lesffzqp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cqqwz.cn/Article/details/gt2asxhbbbl.html

PHP:  // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gt2hlqhvbqm.html

JS:   // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gt2avsphjlg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinqigufen.top/Article/details/gt2szwjoeqv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yonumen.top/Article/details/gt2czhrdztr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.guowangkeji.top/Article/details/gt2mjenlcux.html

Ruby: # 无泛型
来源：http://dali.cdnleiting.top/Article/details/gt2fkzqcfwx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tanke756.top/Article/details/gt2iwotckxt.html

[C15] 解构 / 展开参数
来源：http://dali.zhengqikj.top/Article/details/gt2dwjvutkk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hywenlv.cn/Article/details/gt2zosbgods.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xylfe.cn/Article/details/gt2gygtprxw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ohoqplin.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daxiang520.top/Article/details/gt2ssmvuvuy.html

Java: // 无解构
来源：http://dali.fzhhl.top/Article/details/gt2gnjyzqol.html

Go:   // 无解构
来源：http://dali.jyoumei.cn/Article/details/gt2jhmweoya.html

Ruby: a, b = pair
来源：http://dali.iojbl.cn/Article/details/gt2esmwxqeo.html

C#:   var (a, b) = pair;
来源：http://dali.hammf.cn/Article/details/gt2xuktukez.html

[C16] 函数 / 方法重载
来源：http://dali.hongshengwenyu.top/Article/details/gt2sudqdpyl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jiagoushi.top/Article/details/gt2kekbysxc.html

PHP:  // 无重载
来源：http://dali.sweek.top/Article/details/gt2bhvhytro.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.mhx1999.top/Article/details/gt2cyragfxu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gaohongyu789.top/Article/details/gt2izjmugvv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daxiang520.top/Article/details/gt2ffxluphf.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinqigfzy.top/Article/details/gt2sfloewyz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ytfppnse.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2zqgqjike.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2tmcygxrh.html

D. 数组 / 列表 / 集合
来源：http://dali.gaohongyu789.top/Article/details/gt2sgdxlgck.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2nalsaqns.html

[D01] 创建数组 / 列表
来源：http://dali.shuidangran.top/Article/details/gt2lfmwysxp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhongyouzk.top/Article/details/gt2qvhwjtmm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fengsongda.top/Article/details/gt2ddpwkwzh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj202588.top/Article/details/gt2wziwywtu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nwbrower.top/Article/details/gt2xrpksnfq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gogol.net.cn/Article/details/gt2bbqhduej.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aibaodan.cn/Article/details/gt2wuaqofag.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2njxjjtxk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgufenzy.top/Article/details/gt2augyrbyr.html

[D02] 追加元素到末尾
来源：http://dali.smart0.xyz/Article/details/gt2cofxkqla.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.andypj.xyz/Article/details/gt2dgfzpvho.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bzmvcplb.html

JS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gt2naxgzigp.html

TS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gt2itvaxuzl.html

Java: list.add(4);
来源：http://dali.nanxinkj.top/Article/details/gt2uhswpvud.html

Go:   arr = append(arr, 4)
来源：http://dali.mhx1999.top/Article/details/gt2ehpfgpeq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yueranfly.top/Article/details/gt2eowngkwb.html

C#:   list.Add(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2koyrruyi.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2qmitztzc.html

Py:   arr.insert(0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mmtpbtfc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yangfankeji.com/Article/details/gt2mqpcunhf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hongshengwenyu.top/Article/details/gt2fncflxxa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.0kj1m.cn/Article/details/gt2ajluuysq.html

Java: list.add(0, 0);
来源：http://dali.yj20258888.top/Article/details/gt2imsfkvib.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.316326.xyz/Article/details/gt2anrnvzix.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.snrcjt.cn/Article/details/gt2qudpunjr.html

C#:   list.Insert(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2umdaorhy.html

[D04] 删除元素
来源：http://dali.gotoacloud.top/Article/details/gt2xzlvvkgx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sxryk.cn/Article/details/gt2vdzdmyfa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2bfdseljj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.iojbl.cn/Article/details/gt2xjmngrqc.html

TS:   arr.splice(0, 1);
来源：http://dali.zhoulong.xyz/Article/details/gt2jjjjzrtf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sufxvd.cn/Article/details/gt2hxfxfqhf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.fzhhl.top/Article/details/gt2ighoeovz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hysaishi.cn/Article/details/gt2xuxvgfpz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tianlin.xyz/Article/details/gt2jrodfdsl.html

[D05] 访问与修改元素
来源：http://dali.sxryk.cn/Article/details/gt2cruvumaz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gt2szsapopy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gt2vjuuuflu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gt2gxqgcxzj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shzxlz.cn/Article/details/gt2rlzzmjhl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.guowangkeji.top/Article/details/gt2abdeikqy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gt2knscajag.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gt2rfonocmb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gt2vrpnssiy.html

[D06] 数组长度
来源：http://dali.tanke756.top/Article/details/gt2xdqkbkxj.html

Py:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gt2vcgdimya.html

PHP:  count($arr);
来源：http://dali.cucudq.cn/Article/details/gt2ehzusnna.html

JS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gt2pehkalvx.html

TS:   arr.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ystgvaih.html

Java: list.size();
来源：http://dali.xuetiantiany.cn/Article/details/gt2ruzdwwxo.html

Go:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2hsfhemvz.html

Ruby: arr.length; arr.size
来源：http://dali.316326.xyz/Article/details/gt2wxldicgt.html

C#:   list.Count;
来源：http://dali.ehwqpu.com/Article/details/gt2giqjdldo.html

[D07] 切片 / 取子数组
来源：http://dali.yuanzhike.top/Article/details/gt2yzehgzti.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.iojbl.cn/Article/details/gt2vyfnuywy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigufen.top/Article/details/gt2xdsltfda.html

JS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2rbuhqehe.html

TS:   arr.slice(1, 4);
来源：http://dali.fzhhl.top/Article/details/gt2vdwejnce.html

Java: list.subList(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gt2drsjkrvs.html

Go:   arr[1:4]
来源：http://dali.yj202588.top/Article/details/gt2gjdvahea.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ehdcqpzo.html

C#:   list.GetRange(1, 3);
来源：http://dali.hysaishi.cn/Article/details/gt2yekangyo.html

[D08] 合并两个数组
来源：http://dali.daxiang520.top/Article/details/gt2gvlsaabj.html

Py:   a + b;  a.extend(b)
来源：http://dali.yonumen.top/Article/details/gt2qunkmzfj.html

PHP:  array_merge($a, $b);
来源：http://dali.ivvv.top/Article/details/gt2mgzzyilg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yanxiufei.cn/Article/details/gt2dwygnjkq.html

TS:   [...a, ...b];
来源：http://dali.cqqwz.cn/Article/details/gt2gffupwit.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2grcyuscy.html

Go:   append(a, b...)
来源：http://dali.fengsongda.top/Article/details/gt2hgxonqbb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2skkjwegj.html

C#:   a.Concat(b).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2sjyupgwk.html

[D09] 排序（升序）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sasrabnn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gt2ufmahivd.html

PHP:  sort($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2fpmhgahs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.birdmap.top/Article/details/gt2wsynkdao.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fengsongda.top/Article/details/gt2oaftdbbg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2grxvmxia.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2baijwihb.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gt2itygisny.html

C#:   list.Sort();
来源：http://dali.jlsjyb.cn/Article/details/gt2yiptykyl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imliyvfj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eyhtujvs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jianghu66.top/Article/details/gt2odicrwgx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xinyue.icu/Article/details/gt2zqafoeoy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gt2kzmbbqxw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cheryme.top/Article/details/gt2txeposfr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ybcxt.top/Article/details/gt2iehanjse.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yonumen.top/Article/details/gt2vtljqylj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cdnleiting.top/Article/details/gt2bpzbchom.html

[D11] 反转数组
来源：http://dali.xylfe.cn/Article/details/gt2ssxptxjz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ppjwa.cn/Article/details/gt2hvqddlje.html

PHP:  array_reverse($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2ioogwzxk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cqqwz.cn/Article/details/gt2ekulnmjl.html

TS:   [...arr].reverse();
来源：http://dali.dashuyun.cn/Article/details/gt2aogbjten.html

Java: Collections.reverse(list);
来源：http://dali.yuanzhike.top/Article/details/gt2tvmkeblm.html

Go:   slices.Reverse(arr)
来源：http://dali.hnqzz.top/Article/details/gt2pvmtzejo.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2njhbrqxz.html

C#:   list.Reverse();
来源：http://dali.xinyue.icu/Article/details/gt2nrrewfsg.html

[D12] 查找元素下标
来源：http://dali.cdnleiting.top/Article/details/gt2ydureivr.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sdmtxdcn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hfpthk.cn/Article/details/gt2jmiemcgc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gt2jbibvkgb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gt2lpaeoair.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgfzy.top/Article/details/gt2tqqqddop.html

Go:   slices.Index(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2mlmtfrac.html

Ruby: arr.index(x)
来源：http://dali.9152youxi.cn/Article/details/gt2ncksfwio.html

C#:   list.IndexOf(x);
来源：http://dali.hysaishi.cn/Article/details/gt2nawgdknq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nwbrower.top/Article/details/gt2icasuwhh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yangfankeji.com/Article/details/gt2tmqwblyq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.snrcjt.cn/Article/details/gt2cjayhtgn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gt2tflbixtg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gt2rqrnhxxu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sysykeji.top/Article/details/gt2blhyhlsd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yuxming.cn/Article/details/gt2xmvnpvnz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jsymdvst.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2ndniwlph.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenzaomai.com/Article/details/gt2auwguybk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gzhubu.top/Article/details/gt2yawqjrxi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuxming.cn/Article/details/gt2fxwwujzo.html

JS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gt2ihbspspo.html

TS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gt2qudvmjyk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cucudq.cn/Article/details/gt2gudxebaj.html

Go:   // 手写循环
来源：http://dali.9152youxi.cn/Article/details/gt2otrmzqed.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gt2uknzfqjd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2fbntedhk.html

[D15] 去重
来源：http://dali.xinyue.icu/Article/details/gt2wlpehtdo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gt2ewfcqoau.html

PHP:  array_unique($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2ratxlhuf.html

JS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gt2taqgqdjr.html

TS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gt2hslxlhjg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhiwuduotai.top/Article/details/gt2vjydpach.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenzaomai.com/Article/details/gt2fwyzsqos.html

Ruby: arr.uniq
来源：http://dali.zdqjudy.top/Article/details/gt2qpnqniqo.html

C#:   list.Distinct().ToList()
来源：http://dali.xinyue.icu/Article/details/gt2rvaapaaf.html

[D16] 求和与平均值
来源：http://dali.jqgfzy.top/Article/details/gt2epxarjas.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bwpxbtjg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2txwbycni.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2reroxysg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lqlferze.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuxming.cn/Article/details/gt2mfngqnve.html

Go:   // 手写循环累加
来源：http://dali.chenlongwang.top/Article/details/gt2vwpvtbxn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ydzc1.top/Article/details/gt2awkfbylj.html

C#:   list.Sum();  list.Average()
来源：http://dali.pycfn.com/Article/details/gt2pxgdgndi.html

[D17] 最大值与最小值
来源：http://dali.jlsjyb.cn/Article/details/gt2cgqazpwa.html

Py:   max(arr);  min(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2gcohwdpb.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2vqjforbh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iuwbymrd.html

TS:   Math.max(...arr);
来源：http://dali.xuanzx.com/Article/details/gt2njqbigqa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqimzrq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.bjfxy.top/Article/details/gt2fxhjlqor.html

Ruby: arr.max;  arr.min
来源：http://dali.smart0.xyz/Article/details/gt2hlfzwlmz.html

C#:   list.Max();  list.Min()
来源：http://dali.jyoumei.cn/Article/details/gt2skjogasa.html

[D18] 扁平化嵌套数组
来源：http://dali.jianghu66.top/Article/details/gt2knuqobnh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zycfv.cn/Article/details/gt2rdmgnolz.html

PHP:  array_merge(...$nested);
来源：http://dali.ppjwa.cn/Article/details/gt2vxyoothi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yongpay.top/Article/details/gt2bygsjmoq.html

TS:   nested.flat();
来源：http://dali.9152youxi.cn/Article/details/gt2yuksdtiw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnqzz.top/Article/details/gt2ugqgvpzx.html

Go:   // 手写双层循环
来源：http://dali.fzhhl.top/Article/details/gt2rdqcmtrs.html

Ruby: nested.flatten
来源：http://dali.ppjwa.cn/Article/details/gt2alyccoty.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2opuuqfqt.html

[D19] 按字段分组
来源：http://dali.tanke756.top/Article/details/gt2rxdvmjkh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ehwqpu.com/Article/details/gt2lhflxkdb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.kuanghao11.cn/Article/details/gt2bvapqhkr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gzhubu.top/Article/details/gt2gbryefbb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gt2mgzodado.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.c1oappe.top/Article/details/gt2qjipdymh.html

Go:   // 手写 map[string][]T
来源：http://dali.mhx1999.top/Article/details/gt2bqczyawg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.mhx1999.top/Article/details/gt2xzibzstv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.vqdsnc.cn/Article/details/gt2kumpczbr.html

[D20] 统计每个元素出现次数
来源：http://dali.gaohongyu789.top/Article/details/gt2bgfaocxt.html

Py:   Counter(arr)
来源：http://dali.ybcxt.top/Article/details/gt2ggnynxdj.html

PHP:  array_count_values($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2gmoymeiv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xylfe.cn/Article/details/gt2mypgoqkl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gt2ohdjintx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cdnleiting.top/Article/details/gt2nhrpnfqy.html

Go:   // 手写 map[T]int
来源：http://dali.xziqi.cn/Article/details/gt2mhqkmyou.html

Ruby: arr.tally
来源：http://dali.snrcjt.cn/Article/details/gt2mnucupzs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhixingplan.top/Article/details/gt2cirrador.html

[D21] 判断是否包含某元素
来源：http://dali.cucudq.cn/Article/details/gt2pipwxelc.html

Py:   x in arr
来源：http://dali.hammf.cn/Article/details/gt2jxezklyq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jlsjyb.cn/Article/details/gt2vccvovir.html

JS:   arr.includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2kygtqbmy.html

TS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gt2eitvjeka.html

Java: list.contains(x)
来源：http://dali.ehwqpu.com/Article/details/gt2mjlisesy.html

Go:   slices.Contains(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2lopkmtzf.html

Ruby: arr.include?(x)
来源：http://dali.yuanzhike.top/Article/details/gt2orwoorau.html

C#:   list.Contains(x)
来源：http://dali.ivvv.top/Article/details/gt2jchkpmgp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenjidiqi.icu/Article/details/gt2fijxegjq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hammf.cn/Article/details/gt2spshsrpa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangshuangyany.cn/Article/details/gt2gewpwdcf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ydzc1.top/Article/details/gt2emnnxhxe.html

TS:   [...arr];
来源：http://dali.tian-w.cn/Article/details/gt2qdaegcgz.html

Java: new ArrayList<>(list);
来源：http://dali.kuanghao11.cn/Article/details/gt2rvvovjvd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xdfacvdb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hywenlv.cn/Article/details/gt2rrykiywi.html

C#:   new List<int>(list);
来源：http://dali.yonumen.top/Article/details/gt2eyhjtatg.html

[D23] reduce 累积计算
来源：http://dali.daxiang520.top/Article/details/gt2nlesxrdd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hstmffss.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.bjfxy.top/Article/details/gt2vbccyoej.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gt2elrvulrt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2paveiiwx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sweek.top/Article/details/gt2hkttkvwl.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gt2sncwchdr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hysaishi.cn/Article/details/gt2djqbpqck.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ebtjzhun.html

[D24] 字典 / Map 基本操作
来源：http://dali.cucudq.cn/Article/details/gt2prjlnmba.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yfgrgzdv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pycfn.com/Article/details/gt2baagtkzz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.haohaochexian.top/Article/details/gt2afsjesen.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.316326.xyz/Article/details/gt2qwdtkxes.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.meibo888.top/Article/details/gt2ztltsual.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dianchejie.cn/Article/details/gt2jspostdk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dvudwpil.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jlsjyb.cn/Article/details/gt2kczzhrqo.html

[D25] Set 集合去重与交并差
来源：http://dali.zycfv.cn/Article/details/gt2rrcfdoqx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ablqkdto.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aibaodan.cn/Article/details/gt2uunyhbar.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.andypj.xyz/Article/details/gt2jhposzlz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.kuanghao11.cn/Article/details/gt2dtqaxcxn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aizwys.cn/Article/details/gt2wehibuqz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tianlin.xyz/Article/details/gt2jmsuxkfn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.9152youxi.cn/Article/details/gt2qujlyilv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cashguo.top/Article/details/gt2wafazdug.html

[D26] 数组转字符串
来源：http://dali.guannengcc.top/Article/details/gt2aeomnrul.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rseoepwu.html

PHP:  implode(", ", $arr);
来源：http://dali.yongpay.top/Article/details/gt2vobrrhvh.html

JS:   arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gt2cazbufpq.html

TS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gt2fssmmyle.html

Java: String.join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ipomlbtq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ajgeahfa.html

Ruby: arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gt2xqaxdryh.html

C#:   string.Join(", ", list)
来源：http://dali.meibo888.top/Article/details/gt2nihnejfx.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2toivmyco.html

E. 字符串处理
来源：http://dali.yuanzhike.top/Article/details/gt2mcmpilwj.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2vdocpdrq.html

[E01] 拼接字符串
来源：http://dali.cheryme.top/Article/details/gt2oyfnufws.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ivvv.top/Article/details/gt2tehqfdel.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigufen.top/Article/details/gt2hjduqfgx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gt2kehklnoq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2cjbcsxbl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigfzy.top/Article/details/gt2rlvztuwp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenzaomai.com/Article/details/gt2mrvsxfdw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhongyouzk.top/Article/details/gt2wncujykj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2ibwzmkzo.html

[E02] 重复字符串
来源：http://dali.yuxming.cn/Article/details/gt2rqgiayzd.html

Py:   "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gt2yrjtlihp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xinyue.icu/Article/details/gt2szzjhkod.html

JS:   "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gt2fcxgynvl.html


<!-- 参考信息 -->