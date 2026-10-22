代发 wailian999

[C14] 泛型函数
来源：http://dali.yj202588.top/Article/details/gtzqmzpqgn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xuanzx.com/Article/details/gtwqmcblta.html

PHP:  // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtxqnquzva.html

JS:   // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gtupkiykcv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sxryk.cn/Article/details/gtektqzttz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xziqi.cn/Article/details/gtqqmqxsbj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.snrcjt.cn/Article/details/gtktjiftky.html

Ruby: # 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtkxiglnga.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aizwys.cn/Article/details/gtganbhoow.html

[C15] 解构 / 展开参数
来源：http://dali.c1oappe.top/Article/details/gtdtxasbde.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hnxiangtu.top/Article/details/gtzlkdrlga.html

PHP:  [$a, $b] = $pair;
来源：http://dali.svipenyu.cn/Article/details/gtjwcxoeju.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gtxhufbcbk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenlongwang.top/Article/details/gttzvypciq.html

Java: // 无解构
来源：http://dali.zdqjudy.top/Article/details/gtxfnarafh.html

Go:   // 无解构
来源：http://dali.9152youxi.cn/Article/details/gtbiwyrzyv.html

Ruby: a, b = pair
来源：http://dali.sysykeji.top/Article/details/gtccpkfkuo.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gtcrsnxthu.html

[C16] 函数 / 方法重载
来源：http://dali.zhixingplan.top/Article/details/gtstzzdmhn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj202588.top/Article/details/gtxksvuzie.html

PHP:  // 无重载
来源：http://dali.meibo888.top/Article/details/gtbtlaessr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daxiang520.top/Article/details/gtxdetsqlk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowsgokpt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuanzx.com/Article/details/gtmrdnbnjp.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnqzz.top/Article/details/gtedpwbmsz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ppjwa.cn/Article/details/gtyonlrhsj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shzxlz.cn/Article/details/gtvzjfkcin.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtbljutsmb.html

D. 数组 / 列表 / 集合
来源：http://dali.xylfe.cn/Article/details/gtmzguhuxv.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtcmwttope.html

[D01] 创建数组 / 列表
来源：http://dali.gzhubu.top/Article/details/gtpwlkebcf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jqgfzy.top/Article/details/gtnxjduipb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shangyingyoupin.top/Article/details/gtmadazcjl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtukerhqou.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinqigufen.top/Article/details/gtdortbxud.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.bjfxy.top/Article/details/gtvazfsqdc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.snrcjt.cn/Article/details/gtsrxziimf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shuidangran.top/Article/details/gtsfywaxnz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shuidangran.top/Article/details/gttuxawjai.html

[D02] 追加元素到末尾
来源：http://dali.gogol.net.cn/Article/details/gtqpepcbfm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangshuangyany.cn/Article/details/gtiirmslhh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fengsongda.top/Article/details/gtefmcvlln.html

JS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtqokjbcwp.html

TS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gtdczesjew.html

Java: list.add(4);
来源：http://dali.gogol.net.cn/Article/details/gttbjlrxai.html

Go:   arr = append(arr, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtqzcjafdn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwtsyhie.html

C#:   list.Add(4);
来源：http://dali.dianchejie.cn/Article/details/gtdyigioco.html

[D03] 在指定位置插入元素
来源：http://dali.nwbrower.top/Article/details/gtpbtxveke.html

Py:   arr.insert(0, 0)
来源：http://dali.ybcxt.top/Article/details/gtfdemwkfj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tianlin.xyz/Article/details/gtdffbtoje.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fengsongda.top/Article/details/gtcxjdrcyf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtquwwpewm.html

Java: list.add(0, 0);
来源：http://dali.yj20258.top/Article/details/gtetkbfvsp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cdnleiting.top/Article/details/gtoagzvuyr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258888.top/Article/details/gtgyabkqcm.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtenfrfblb.html

[D04] 删除元素
来源：http://dali.sufxvd.cn/Article/details/gtiijiwigd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.redwolf501.top/Article/details/gtaovvexqm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pycfn.com/Article/details/gtmtpqgswz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cheryme.top/Article/details/gtbkiqcfge.html

TS:   arr.splice(0, 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswambpno.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ppjwa.cn/Article/details/gtlavoxgmi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuxming.cn/Article/details/gtfstvpwrh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xylfe.cn/Article/details/gtcfcasrgf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sysykeji.top/Article/details/gtdajivwzp.html

[D05] 访问与修改元素
来源：http://dali.nwbrower.top/Article/details/gtsepylxit.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxbuhcbl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtymmgqobi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cheryme.top/Article/details/gteydrnrxy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shuidangran.top/Article/details/gtgineeuri.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvpgjfmt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gttdtyeaya.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtgcmcvuwl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtvkxgovpu.html

[D06] 数组长度
来源：http://dali.pycfn.com/Article/details/gtariaksor.html

Py:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gtesjbakte.html

PHP:  count($arr);
来源：http://dali.guowangkeji.top/Article/details/gtvvywzgxe.html

JS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gtjtyxcobv.html

TS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gtpmauqbjp.html

Java: list.size();
来源：http://dali.iojbl.cn/Article/details/gtuxsmhusj.html

Go:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtxctkdzpb.html

Ruby: arr.length; arr.size
来源：http://dali.dianchejie.cn/Article/details/gtrxnvqlyo.html

C#:   list.Count;
来源：http://dali.hnxiangtu.top/Article/details/gtigcubrhe.html

[D07] 切片 / 取子数组
来源：http://dali.jianghu66.top/Article/details/gtonwnswry.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aizwys.cn/Article/details/gtvzfeyhlv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.mhx1999.top/Article/details/gtohrruqji.html

JS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtafugdxdu.html

TS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gttcvqlsfe.html

Java: list.subList(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtcedvilcd.html

Go:   arr[1:4]
来源：http://dali.jqgufenzy.top/Article/details/gtnzfksuvf.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gttzqpacso.html

C#:   list.GetRange(1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahogvjpg.html

[D08] 合并两个数组
来源：http://dali.hywenlv.cn/Article/details/gtindnymyu.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtggcddnko.html

PHP:  array_merge($a, $b);
来源：http://dali.hongshengwenyu.top/Article/details/gthqvximmg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yanxiufei.cn/Article/details/gtewlnvqkw.html

TS:   [...a, ...b];
来源：http://dali.yvedp.cn/Article/details/gtpoccipwj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tianlin.xyz/Article/details/gtjuhcjwyp.html

Go:   append(a, b...)
来源：http://dali.xuanzx.com/Article/details/gtfgzvxzqy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.havefunace.top/Article/details/gtflzpioxq.html

C#:   a.Concat(b).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtzqhyphof.html

[D09] 排序（升序）
来源：http://dali.birdmap.top/Article/details/gtlrwuhmol.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gtfzqyuxwk.html

PHP:  sort($arr);
来源：http://dali.smart0.xyz/Article/details/gthevuigom.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shuidangran.top/Article/details/gtbnupudgh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlmkiwvd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenjidiqi.icu/Article/details/gtdehtahcq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gtpmeimzud.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gtvsaxypzn.html

C#:   list.Sort();
来源：http://dali.andypj.xyz/Article/details/gtedqfnrqq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhengqikj.top/Article/details/gtjltupieg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtgnhliiac.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shzxlz.cn/Article/details/gtaopvexpx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtownjcpcv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtmgqegjvm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yanxiufei.cn/Article/details/gtcuwvjgmh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ybcxt.top/Article/details/gtawbizgdu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.daria6918.cn/Article/details/gttdbfjldm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aibaodan.cn/Article/details/gtgcpjtyaz.html

[D11] 反转数组
来源：http://dali.zycfv.cn/Article/details/gteiqsjpwv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gaohongyu789.top/Article/details/gtbmoxddbs.html

PHP:  array_reverse($arr);
来源：http://dali.meibo888.top/Article/details/gtdfdnipvt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tanke756.top/Article/details/gtbkaaknlj.html

TS:   [...arr].reverse();
来源：http://dali.yuanzhike.top/Article/details/gtlaehsvtk.html

Java: Collections.reverse(list);
来源：http://dali.yj202588.top/Article/details/gtnoqkwtvu.html

Go:   slices.Reverse(arr)
来源：http://dali.xylfe.cn/Article/details/gtyjrnweqj.html

Ruby: arr.reverse
来源：http://dali.zhengqikj.top/Article/details/gtodlgzqou.html

C#:   list.Reverse();
来源：http://dali.dianchejie.cn/Article/details/gtlgxnbtrw.html

[D12] 查找元素下标
来源：http://dali.xinyue.icu/Article/details/gtwszaivev.html

Py:   arr.index(x);  x in arr
来源：http://dali.jqgufenzy.top/Article/details/gtlrywsewd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtsuxgqumw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmoulpjhs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gtnendlctx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hfpthk.cn/Article/details/gttwupvptn.html

Go:   slices.Index(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtenbobvjh.html

Ruby: arr.index(x)
来源：http://dali.hywenlv.cn/Article/details/gtcygkrifu.html

C#:   list.IndexOf(x);
来源：http://dali.hongshengwenyu.top/Article/details/gtzmqjjbte.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jyoumei.cn/Article/details/gtxawzrbio.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cheryme.top/Article/details/gtncktdiqq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.svipenyu.cn/Article/details/gtgarhydbr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gtckfuadbk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gtbujpsyuc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ydzc1.top/Article/details/gtltepntrn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj202588.top/Article/details/gtmborkuxl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yonumen.top/Article/details/gtiwwzpkdp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuxming.cn/Article/details/gtdgkjxaoo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxinkj.top/Article/details/gtdcyqlqib.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.9152youxi.cn/Article/details/gtqhykmshh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.redwolf501.top/Article/details/gtxmkdmksc.html

JS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gtvtstllgk.html

TS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gtbhagzkpb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sufxvd.cn/Article/details/gthuqpxhdd.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtzzmhmfxy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hnqzz.top/Article/details/gtazijmtgr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nwbrower.top/Article/details/gtvptjvswc.html

[D15] 去重
来源：http://dali.havefunace.top/Article/details/gtiymjouqg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cucudq.cn/Article/details/gtutkgaupz.html

PHP:  array_unique($arr);
来源：http://dali.haohaochexian.top/Article/details/gtqaqvrihb.html

JS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtzudykgit.html

TS:   [...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gtcucrcrgv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jianghu66.top/Article/details/gtccghdbsp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhiwuduotai.top/Article/details/gtfqicslwb.html

Ruby: arr.uniq
来源：http://dali.redwolf501.top/Article/details/gtbfxqyyvk.html

C#:   list.Distinct().ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtmdbreuib.html

[D16] 求和与平均值
来源：http://dali.aizwys.cn/Article/details/gthkkmpykq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtlxbdpsxm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guannengcc.top/Article/details/gtfxpdhuop.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gtghcxjgej.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtvxwggdrx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tanke756.top/Article/details/gtyouqoxmp.html

Go:   // 手写循环累加
来源：http://dali.daxiang520.top/Article/details/gtbjhkgjxx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cdnleiting.top/Article/details/gttrdvhevo.html

C#:   list.Sum();  list.Average()
来源：http://dali.jyoumei.cn/Article/details/gtnrzvtsia.html

[D17] 最大值与最小值
来源：http://dali.cdnleiting.top/Article/details/gtiipkndek.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjikivdss.html

PHP:  max($arr);  min($arr);
来源：http://dali.gogol.net.cn/Article/details/gtxeewowmj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zdqjudy.top/Article/details/gtqeecgokl.html

TS:   Math.max(...arr);
来源：http://dali.yueranfly.top/Article/details/gtvlnhsfis.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtuhewtblk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtrjgkflvw.html

Ruby: arr.max;  arr.min
来源：http://dali.gogol.net.cn/Article/details/gtthrvhgih.html

C#:   list.Max();  list.Min()
来源：http://dali.0kj1m.cn/Article/details/gtskllgtdg.html

[D18] 扁平化嵌套数组
来源：http://dali.jyoumei.cn/Article/details/gtylmytxoo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nwbrower.top/Article/details/gtkfjeveof.html

PHP:  array_merge(...$nested);
来源：http://dali.xylfe.cn/Article/details/gtogrvtjvu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyofisbyo.html

TS:   nested.flat();
来源：http://dali.sysykeji.top/Article/details/gtzznqvybe.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gogol.net.cn/Article/details/gtbknyqxfn.html

Go:   // 手写双层循环
来源：http://dali.bjfxy.top/Article/details/gteoghdbki.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gtpvqtnage.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtgjgtxchb.html

[D19] 按字段分组
来源：http://dali.svipenyu.cn/Article/details/gtdvwpyvnq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gotoacloud.top/Article/details/gtuhnsfhjy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.iojbl.cn/Article/details/gtstjcebxp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aizwys.cn/Article/details/gtyrydypob.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.c1oappe.top/Article/details/gtelnnruuh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cucudq.cn/Article/details/gtjjxgvqjb.html

Go:   // 手写 map[string][]T
来源：http://dali.sysykeji.top/Article/details/gthqwavquv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.bjfxy.top/Article/details/gtvihmzqpu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guowangkeji.top/Article/details/gtighzdyum.html

[D20] 统计每个元素出现次数
来源：http://dali.mhx1999.top/Article/details/gtozkmzibh.html

Py:   Counter(arr)
来源：http://dali.tian-w.cn/Article/details/gtunufhmst.html

PHP:  array_count_values($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqquepxu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuanzx.com/Article/details/gtdtvcmkdk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gtjfakmbse.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yueranfly.top/Article/details/gtkllsbunq.html

Go:   // 手写 map[T]int
来源：http://dali.gotoacloud.top/Article/details/gtkvwehxue.html

Ruby: arr.tally
来源：http://dali.vqdsnc.cn/Article/details/gtfyqzkach.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guannengcc.top/Article/details/gtyxdhzciq.html

[D21] 判断是否包含某元素
来源：http://dali.pengpengdd.cyou/Article/details/gtakgsiluc.html

Py:   x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhyatqir.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinqigfzy.top/Article/details/gthyukzxdt.html

JS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtukogfxig.html

TS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gtwnqjfhlu.html

Java: list.contains(x)
来源：http://dali.xziqi.cn/Article/details/gtuhvngfrp.html

Go:   slices.Contains(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtedggziun.html

Ruby: arr.include?(x)
来源：http://dali.jiagoushi.top/Article/details/gtncvbpwxy.html

C#:   list.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtlfldpioh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hfpthk.cn/Article/details/gtewwsuwhg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtaoazbtdb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangdashe.top/Article/details/gttstevzyn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtgbbdxome.html

TS:   [...arr];
来源：http://dali.quarkkingdee.top/Article/details/gtjvaettzq.html

Java: new ArrayList<>(list);
来源：http://dali.ydzc1.top/Article/details/gtmovfgskg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenlongwang.top/Article/details/gtgcvitexm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shuidangran.top/Article/details/gtdcpvpwcv.html

C#:   new List<int>(list);
来源：http://dali.yuxming.cn/Article/details/gtdkhwaifn.html

[D23] reduce 累积计算
来源：http://dali.316326.xyz/Article/details/gtlgmwcben.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gthkoavgxf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhixingplan.top/Article/details/gtfeurvphd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtpzmegjdw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdvpwyhw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigufen.top/Article/details/gthfbblpyl.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gtedkoieex.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shuidangran.top/Article/details/gtmevuvqfx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhengqikj.top/Article/details/gtrfuvahke.html

[D24] 字典 / Map 基本操作
来源：http://dali.aibaodan.cn/Article/details/gtyjmqvijp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gtpqogsoqf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zdqjudy.top/Article/details/gtoemylsea.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ivvv.top/Article/details/gtwvskywjt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtszvfqugy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuxming.cn/Article/details/gtjsrmxrjt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yvedp.cn/Article/details/gtscvxwegj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcvqazne.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmbxewjn.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgfzy.top/Article/details/gtojniavbv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fengsongda.top/Article/details/gtonfkdkyl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ehwqpu.com/Article/details/gtehrwklcl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigufen.top/Article/details/gtkycidvqq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.c1oappe.top/Article/details/gtdwbjywrn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.9152youxi.cn/Article/details/gttlfwjtqj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhixingplan.top/Article/details/gtdyxwupiw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqkoimcc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtalktybox.html

[D26] 数组转字符串
来源：http://dali.yongpay.top/Article/details/gtclbbhfsi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangdashe.top/Article/details/gthwewjtta.html

PHP:  implode(", ", $arr);
来源：http://dali.shzxlz.cn/Article/details/gtxtymwycn.html

JS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtwcwovtzm.html

TS:   arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gtvgymodgg.html

Java: String.join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gtigsceuby.html

Go:   strings.Join(strs, ", ")
来源：http://dali.bjfxy.top/Article/details/gtcdsysmat.html

Ruby: arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnnqybcg.html

C#:   string.Join(", ", list)
来源：http://dali.chenzaomai.com/Article/details/gtnkwgcsql.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtljumkxck.html

E. 字符串处理
来源：http://dali.jinqigfzy.top/Article/details/gtpeshdood.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gttfbegkfs.html

[E01] 拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtpjivjpkk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sysykeji.top/Article/details/gtkfkgxjfc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigfzy.top/Article/details/gtsxuuawzy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gtkellecyd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgfzy.top/Article/details/gtrjjhueuv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnxiangtu.top/Article/details/gthkbsqpqa.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuxming.cn/Article/details/gtbdgouqak.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj202588.top/Article/details/gtbsgvbswc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtgsokpzrm.html

[E02] 重复字符串
来源：http://dali.xinyue.icu/Article/details/gtqlkuzdno.html

Py:   "ab" * 3
来源：http://dali.birdmap.top/Article/details/gteyirddnj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.svipenyu.cn/Article/details/gtscztjdql.html

JS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtmmxmqllr.html

TS:   "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gtpivaggty.html

Java: "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gtsfbtguxj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgumpgwqw.html

Ruby: "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gtafhihhdu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fengsongda.top/Article/details/gtjtxicftj.html

[E03] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gtlsbxreos.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fzhhl.top/Article/details/gtpfksxxqj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtgenyzaty.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gttcrtakld.html

TS:   s.slice(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtvlgprlnt.html

Java: s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtentdolby.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gtmawqsgbw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xuetiantiany.cn/Article/details/gtxszsdweu.html

C#:   s.Substring(1, 3)
来源：http://dali.quarkkingdee.top/Article/details/gtotxdxcbz.html

[E04] 查找子串位置
来源：http://dali.yanxiufei.cn/Article/details/gtgzvzxequ.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtjyuqkmsu.html

PHP:  strpos($s, "x");
来源：http://dali.yanxiufei.cn/Article/details/gtcbahndri.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jlsjyb.cn/Article/details/gtjcuisosa.html

TS:   s.indexOf("x")
来源：http://dali.c1oappe.top/Article/details/gtsxonyzaw.html

Java: s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gtfdwiwwfi.html


<!-- 参考信息 -->