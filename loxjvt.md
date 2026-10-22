代发 wailian999

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhengqikj.top/Article/details/gtqqgengdc.html

C#:   using System.Text;
来源：http://dali.ybcxt.top/Article/details/gtefdeiuxy.html

[C12] 立即执行函数 IIFE
来源：http://dali.gzhubu.top/Article/details/gtbwowhhjj.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxinkj.top/Article/details/gtzgiykybs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.mhx1999.top/Article/details/gtpbmwkvri.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ydzc1.top/Article/details/gtnhducsgu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkaswcrli.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ehwqpu.com/Article/details/gtsflduipl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jyoumei.cn/Article/details/gtzesvbwww.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258888.top/Article/details/gtkgchyeva.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jyoumei.cn/Article/details/gtnlzxpcgq.html

[C13] 类型声明 / 类型注解
来源：http://dali.yonumen.top/Article/details/gtdlwyvxpb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hammf.cn/Article/details/gthgenrdef.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtzbwpqjin.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aizwys.cn/Article/details/gtucigoyrw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtwbqgepdp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtzbpmnxkx.html

Go:   func add(a, b int) int
来源：http://dali.havefunace.top/Article/details/gtwcwqagki.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hywenlv.cn/Article/details/gtnpgnxlqr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangdashe.top/Article/details/gtoveovbky.html

[C14] 泛型函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxvqyfkp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daxiang520.top/Article/details/gtxffvdrfm.html

PHP:  // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gtyoxuzeyz.html

JS:   // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gtrmcyujcb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gaohongyu789.top/Article/details/gtfixyrlgo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgufenzy.top/Article/details/gtudghcagm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jiagoushi.top/Article/details/gtmejgraae.html

Ruby: # 无泛型
来源：http://dali.ybcxt.top/Article/details/gtwgjkolgc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aibaodan.cn/Article/details/gteeityhdr.html

[C15] 解构 / 展开参数
来源：http://dali.nanxinkj.top/Article/details/gtkqrzlwxc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuanzhike.top/Article/details/gtfsgwycbc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtpnzywuau.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gttfwufzkm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ehwqpu.com/Article/details/gtqgxzsvkt.html

Java: // 无解构
来源：http://dali.sysykeji.top/Article/details/gtsvohelvo.html

Go:   // 无解构
来源：http://dali.0kj1m.cn/Article/details/gtwowbesax.html

Ruby: a, b = pair
来源：http://dali.zhengqikj.top/Article/details/gtnfqzwryv.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258888.top/Article/details/gtqdlehmie.html

[C16] 函数 / 方法重载
来源：http://dali.hnxiangtu.top/Article/details/gttmbjftov.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.havefunace.top/Article/details/gtcfhvzphj.html

PHP:  // 无重载
来源：http://dali.iojbl.cn/Article/details/gtmlczcdfu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tianlin.xyz/Article/details/gtnqhdisyq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphhkriae.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xziqi.cn/Article/details/gtorfxejzu.html

Go:   // 无重载：用不同函数名
来源：http://dali.316326.xyz/Article/details/gtyxsuwgrm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cashguo.top/Article/details/gtinxfblps.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgfzy.top/Article/details/gtlgtjvjbm.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtsozzqbvt.html

D. 数组 / 列表 / 集合
来源：http://dali.wangshuangyany.cn/Article/details/gtyzupvoql.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtefgteoaw.html

[D01] 创建数组 / 列表
来源：http://dali.gaohongyu789.top/Article/details/gtdkeqipyw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jlsjyb.cn/Article/details/gtvlgfcbkj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jqgfzy.top/Article/details/gtbfpvjxlx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.haohaochexian.top/Article/details/gtsixccxoe.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ppjwa.cn/Article/details/gtiemirnhb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolkyufeo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.andypj.xyz/Article/details/gtmfhdsgwu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenlongwang.top/Article/details/gtpdfwwxfn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj202588.top/Article/details/gtzpupyfng.html

[D02] 追加元素到末尾
来源：http://dali.haohaochexian.top/Article/details/gtjgoftcae.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgfzy.top/Article/details/gtkdnljlsh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hammf.cn/Article/details/gtnjzqgijw.html

JS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gtwghhsxro.html

TS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gtdhaclbhh.html

Java: list.add(4);
来源：http://dali.dashuyun.cn/Article/details/gtjaahwpsq.html

Go:   arr = append(arr, 4)
来源：http://dali.wangdashe.top/Article/details/gtzcgzbjgc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.kuanghao11.cn/Article/details/gtqxpfllte.html

C#:   list.Add(4);
来源：http://dali.hnqzz.top/Article/details/gtbztyjyxy.html

[D03] 在指定位置插入元素
来源：http://dali.hammf.cn/Article/details/gtkjemjubf.html

Py:   arr.insert(0, 0)
来源：http://dali.meibo888.top/Article/details/gtbyuqihag.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cashguo.top/Article/details/gtykplxcgm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuanzhike.top/Article/details/gtkrmcpoxg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtpxcpyhmr.html

Java: list.add(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gtintiwzsl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuanzx.com/Article/details/gtcskdhfoy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ivvv.top/Article/details/gtuxwdhmhv.html

C#:   list.Insert(0, 0);
来源：http://dali.cheryme.top/Article/details/gtkkmevwek.html

[D04] 删除元素
来源：http://dali.jqgufenzy.top/Article/details/gthequhtjg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangdashe.top/Article/details/gtzhtaewek.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yangfankeji.com/Article/details/gtabtlxlps.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhixingplan.top/Article/details/gtvnwljtll.html

TS:   arr.splice(0, 1);
来源：http://dali.yueranfly.top/Article/details/gtciphewef.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hfpthk.cn/Article/details/gtfytwilby.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guowangkeji.top/Article/details/gtqlykhhsg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.0kj1m.cn/Article/details/gtvayytlxe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cashguo.top/Article/details/gtwtpmpcdf.html

[D05] 访问与修改元素
来源：http://dali.nanxuanxn.top/Article/details/gtjrakbowj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gtmwlvmjgs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtljgfrzui.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtwixqihsm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jianghu66.top/Article/details/gtmphxjzxx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zycfv.cn/Article/details/gtdylgomta.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gtfsanbotb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtwacogbbd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtvdaachox.html

[D06] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gtzzvmxlzi.html

Py:   len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtysiddkwp.html

PHP:  count($arr);
来源：http://dali.fengsongda.top/Article/details/gtyaznaqqb.html

JS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gtyivctznz.html

TS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtnjktsdqc.html

Java: list.size();
来源：http://dali.sufxvd.cn/Article/details/gtavovuncr.html

Go:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gtsezzurjk.html

Ruby: arr.length; arr.size
来源：http://dali.yvedp.cn/Article/details/gtwqlbgxlk.html

C#:   list.Count;
来源：http://dali.zhiwuduotai.top/Article/details/gtdiwcmbbg.html

[D07] 切片 / 取子数组
来源：http://dali.shangyingyoupin.top/Article/details/gtabudejsm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zdqjudy.top/Article/details/gtakkvmtna.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtynptcksd.html

JS:   arr.slice(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtvdtlbscy.html

TS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtyipyoqvy.html

Java: list.subList(1, 4);
来源：http://dali.guannengcc.top/Article/details/gtpwvrtlrb.html

Go:   arr[1:4]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpiiwvdxa.html

Ruby: arr[1, 3]
来源：http://dali.316326.xyz/Article/details/gtfpedarip.html

C#:   list.GetRange(1, 3);
来源：http://dali.dashuyun.cn/Article/details/gtcdiwokly.html

[D08] 合并两个数组
来源：http://dali.yongpay.top/Article/details/gtfjmayorp.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgufenzy.top/Article/details/gtnhsizvcx.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgufenzy.top/Article/details/gtkyzdgfsa.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gterddnlxr.html

TS:   [...a, ...b];
来源：http://dali.mhx1999.top/Article/details/gtrblxvejk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjpixiup.html

Go:   append(a, b...)
来源：http://dali.hfpthk.cn/Article/details/gtrmccphli.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnliysmpz.html

C#:   a.Concat(b).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtlbltksdd.html

[D09] 排序（升序）
来源：http://dali.aibaodan.cn/Article/details/gtdgghpgtz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gtyjwopedc.html

PHP:  sort($arr);
来源：http://dali.xylfe.cn/Article/details/gtmtbbdzgn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.316326.xyz/Article/details/gtefnkxiyp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sysykeji.top/Article/details/gtolcyklru.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgfzy.top/Article/details/gtvnrkclpk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gtfazviejb.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gthwefyrza.html

C#:   list.Sort();
来源：http://dali.ybcxt.top/Article/details/gtligeulql.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodqswxxm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cheryme.top/Article/details/gtfvkmcrtz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtryuqitzf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gtihbxfjii.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.9152youxi.cn/Article/details/gtewycqhtt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.iojbl.cn/Article/details/gtcwfkocqv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ppjwa.cn/Article/details/gtskigyfpu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.andypj.xyz/Article/details/gtumwumugb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigfzy.top/Article/details/gtrehstacj.html

[D11] 反转数组
来源：http://dali.jqgufenzy.top/Article/details/gtnfifezyi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.aibaodan.cn/Article/details/gtenfjzrmd.html

PHP:  array_reverse($arr);
来源：http://dali.zhengqikj.top/Article/details/gtpgsunqjc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.snrcjt.cn/Article/details/gtxkurkfmf.html

TS:   [...arr].reverse();
来源：http://dali.pycfn.com/Article/details/gtsrfqxgkx.html

Java: Collections.reverse(list);
来源：http://dali.redwolf501.top/Article/details/gtpqnxxvxg.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtfguiiapd.html

Ruby: arr.reverse
来源：http://dali.jiagoushi.top/Article/details/gtglyrolud.html

C#:   list.Reverse();
来源：http://dali.jianghu66.top/Article/details/gtshxodydw.html

[D12] 查找元素下标
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqhjtoxc.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj202588.top/Article/details/gtqjwwyvkv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtsjrmgcjy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gteunpfzju.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gtdzfhdsfx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gtcnllecbx.html

Go:   slices.Index(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtnubesuou.html

Ruby: arr.index(x)
来源：http://dali.xuanzx.com/Article/details/gthwbjqckm.html

C#:   list.IndexOf(x);
来源：http://dali.hywenlv.cn/Article/details/gtdcfjrqhl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daxiang520.top/Article/details/gtzaxmqjog.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxinkj.top/Article/details/gtnvyxhfou.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hfpthk.cn/Article/details/gtfkdlwzcj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gtotswohmj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtvdudrywq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtisyoqmll.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.0kj1m.cn/Article/details/gtfhkarasx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.vqdsnc.cn/Article/details/gtyrsmlbmu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnqzz.top/Article/details/gtozrkizmt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hammf.cn/Article/details/gtosrzbkor.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.svipenyu.cn/Article/details/gtbnxlncjd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.haohaochexian.top/Article/details/gtcqhpawgt.html

JS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gtlccljoqw.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzrugezf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.316326.xyz/Article/details/gtijfrebpq.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gtftuqhnom.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtbvcslynw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sxryk.cn/Article/details/gtotppqoig.html

[D15] 去重
来源：http://dali.chenzaomai.com/Article/details/gtsbgebrrg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigufen.top/Article/details/gtpuddlpvq.html

PHP:  array_unique($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtiokzqzyx.html

JS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtshlewoxe.html

TS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gtqsaosfmm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hfpthk.cn/Article/details/gtunzgyepk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenzaomai.com/Article/details/gtswxdnlmo.html

Ruby: arr.uniq
来源：http://dali.jlsjyb.cn/Article/details/gtjvsiespl.html

C#:   list.Distinct().ToList()
来源：http://dali.xylfe.cn/Article/details/gtbollxmyp.html

[D16] 求和与平均值
来源：http://dali.hnxiangtu.top/Article/details/gtquauhtie.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsmkgvnc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aibaodan.cn/Article/details/gtolxnxwjy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gtfgeldrmq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gtjmfciawd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tanke756.top/Article/details/gtjvicpubo.html

Go:   // 手写循环累加
来源：http://dali.zhixingplan.top/Article/details/gtnmpuknml.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dashuyun.cn/Article/details/gtyxitcmrp.html

C#:   list.Sum();  list.Average()
来源：http://dali.shzxlz.cn/Article/details/gtpaaansqq.html

[D17] 最大值与最小值
来源：http://dali.ppjwa.cn/Article/details/gtsihnvxbd.html

Py:   max(arr);  min(arr)
来源：http://dali.bjfxy.top/Article/details/gtafoxktsr.html

PHP:  max($arr);  min($arr);
来源：http://dali.xinyue.icu/Article/details/gtjquoeyih.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ppjwa.cn/Article/details/gtjirbmbbq.html

TS:   Math.max(...arr);
来源：http://dali.wangdashe.top/Article/details/gtasephove.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sufxvd.cn/Article/details/gtksubbcfv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.smart0.xyz/Article/details/gtscevdurr.html

Ruby: arr.max;  arr.min
来源：http://dali.yvedp.cn/Article/details/gtptqssufv.html

C#:   list.Max();  list.Min()
来源：http://dali.birdmap.top/Article/details/gthvlorebo.html

[D18] 扁平化嵌套数组
来源：http://dali.pycfn.com/Article/details/gtkgxefltu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cqqwz.cn/Article/details/gttigjykuz.html

PHP:  array_merge(...$nested);
来源：http://dali.nwbrower.top/Article/details/gtwwwynkjy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xylfe.cn/Article/details/gttwgsesce.html

TS:   nested.flat();
来源：http://dali.xylfe.cn/Article/details/gtbybhudbn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gotoacloud.top/Article/details/gtucmervof.html

Go:   // 手写双层循环
来源：http://dali.chenjidiqi.icu/Article/details/gtcegilcga.html

Ruby: nested.flatten
来源：http://dali.yangfankeji.com/Article/details/gtvwenwepr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtmmnfgfto.html

[D19] 按字段分组
来源：http://dali.cashguo.top/Article/details/gttocglter.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guowangkeji.top/Article/details/gtxozupbrl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.meibo888.top/Article/details/gtgftoekyy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shangyingyoupin.top/Article/details/gtaprzjypr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.andypj.xyz/Article/details/gtjjjvkwfl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gotoacloud.top/Article/details/gtdqgowhci.html

Go:   // 手写 map[string][]T
来源：http://dali.redwolf501.top/Article/details/gtptedfgmj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tianlin.xyz/Article/details/gtbxqjyiwf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cashguo.top/Article/details/gtqchiaifq.html

[D20] 统计每个元素出现次数
来源：http://dali.dashuyun.cn/Article/details/gtoiuakhdr.html

Py:   Counter(arr)
来源：http://dali.yonumen.top/Article/details/gtmqhqxlvd.html

PHP:  array_count_values($arr);
来源：http://dali.meibo888.top/Article/details/gthczstrxu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gtzaqrybvd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gtqjoswlla.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhiwuduotai.top/Article/details/gteakyhrbf.html

Go:   // 手写 map[T]int
来源：http://dali.kuanghao11.cn/Article/details/gtkkqlrhjw.html

Ruby: arr.tally
来源：http://dali.xylfe.cn/Article/details/gtbxrvngxz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuetiantiany.cn/Article/details/gtuhnoayoj.html

[D21] 判断是否包含某元素
来源：http://dali.fengsongda.top/Article/details/gtdyownqvh.html

Py:   x in arr
来源：http://dali.birdmap.top/Article/details/gtmkxyuduk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zdqjudy.top/Article/details/gtahaubaii.html

JS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtqgkvtihq.html

TS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtxrutmrqv.html

Java: list.contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtbaowlzlf.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtdnhkkesu.html

Ruby: arr.include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvtgwosd.html

C#:   list.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtyutsgorv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhengqikj.top/Article/details/gtbxucmtte.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtkapuleyi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xinyue.icu/Article/details/gtlhlbwbln.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guannengcc.top/Article/details/gtyjhndgyx.html

TS:   [...arr];
来源：http://dali.shangyingyoupin.top/Article/details/gthbcuhqen.html

Java: new ArrayList<>(list);
来源：http://dali.chenzaomai.com/Article/details/gtoxvoakru.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ydzc1.top/Article/details/gtgzpaebsd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.snrcjt.cn/Article/details/gtpyestcmj.html

C#:   new List<int>(list);
来源：http://dali.haohaochexian.top/Article/details/gtzbitpgfp.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbmqwldr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sysykeji.top/Article/details/gtvcplwxqs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.haohaochexian.top/Article/details/gtvckbfwia.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gtilipvgwg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtjuipzdji.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ydzc1.top/Article/details/gtrzaojxrp.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gtplmttrqt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuanzx.com/Article/details/gtygkmyhkk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuanzhike.top/Article/details/gtqrqvxqqu.html

[D24] 字典 / Map 基本操作
来源：http://dali.yvedp.cn/Article/details/gtihcccaij.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gogol.net.cn/Article/details/gtrffvqcbl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yangfankeji.com/Article/details/gtogsdklym.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqwpigce.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtmxzfnuyo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jianghu66.top/Article/details/gtinvdvvqn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cheryme.top/Article/details/gtorlptywh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangdashe.top/Article/details/gtpkvyjcyg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hongshengwenyu.top/Article/details/gtdoszzowh.html

[D25] Set 集合去重与交并差
来源：http://dali.yueranfly.top/Article/details/gthawmhhnv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guowangkeji.top/Article/details/gtmfnjqesy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.havefunace.top/Article/details/gtnjyndzbb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jianghu66.top/Article/details/gtjjbwvayr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pycfn.com/Article/details/gthbfiaaka.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xylfe.cn/Article/details/gtccewzdjj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jianghu66.top/Article/details/gtxtdsmswz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.mhx1999.top/Article/details/gtzseebdlq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuxming.cn/Article/details/gtfddltlch.html

[D26] 数组转字符串
来源：http://dali.gotoacloud.top/Article/details/gtccfofehm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xinyue.icu/Article/details/gtoqgkifwb.html

PHP:  implode(", ", $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtsivnebws.html

JS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtpehcikkb.html

TS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gtdbgkgxzd.html

Java: String.join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gtbeimibck.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cqqwz.cn/Article/details/gtupeeppnv.html

Ruby: arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtkmqmkoxq.html

C#:   string.Join(", ", list)
来源：http://dali.shuidangran.top/Article/details/gtmsavjkwi.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtueofmikm.html

E. 字符串处理
来源：http://dali.cheryme.top/Article/details/gthmdybeoi.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtdnrweptt.html

[E01] 拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gtbwnjiuoz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yangfankeji.com/Article/details/gtbcohrmui.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigufen.top/Article/details/gtjxrucpep.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gttyzaojgt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ybcxt.top/Article/details/gttxtjpzce.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xylfe.cn/Article/details/gtjucgqejp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.snrcjt.cn/Article/details/gtcrmfycrq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hywenlv.cn/Article/details/gtgsterkcm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtwqhgqhtl.html

[E02] 重复字符串
来源：http://dali.sweek.top/Article/details/gthrkfucva.html

Py:   "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gtbpejykpt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnqzz.top/Article/details/gtqbweakuv.html

JS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtlgadcybj.html


<!-- 参考信息 -->