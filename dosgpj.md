代发 wailian999

PHP:  (function () { echo "run"; })();
来源：http://dali.shzxlz.cn/Article/details/gtklajqfwb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gtedjgktxo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nanxinkj.top/Article/details/gtmbtkatga.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigufen.top/Article/details/gtauwmbzwz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yvedp.cn/Article/details/gthguygjlm.html

Ruby: -> { puts "run" }.call
来源：http://dali.hongshengwenyu.top/Article/details/gtnlqfxhmq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtqxlyvbto.html

[C13] 类型声明 / 类型注解
来源：http://dali.meibo888.top/Article/details/gttdayuaom.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xylfe.cn/Article/details/gtwdfdceay.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfejepwjg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xylfe.cn/Article/details/gtderyvdla.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtzrwbyxpd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtloepvwzz.html

Go:   func add(a, b int) int
来源：http://dali.fzhhl.top/Article/details/gtfgeounbo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.316326.xyz/Article/details/gtlocwprii.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jianghu66.top/Article/details/gtvnloojwc.html

[C14] 泛型函数
来源：http://dali.sweek.top/Article/details/gtcyzqmzmr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.birdmap.top/Article/details/gtaklvaeut.html

PHP:  // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gtkkfrhexy.html

JS:   // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gtwzctrsdg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guowangkeji.top/Article/details/gtvwjapsjm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.9152youxi.cn/Article/details/gtiwmpkizf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gtlisaneix.html

Ruby: # 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtbbgceffs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.c1oappe.top/Article/details/gtpbndzzaf.html

[C15] 解构 / 展开参数
来源：http://dali.ybcxt.top/Article/details/gtbbfuwbrv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.mhx1999.top/Article/details/gtiraukhme.html

PHP:  [$a, $b] = $pair;
来源：http://dali.vqdsnc.cn/Article/details/gtwuavfddy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gtmzmlybqi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ehwqpu.com/Article/details/gtxpepzinh.html

Java: // 无解构
来源：http://dali.xziqi.cn/Article/details/gtpjrqjody.html

Go:   // 无解构
来源：http://dali.316326.xyz/Article/details/gtwurccrcw.html

Ruby: a, b = pair
来源：http://dali.haohaochexian.top/Article/details/gtcylmvsgi.html

C#:   var (a, b) = pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtcdkjnveu.html

[C16] 函数 / 方法重载
来源：http://dali.pycfn.com/Article/details/gtgwxvpsng.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tian-w.cn/Article/details/gtcugoxhcg.html

PHP:  // 无重载
来源：http://dali.cdnleiting.top/Article/details/gtnhgpyihj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shzxlz.cn/Article/details/gtxfybpfef.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.havefunace.top/Article/details/gtblzvjijk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gthxsgoyqm.html

Go:   // 无重载：用不同函数名
来源：http://dali.fengsongda.top/Article/details/gtlmuvbryj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gtrdznefda.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daxiang520.top/Article/details/gtybdvqmyb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtopbyroen.html

D. 数组 / 列表 / 集合
来源：http://dali.andypj.xyz/Article/details/gtpoymjyvj.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxhnaqhoa.html

[D01] 创建数组 / 列表
来源：http://dali.jlsjyb.cn/Article/details/gttkuufmzj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cashguo.top/Article/details/gtqxexdrgg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fzhhl.top/Article/details/gtkpxaxbkf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangshuangyany.cn/Article/details/gtjtdhxvrk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xziqi.cn/Article/details/gtinynyeon.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nanxinkj.top/Article/details/gtkqxgynxu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ivvv.top/Article/details/gtdkjhetkj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xziqi.cn/Article/details/gtnicwqghj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258.top/Article/details/gtbaoejxno.html

[D02] 追加元素到末尾
来源：http://dali.fzhhl.top/Article/details/gtdatxctop.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinyuanbaomall.cn/Article/details/gteztzeybg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aibaodan.cn/Article/details/gtkkqcxtcu.html

JS:   arr.push(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvbckfuo.html

TS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gtzfqgkwxv.html

Java: list.add(4);
来源：http://dali.fzhhl.top/Article/details/gtrkjdddyc.html

Go:   arr = append(arr, 4)
来源：http://dali.bjfxy.top/Article/details/gtmbfpwjji.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sweek.top/Article/details/gtkdfkwyqb.html

C#:   list.Add(4);
来源：http://dali.yueranfly.top/Article/details/gtjezqarvg.html

[D03] 在指定位置插入元素
来源：http://dali.hywenlv.cn/Article/details/gthemfzpiu.html

Py:   arr.insert(0, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtyyjzzbdd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenlongwang.top/Article/details/gtscadigoy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhengqikj.top/Article/details/gtblckodfk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zycfv.cn/Article/details/gtvqshovyu.html

Java: list.add(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtgreexpgu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj202588.top/Article/details/gttmdwupnv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.vqdsnc.cn/Article/details/gtotcewuvf.html

C#:   list.Insert(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtddnbujqp.html

[D04] 删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtjtpkdqco.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.kuanghao11.cn/Article/details/gtltzmbhzx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ybcxt.top/Article/details/gtlrqzzmlq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.smart0.xyz/Article/details/gtnfswsjiu.html

TS:   arr.splice(0, 1);
来源：http://dali.mhx1999.top/Article/details/gtnhdyggqi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tian-w.cn/Article/details/gtwhwyvwiy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnqzz.top/Article/details/gtbtppmwmi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtnqlfxnwq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuanzhike.top/Article/details/gtgcxebdjv.html

[D05] 访问与修改元素
来源：http://dali.jiagoushi.top/Article/details/gtyinyxmrf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gtacjjtbye.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gtcdsxqlyg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtfzdzlpyf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxinkj.top/Article/details/gtfxthvhrf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.9152youxi.cn/Article/details/gtvchsouvb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtadtwwmru.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gtbouatgyf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yonumen.top/Article/details/gtcyenllno.html

[D06] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gtdxxhclxf.html

Py:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gthwsfzush.html

PHP:  count($arr);
来源：http://dali.ybcxt.top/Article/details/gtndyhzroc.html

JS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gtuzobnvrv.html

TS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gtjdnvcdln.html

Java: list.size();
来源：http://dali.ivvv.top/Article/details/gtygwlrwiv.html

Go:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gtsthqktto.html

Ruby: arr.length; arr.size
来源：http://dali.316326.xyz/Article/details/gteichcllv.html

C#:   list.Count;
来源：http://dali.guannengcc.top/Article/details/gtcwsrumok.html

[D07] 切片 / 取子数组
来源：http://dali.jyoumei.cn/Article/details/gtcfwyymyr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yueranfly.top/Article/details/gtreheuevm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daxiang520.top/Article/details/gtzwmxblrx.html

JS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtpwvwzvfw.html

TS:   arr.slice(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gtglrxkfxo.html

Java: list.subList(1, 4);
来源：http://dali.gzhubu.top/Article/details/gtkiohwdai.html

Go:   arr[1:4]
来源：http://dali.meibo888.top/Article/details/gtomehjsrj.html

Ruby: arr[1, 3]
来源：http://dali.hysaishi.cn/Article/details/gtctgzvkmh.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtmrkbtwkx.html

[D08] 合并两个数组
来源：http://dali.hfpthk.cn/Article/details/gteilvhuty.html

Py:   a + b;  a.extend(b)
来源：http://dali.zdqjudy.top/Article/details/gtybejqdsf.html

PHP:  array_merge($a, $b);
来源：http://dali.aizwys.cn/Article/details/gtvnehgkno.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tanke756.top/Article/details/gtiyukkdap.html

TS:   [...a, ...b];
来源：http://dali.shangyingyoupin.top/Article/details/gtcjngqizs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtmubfkmwh.html

Go:   append(a, b...)
来源：http://dali.zdqjudy.top/Article/details/gtczmkmxlb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hnxiangtu.top/Article/details/gtnhzgygai.html

C#:   a.Concat(b).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtqyvlnrzn.html

[D09] 排序（升序）
来源：http://dali.bjfxy.top/Article/details/gtrhwdqggm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gtwpupudgl.html

PHP:  sort($arr);
来源：http://dali.yangfankeji.com/Article/details/gtpiyitstc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.iojbl.cn/Article/details/gtqoesowbi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gotoacloud.top/Article/details/gtbjpxglsx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xylfe.cn/Article/details/gtuxrfpquw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtsakjnbjz.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gttgbqufoo.html

C#:   list.Sort();
来源：http://dali.guannengcc.top/Article/details/gtwwgaxxgr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.havefunace.top/Article/details/gtjqagninq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsejmklkk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.vqdsnc.cn/Article/details/gtijjfcpbg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gtavqiuqcg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gtdgrajaqa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ydzc1.top/Article/details/gtizgmjjqo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cheryme.top/Article/details/gtcosfsobb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.quarkkingdee.top/Article/details/gthualhopi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tanke756.top/Article/details/gtdmofbnxv.html

[D11] 反转数组
来源：http://dali.shzxlz.cn/Article/details/gttepupkhq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nanxuanxn.top/Article/details/gtkvnalkjg.html

PHP:  array_reverse($arr);
来源：http://dali.jiagoushi.top/Article/details/gtqbdlgung.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nanxinkj.top/Article/details/gtqqtmiake.html

TS:   [...arr].reverse();
来源：http://dali.gogol.net.cn/Article/details/gteoodjllg.html

Java: Collections.reverse(list);
来源：http://dali.jinqigfzy.top/Article/details/gtwydwwlmi.html

Go:   slices.Reverse(arr)
来源：http://dali.shuidangran.top/Article/details/gtmubeunvj.html

Ruby: arr.reverse
来源：http://dali.aizwys.cn/Article/details/gtdepkwlys.html

C#:   list.Reverse();
来源：http://dali.dianchejie.cn/Article/details/gtonjuxvvp.html

[D12] 查找元素下标
来源：http://dali.sufxvd.cn/Article/details/gtwdgcttpg.html

Py:   arr.index(x);  x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gtzvijxcnw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cdnleiting.top/Article/details/gtnwuyfodf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gtqhznhzao.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ehwqpu.com/Article/details/gtjyzgaqoa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xziqi.cn/Article/details/gtdtmpgtwd.html

Go:   slices.Index(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gthcfbigij.html

Ruby: arr.index(x)
来源：http://dali.sweek.top/Article/details/gtrwzujlwu.html

C#:   list.IndexOf(x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsdemgcf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gaohongyu789.top/Article/details/gtjximncvh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daria6918.cn/Article/details/gtcygbutve.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hywenlv.cn/Article/details/gtmhvonbno.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gthfnjzbne.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gtbcumzzzw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhixingplan.top/Article/details/gtfazchtnm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shangyingyoupin.top/Article/details/gtmodrfiuy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgfzy.top/Article/details/gtrcmtjsto.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gzhubu.top/Article/details/gtgqacpcjt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gzhubu.top/Article/details/gtcmxztacn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ppjwa.cn/Article/details/gtmkopmsme.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hammf.cn/Article/details/gtejqodyhg.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gtwujsyzlu.html

TS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gtlnijbvpt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtuaheoegj.html

Go:   // 手写循环
来源：http://dali.0kj1m.cn/Article/details/gtximvykjc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtiwnujwaw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtfhpikqkz.html

[D15] 去重
来源：http://dali.jianghu66.top/Article/details/gtgoydqobt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zycfv.cn/Article/details/gtqqlsdydd.html

PHP:  array_unique($arr);
来源：http://dali.yuanzhike.top/Article/details/gtqnrpkfyw.html

JS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gtrccdqlnq.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gtigvkdpmp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhiwuduotai.top/Article/details/gtodzyzfij.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pengpengdd.cyou/Article/details/gtbqhoocgo.html

Ruby: arr.uniq
来源：http://dali.yj202588.top/Article/details/gthxnuohux.html

C#:   list.Distinct().ToList()
来源：http://dali.yangfankeji.com/Article/details/gtxkbpipqf.html

[D16] 求和与平均值
来源：http://dali.jiagoushi.top/Article/details/gtlpwlcnna.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtutqnbroz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fengsongda.top/Article/details/gtwjbedttj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gtmucmectv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gthmmksmhn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.daxiang520.top/Article/details/gtpislvure.html

Go:   // 手写循环累加
来源：http://dali.daxiang520.top/Article/details/gthxdbyadv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yongpay.top/Article/details/gtbxkbtaou.html

C#:   list.Sum();  list.Average()
来源：http://dali.hfpthk.cn/Article/details/gtfkafkeac.html

[D17] 最大值与最小值
来源：http://dali.wangshuangyany.cn/Article/details/gtysttncfp.html

Py:   max(arr);  min(arr)
来源：http://dali.cqqwz.cn/Article/details/gtottumlnj.html

PHP:  max($arr);  min($arr);
来源：http://dali.gzhubu.top/Article/details/gtfgxdcwxl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenzaomai.com/Article/details/gtlddkndxf.html

TS:   Math.max(...arr);
来源：http://dali.iojbl.cn/Article/details/gtjugdbyyt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yongpay.top/Article/details/gtjmlrppoh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtpvfguyou.html

Ruby: arr.max;  arr.min
来源：http://dali.zdqjudy.top/Article/details/gtqcltovef.html

C#:   list.Max();  list.Min()
来源：http://dali.meibo888.top/Article/details/gtfextaymf.html

[D18] 扁平化嵌套数组
来源：http://dali.shuidangran.top/Article/details/gtsbfsseus.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.snrcjt.cn/Article/details/gtkqixbuqp.html

PHP:  array_merge(...$nested);
来源：http://dali.yonumen.top/Article/details/gtuqcgxgat.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ybcxt.top/Article/details/gtbxmtcvbg.html

TS:   nested.flat();
来源：http://dali.pengpengdd.cyou/Article/details/gtsualqbal.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtosrncmao.html

Go:   // 手写双层循环
来源：http://dali.ydzc1.top/Article/details/gttiovarlq.html

Ruby: nested.flatten
来源：http://dali.dashuyun.cn/Article/details/gttkgdjpth.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cashguo.top/Article/details/gtcygsjcif.html

[D19] 按字段分组
来源：http://dali.hnqzz.top/Article/details/gtyftmufra.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxinkj.top/Article/details/gtxjmmcfaj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangtech.top/Article/details/gtursccxsj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.quarkkingdee.top/Article/details/gtfwacqnqg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gtshlqaiin.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hammf.cn/Article/details/gtvqkeftxj.html

Go:   // 手写 map[string][]T
来源：http://dali.vqdsnc.cn/Article/details/gtqnxuqmrv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhiwuduotai.top/Article/details/gtgadovcql.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.kuanghao11.cn/Article/details/gtbewwjmvt.html

[D20] 统计每个元素出现次数
来源：http://dali.havefunace.top/Article/details/gtkfetdtii.html

Py:   Counter(arr)
来源：http://dali.meibo888.top/Article/details/gtfnjwctvq.html

PHP:  array_count_values($arr);
来源：http://dali.cashguo.top/Article/details/gtqcrmzenq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtihejpasa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gtctksoryq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cqqwz.cn/Article/details/gtcexhjvmc.html

Go:   // 手写 map[T]int
来源：http://dali.jianghu66.top/Article/details/gtilsksnkk.html

Ruby: arr.tally
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjprutqw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.vqdsnc.cn/Article/details/gtwtpupipy.html

[D21] 判断是否包含某元素
来源：http://dali.jqgfzy.top/Article/details/gtqomzzwvg.html

Py:   x in arr
来源：http://dali.zhoulong.xyz/Article/details/gtnqbiioos.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jianghu66.top/Article/details/gtmznhrkms.html

JS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtkikppaly.html

TS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtzcgvbkhs.html

Java: list.contains(x)
来源：http://dali.aizwys.cn/Article/details/gtzwzbgrce.html

Go:   slices.Contains(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtpmtumumh.html

Ruby: arr.include?(x)
来源：http://dali.zhixingplan.top/Article/details/gtjydhwmvj.html

C#:   list.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtvuviavbg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yangfankeji.com/Article/details/gtxhqhqnzl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zycfv.cn/Article/details/gtmmmglepo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhixingplan.top/Article/details/gthmafqnaz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtgmuwsrmb.html

TS:   [...arr];
来源：http://dali.zhoulong.xyz/Article/details/gtrrmnqacv.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigufen.top/Article/details/gtapizbazi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yuanzhike.top/Article/details/gtzeqdoxai.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ivvv.top/Article/details/gtweobfmbl.html

C#:   new List<int>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtjfclwffn.html

[D23] reduce 累积计算
来源：http://dali.redwolf501.top/Article/details/gteizszenn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guowangkeji.top/Article/details/gtuaxuwyoz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangdashe.top/Article/details/gtsksxevqz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gtouxugfvk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gtufsdmyjm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhixingplan.top/Article/details/gtjtitwqgl.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gttyeiyyyg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gotoacloud.top/Article/details/gtqtsoscbu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuanzhike.top/Article/details/gtltdbokny.html

[D24] 字典 / Map 基本操作
来源：http://dali.0kj1m.cn/Article/details/gtvkbtolxc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yueranfly.top/Article/details/gtnuvgrxwj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hammf.cn/Article/details/gttpwhyxbm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cashguo.top/Article/details/gtgitodsbi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtwketrnwp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daria6918.cn/Article/details/gtjggvtmle.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigfzy.top/Article/details/gtmnswxnov.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuanzx.com/Article/details/gttqjqoqsn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gzhubu.top/Article/details/gtvydzyzho.html

[D25] Set 集合去重与交并差
来源：http://dali.hammf.cn/Article/details/gtgxhjfytx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tian-w.cn/Article/details/gtskdngign.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fzhhl.top/Article/details/gtxzicqjah.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zdqjudy.top/Article/details/gtgzxqprmt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlekaxlal.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cheryme.top/Article/details/gttdobvput.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zdqjudy.top/Article/details/gtyyfljnod.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gzhubu.top/Article/details/gtojqtpsou.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shuidangran.top/Article/details/gtuoilpnil.html

[D26] 数组转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtinxiggbh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sxryk.cn/Article/details/gtlprqhbbk.html

PHP:  implode(", ", $arr);
来源：http://dali.aibaodan.cn/Article/details/gtkopsossb.html

JS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtlbxnemeh.html

TS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtmvggoyrx.html

Java: String.join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gtqmnfncvl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gzhubu.top/Article/details/gtnkhbifva.html

Ruby: arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gtkijwuivl.html

C#:   string.Join(", ", list)
来源：http://dali.yj20258.top/Article/details/gtrlogdmsd.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtqvznypgb.html

E. 字符串处理
来源：http://dali.wangdashe.top/Article/details/gtgqrgckzs.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtsbdcmedd.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gthpvbwxmu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yonumen.top/Article/details/gtlfaigbzk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenlongwang.top/Article/details/gtcbzzozhl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gtikwphlks.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gtqliyhtjd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hysaishi.cn/Article/details/gtzojkpzjy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hfpthk.cn/Article/details/gtyhmfjgtl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.kuanghao11.cn/Article/details/gtxjhnjbox.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnziahby.html

[E02] 重复字符串
来源：http://dali.yonumen.top/Article/details/gtmbshbevk.html

Py:   "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gtomwfupxg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhoulong.xyz/Article/details/gtbizlzwnq.html

JS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtigyumrrj.html

TS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gteixdxhzl.html

Java: "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gtjblmdvcb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcnjyynn.html

Ruby: "ab" * 3
来源：http://dali.fengsongda.top/Article/details/gtrvdhaeyw.html


<!-- 参考信息 -->