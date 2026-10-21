代发 wailian999

[C14] 泛型函数
来源：http://dali.quarkkingdee.top/Article/details/gtzyxwyxwh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.meibo888.top/Article/details/gtihnvolps.html

PHP:  // 无泛型
来源：http://dali.yuanzhike.top/Article/details/gtohizykoh.html

JS:   // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gtbffwovrj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtciqwuyti.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yangfankeji.com/Article/details/gtoqvecgff.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.9152youxi.cn/Article/details/gtupflgkqm.html

Ruby: # 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtazliqfru.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuetiantiany.cn/Article/details/gtvefjviqv.html

[C15] 解构 / 展开参数
来源：http://dali.yuanzhike.top/Article/details/gtvffnjyox.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yangfankeji.com/Article/details/gtyesrjyhq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.andypj.xyz/Article/details/gtduggjepw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.svipenyu.cn/Article/details/gtvavjhzjf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.smart0.xyz/Article/details/gtfibrhrnz.html

Java: // 无解构
来源：http://dali.zycfv.cn/Article/details/gtcguxfslj.html

Go:   // 无解构
来源：http://dali.jianghu66.top/Article/details/gtpruhgagl.html

Ruby: a, b = pair
来源：http://dali.ybcxt.top/Article/details/gtvndnwger.html

C#:   var (a, b) = pair;
来源：http://dali.yuxming.cn/Article/details/gtuftovkno.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gtnrezmzwg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.havefunace.top/Article/details/gtpbowgwkd.html

PHP:  // 无重载
来源：http://dali.shuidangran.top/Article/details/gtholsasic.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xziqi.cn/Article/details/gtvyyvvzut.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zdqjudy.top/Article/details/gtypdiddsf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.mhx1999.top/Article/details/gtkjbwtpcf.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmdnqhhq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sufxvd.cn/Article/details/gtahsysuhm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuiwojpub.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtmpcuspai.html

D. 数组 / 列表 / 集合
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnkbjokb.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtqkvdvtym.html

[D01] 创建数组 / 列表
来源：http://dali.kuanghao11.cn/Article/details/gtcafbhlzd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gogol.net.cn/Article/details/gtsrhzzwkm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258.top/Article/details/gtafkvbmbw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daxiang520.top/Article/details/gtyjxvwxga.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.0kj1m.cn/Article/details/gtnjyhzuaq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.snrcjt.cn/Article/details/gtdtdbxddw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yanxiufei.cn/Article/details/gtiuyhwzbc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zycfv.cn/Article/details/gtwhebfkvb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj202588.top/Article/details/gtmowiomiy.html

[D02] 追加元素到末尾
来源：http://dali.yonumen.top/Article/details/gtrttkphmj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ehwqpu.com/Article/details/gtbzzpgdtb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zycfv.cn/Article/details/gtpxkvuayt.html

JS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gtkvdggiqb.html

TS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gthpkfndge.html

Java: list.add(4);
来源：http://dali.zhongyouzk.top/Article/details/gtyyevwxns.html

Go:   arr = append(arr, 4)
来源：http://dali.daxiang520.top/Article/details/gtptpmxtzw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.wangdashe.top/Article/details/gthtotjkyv.html

C#:   list.Add(4);
来源：http://dali.aibaodan.cn/Article/details/gtnnlnsncg.html

[D03] 在指定位置插入元素
来源：http://dali.hnxiangtu.top/Article/details/gtbdzaohik.html

Py:   arr.insert(0, 0)
来源：http://dali.ivvv.top/Article/details/gtvgjpntpq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhongyouzk.top/Article/details/gtmwvfnlve.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gaohongyu789.top/Article/details/gtefdhptme.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tian-w.cn/Article/details/gtopqphcfy.html

Java: list.add(0, 0);
来源：http://dali.yonumen.top/Article/details/gtrwxocqrz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigufen.top/Article/details/gtwkowjbdt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxrezocg.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtjqoalpwe.html

[D04] 删除元素
来源：http://dali.zhixingplan.top/Article/details/gtcoucgvya.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jianghu66.top/Article/details/gtggirdjmm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.c1oappe.top/Article/details/gtitgjmdpv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fengsongda.top/Article/details/gtddqjybaz.html

TS:   arr.splice(0, 1);
来源：http://dali.yangfankeji.com/Article/details/gtpymwegkh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pycfn.com/Article/details/gtetqqdgsj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenzaomai.com/Article/details/gtfkwiiquv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj202588.top/Article/details/gtipfigigi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cdnleiting.top/Article/details/gtvkygpvrb.html

[D05] 访问与修改元素
来源：http://dali.jqgufenzy.top/Article/details/gtpqycrocr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gthskojkzm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gtevjgzsaj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gtzhzqmpfw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daria6918.cn/Article/details/gtdfaecaxy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangdashe.top/Article/details/gtqzmsedzb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gtgjgfjzot.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtvyyascra.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gthyogmxth.html

[D06] 数组长度
来源：http://dali.316326.xyz/Article/details/gtghngpmrb.html

Py:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gtsrrojqib.html

PHP:  count($arr);
来源：http://dali.iojbl.cn/Article/details/gtwwkuapzo.html

JS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gtloyogayx.html

TS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gtswkoxaod.html

Java: list.size();
来源：http://dali.yangfankeji.com/Article/details/gtymfucbxc.html

Go:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtzordhfdq.html

Ruby: arr.length; arr.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjlcmdez.html

C#:   list.Count;
来源：http://dali.aizwys.cn/Article/details/gtnpehsqrn.html

[D07] 切片 / 取子数组
来源：http://dali.tanke756.top/Article/details/gtfklluxfw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhixingplan.top/Article/details/gtgacneawb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dianchejie.cn/Article/details/gtsjjgyltm.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtvosaybur.html

TS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gtqbmdtmfp.html

Java: list.subList(1, 4);
来源：http://dali.meibo888.top/Article/details/gtxlsgqyhn.html

Go:   arr[1:4]
来源：http://dali.hnqzz.top/Article/details/gtvymosyvt.html

Ruby: arr[1, 3]
来源：http://dali.cheryme.top/Article/details/gtsovhhxmr.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenzaomai.com/Article/details/gtzsakwerl.html

[D08] 合并两个数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdudqeib.html

Py:   a + b;  a.extend(b)
来源：http://dali.shuidangran.top/Article/details/gthjdvhbkz.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttghlgwxq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj202588.top/Article/details/gtomzahdwj.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gtwhngmeqe.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtfsietjtv.html

Go:   append(a, b...)
来源：http://dali.yvedp.cn/Article/details/gtfnbwmisw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dianchejie.cn/Article/details/gthutbkjhs.html

C#:   a.Concat(b).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtwkaynjjw.html

[D09] 排序（升序）
来源：http://dali.cqqwz.cn/Article/details/gtmzkcvjuu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gtjzykrwpo.html

PHP:  sort($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqdktiag.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sxryk.cn/Article/details/gtqkcldpwo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenzaomai.com/Article/details/gtryskwdkg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gaohongyu789.top/Article/details/gtmfruylee.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfvytggi.html

Ruby: arr.sort
来源：http://dali.zycfv.cn/Article/details/gtlhqoyffw.html

C#:   list.Sort();
来源：http://dali.jlsjyb.cn/Article/details/gtnmlwiqun.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.andypj.xyz/Article/details/gtgettltsm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.c1oappe.top/Article/details/gtwlfmkxjm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuxming.cn/Article/details/gtkrripeox.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gtzvdgzcrm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gtpigkqiyh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aizwys.cn/Article/details/gthjszifkz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.birdmap.top/Article/details/gtfflnztsm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fzhhl.top/Article/details/gtcqsrabeb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenzaomai.com/Article/details/gthbdxveic.html

[D11] 反转数组
来源：http://dali.feifeiyinyue.top/Article/details/gtuqoojuek.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.havefunace.top/Article/details/gtdnkrfnuz.html

PHP:  array_reverse($arr);
来源：http://dali.shuidangran.top/Article/details/gtwnzfrwiu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aizwys.cn/Article/details/gtceccxnbg.html

TS:   [...arr].reverse();
来源：http://dali.guowangkeji.top/Article/details/gtskebynro.html

Java: Collections.reverse(list);
来源：http://dali.haohaochexian.top/Article/details/gtqdvxkljo.html

Go:   slices.Reverse(arr)
来源：http://dali.jiagoushi.top/Article/details/gtuftlmhnw.html

Ruby: arr.reverse
来源：http://dali.yvedp.cn/Article/details/gtyobvndgh.html

C#:   list.Reverse();
来源：http://dali.smart0.xyz/Article/details/gtpxffrojj.html

[D12] 查找元素下标
来源：http://dali.guowangkeji.top/Article/details/gthpnvbuen.html

Py:   arr.index(x);  x in arr
来源：http://dali.nwbrower.top/Article/details/gtaonrtral.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guowangkeji.top/Article/details/gtzdchxwlu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gtmablwhst.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.andypj.xyz/Article/details/gtsvnkrlpi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jiagoushi.top/Article/details/gtyttuvkyn.html

Go:   slices.Index(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtmphfiapj.html

Ruby: arr.index(x)
来源：http://dali.pycfn.com/Article/details/gtqvygplqn.html

C#:   list.IndexOf(x);
来源：http://dali.ybcxt.top/Article/details/gtgilaicus.html

[D13] 过滤（保留满足条件的）
来源：http://dali.smart0.xyz/Article/details/gtpoxrgmvl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.guannengcc.top/Article/details/gtefgjehrh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jqgufenzy.top/Article/details/gtmmhttefg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtbawyumps.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjvefewp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.meibo888.top/Article/details/gthreknlzd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yongpay.top/Article/details/gtwgjqvtns.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuxming.cn/Article/details/gtkogiagly.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtnkpzwhwz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hongshengwenyu.top/Article/details/gthtfohsly.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cucudq.cn/Article/details/gtqaexrsae.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nwbrower.top/Article/details/gtbxutrejw.html

JS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gtfrmzqmhl.html

TS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtwmkbowkd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gogol.net.cn/Article/details/gtjzjqkinn.html

Go:   // 手写循环
来源：http://dali.sysykeji.top/Article/details/gtcuqztztg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.andypj.xyz/Article/details/gtoihrwpzw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.redwolf501.top/Article/details/gtcauypbep.html

[D15] 去重
来源：http://dali.gzhubu.top/Article/details/gtstamktlb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtgvwpcvhj.html

PHP:  array_unique($arr);
来源：http://dali.shzxlz.cn/Article/details/gtalakllpb.html

JS:   [...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gtaitqvedm.html

TS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gtaatmuckx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xinyue.icu/Article/details/gtnizzyebl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yueranfly.top/Article/details/gtppmxhjrv.html

Ruby: arr.uniq
来源：http://dali.shzxlz.cn/Article/details/gtcdysowhy.html

C#:   list.Distinct().ToList()
来源：http://dali.yuxming.cn/Article/details/gtfwnsflzj.html

[D16] 求和与平均值
来源：http://dali.wangdashe.top/Article/details/gtnqrjtmyk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.316326.xyz/Article/details/gtwdcgcplp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.svipenyu.cn/Article/details/gtsfmwrtox.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtvakjoxlq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtfhmzjdoj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhoulong.xyz/Article/details/gtevtmapaf.html

Go:   // 手写循环累加
来源：http://dali.daria6918.cn/Article/details/gttwkvflux.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedxlctdx.html

C#:   list.Sum();  list.Average()
来源：http://dali.cheryme.top/Article/details/gtkyjicztb.html

[D17] 最大值与最小值
来源：http://dali.sweek.top/Article/details/gtcwovqcls.html

Py:   max(arr);  min(arr)
来源：http://dali.gotoacloud.top/Article/details/gtwwxetzth.html

PHP:  max($arr);  min($arr);
来源：http://dali.xziqi.cn/Article/details/gtwxovzmfb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.iojbl.cn/Article/details/gtemncqipd.html

TS:   Math.max(...arr);
来源：http://dali.yj20258.top/Article/details/gtewegkipi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shuidangran.top/Article/details/gtccshouck.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhixingplan.top/Article/details/gtgtcnkbxq.html

Ruby: arr.max;  arr.min
来源：http://dali.cashguo.top/Article/details/gtvlcqrdpp.html

C#:   list.Max();  list.Min()
来源：http://dali.xinyue.icu/Article/details/gtgugjsphk.html

[D18] 扁平化嵌套数组
来源：http://dali.birdmap.top/Article/details/gtbwgeaqvb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hfpthk.cn/Article/details/gtpbhepwjl.html

PHP:  array_merge(...$nested);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbqlcfyy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yangfankeji.com/Article/details/gtcppurdbn.html

TS:   nested.flat();
来源：http://dali.zhengqikj.top/Article/details/gtbrceptvi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yangfankeji.com/Article/details/gtggaiwdsu.html

Go:   // 手写双层循环
来源：http://dali.guannengcc.top/Article/details/gtyunhxkuc.html

Ruby: nested.flatten
来源：http://dali.aizwys.cn/Article/details/gtdlljgczt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gttdmijqks.html

[D19] 按字段分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwglehbs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sxryk.cn/Article/details/gtbbcbyjzk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yvedp.cn/Article/details/gtlibrbfgl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258888.top/Article/details/gtlsybpthr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gtwcpqmagk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.9152youxi.cn/Article/details/gtrrddjkfq.html

Go:   // 手写 map[string][]T
来源：http://dali.xuanzx.com/Article/details/gttsbeohem.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tianlin.xyz/Article/details/gtybefsnem.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.0kj1m.cn/Article/details/gtycmecfly.html

[D20] 统计每个元素出现次数
来源：http://dali.cqqwz.cn/Article/details/gtpszcpphl.html

Py:   Counter(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtiddpcqhf.html

PHP:  array_count_values($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtrtpmqkzm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gtkxyofdna.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmvylhhy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxinkj.top/Article/details/gtwhnonuhr.html

Go:   // 手写 map[T]int
来源：http://dali.fzhhl.top/Article/details/gtcqhbdjsi.html

Ruby: arr.tally
来源：http://dali.pengpengdd.cyou/Article/details/gtpfdksnpf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ppjwa.cn/Article/details/gtegqmmjab.html

[D21] 判断是否包含某元素
来源：http://dali.meibo888.top/Article/details/gtpcpxooob.html

Py:   x in arr
来源：http://dali.nwbrower.top/Article/details/gtntehuwxx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daxiang520.top/Article/details/gthjtsowhc.html

JS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gtczktujyz.html

TS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtbefprgbc.html

Java: list.contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslrnxaix.html

Go:   slices.Contains(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtgujqqkbk.html

Ruby: arr.include?(x)
来源：http://dali.nwbrower.top/Article/details/gtbiqohllz.html

C#:   list.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gtnxqswbny.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gzhubu.top/Article/details/gtbyibxiie.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gthcgtyofi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hammf.cn/Article/details/gtljpbixhv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtxcvqdfxw.html

TS:   [...arr];
来源：http://dali.aizwys.cn/Article/details/gtndzuzeqp.html

Java: new ArrayList<>(list);
来源：http://dali.daria6918.cn/Article/details/gtuxbaieel.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daxiang520.top/Article/details/gtmblfclfg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yueranfly.top/Article/details/gtqipckrfo.html

C#:   new List<int>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtehscqgwz.html

[D23] reduce 累积计算
来源：http://dali.smart0.xyz/Article/details/gtdystafta.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tianlin.xyz/Article/details/gtcspkxqsa.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtagrbyamc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtznseuiqv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gogol.net.cn/Article/details/gtlbeebdxi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cashguo.top/Article/details/gtbumnopyz.html

Go:   // 手写循环
来源：http://dali.hfpthk.cn/Article/details/gtmsbiuukp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shangyingyoupin.top/Article/details/gtwcaljelr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jianghu66.top/Article/details/gtjpkbkwcs.html

[D24] 字典 / Map 基本操作
来源：http://dali.nwbrower.top/Article/details/gtbcwnrkqs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenlongwang.top/Article/details/gtfhkykanx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtkzocklju.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtmqvjkoha.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtcaonuzet.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daria6918.cn/Article/details/gtvzdrcvgz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangdashe.top/Article/details/gtqovxhkjl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtjnwgspau.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sweek.top/Article/details/gtwqoyzvgt.html

[D25] Set 集合去重与交并差
来源：http://dali.gzhubu.top/Article/details/gtcaqzptoy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ivvv.top/Article/details/gtbpalytea.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.quarkkingdee.top/Article/details/gtxyudroch.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ybcxt.top/Article/details/gtakodawgr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.andypj.xyz/Article/details/gtiicqihyb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cqqwz.cn/Article/details/gtshatmnmo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuxming.cn/Article/details/gttpicwenw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtchppndct.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cucudq.cn/Article/details/gtsxcmlsvu.html

[D26] 数组转字符串
来源：http://dali.wangdashe.top/Article/details/gtawfxuapj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tian-w.cn/Article/details/gtpbgayahw.html

PHP:  implode(", ", $arr);
来源：http://dali.yongpay.top/Article/details/gtvcolaigo.html

JS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtueyafzbw.html

TS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtzduiibkh.html

Java: String.join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gtlalawicx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.smart0.xyz/Article/details/gtsfismway.html

Ruby: arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtxbpnqcsy.html

C#:   string.Join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gtuuytirkf.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtgmoundlp.html

E. 字符串处理
来源：http://dali.yuxming.cn/Article/details/gtyhfbrbpe.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtfdxvgpzn.html

[E01] 拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gttwvxpkzw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gzhubu.top/Article/details/gtgidxgkcy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nwbrower.top/Article/details/gtbefhfxgi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gtskutqkej.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gtzystyqid.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxuanxn.top/Article/details/gtarmhjqai.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtxkzjaykh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.havefunace.top/Article/details/gtgxinxgov.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.316326.xyz/Article/details/gtuepuwpiz.html

[E02] 重复字符串
来源：http://dali.jqgufenzy.top/Article/details/gtwawpfzua.html

Py:   "ab" * 3
来源：http://dali.guowangkeji.top/Article/details/gtarknpdux.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jianghu66.top/Article/details/gtyxfxmewd.html

JS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gteffzraae.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gtoyovqqyn.html

Java: "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gtkcmsuhyz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ehwqpu.com/Article/details/gtlgxkufrk.html

Ruby: "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gtikqnafao.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jianghu66.top/Article/details/gtddehmxgo.html

[E03] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gtgmdwafsl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenzaomai.com/Article/details/gtwhgnbqij.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtmipvddvi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtrpgwplwv.html

TS:   s.slice(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtzjiyelpg.html

Java: s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtkuuducpx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gtrbzroosq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xuetiantiany.cn/Article/details/gtesusomad.html

C#:   s.Substring(1, 3)
来源：http://dali.shuidangran.top/Article/details/gtfguxrsjx.html

[E04] 查找子串位置
来源：http://dali.jlsjyb.cn/Article/details/gttgenwoas.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tian-w.cn/Article/details/gttkmicnda.html

PHP:  strpos($s, "x");
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrcnavwn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yueranfly.top/Article/details/gttuannsnb.html

TS:   s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtfwrbqmxg.html

Java: s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtbqcboipf.html


<!-- 参考信息 -->