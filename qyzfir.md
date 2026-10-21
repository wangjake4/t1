代发 wailian999

PHP:  (function () { echo "run"; })();
来源：http://dali.cucudq.cn/Article/details/gtmfiokaxv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gtoaprmceh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.dianchejie.cn/Article/details/gtdgciaqvk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258.top/Article/details/gttsxyukqq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.haohaochexian.top/Article/details/gtqumlarmm.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhixingplan.top/Article/details/gtmnuqogha.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tanke756.top/Article/details/gtpdrwvhvw.html

[C13] 类型声明 / 类型注解
来源：http://dali.daria6918.cn/Article/details/gtmiedptby.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dashuyun.cn/Article/details/gtikjdbyla.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtcixpcjzg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.feifeiyinyue.top/Article/details/gtdbwvfijh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtmtlwdh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtqkxtvebe.html

Go:   func add(a, b int) int
来源：http://dali.gzhubu.top/Article/details/gtxondeics.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shzxlz.cn/Article/details/gtrbpjerwe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxinkj.top/Article/details/gtuyvclhhf.html

[C14] 泛型函数
来源：http://dali.0kj1m.cn/Article/details/gtrpaadjzf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigfzy.top/Article/details/gtmlhemawt.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdifxevwo.html

JS:   // 无泛型
来源：http://dali.wangdashe.top/Article/details/gtnnwpwbfi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgufenzy.top/Article/details/gtormhcuqo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.daxiang520.top/Article/details/gtweaqtyhn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gzhubu.top/Article/details/gtfmtdldoj.html

Ruby: # 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtljnthnjo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aizwys.cn/Article/details/gtcgnjdljh.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqpnalzm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gogol.net.cn/Article/details/gthmqdiuks.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shuidangran.top/Article/details/gtunlcptgq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.svipenyu.cn/Article/details/gtbvfrynod.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.havefunace.top/Article/details/gtyecrmrdt.html

Java: // 无解构
来源：http://dali.ybcxt.top/Article/details/gtchzxjcth.html

Go:   // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmaaeukc.html

Ruby: a, b = pair
来源：http://dali.yvedp.cn/Article/details/gtaczudscg.html

C#:   var (a, b) = pair;
来源：http://dali.yvedp.cn/Article/details/gtfozmsdmm.html

[C16] 函数 / 方法重载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkhrnfgl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yangfankeji.com/Article/details/gtknbajdeo.html

PHP:  // 无重载
来源：http://dali.zhengqikj.top/Article/details/gtdxkpgjjh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cucudq.cn/Article/details/gtlefmquux.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhengqikj.top/Article/details/gtsjqbhtum.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pycfn.com/Article/details/gtpdaalulw.html

Go:   // 无重载：用不同函数名
来源：http://dali.andypj.xyz/Article/details/gtynycsugs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.andypj.xyz/Article/details/gtjpcicwxg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigfzy.top/Article/details/gtuxljhiek.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtuflncahj.html

D. 数组 / 列表 / 集合
来源：http://dali.vqdsnc.cn/Article/details/gtmsqdqkas.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpstqwcmf.html

[D01] 创建数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gtkebudxai.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sxryk.cn/Article/details/gtopaekpzy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jqgufenzy.top/Article/details/gtpcllfxhb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtquegbrak.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.svipenyu.cn/Article/details/gtbuicglzm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenzaomai.com/Article/details/gtfwfchrhc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yanxiufei.cn/Article/details/gtyzxylyed.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258.top/Article/details/gtfsaahltf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhiwuduotai.top/Article/details/gtuyvfadbl.html

[D02] 追加元素到末尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwcegwix.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.svipenyu.cn/Article/details/gtzjysqoes.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpblhaxm.html

JS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gttctgviot.html

TS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gtjxfsyeuh.html

Java: list.add(4);
来源：http://dali.nanxinkj.top/Article/details/gtjcpmzgof.html

Go:   arr = append(arr, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtemcpmdhx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cucudq.cn/Article/details/gtcbmqfysu.html

C#:   list.Add(4);
来源：http://dali.316326.xyz/Article/details/gtnwotzzed.html

[D03] 在指定位置插入元素
来源：http://dali.yongpay.top/Article/details/gtqlarkvvc.html

Py:   arr.insert(0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtngtjojyv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shuidangran.top/Article/details/gtawszpxcb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuanzhike.top/Article/details/gtditmkopn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtjomcnpag.html

Java: list.add(0, 0);
来源：http://dali.ydzc1.top/Article/details/gtdiamnrxj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.iojbl.cn/Article/details/gtrpmzigip.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shzxlz.cn/Article/details/gttprjujqu.html

C#:   list.Insert(0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtennqgmyl.html

[D04] 删除元素
来源：http://dali.daria6918.cn/Article/details/gttptmsgoi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guannengcc.top/Article/details/gtxhfhaseb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zycfv.cn/Article/details/gtwsmqusrl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pycfn.com/Article/details/gtqrrlqrrs.html

TS:   arr.splice(0, 1);
来源：http://dali.birdmap.top/Article/details/gtyrvfeqpi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ehwqpu.com/Article/details/gtwkmybtua.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigufen.top/Article/details/gtrgoyqlgr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guowangkeji.top/Article/details/gtecahlpac.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ivvv.top/Article/details/gtdlistipf.html

[D05] 访问与修改元素
来源：http://dali.zhoulong.xyz/Article/details/gttsouxvgj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtdmgzwgsv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gtialnsiyf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gtwylisoda.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.316326.xyz/Article/details/gtcegktdkv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zdqjudy.top/Article/details/gtlebtmkol.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gtpkoesqak.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gthvozojgj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtimydtuuh.html

[D06] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gtqwnjyxwh.html

Py:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtaajgklju.html

PHP:  count($arr);
来源：http://dali.daria6918.cn/Article/details/gtpbjyxieh.html

JS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gtlvsnbeyn.html

TS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gtpsjqygku.html

Java: list.size();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtqljlqq.html

Go:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gtecoxkimd.html

Ruby: arr.length; arr.size
来源：http://dali.chenlongwang.top/Article/details/gttzrhmvlh.html

C#:   list.Count;
来源：http://dali.9152youxi.cn/Article/details/gtonwgpsee.html

[D07] 切片 / 取子数组
来源：http://dali.chenjidiqi.icu/Article/details/gtdzbzuwdf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gaohongyu789.top/Article/details/gtezdivdie.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtwecgbdcy.html

JS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtdawzyyrr.html

TS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtsaivgrlh.html

Java: list.subList(1, 4);
来源：http://dali.meibo888.top/Article/details/gtxcshluor.html

Go:   arr[1:4]
来源：http://dali.fengsongda.top/Article/details/gtxfelwqux.html

Ruby: arr[1, 3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmonnilv.html

C#:   list.GetRange(1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtyllnwifu.html

[D08] 合并两个数组
来源：http://dali.tian-w.cn/Article/details/gtvjmdmcqv.html

Py:   a + b;  a.extend(b)
来源：http://dali.xziqi.cn/Article/details/gtwzomrwpe.html

PHP:  array_merge($a, $b);
来源：http://dali.yvedp.cn/Article/details/gtesdctule.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.0kj1m.cn/Article/details/gtmcycydtq.html

TS:   [...a, ...b];
来源：http://dali.wangshuangyany.cn/Article/details/gtzhjyoezn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.andypj.xyz/Article/details/gtyggphnht.html

Go:   append(a, b...)
来源：http://dali.hnxiangtu.top/Article/details/gtlwhizumf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cqqwz.cn/Article/details/gtufezreea.html

C#:   a.Concat(b).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtaysqvoxo.html

[D09] 排序（升序）
来源：http://dali.zhongyouzk.top/Article/details/gtakxdmksp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gtwlrahjey.html

PHP:  sort($arr);
来源：http://dali.birdmap.top/Article/details/gtfrzebjyl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hysaishi.cn/Article/details/gtzavnppzs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yangfankeji.com/Article/details/gtdczwdmgl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenzaomai.com/Article/details/gtdvcqidxg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtdsmgbyni.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gtmtyruzqh.html

C#:   list.Sort();
来源：http://dali.gotoacloud.top/Article/details/gttmkcaejl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gtnbgmwxca.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daxiang520.top/Article/details/gtvoimecmz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.havefunace.top/Article/details/gtzncyprqp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gtzzqmchqs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cqqwz.cn/Article/details/gtbvphsbwi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.iojbl.cn/Article/details/gtfsmqmitd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hysaishi.cn/Article/details/gtktdtbsqn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cdnleiting.top/Article/details/gtzpwnrppc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cashguo.top/Article/details/gtffobmgia.html

[D11] 反转数组
来源：http://dali.chenlongwang.top/Article/details/gtlftrngbm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiumbcror.html

PHP:  array_reverse($arr);
来源：http://dali.cucudq.cn/Article/details/gtlmhktvli.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nanxuanxn.top/Article/details/gtektmcuuz.html

TS:   [...arr].reverse();
来源：http://dali.ivvv.top/Article/details/gteqqovaqc.html

Java: Collections.reverse(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtparpssaf.html

Go:   slices.Reverse(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvpqhcfg.html

Ruby: arr.reverse
来源：http://dali.haohaochexian.top/Article/details/gtdhosggbg.html

C#:   list.Reverse();
来源：http://dali.hammf.cn/Article/details/gtmhtqtjkn.html

[D12] 查找元素下标
来源：http://dali.0kj1m.cn/Article/details/gtfpzamvmv.html

Py:   arr.index(x);  x in arr
来源：http://dali.yanxiufei.cn/Article/details/gtcltkbllt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinqigufen.top/Article/details/gtcydypjmf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigufen.top/Article/details/gtighzjbtf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gtkwlfffsu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuxming.cn/Article/details/gtzzgvizgm.html

Go:   slices.Index(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gthlswqbwj.html

Ruby: arr.index(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtpjmvoysk.html

C#:   list.IndexOf(x);
来源：http://dali.guowangkeji.top/Article/details/gtuovdxgye.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinqigufen.top/Article/details/gtxohxjhoc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuxming.cn/Article/details/gtwmucogbf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yueranfly.top/Article/details/gtjconxnzx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xylfe.cn/Article/details/gtvopxnrdp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtnwflqvlx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj202588.top/Article/details/gtneypxzfr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhiwuduotai.top/Article/details/gtvtxtzsje.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.havefunace.top/Article/details/gtidrqausf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cucudq.cn/Article/details/gtphrlmmpk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shzxlz.cn/Article/details/gthxdthkhv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yonumen.top/Article/details/gtpieuxakh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daria6918.cn/Article/details/gtrorymyck.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnaknxtl.html

TS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtohtuduwb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxqeitfi.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gtcgbxgpzx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ydzc1.top/Article/details/gtkfltgmnq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtklpbgwek.html

[D15] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmyfizrpk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gthaxourzt.html

PHP:  array_unique($arr);
来源：http://dali.redwolf501.top/Article/details/gtbxmymveu.html

JS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gtzstocnqk.html

TS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gtvjglzfdb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fengsongda.top/Article/details/gtntdxzjsi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shangyingyoupin.top/Article/details/gtgynzxqrb.html

Ruby: arr.uniq
来源：http://dali.yanxiufei.cn/Article/details/gtefkflvyw.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgfzy.top/Article/details/gtsirvkhhz.html

[D16] 求和与平均值
来源：http://dali.guannengcc.top/Article/details/gtnqdpfnpi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtttjnjzrf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nwbrower.top/Article/details/gtjytpioul.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gtiilxjnpr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtkrjbydya.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yvedp.cn/Article/details/gtgawfiutr.html

Go:   // 手写循环累加
来源：http://dali.quarkkingdee.top/Article/details/gtxjyrtuyu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shuidangran.top/Article/details/gtypovlzcu.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinghuilouyu.cn/Article/details/gtufjcpoji.html

[D17] 最大值与最小值
来源：http://dali.zhongyouzk.top/Article/details/gtrncpziqs.html

Py:   max(arr);  min(arr)
来源：http://dali.smart0.xyz/Article/details/gtltscudvb.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigufen.top/Article/details/gtxxpopwyn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhengqikj.top/Article/details/gtgumxnraf.html

TS:   Math.max(...arr);
来源：http://dali.hnqzz.top/Article/details/gtfuaeaqhn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yanxiufei.cn/Article/details/gtwnwrfdwl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cdnleiting.top/Article/details/gtqnytzuwu.html

Ruby: arr.max;  arr.min
来源：http://dali.dianchejie.cn/Article/details/gtxlrrzrdc.html

C#:   list.Max();  list.Min()
来源：http://dali.fengsongda.top/Article/details/gtvhpxkaia.html

[D18] 扁平化嵌套数组
来源：http://dali.yongpay.top/Article/details/gtsxhuisuy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangkeji.top/Article/details/gttnvuzvys.html

PHP:  array_merge(...$nested);
来源：http://dali.9152youxi.cn/Article/details/gttoxvoijx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.wangshuangyany.cn/Article/details/gtzxpaiyme.html

TS:   nested.flat();
来源：http://dali.dashuyun.cn/Article/details/gtnxbbxnqu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shuidangran.top/Article/details/gtfxmffqrk.html

Go:   // 手写双层循环
来源：http://dali.fzhhl.top/Article/details/gtlopmtkof.html

Ruby: nested.flatten
来源：http://dali.sxryk.cn/Article/details/gtynrfpfuf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtnfihvbml.html

[D19] 按字段分组
来源：http://dali.smart0.xyz/Article/details/gtxwylujht.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jianghu66.top/Article/details/gtgetblbbz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yvedp.cn/Article/details/gtogifehdz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkgiqsxc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gtkrzrpncp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.redwolf501.top/Article/details/gthbhzzgki.html

Go:   // 手写 map[string][]T
来源：http://dali.tanke756.top/Article/details/gtamndytka.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yanxiufei.cn/Article/details/gtepvbnwxx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxinkj.top/Article/details/gtmjljndsm.html

[D20] 统计每个元素出现次数
来源：http://dali.hnxiangtu.top/Article/details/gtgxmtqrce.html

Py:   Counter(arr)
来源：http://dali.yj20258888.top/Article/details/gtnpganvyg.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelxqyrus.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gtcrizojbc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gtckfzkbph.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yonumen.top/Article/details/gttloqqlur.html

Go:   // 手写 map[T]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjwwuvhd.html

Ruby: arr.tally
来源：http://dali.shangyingyoupin.top/Article/details/gtxmqivrdh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jyoumei.cn/Article/details/gtxzfxajzw.html

[D21] 判断是否包含某元素
来源：http://dali.yonumen.top/Article/details/gtebaegnuj.html

Py:   x in arr
来源：http://dali.cucudq.cn/Article/details/gtrwdypfeb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ydzc1.top/Article/details/gtgnsdniqq.html

JS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gttdfltdpq.html

TS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gtzynplavs.html

Java: list.contains(x)
来源：http://dali.fengsongda.top/Article/details/gtyzlnpbla.html

Go:   slices.Contains(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtkrfcyafq.html

Ruby: arr.include?(x)
来源：http://dali.ppjwa.cn/Article/details/gtuwtodtyq.html

C#:   list.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtjnlhxtti.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ybcxt.top/Article/details/gtkrzdxpsn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtiislazdu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtenqzmzpe.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgfzy.top/Article/details/gtkbwmtvsj.html

TS:   [...arr];
来源：http://dali.sufxvd.cn/Article/details/gtcpeaxkac.html

Java: new ArrayList<>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtyaiwglkn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ivvv.top/Article/details/gtbcbsklek.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tianlin.xyz/Article/details/gthuunxdjm.html

C#:   new List<int>(list);
来源：http://dali.chenlongwang.top/Article/details/gtagdvyceh.html

[D23] reduce 累积计算
来源：http://dali.yonumen.top/Article/details/gtkbxzxqkp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jyoumei.cn/Article/details/gtdeksoibc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.0kj1m.cn/Article/details/gtpzgrbngf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gttmcpreww.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gtydbsrwac.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.pycfn.com/Article/details/gtgblodabk.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gtczyyovbo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shangyingyoupin.top/Article/details/gtyqgekknc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tianlin.xyz/Article/details/gtsqllxrln.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxinkj.top/Article/details/gtzuoskdte.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hywenlv.cn/Article/details/gtzbglejtc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtkvdmmjty.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtbcsjjxrw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cheryme.top/Article/details/gtgxborrin.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtmalpqmwo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxuanxn.top/Article/details/gtdxgvmhmy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yonumen.top/Article/details/gtovruqrzs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.svipenyu.cn/Article/details/gtnevwkwla.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxuanxn.top/Article/details/gtalzprtcg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cheryme.top/Article/details/gtdbmcepam.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dianchejie.cn/Article/details/gtclqduqme.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daria6918.cn/Article/details/gtkqvvlhyn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj202588.top/Article/details/gtjwjwblsx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.wangshuangyany.cn/Article/details/gteixlfhoo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daria6918.cn/Article/details/gtdkgdzfsi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cheryme.top/Article/details/gthvckwpsj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtihslsvib.html

[D26] 数组转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtasbyeqrc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtvyxdcjoh.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtewblcqso.html

JS:   arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtailsleja.html

TS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtpmtdpjwo.html

Java: String.join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gtlfpkdphe.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cdnleiting.top/Article/details/gtobmfiiak.html

Ruby: arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtfiufyutt.html

C#:   string.Join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gtsxsgofij.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtocvvemqy.html

E. 字符串处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglsgcwkt.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtibhqzesc.html

[E01] 拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gtpaonoglo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xinyue.icu/Article/details/gtherfgfry.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxuanxn.top/Article/details/gtovmbqqbs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgfzy.top/Article/details/gtqwczamzr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.316326.xyz/Article/details/gtmjbfpgor.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fzhhl.top/Article/details/gtqibhcsij.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yvedp.cn/Article/details/gtwbyujrqs.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yongpay.top/Article/details/gtuovuvggv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtyzetlzdq.html

[E02] 重复字符串
来源：http://dali.meibo888.top/Article/details/gtdcyluscf.html

Py:   "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gtppcqyouh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuanzhike.top/Article/details/gtlclmocgq.html

JS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtcgqfgtxc.html

TS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtuzfqoeec.html

Java: "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtnbzfbsrp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.svipenyu.cn/Article/details/gtqnpeyqdw.html

Ruby: "ab" * 3
来源：http://dali.andypj.xyz/Article/details/gtokeyfnlv.html


<!-- 参考信息 -->