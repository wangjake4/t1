代发 wailian999

[C14] 泛型函数
来源：http://dali.yuxming.cn/Article/details/gtmbujlffi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.andypj.xyz/Article/details/gtwhvmcatf.html

PHP:  // 无泛型
来源：http://dali.chenlongwang.top/Article/details/gtqvkmcyic.html

JS:   // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtlhqzdctn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jlsjyb.cn/Article/details/gtfwedetof.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aibaodan.cn/Article/details/gtwwdblozd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hnqzz.top/Article/details/gtkxsrrneb.html

Ruby: # 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtspqestpt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.fzhhl.top/Article/details/gtlwbynxyh.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258.top/Article/details/gtircgqdkp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuetiantiany.cn/Article/details/gthtjgifad.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shuidangran.top/Article/details/gtbtwkzisg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxinkj.top/Article/details/gteonfwity.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.iojbl.cn/Article/details/gtiavoifrw.html

Java: // 无解构
来源：http://dali.jinqigufen.top/Article/details/gtoupolwhu.html

Go:   // 无解构
来源：http://dali.sufxvd.cn/Article/details/gtcrhpqmua.html

Ruby: a, b = pair
来源：http://dali.andypj.xyz/Article/details/gtjqlrhpbk.html

C#:   var (a, b) = pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gtttxalmbw.html

[C16] 函数 / 方法重载
来源：http://dali.jianghu66.top/Article/details/gtnjhxcydc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258.top/Article/details/gtbundmfxj.html

PHP:  // 无重载
来源：http://dali.sysykeji.top/Article/details/gtweqgengm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.smart0.xyz/Article/details/gtxyduzrkh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pengpengdd.cyou/Article/details/gtzatptkkv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.havefunace.top/Article/details/gtcxjjccaj.html

Go:   // 无重载：用不同函数名
来源：http://dali.yvedp.cn/Article/details/gtvnlvueqd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jlsjyb.cn/Article/details/gtkqlgnydd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cucudq.cn/Article/details/gthyoztgzd.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtoozihclg.html

D. 数组 / 列表 / 集合
来源：http://dali.hnxiangtu.top/Article/details/gtlagbnrve.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtucscmdgl.html

[D01] 创建数组 / 列表
来源：http://dali.zhengqikj.top/Article/details/gttzpvwwqa.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ybcxt.top/Article/details/gttmtxflmy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhengqikj.top/Article/details/gtigjotrze.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenlongwang.top/Article/details/gtlfxdgwyr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shuidangran.top/Article/details/gtbznnyivk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaloliimd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuanzhike.top/Article/details/gtsmmvhtru.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sysykeji.top/Article/details/gtickcpfaa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.bjfxy.top/Article/details/gtlmkmouok.html

[D02] 追加元素到末尾
来源：http://dali.andypj.xyz/Article/details/gtzwxssyqa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sweek.top/Article/details/gtfgeifqqa.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sxryk.cn/Article/details/gtchtkxsue.html

JS:   arr.push(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtvvokuetc.html

TS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtpdxidsax.html

Java: list.add(4);
来源：http://dali.yonumen.top/Article/details/gtcncvbfxt.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtilpjnfeq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.svipenyu.cn/Article/details/gtecoosazr.html

C#:   list.Add(4);
来源：http://dali.wangdashe.top/Article/details/gtfluyuufc.html

[D03] 在指定位置插入元素
来源：http://dali.aibaodan.cn/Article/details/gtcusgmqac.html

Py:   arr.insert(0, 0)
来源：http://dali.ybcxt.top/Article/details/gtkdupsprx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.vqdsnc.cn/Article/details/gtphezlltj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fzhhl.top/Article/details/gtndlqanha.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtonvuwafh.html

Java: list.add(0, 0);
来源：http://dali.tian-w.cn/Article/details/gtgokqoabf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hysaishi.cn/Article/details/gtxbblvtwy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yuanzhike.top/Article/details/gtqjobxmgb.html

C#:   list.Insert(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbruypps.html

[D04] 删除元素
来源：http://dali.bjfxy.top/Article/details/gtuvcvilvs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.mhx1999.top/Article/details/gtacesbnfb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.havefunace.top/Article/details/gtgdcyjfkz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shzxlz.cn/Article/details/gtmwaoisae.html

TS:   arr.splice(0, 1);
来源：http://dali.wangdashe.top/Article/details/gtvxgfhrqj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtddrddwjr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yueranfly.top/Article/details/gtciirmtpx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtuubyuhhu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnqzz.top/Article/details/gtnrtqmfzc.html

[D05] 访问与修改元素
来源：http://dali.zhongyouzk.top/Article/details/gttwvejhss.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtzfcfuuwx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtwwzyfynt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtekjsbtxo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xziqi.cn/Article/details/gtlvszqtji.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xylfe.cn/Article/details/gtpaqzsnfo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gthjnoqvpu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gttkgppgwi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cheryme.top/Article/details/gtifugemmg.html

[D06] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtukwknkva.html

Py:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gtmxpfoknp.html

PHP:  count($arr);
来源：http://dali.9152youxi.cn/Article/details/gtfdglnwem.html

JS:   arr.length
来源：http://dali.shzxlz.cn/Article/details/gtdugnlxas.html

TS:   arr.length
来源：http://dali.vqdsnc.cn/Article/details/gtrccphauq.html

Java: list.size();
来源：http://dali.aibaodan.cn/Article/details/gtyghgbfif.html

Go:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtmhqryeuw.html

Ruby: arr.length; arr.size
来源：http://dali.gaohongyu789.top/Article/details/gtvrzqsjzi.html

C#:   list.Count;
来源：http://dali.gogol.net.cn/Article/details/gtixfjhpjy.html

[D07] 切片 / 取子数组
来源：http://dali.smart0.xyz/Article/details/gtzxloofhz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jianghu66.top/Article/details/gtwzdmqhjc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvvobkjx.html

JS:   arr.slice(1, 4);
来源：http://dali.zycfv.cn/Article/details/gtlmypeoih.html

TS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gtyywpbxxg.html

Java: list.subList(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtlnypkvct.html

Go:   arr[1:4]
来源：http://dali.ydzc1.top/Article/details/gtvaxjkjig.html

Ruby: arr[1, 3]
来源：http://dali.yangfankeji.com/Article/details/gtopmaiwwx.html

C#:   list.GetRange(1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtsqspvnmo.html

[D08] 合并两个数组
来源：http://dali.ehwqpu.com/Article/details/gtvoqnhzzf.html

Py:   a + b;  a.extend(b)
来源：http://dali.sweek.top/Article/details/gtmdiattlx.html

PHP:  array_merge($a, $b);
来源：http://dali.hongshengwenyu.top/Article/details/gtfogpxugo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvytcidt.html

TS:   [...a, ...b];
来源：http://dali.yj20258888.top/Article/details/gtpjhclwky.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ehwqpu.com/Article/details/gtxcwwdqnu.html

Go:   append(a, b...)
来源：http://dali.xylfe.cn/Article/details/gtmdoexyhd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenlongwang.top/Article/details/gthavgxvcl.html

C#:   a.Concat(b).ToList()
来源：http://dali.shuidangran.top/Article/details/gtfbxfqqkj.html

[D09] 排序（升序）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjpzqzki.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gtsrjozbaf.html

PHP:  sort($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtsenqhtvv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgfzy.top/Article/details/gtaiyfgbix.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shuidangran.top/Article/details/gtfgbkvbgr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gzhubu.top/Article/details/gtbtmzhqsf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gtufsnpief.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyimvxln.html

C#:   list.Sort();
来源：http://dali.mhx1999.top/Article/details/gtcwwtnpex.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sufxvd.cn/Article/details/gtqfcsmzbi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqnxtanj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtihaikqkk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gtiuuxwzur.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gtldbiomvn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.feifeiyinyue.top/Article/details/gtexckbbxj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zycfv.cn/Article/details/gtttajkpjh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.9152youxi.cn/Article/details/gtrfjzhmoj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yuxming.cn/Article/details/gtzbvbvhsv.html

[D11] 反转数组
来源：http://dali.xinyue.icu/Article/details/gtlqqkmmld.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxyeoehrz.html

PHP:  array_reverse($arr);
来源：http://dali.zycfv.cn/Article/details/gtlqogbvhm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daxiang520.top/Article/details/gttnqtxmyx.html

TS:   [...arr].reverse();
来源：http://dali.hywenlv.cn/Article/details/gtixyijmrn.html

Java: Collections.reverse(list);
来源：http://dali.smart0.xyz/Article/details/gtsensqqqe.html

Go:   slices.Reverse(arr)
来源：http://dali.xylfe.cn/Article/details/gtvwulljes.html

Ruby: arr.reverse
来源：http://dali.fengsongda.top/Article/details/gtrpjuuhhi.html

C#:   list.Reverse();
来源：http://dali.jyoumei.cn/Article/details/gtycmpuklq.html

[D12] 查找元素下标
来源：http://dali.mhx1999.top/Article/details/gtqtqczgjr.html

Py:   arr.index(x);  x in arr
来源：http://dali.wangdashe.top/Article/details/gtpgbfzzaw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.0kj1m.cn/Article/details/gtyydfiigc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gtbkoqeead.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gtwkyzdlav.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangshuangyany.cn/Article/details/gtstnzigyf.html

Go:   slices.Index(arr, x)
来源：http://dali.cheryme.top/Article/details/gtstvvmnsg.html

Ruby: arr.index(x)
来源：http://dali.hnxiangtu.top/Article/details/gtwvzvyzwm.html

C#:   list.IndexOf(x);
来源：http://dali.xylfe.cn/Article/details/gtxjbdklqn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.mhx1999.top/Article/details/gtakpdjebe.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cdnleiting.top/Article/details/gthscogwsx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yueranfly.top/Article/details/gtphoykbax.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtbafremym.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gtflgizgyr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jqgfzy.top/Article/details/gtgtmdbmem.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigufen.top/Article/details/gthlecgffs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxuanxn.top/Article/details/gtwdowyvfx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtykgdzcoy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.bjfxy.top/Article/details/gtmycujkch.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenlongwang.top/Article/details/gtxtwncvjg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanpfqqyr.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqvbhoem.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gtjkxfdugn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zycfv.cn/Article/details/gtjxvzkzrq.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gtbzqepskk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtjospzlds.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtjvoonomh.html

[D15] 去重
来源：http://dali.haohaochexian.top/Article/details/gtbqlkyied.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gtejlkdihc.html

PHP:  array_unique($arr);
来源：http://dali.yj20258888.top/Article/details/gtrrjxsvek.html

JS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtgdwtvzfu.html

TS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gtksdywzsh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlalakfm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gogol.net.cn/Article/details/gtyjzvgcwm.html

Ruby: arr.uniq
来源：http://dali.zdqjudy.top/Article/details/gtvqjgjxux.html

C#:   list.Distinct().ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdltlbxbp.html

[D16] 求和与平均值
来源：http://dali.yuxming.cn/Article/details/gttrsaasgx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtysqrloqp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xuanzx.com/Article/details/gtbqqecxsg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gtvalzqkyg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtzixoeoti.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nwbrower.top/Article/details/gtzalrklrz.html

Go:   // 手写循环累加
来源：http://dali.yuanzhike.top/Article/details/gtdeuftpsm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sysykeji.top/Article/details/gtptcofelf.html

C#:   list.Sum();  list.Average()
来源：http://dali.gotoacloud.top/Article/details/gtntdugvxq.html

[D17] 最大值与最小值
来源：http://dali.gaohongyu789.top/Article/details/gtjcwsdarg.html

Py:   max(arr);  min(arr)
来源：http://dali.zycfv.cn/Article/details/gtilypruti.html

PHP:  max($arr);  min($arr);
来源：http://dali.xziqi.cn/Article/details/gtjycedoat.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daxiang520.top/Article/details/gtvetlypwo.html

TS:   Math.max(...arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmnsyjok.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xinyue.icu/Article/details/gtlhrkdmdk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.bjfxy.top/Article/details/gtjdnansub.html

Ruby: arr.max;  arr.min
来源：http://dali.birdmap.top/Article/details/gtyvjdvyzo.html

C#:   list.Max();  list.Min()
来源：http://dali.daxiang520.top/Article/details/gthevawkma.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtneylvsto.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yongpay.top/Article/details/gtrdvvgcwr.html

PHP:  array_merge(...$nested);
来源：http://dali.chenzaomai.com/Article/details/gttbegetlv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zdqjudy.top/Article/details/gtmbsrwwse.html

TS:   nested.flat();
来源：http://dali.cheryme.top/Article/details/gtzwwiqpyl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.smart0.xyz/Article/details/gtnmabankr.html

Go:   // 手写双层循环
来源：http://dali.zhoulong.xyz/Article/details/gtgqptfias.html

Ruby: nested.flatten
来源：http://dali.jianghu66.top/Article/details/gtsvupyfby.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nwbrower.top/Article/details/gtzopktran.html

[D19] 按字段分组
来源：http://dali.pycfn.com/Article/details/gtjywnribl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcipnhhtj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkcsesqe.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xinyue.icu/Article/details/gtatajenlo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gtzhleeufl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangshuangyany.cn/Article/details/gtyamaerhi.html

Go:   // 手写 map[string][]T
来源：http://dali.hysaishi.cn/Article/details/gtafjahnje.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cqqwz.cn/Article/details/gthbmqnupl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fengsongda.top/Article/details/gtqihlfdba.html

[D20] 统计每个元素出现次数
来源：http://dali.jlsjyb.cn/Article/details/gtievghgxc.html

Py:   Counter(arr)
来源：http://dali.aibaodan.cn/Article/details/gtsrzpsnyf.html

PHP:  array_count_values($arr);
来源：http://dali.andypj.xyz/Article/details/gtixsgpupm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gtnnhhddii.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gtujwadolh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fzhhl.top/Article/details/gtvzxtmvny.html

Go:   // 手写 map[T]int
来源：http://dali.tianlin.xyz/Article/details/gtxoianrqd.html

Ruby: arr.tally
来源：http://dali.jinqigfzy.top/Article/details/gtvwabxikd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sxryk.cn/Article/details/gtigveukua.html

[D21] 判断是否包含某元素
来源：http://dali.dianchejie.cn/Article/details/gtqmqcyuww.html

Py:   x in arr
来源：http://dali.zhixingplan.top/Article/details/gtitxigxmj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gotoacloud.top/Article/details/gtfyzmbdit.html

JS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtybfdrqai.html

TS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnuhooowc.html

Java: list.contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtgiowjqqc.html

Go:   slices.Contains(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtgydpucpk.html

Ruby: arr.include?(x)
来源：http://dali.cucudq.cn/Article/details/gtpzuqmtzb.html

C#:   list.Contains(x)
来源：http://dali.guannengcc.top/Article/details/gtyxbcbppc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yueranfly.top/Article/details/gtryxxfgrb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhengqikj.top/Article/details/gtxikjywyc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.9152youxi.cn/Article/details/gtcrywdhmc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shuidangran.top/Article/details/gthmsztkqx.html

TS:   [...arr];
来源：http://dali.316326.xyz/Article/details/gtfvnazjnh.html

Java: new ArrayList<>(list);
来源：http://dali.cashguo.top/Article/details/gtpjwqnudm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gtktrbtpbb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.havefunace.top/Article/details/gtftwmzioq.html

C#:   new List<int>(list);
来源：http://dali.daxiang520.top/Article/details/gtcgvsmfdt.html

[D23] reduce 累积计算
来源：http://dali.guowangkeji.top/Article/details/gtsupbfwai.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhengqikj.top/Article/details/gtwiomeoeo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxikcqyne.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndxtegya.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gtuedhgerj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhoulong.xyz/Article/details/gtfvsnjysy.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gtefdbiclh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinghuilouyu.cn/Article/details/gteuqmhpwe.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhxjbgfd.html

[D24] 字典 / Map 基本操作
来源：http://dali.andypj.xyz/Article/details/gtupzmqdmz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.smart0.xyz/Article/details/gtywjftpxa.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenlongwang.top/Article/details/gtvfqkvavy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258.top/Article/details/gtbnjtvodr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gthsoltvcc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhoulong.xyz/Article/details/gtzldttpkq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.birdmap.top/Article/details/gtnzzgbwvx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.mhx1999.top/Article/details/gtdkroshio.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tianlin.xyz/Article/details/gtoylyqplg.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gtczdtwxbc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ydzc1.top/Article/details/gtduvvfvql.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xinyue.icu/Article/details/gtxbwetcsf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.pycfn.com/Article/details/gtcecvygmr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pengpengdd.cyou/Article/details/gtxgiceeyg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtduwvirax.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinghuilouyu.cn/Article/details/gtsofmmfwo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenlongwang.top/Article/details/gtfsgytmbj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258888.top/Article/details/gtsvysdtwo.html

[D26] 数组转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtormpbqxc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.smart0.xyz/Article/details/gtmlisxscg.html

PHP:  implode(", ", $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtsmzqeune.html

JS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtjqkcxkap.html

TS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gttulszgon.html

Java: String.join(", ", list)
来源：http://dali.tanke756.top/Article/details/gtftjflfhw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jyoumei.cn/Article/details/gtkkzmfrep.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtfgsppbhj.html

C#:   string.Join(", ", list)
来源：http://dali.wangshuangyany.cn/Article/details/gtynvzihvf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtlobsqmvg.html

E. 字符串处理
来源：http://dali.kuanghao11.cn/Article/details/gtedaocxxi.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtorrrzzsn.html

[E01] 拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtjcwcsrmo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hysaishi.cn/Article/details/gtglkjbkmm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenlongwang.top/Article/details/gttmqclbam.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ybcxt.top/Article/details/gtfugdoync.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzctvantg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfhgomob.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhixingplan.top/Article/details/gtmriebubg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shzxlz.cn/Article/details/gtidlkuljc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtgfspdqnc.html

[E02] 重复字符串
来源：http://dali.cdnleiting.top/Article/details/gtzamejkxq.html

Py:   "ab" * 3
来源：http://dali.aibaodan.cn/Article/details/gtsotrbcmf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.daria6918.cn/Article/details/gtpspaocja.html

JS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtjvnwbwfg.html

TS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtesntvepn.html

Java: "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtglctthcz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dashuyun.cn/Article/details/gtxejubdpr.html

Ruby: "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gtxljenmgn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcjssmrq.html

[E03] 截取子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbqfphhb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zdqjudy.top/Article/details/gtskjazwoy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtvexcuetb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gtoqwxzyge.html

TS:   s.slice(1, 4)
来源：http://dali.pycfn.com/Article/details/gteypndvly.html

Java: s.substring(1, 4)
来源：http://dali.yonumen.top/Article/details/gtwofuzzgw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zycfv.cn/Article/details/gtveeklkgx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pycfn.com/Article/details/gthrxtzmgu.html

C#:   s.Substring(1, 3)
来源：http://dali.xuanzx.com/Article/details/gtpegeldof.html

[E04] 查找子串位置
来源：http://dali.ydzc1.top/Article/details/gtjsxvrlgd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hnqzz.top/Article/details/gtfeobstda.html

PHP:  strpos($s, "x");
来源：http://dali.jqgufenzy.top/Article/details/gtneshjquz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxinkj.top/Article/details/gtdrzdmzzr.html

TS:   s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gterqhnaim.html

Java: s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtyrmhirlm.html


<!-- 参考信息 -->