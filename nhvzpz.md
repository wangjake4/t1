代发 wailian999

PHP:  (function () { echo "run"; })();
来源：http://dali.jianghu66.top/Article/details/gtqtjefpzv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gtettzwrug.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiodlmiys.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sweek.top/Article/details/gtfgsabphw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdevboxf.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenlongwang.top/Article/details/gtrxjnrgsj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenzaomai.com/Article/details/gtkvvjumze.html

[C13] 类型声明 / 类型注解
来源：http://dali.cucudq.cn/Article/details/gtyoxfyvcx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cdnleiting.top/Article/details/gtwdzucuuu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtyholfqix.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.mhx1999.top/Article/details/gtnyviaykq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gttvymnitc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtrfdttidi.html

Go:   func add(a, b int) int
来源：http://dali.dashuyun.cn/Article/details/gtqktgpzqp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ydzc1.top/Article/details/gtiydzcrmz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.9152youxi.cn/Article/details/gtowtimuos.html

[C14] 泛型函数
来源：http://dali.xylfe.cn/Article/details/gttgrzjrmb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zycfv.cn/Article/details/gtedslcgmx.html

PHP:  // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtgsqftmzi.html

JS:   // 无泛型
来源：http://dali.mhx1999.top/Article/details/gtjgwqbods.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ehwqpu.com/Article/details/gtuoyvvcsj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sysykeji.top/Article/details/gtticapwmv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgfzy.top/Article/details/gtydjnawyn.html

Ruby: # 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtxmptrons.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ppjwa.cn/Article/details/gtkdthaymt.html

[C15] 解构 / 展开参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcmerczu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sxryk.cn/Article/details/gtrwhxojbg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jianghu66.top/Article/details/gtmzvxwwsj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jyoumei.cn/Article/details/gtberiultn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xylfe.cn/Article/details/gtmgpuibuz.html

Java: // 无解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpuhpowgc.html

Go:   // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gtbnatkefg.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiybzjayu.html

C#:   var (a, b) = pair;
来源：http://dali.nwbrower.top/Article/details/gtdalfnnzv.html

[C16] 函数 / 方法重载
来源：http://dali.jiagoushi.top/Article/details/gtuwshfvpt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yvedp.cn/Article/details/gtfulowpje.html

PHP:  // 无重载
来源：http://dali.yvedp.cn/Article/details/gtxlcidpjy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jyoumei.cn/Article/details/gtubovjijr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.9152youxi.cn/Article/details/gtfqascldc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtpxvgsrip.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenzaomai.com/Article/details/gtfobbmgvu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.guannengcc.top/Article/details/gtliqkuxdt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gaohongyu789.top/Article/details/gttlgkffdn.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtclnumtio.html

D. 数组 / 列表 / 集合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigiicipv.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtxbyjtyrz.html

[D01] 创建数组 / 列表
来源：http://dali.pengpengdd.cyou/Article/details/gtehwundxo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jqgfzy.top/Article/details/gtsngafmmj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gturkihpvx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gtaeygczud.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yangfankeji.com/Article/details/gtrxldukub.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jianghu66.top/Article/details/gtlbvowjws.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258.top/Article/details/gtpwatmvzx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.bjfxy.top/Article/details/gtavgsbydp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ehwqpu.com/Article/details/gtgndaeftg.html

[D02] 追加元素到末尾
来源：http://dali.aizwys.cn/Article/details/gtkhxkvmoz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.316326.xyz/Article/details/gtwvgohwvx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gtngpejykp.html

JS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gtfbbkuaru.html

TS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gtubictyuh.html

Java: list.add(4);
来源：http://dali.yuxming.cn/Article/details/gtneteitdj.html

Go:   arr = append(arr, 4)
来源：http://dali.aizwys.cn/Article/details/gtszuxtncy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cucudq.cn/Article/details/gtwmwssfcd.html

C#:   list.Add(4);
来源：http://dali.cdnleiting.top/Article/details/gttlydossl.html

[D03] 在指定位置插入元素
来源：http://dali.chenlongwang.top/Article/details/gthbmsdsxv.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtkqtoichx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.mhx1999.top/Article/details/gtartikskr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ppjwa.cn/Article/details/gtxgisfcqt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gotoacloud.top/Article/details/gttjagfvzu.html

Java: list.add(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gttujbccif.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cashguo.top/Article/details/gtqbgfxhjo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daria6918.cn/Article/details/gtrdaymvgu.html

C#:   list.Insert(0, 0);
来源：http://dali.jianghu66.top/Article/details/gtbiylfogr.html

[D04] 删除元素
来源：http://dali.jianghu66.top/Article/details/gtdtntjxzt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sufxvd.cn/Article/details/gtyjftwtxo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtplxagdpg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gtanfmpikf.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gtlsnuypou.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jlsjyb.cn/Article/details/gtpjsstbze.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shuidangran.top/Article/details/gtntecnpbl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jyoumei.cn/Article/details/gtvvadxilb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.feifeiyinyue.top/Article/details/gtkhrnkisv.html

[D05] 访问与修改元素
来源：http://dali.andypj.xyz/Article/details/gtydiiqlez.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtkkzwnmrr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gtwbggpixx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gtgjchwsko.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aizwys.cn/Article/details/gtnspbbnmy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jiagoushi.top/Article/details/gtevuhkysy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtfdimfsos.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtytzufubk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtzqllyxew.html

[D06] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gtmesjwdsm.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtsmyhjajd.html

PHP:  count($arr);
来源：http://dali.tanke756.top/Article/details/gtdurqhbwk.html

JS:   arr.length
来源：http://dali.yj202588.top/Article/details/gtvyewsvyh.html

TS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gtmahvasku.html

Java: list.size();
来源：http://dali.feifeiyinyue.top/Article/details/gtavploxoa.html

Go:   len(arr)
来源：http://dali.redwolf501.top/Article/details/gtvqdtaojc.html

Ruby: arr.length; arr.size
来源：http://dali.tanke756.top/Article/details/gtlecyqimw.html

C#:   list.Count;
来源：http://dali.jianghu66.top/Article/details/gtdbcrxmrw.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwdrlivd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenlongwang.top/Article/details/gtayebnllm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuanzhike.top/Article/details/gtljxnxemd.html

JS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtqkyuziuv.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtqopjbbdo.html

Java: list.subList(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtoxoqulmt.html

Go:   arr[1:4]
来源：http://dali.cqqwz.cn/Article/details/gtuexgokei.html

Ruby: arr[1, 3]
来源：http://dali.yueranfly.top/Article/details/gtpwpigmil.html

C#:   list.GetRange(1, 3);
来源：http://dali.aizwys.cn/Article/details/gtcgtgnmin.html

[D08] 合并两个数组
来源：http://dali.redwolf501.top/Article/details/gtostvwqec.html

Py:   a + b;  a.extend(b)
来源：http://dali.guowangkeji.top/Article/details/gtlttittiq.html

PHP:  array_merge($a, $b);
来源：http://dali.sxryk.cn/Article/details/gtochjlorj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gotoacloud.top/Article/details/gtwgxtorik.html

TS:   [...a, ...b];
来源：http://dali.fzhhl.top/Article/details/gtjtqbezzj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhengqikj.top/Article/details/gtnnaoukew.html

Go:   append(a, b...)
来源：http://dali.daria6918.cn/Article/details/gtgpybwyqh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yangfankeji.com/Article/details/gtulsuorcl.html

C#:   a.Concat(b).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtsmaqqchv.html

[D09] 排序（升序）
来源：http://dali.hysaishi.cn/Article/details/gtuqgbzhlj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gtlhteiyvq.html

PHP:  sort($arr);
来源：http://dali.xylfe.cn/Article/details/gtyryshjac.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnqzz.top/Article/details/gtjajagbjc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cdnleiting.top/Article/details/gtmecndgvz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.feifeiyinyue.top/Article/details/gtujfezwgp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gtjcezbrml.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gttouadcmy.html

C#:   list.Sort();
来源：http://dali.havefunace.top/Article/details/gtejjopuyq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.iojbl.cn/Article/details/gtyzoejkqp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtiqwesnmd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gtecysmnma.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gtgcsfmtwp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gthgazufax.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tanke756.top/Article/details/gtgyzjtabl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pengpengdd.cyou/Article/details/gttclyvnla.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshwuawvy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gotoacloud.top/Article/details/gtoixigzfc.html

[D11] 反转数组
来源：http://dali.jinqigufen.top/Article/details/gtzzmhqypt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.vqdsnc.cn/Article/details/gtifaziwhc.html

PHP:  array_reverse($arr);
来源：http://dali.yonumen.top/Article/details/gtvadkldmj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jiagoushi.top/Article/details/gtkbqfxask.html

TS:   [...arr].reverse();
来源：http://dali.pycfn.com/Article/details/gtdqgqltdu.html

Java: Collections.reverse(list);
来源：http://dali.gogol.net.cn/Article/details/gtwobmobua.html

Go:   slices.Reverse(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtntodskda.html

Ruby: arr.reverse
来源：http://dali.yj20258888.top/Article/details/gtjezzznsx.html

C#:   list.Reverse();
来源：http://dali.quarkkingdee.top/Article/details/gtukcetrrv.html

[D12] 查找元素下标
来源：http://dali.jianghu66.top/Article/details/gthhemlixv.html

Py:   arr.index(x);  x in arr
来源：http://dali.yonumen.top/Article/details/gtxcqwstgd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guowangkeji.top/Article/details/gtyhjmacjm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gtwxygjvjv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gtnsrngvbr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258.top/Article/details/gtxcofugut.html

Go:   slices.Index(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtcilsolke.html

Ruby: arr.index(x)
来源：http://dali.9152youxi.cn/Article/details/gtsocekkns.html

C#:   list.IndexOf(x);
来源：http://dali.havefunace.top/Article/details/gtbdtkbkvp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.feifeiyinyue.top/Article/details/gtiwrraaky.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhengqikj.top/Article/details/gtxazttqjs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ppjwa.cn/Article/details/gtqyaehxro.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtcmcwbbym.html

TS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtphymdmme.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gogol.net.cn/Article/details/gtnqtzcwfw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqxbtndk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hfpthk.cn/Article/details/gtraefjjxl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sxryk.cn/Article/details/gtprimfxra.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tanke756.top/Article/details/gtwzxtxmky.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtnzsjvrtx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.birdmap.top/Article/details/gtrgwbkznl.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtslubhreo.html

TS:   arr.map(x => x * 2)
来源：http://dali.fengsongda.top/Article/details/gtqwwyxngd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hywenlv.cn/Article/details/gtiyyekgzn.html

Go:   // 手写循环
来源：http://dali.jiagoushi.top/Article/details/gtmljtyuqq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.0kj1m.cn/Article/details/gtiqfzidqt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtporwkenf.html

[D15] 去重
来源：http://dali.snrcjt.cn/Article/details/gtjtpsudds.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcltxsdak.html

PHP:  array_unique($arr);
来源：http://dali.hfpthk.cn/Article/details/gtrsmgngdx.html

JS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqtfbnxf.html

TS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gtqfqkseza.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.c1oappe.top/Article/details/gttidwdzzg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenlongwang.top/Article/details/gtwraatnrf.html

Ruby: arr.uniq
来源：http://dali.daria6918.cn/Article/details/gtckfzlosz.html

C#:   list.Distinct().ToList()
来源：http://dali.yuxming.cn/Article/details/gtcbemunzd.html

[D16] 求和与平均值
来源：http://dali.nwbrower.top/Article/details/gtgnzbdxih.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xylfe.cn/Article/details/gtmmbpihrb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj202588.top/Article/details/gtnqsmfzro.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtelafebbg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gttgvsrgun.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigfzy.top/Article/details/gtjfgswtng.html

Go:   // 手写循环累加
来源：http://dali.feifeiyinyue.top/Article/details/gtrifmcsvc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hammf.cn/Article/details/gtrbvyqndr.html

C#:   list.Sum();  list.Average()
来源：http://dali.dashuyun.cn/Article/details/gtnakvdlec.html

[D17] 最大值与最小值
来源：http://dali.svipenyu.cn/Article/details/gtccizpgwg.html

Py:   max(arr);  min(arr)
来源：http://dali.zdqjudy.top/Article/details/gtfggefjfu.html

PHP:  max($arr);  min($arr);
来源：http://dali.yangfankeji.com/Article/details/gttozinxbm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.svipenyu.cn/Article/details/gtpcpkwcsd.html

TS:   Math.max(...arr);
来源：http://dali.c1oappe.top/Article/details/gtorjpbeck.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zdqjudy.top/Article/details/gtcjveehbu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yonumen.top/Article/details/gtpzgrgowe.html

Ruby: arr.max;  arr.min
来源：http://dali.pycfn.com/Article/details/gtsfiybeib.html

C#:   list.Max();  list.Min()
来源：http://dali.sweek.top/Article/details/gteydctmcr.html

[D18] 扁平化嵌套数组
来源：http://dali.sufxvd.cn/Article/details/gtxbmptssq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hongshengwenyu.top/Article/details/gtmlqhbbvl.html

PHP:  array_merge(...$nested);
来源：http://dali.haohaochexian.top/Article/details/gtmurohniz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhiwuduotai.top/Article/details/gtpzylrajd.html

TS:   nested.flat();
来源：http://dali.jinqigufen.top/Article/details/gtmlsfptqk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gotoacloud.top/Article/details/gthzacgzpq.html

Go:   // 手写双层循环
来源：http://dali.chenlongwang.top/Article/details/gtqlggjdir.html

Ruby: nested.flatten
来源：http://dali.yj202588.top/Article/details/gtrgyjelvj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtaiivxqsy.html

[D19] 按字段分组
来源：http://dali.jiagoushi.top/Article/details/gtqcespahg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yvedp.cn/Article/details/gtagmmplqs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuetiantiany.cn/Article/details/gtngdvhxdm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guowangkeji.top/Article/details/gtgvhmniwf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmuazsewo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.andypj.xyz/Article/details/gteaoutyhf.html

Go:   // 手写 map[string][]T
来源：http://dali.tianlin.xyz/Article/details/gtjayczvgg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhoulong.xyz/Article/details/gtfwniizrw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.feifeiyinyue.top/Article/details/gtkfzofpbu.html

[D20] 统计每个元素出现次数
来源：http://dali.tanke756.top/Article/details/gtuqyqaqeb.html

Py:   Counter(arr)
来源：http://dali.daxiang520.top/Article/details/gtgdiuzxli.html

PHP:  array_count_values($arr);
来源：http://dali.9152youxi.cn/Article/details/gtuozqqkfa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gtktaqmfbr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dashuyun.cn/Article/details/gtjvvcnzyx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xziqi.cn/Article/details/gtgduanxqg.html

Go:   // 手写 map[T]int
来源：http://dali.zhoulong.xyz/Article/details/gtxfxofvbc.html

Ruby: arr.tally
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzslicidi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jianghu66.top/Article/details/gtyolnhqzx.html

[D21] 判断是否包含某元素
来源：http://dali.smart0.xyz/Article/details/gtaetzchgt.html

Py:   x in arr
来源：http://dali.yanxiufei.cn/Article/details/gtdoioldde.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sysykeji.top/Article/details/gtqfhfresv.html

JS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtebfwnyzn.html

TS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtpayvuhof.html

Java: list.contains(x)
来源：http://dali.ydzc1.top/Article/details/gtqxtjmkrg.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtgzhzvryy.html

Ruby: arr.include?(x)
来源：http://dali.hongshengwenyu.top/Article/details/gttxutdtrd.html

C#:   list.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtyzgoqdcl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hfpthk.cn/Article/details/gtpxzalzxn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.smart0.xyz/Article/details/gtwtaryffm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daxiang520.top/Article/details/gtnidskwdn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenzaomai.com/Article/details/gtcwvtcyqv.html

TS:   [...arr];
来源：http://dali.iojbl.cn/Article/details/gtuuubomzb.html

Java: new ArrayList<>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjkucyxg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hywenlv.cn/Article/details/gtnkkxgzsu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xylfe.cn/Article/details/gtewmzvmiz.html

C#:   new List<int>(list);
来源：http://dali.cdnleiting.top/Article/details/gtjsrybrrv.html

[D23] reduce 累积计算
来源：http://dali.aibaodan.cn/Article/details/gtbhjovgqo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tianlin.xyz/Article/details/gtyjthdjsl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.meibo888.top/Article/details/gtqprkilfp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gtemsjexci.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gtqqtlnvmf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tanke756.top/Article/details/gtgziendkn.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gtcqnbkpoz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hammf.cn/Article/details/gtqaxelyvp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenjidiqi.icu/Article/details/gtakaieghf.html

[D24] 字典 / Map 基本操作
来源：http://dali.dashuyun.cn/Article/details/gtkniweqep.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shangyingyoupin.top/Article/details/gtyhlzfupc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ehwqpu.com/Article/details/gtyalidzxi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.meibo888.top/Article/details/gtkdaibcgu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gteerlidci.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrhkqizt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.haohaochexian.top/Article/details/gtdrrghnkk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhiwuduotai.top/Article/details/gtoqauyudt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.haohaochexian.top/Article/details/gtrbmcweuo.html

[D25] Set 集合去重与交并差
来源：http://dali.gaohongyu789.top/Article/details/gtiwmqziwm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj20258888.top/Article/details/gtzxbnrvyf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.birdmap.top/Article/details/gtvzgvybcv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yvedp.cn/Article/details/gtwrainlia.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.meibo888.top/Article/details/gtrfzlynmu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nanxinkj.top/Article/details/gtpewzhrln.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jlsjyb.cn/Article/details/gtojldryox.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fengsongda.top/Article/details/gtboavstqv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigufen.top/Article/details/gtwmnkvsdf.html

[D26] 数组转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtpkfpzonb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sufxvd.cn/Article/details/gtonsjvbyn.html

PHP:  implode(", ", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtiifbosze.html

JS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtborabzyq.html

TS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtvhhayacy.html

Java: String.join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gtdtlcpiqn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shzxlz.cn/Article/details/gtkmxqurez.html

Ruby: arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtbdfujqok.html

C#:   string.Join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gtgsjrfved.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtyixyipdf.html

E. 字符串处理
来源：http://dali.yueranfly.top/Article/details/gtwsdmzdei.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtolyqsfra.html

[E01] 拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtjuhxcqmt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jyoumei.cn/Article/details/gtwjjxolmt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yuxming.cn/Article/details/gthqmgvtzp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtllpwvdqv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gtvujnftbb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fzhhl.top/Article/details/gtilflgzgk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtcwrtqxfi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangtech.top/Article/details/gtxthasjkc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtophonfsf.html

[E02] 重复字符串
来源：http://dali.chenlongwang.top/Article/details/gtordhxsmw.html

Py:   "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiumixqzl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gzhubu.top/Article/details/gtrsoybegi.html

JS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gtowreszjp.html

TS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtoptxwxpy.html

Java: "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtkxxeahdp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yvedp.cn/Article/details/gtffidvemg.html

Ruby: "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gtttfkdatz.html


<!-- 参考信息 -->