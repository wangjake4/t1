代发 wailian999

PHP:  (function () { echo "run"; })();
来源：http://dali.tianlin.xyz/Article/details/gtmxyqioyt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tian-w.cn/Article/details/gthiruasth.html

TS:   (() => { console.log("run"); })();
来源：http://dali.iojbl.cn/Article/details/gtrgzsxfuq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258.top/Article/details/gtnhubxnee.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.dianchejie.cn/Article/details/gtzmvdfcwd.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnqzz.top/Article/details/gtsccrcewr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aibaodan.cn/Article/details/gtsfrtfrvb.html

[C13] 类型声明 / 类型注解
来源：http://dali.jiagoushi.top/Article/details/gtfnzpoxus.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xinyue.icu/Article/details/gtzveqlysj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtecanidmy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gzhubu.top/Article/details/gtmfptmfyy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtieaukyjp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtujjihlcn.html

Go:   func add(a, b int) int
来源：http://dali.daxiang520.top/Article/details/gtrvrbimxa.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhixingplan.top/Article/details/gthugpfaxv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnqzz.top/Article/details/gticivdbjc.html

[C14] 泛型函数
来源：http://dali.ppjwa.cn/Article/details/gtvcvlyokm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tian-w.cn/Article/details/gtysdisbnj.html

PHP:  // 无泛型
来源：http://dali.ydzc1.top/Article/details/gtnffinnju.html

JS:   // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtdctegzwf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hnxiangtu.top/Article/details/gtbyqamnjn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hywenlv.cn/Article/details/gtnkeuojej.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.iojbl.cn/Article/details/gtdadlzdwq.html

Ruby: # 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtvygxbfuw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zycfv.cn/Article/details/gtwwjvxumc.html

[C15] 解构 / 展开参数
来源：http://dali.tanke756.top/Article/details/gtsukqenyq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.havefunace.top/Article/details/gtyjtnazrw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shuidangran.top/Article/details/gtkjtwcqfs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gtblxjpwcb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.aibaodan.cn/Article/details/gtotbnozdl.html

Java: // 无解构
来源：http://dali.gogol.net.cn/Article/details/gttghjwlqm.html

Go:   // 无解构
来源：http://dali.nanxinkj.top/Article/details/gtheoauyyb.html

Ruby: a, b = pair
来源：http://dali.sufxvd.cn/Article/details/gtxhowkdsv.html

C#:   var (a, b) = pair;
来源：http://dali.yuxming.cn/Article/details/gtatsqcgoy.html

[C16] 函数 / 方法重载
来源：http://dali.ivvv.top/Article/details/gttxoegiku.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrfrywxh.html

PHP:  // 无重载
来源：http://dali.daxiang520.top/Article/details/gtnnbckzce.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.redwolf501.top/Article/details/gtnfdhlkxb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnxiangtu.top/Article/details/gtycdjzhuy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.havefunace.top/Article/details/gtjeanmdnb.html

Go:   // 无重载：用不同函数名
来源：http://dali.yuanzhike.top/Article/details/gtawbevwxu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sxryk.cn/Article/details/gtrjdlqjyz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.mhx1999.top/Article/details/gtxxcndlsr.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtbdzbswmt.html

D. 数组 / 列表 / 集合
来源：http://dali.yonumen.top/Article/details/gtwreasvjo.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtocbrfoyo.html

[D01] 创建数组 / 列表
来源：http://dali.daxiang520.top/Article/details/gtnomjgtct.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yonumen.top/Article/details/gtsurusdhz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrnbqxwe.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.snrcjt.cn/Article/details/gtathsovov.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangdashe.top/Article/details/gtshjzaeqs.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yueranfly.top/Article/details/gtxyleybuy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.0kj1m.cn/Article/details/gtuknzkbrc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guannengcc.top/Article/details/gtcukjfiwd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258888.top/Article/details/gtqanmftmy.html

[D02] 追加元素到末尾
来源：http://dali.fengsongda.top/Article/details/gtihrjdhdh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.meibo888.top/Article/details/gtpmqfwwib.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gtoxornjwq.html

JS:   arr.push(4);
来源：http://dali.zycfv.cn/Article/details/gtxlnilvlb.html

TS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gtmeqeytfl.html

Java: list.add(4);
来源：http://dali.gzhubu.top/Article/details/gtrybttnyz.html

Go:   arr = append(arr, 4)
来源：http://dali.yangfankeji.com/Article/details/gtkfrpmafm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnxiangtu.top/Article/details/gtkidsbzes.html

C#:   list.Add(4);
来源：http://dali.smart0.xyz/Article/details/gtyzzlltnc.html

[D03] 在指定位置插入元素
来源：http://dali.zhixingplan.top/Article/details/gtufdmltdo.html

Py:   arr.insert(0, 0)
来源：http://dali.tian-w.cn/Article/details/gtpwsftioq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cheryme.top/Article/details/gtkckyhmfy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yangfankeji.com/Article/details/gtsdbyrduk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtnadpepjd.html

Java: list.add(0, 0);
来源：http://dali.havefunace.top/Article/details/gtufcttmof.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zdqjudy.top/Article/details/gtjydcypze.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dianchejie.cn/Article/details/gtvsrynlln.html

C#:   list.Insert(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtbjyzglbj.html

[D04] 删除元素
来源：http://dali.gzhubu.top/Article/details/gtpubymacu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.pycfn.com/Article/details/gtterdfehm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pycfn.com/Article/details/gtnhwuyfge.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ivvv.top/Article/details/gttqfrubcb.html

TS:   arr.splice(0, 1);
来源：http://dali.kuanghao11.cn/Article/details/gtntqllrts.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.meibo888.top/Article/details/gtgwmmrzpe.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnqzz.top/Article/details/gtxfrxsxuo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgfzy.top/Article/details/gttdiwksql.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yanxiufei.cn/Article/details/gtelotpxuc.html

[D05] 访问与修改元素
来源：http://dali.jianghu66.top/Article/details/gtlnruajbl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gtcjvgxycc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtzrnvgxqh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtlgnvtief.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cdnleiting.top/Article/details/gtfyetulxb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fzhhl.top/Article/details/gtuqhtrzpa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtzfkfcjuu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtpiuxtebx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sweek.top/Article/details/gtktjbpybj.html

[D06] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gtxqaihwqv.html

Py:   len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gthvfnqzlk.html

PHP:  count($arr);
来源：http://dali.pycfn.com/Article/details/gtazqkajnl.html

JS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gtridzjtmh.html

TS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gtikkmhmpa.html

Java: list.size();
来源：http://dali.dashuyun.cn/Article/details/gtyakxwbdj.html

Go:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtybjcqhmt.html

Ruby: arr.length; arr.size
来源：http://dali.ppjwa.cn/Article/details/gtqpacbjkh.html

C#:   list.Count;
来源：http://dali.tian-w.cn/Article/details/gtlmixuutc.html

[D07] 切片 / 取子数组
来源：http://dali.feifeiyinyue.top/Article/details/gtzwwwtfru.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.havefunace.top/Article/details/gtgsqxjewv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yonumen.top/Article/details/gtewsmtrzw.html

JS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtbbxycghn.html

TS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gtxxivblqy.html

Java: list.subList(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfelyefyi.html

Go:   arr[1:4]
来源：http://dali.zhongyouzk.top/Article/details/gtohjidjar.html

Ruby: arr[1, 3]
来源：http://dali.daxiang520.top/Article/details/gtzxztxwpr.html

C#:   list.GetRange(1, 3);
来源：http://dali.ppjwa.cn/Article/details/gtkalnssxy.html

[D08] 合并两个数组
来源：http://dali.zhengqikj.top/Article/details/gtpkaeycxj.html

Py:   a + b;  a.extend(b)
来源：http://dali.ppjwa.cn/Article/details/gtwtkiavqo.html

PHP:  array_merge($a, $b);
来源：http://dali.fzhhl.top/Article/details/gtjvdrcbhk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhengqikj.top/Article/details/gtqbornsdq.html

TS:   [...a, ...b];
来源：http://dali.yueranfly.top/Article/details/gtauacfmsb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cucudq.cn/Article/details/gtiunpxzcf.html

Go:   append(a, b...)
来源：http://dali.hnxiangtu.top/Article/details/gtnkllzuzs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtcedffewa.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyvszmtc.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gtjgwarvco.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gtowphcsaf.html

PHP:  sort($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtfluhgxop.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ybcxt.top/Article/details/gtttohwjsg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigufen.top/Article/details/gtwyutarwk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guannengcc.top/Article/details/gtcwddfqzk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gtoskqnpla.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gtfftsurgh.html

C#:   list.Sort();
来源：http://dali.wangshuangyany.cn/Article/details/gtblokssfx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnqzz.top/Article/details/gtpwhoxjyu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hysaishi.cn/Article/details/gtqmlhxcer.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhongyouzk.top/Article/details/gtgfzqveri.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigufen.top/Article/details/gtirmmmfys.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtuiqmmcxo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guowangkeji.top/Article/details/gtpcraoovk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigfzy.top/Article/details/gtmgqurobg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hywenlv.cn/Article/details/gtgfzsumvf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenzaomai.com/Article/details/gttvpsqdxj.html

[D11] 反转数组
来源：http://dali.yj202588.top/Article/details/gtulglwlwj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zdqjudy.top/Article/details/gtlcyemxsc.html

PHP:  array_reverse($arr);
来源：http://dali.xylfe.cn/Article/details/gtnawdwlep.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gtfvbjqakn.html

TS:   [...arr].reverse();
来源：http://dali.ydzc1.top/Article/details/gtmbhqyivp.html

Java: Collections.reverse(list);
来源：http://dali.tianlin.xyz/Article/details/gtvxjulvft.html

Go:   slices.Reverse(arr)
来源：http://dali.c1oappe.top/Article/details/gtyqqebkle.html

Ruby: arr.reverse
来源：http://dali.bjfxy.top/Article/details/gtyyrvgxnl.html

C#:   list.Reverse();
来源：http://dali.daria6918.cn/Article/details/gtgavhoubp.html

[D12] 查找元素下标
来源：http://dali.daria6918.cn/Article/details/gtfbbndztk.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigfzy.top/Article/details/gtcvhjlbcf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.smart0.xyz/Article/details/gtqrsfuktc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shzxlz.cn/Article/details/gtxomkbquf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gttdcrrwmw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jiagoushi.top/Article/details/gtpbyhltxp.html

Go:   slices.Index(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtgnsmxdur.html

Ruby: arr.index(x)
来源：http://dali.ydzc1.top/Article/details/gtwglnraqv.html

C#:   list.IndexOf(x);
来源：http://dali.fzhhl.top/Article/details/gtmahdkcox.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ywan-chungtsiang.top/Article/details/gttivpdlew.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cheryme.top/Article/details/gtbcpyceyz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuanzx.com/Article/details/gtnrbwwtgx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtarpvsplp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtcvbnwhsr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guowangkeji.top/Article/details/gtkcwhilrv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tanke756.top/Article/details/gthtpczlfl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258888.top/Article/details/gtzokvkksh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtjbmravpg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxuanxn.top/Article/details/gtlckhrwil.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hammf.cn/Article/details/gthagjyopi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenlongwang.top/Article/details/gtubmmaffi.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gtkzfuizmx.html

TS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gtpirvnbyy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cucudq.cn/Article/details/gtmwmlsoye.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gtvxjtlycn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtprtsjdif.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtfogczhqn.html

[D15] 去重
来源：http://dali.aibaodan.cn/Article/details/gtamowaime.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxqvhiho.html

PHP:  array_unique($arr);
来源：http://dali.zhengqikj.top/Article/details/gtpazzbphu.html

JS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gtjsdkqdkk.html

TS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbuftzorw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gtfiuvxlem.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xuetiantiany.cn/Article/details/gtnwtgmiet.html

Ruby: arr.uniq
来源：http://dali.yuanzhike.top/Article/details/gtzsfjnaqs.html

C#:   list.Distinct().ToList()
来源：http://dali.xuanzx.com/Article/details/gtngmgesby.html

[D16] 求和与平均值
来源：http://dali.chenjidiqi.icu/Article/details/gtgvsgtges.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtvscxtmcd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtbnaftvqe.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtzisdeqvm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtsbwuwwic.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenjidiqi.icu/Article/details/gtfpiqmshx.html

Go:   // 手写循环累加
来源：http://dali.tanke756.top/Article/details/gtjpbgclck.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnxiangtu.top/Article/details/gtxiqdxvcd.html

C#:   list.Sum();  list.Average()
来源：http://dali.ehwqpu.com/Article/details/gtlxojkzky.html

[D17] 最大值与最小值
来源：http://dali.cucudq.cn/Article/details/gtonqqdxqq.html

Py:   max(arr);  min(arr)
来源：http://dali.fengsongda.top/Article/details/gtcvjopqyc.html

PHP:  max($arr);  min($arr);
来源：http://dali.smart0.xyz/Article/details/gtxhxilxfv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ybcxt.top/Article/details/gtvqmhhxxf.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzybuhphv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hammf.cn/Article/details/gtcwwkjhca.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nwbrower.top/Article/details/gttztkmpms.html

Ruby: arr.max;  arr.min
来源：http://dali.feifeiyinyue.top/Article/details/gthzocizyw.html

C#:   list.Max();  list.Min()
来源：http://dali.yvedp.cn/Article/details/gtlffgqdbz.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gtrymiwgsx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dashuyun.cn/Article/details/gtsqezqwkn.html

PHP:  array_merge(...$nested);
来源：http://dali.havefunace.top/Article/details/gtlvorgtqo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.c1oappe.top/Article/details/gtjncjomve.html

TS:   nested.flat();
来源：http://dali.yongpay.top/Article/details/gtooglojgt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tian-w.cn/Article/details/gtgslaljlf.html

Go:   // 手写双层循环
来源：http://dali.vqdsnc.cn/Article/details/gtltbgjohc.html

Ruby: nested.flatten
来源：http://dali.chenlongwang.top/Article/details/gtmilvvscn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ybcxt.top/Article/details/gthhnkxawe.html

[D19] 按字段分组
来源：http://dali.jinqigfzy.top/Article/details/gtlvigxeob.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ehwqpu.com/Article/details/gtdfpwodtg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gaohongyu789.top/Article/details/gtnfysxhof.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnqzz.top/Article/details/gthtygubwd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gtgjmthbro.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gtddaklgbo.html

Go:   // 手写 map[string][]T
来源：http://dali.pycfn.com/Article/details/gtolqozoco.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daxiang520.top/Article/details/gtnjihqxcd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258888.top/Article/details/gtllwtdbqj.html

[D20] 统计每个元素出现次数
来源：http://dali.mhx1999.top/Article/details/gtieklccsk.html

Py:   Counter(arr)
来源：http://dali.aizwys.cn/Article/details/gtrjokpwge.html

PHP:  array_count_values($arr);
来源：http://dali.xuanzx.com/Article/details/gtsrjyssxx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.snrcjt.cn/Article/details/gtdegjebfq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gtdorhiwcw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pycfn.com/Article/details/gtqktxcfav.html

Go:   // 手写 map[T]int
来源：http://dali.smart0.xyz/Article/details/gtqtbmgsfq.html

Ruby: arr.tally
来源：http://dali.hammf.cn/Article/details/gtzlzqbgib.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pycfn.com/Article/details/gtxgqjcwad.html

[D21] 判断是否包含某元素
来源：http://dali.yangfankeji.com/Article/details/gthqjjlpby.html

Py:   x in arr
来源：http://dali.snrcjt.cn/Article/details/gtrxrhbgbt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zdqjudy.top/Article/details/gtvsndsneb.html

JS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtsjjfupvb.html

TS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gtnhnffhuk.html

Java: list.contains(x)
来源：http://dali.nwbrower.top/Article/details/gtkrvhznrz.html

Go:   slices.Contains(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtkeeqyqxo.html

Ruby: arr.include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtfretukhh.html

C#:   list.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gtmbnprlzl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hongshengwenyu.top/Article/details/gtteqgihqn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigufen.top/Article/details/gtogfvibza.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.c1oappe.top/Article/details/gtdlwjfmfp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guannengcc.top/Article/details/gtqkdghokn.html

TS:   [...arr];
来源：http://dali.aizwys.cn/Article/details/gtnksobvrq.html

Java: new ArrayList<>(list);
来源：http://dali.andypj.xyz/Article/details/gtpkzpdpzh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gzhubu.top/Article/details/gtitgctdcp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenjidiqi.icu/Article/details/gtcnyvbnue.html

C#:   new List<int>(list);
来源：http://dali.sufxvd.cn/Article/details/gtrlnjhrbj.html

[D23] reduce 累积计算
来源：http://dali.cqqwz.cn/Article/details/gtonwocdno.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fengsongda.top/Article/details/gtqlxyjhdd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwpuzbuw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gtcjfjhwxy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gtsukzmvsq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvrtjtcr.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtbczwirts.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yanxiufei.cn/Article/details/gtxcsqspxf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmoyzrcmx.html

[D24] 字典 / Map 基本操作
来源：http://dali.jianghu66.top/Article/details/gthaputtkf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangdashe.top/Article/details/gtmjwcmkvn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.c1oappe.top/Article/details/gtrajcswyg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fzhhl.top/Article/details/gtxyeghqle.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtpysghhsv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwbiqxgg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.redwolf501.top/Article/details/gtmnsosmww.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aibaodan.cn/Article/details/gtmhftzmnk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.feifeiyinyue.top/Article/details/gtrngwkztx.html

[D25] Set 集合去重与交并差
来源：http://dali.svipenyu.cn/Article/details/gtcibuiwvq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjahwjevr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sufxvd.cn/Article/details/gtnflrdbsv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtmtudexhb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hfpthk.cn/Article/details/gtmhxiaubu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.vqdsnc.cn/Article/details/gtjwdczjnd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aizwys.cn/Article/details/gtwxqepqek.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtgmlwbdif.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.svipenyu.cn/Article/details/gtzbvanteg.html

[D26] 数组转字符串
来源：http://dali.mhx1999.top/Article/details/gtbutdhjdy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gotoacloud.top/Article/details/gtrvyzqsdm.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtelznasim.html

JS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gteypyfrmp.html

TS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gtivksngsx.html

Java: String.join(", ", list)
来源：http://dali.cheryme.top/Article/details/gthcndsibn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258888.top/Article/details/gtinmohncz.html

Ruby: arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtlysafzvg.html

C#:   string.Join(", ", list)
来源：http://dali.pycfn.com/Article/details/gttqaeognd.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtxdvopbpi.html

E. 字符串处理
来源：http://dali.ppjwa.cn/Article/details/gtwcrfamei.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtixulhexx.html

[E01] 拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtrwabhywu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yvedp.cn/Article/details/gtaxvsnkfr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jianghu66.top/Article/details/gtumfjpgug.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtyvbscbxq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtqpgqhxby.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pengpengdd.cyou/Article/details/gtizyhvauj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.kuanghao11.cn/Article/details/gtqogowrdu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuanzhike.top/Article/details/gtviebkvwg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtxluwcivs.html

[E02] 重复字符串
来源：http://dali.meibo888.top/Article/details/gtbmqfpfbk.html

Py:   "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gtujguspcf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cucudq.cn/Article/details/gtkmqjdfsg.html

JS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gthqyjofvw.html

TS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtvnnhgrgz.html

Java: "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtcqrnmkmn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.316326.xyz/Article/details/gtiksufjjc.html

Ruby: "ab" * 3
来源：http://dali.cheryme.top/Article/details/gtfywzhkgv.html


<!-- 参考信息 -->