代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclrucdja.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xinyue.icu/Article/details/gtvorjwwtr.html

Java: // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gtnskskdzj.html

Go:   // 无解构
来源：http://dali.xylfe.cn/Article/details/gtriubujnr.html

Ruby: a, b = pair
来源：http://dali.zhoulong.xyz/Article/details/gthnnianve.html

C#:   var (a, b) = pair;
来源：http://dali.yonumen.top/Article/details/gtgeiylhjs.html

[C16] 函数 / 方法重载
来源：http://dali.9152youxi.cn/Article/details/gtgtvdudju.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sweek.top/Article/details/gtnfihbybt.html

PHP:  // 无重载
来源：http://dali.jlsjyb.cn/Article/details/gtcodisvgc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hfpthk.cn/Article/details/gtktwcseae.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gzhubu.top/Article/details/gtovircutl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnxiangtu.top/Article/details/gtkwaxhjth.html

Go:   // 无重载：用不同函数名
来源：http://dali.yuxming.cn/Article/details/gtrnzkcxau.html

Ruby: # 无重载：靠动态参数
来源：http://dali.0kj1m.cn/Article/details/gtofcmjqxb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cdnleiting.top/Article/details/gtznfsqtbe.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtqpqodkwx.html

D. 数组 / 列表 / 集合
来源：http://dali.yangfankeji.com/Article/details/gtqyeghnpp.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtnsoqyrqs.html

[D01] 创建数组 / 列表
来源：http://dali.yonumen.top/Article/details/gtguhszjbv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258.top/Article/details/gtjtsylbko.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hnqzz.top/Article/details/gtesayqkue.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gtqleedyxy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ehwqpu.com/Article/details/gtpghlinve.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jianghu66.top/Article/details/gtywcbicic.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhengqikj.top/Article/details/gtihmozxin.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cheryme.top/Article/details/gtltxzuytc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenzaomai.com/Article/details/gtfcydybcr.html

[D02] 追加元素到末尾
来源：http://dali.pycfn.com/Article/details/gtsirrqjly.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenlongwang.top/Article/details/gtmahxrufm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.havefunace.top/Article/details/gtlyinfnfu.html

JS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gtuaqbwaoq.html

TS:   arr.push(4);
来源：http://dali.jyoumei.cn/Article/details/gtpwbtbnex.html

Java: list.add(4);
来源：http://dali.ybcxt.top/Article/details/gtwvgqylmy.html

Go:   arr = append(arr, 4)
来源：http://dali.cheryme.top/Article/details/gtxhdahavd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yvedp.cn/Article/details/gtjtsgbdzf.html

C#:   list.Add(4);
来源：http://dali.9152youxi.cn/Article/details/gtrzewogzd.html

[D03] 在指定位置插入元素
来源：http://dali.ydzc1.top/Article/details/gtukhbkijn.html

Py:   arr.insert(0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtxbbcrytm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pycfn.com/Article/details/gtnoqufuod.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.havefunace.top/Article/details/gtqrwzncoj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.aibaodan.cn/Article/details/gtgltkdfey.html

Java: list.add(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtgewwqfyo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dianchejie.cn/Article/details/gtgjtywsxo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.haohaochexian.top/Article/details/gttegivbvc.html

C#:   list.Insert(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtscvgafdj.html

[D04] 删除元素
来源：http://dali.jinqigufen.top/Article/details/gtocpmofmz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.havefunace.top/Article/details/gtweopcsxv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtytaxkzcy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj202588.top/Article/details/gtdkezjrah.html

TS:   arr.splice(0, 1);
来源：http://dali.zhoulong.xyz/Article/details/gtthbphtzo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yongpay.top/Article/details/gtptinukpv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hammf.cn/Article/details/gtbeljvguo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hysaishi.cn/Article/details/gtankcoqtn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xinyue.icu/Article/details/gtzotozosh.html

[D05] 访问与修改元素
来源：http://dali.nwbrower.top/Article/details/gtvqnesxfk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtmsnlfsfr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtxyvfbvzx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtgiddmyed.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hongshengwenyu.top/Article/details/gtdourvswr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258888.top/Article/details/gtpwylxytj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtxezoeziv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gtfkvvaynm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtgonncimw.html

[D06] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gtpcejgasd.html

Py:   len(arr)
来源：http://dali.tanke756.top/Article/details/gtrcfayxxe.html

PHP:  count($arr);
来源：http://dali.hfpthk.cn/Article/details/gtpwakindm.html

JS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gtmpoazcgw.html

TS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gtjothyarn.html

Java: list.size();
来源：http://dali.jiagoushi.top/Article/details/gtkuhbqmhb.html

Go:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtmpmcyuyi.html

Ruby: arr.length; arr.size
来源：http://dali.tanke756.top/Article/details/gtzkiqzmhf.html

C#:   list.Count;
来源：http://dali.birdmap.top/Article/details/gteugmpvnr.html

[D07] 切片 / 取子数组
来源：http://dali.gaohongyu789.top/Article/details/gtufjwskfk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.c1oappe.top/Article/details/gtzkwpwksy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuxming.cn/Article/details/gtgowzikmi.html

JS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gtdwjgugcb.html

TS:   arr.slice(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtfuwkmzgg.html

Java: list.subList(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtdvjqzmws.html

Go:   arr[1:4]
来源：http://dali.cashguo.top/Article/details/gtdpkzlmzk.html

Ruby: arr[1, 3]
来源：http://dali.zhoulong.xyz/Article/details/gtacjixbxa.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtzrsyzwdi.html

[D08] 合并两个数组
来源：http://dali.zhixingplan.top/Article/details/gtgsamppzf.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlovhdmrq.html

PHP:  array_merge($a, $b);
来源：http://dali.tian-w.cn/Article/details/gtfdeaeyys.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuetiantiany.cn/Article/details/gtmgtkmxbh.html

TS:   [...a, ...b];
来源：http://dali.yj20258888.top/Article/details/gtpndxlgkc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.birdmap.top/Article/details/gtlhhbrmvy.html

Go:   append(a, b...)
来源：http://dali.ivvv.top/Article/details/gtrmmjbdog.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gzhubu.top/Article/details/gtxsevanls.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtfblgofjz.html

[D09] 排序（升序）
来源：http://dali.smart0.xyz/Article/details/gtweattthm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtiajehtmw.html

PHP:  sort($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtuurzrecv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.quarkkingdee.top/Article/details/gtxsejsuct.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.haohaochexian.top/Article/details/gtirhhjeoj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgfzy.top/Article/details/gtkhexevdh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gtklcjoxyj.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gtjehbfcia.html

C#:   list.Sort();
来源：http://dali.hnqzz.top/Article/details/gtflynmvic.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.guowangkeji.top/Article/details/gtbbumizuz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtluegykfo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.c1oappe.top/Article/details/gtjiwrejky.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gtweattyrx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gtmepjigru.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.mhx1999.top/Article/details/gtrlmqyosf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yanxiufei.cn/Article/details/gtfhmorvhf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.kuanghao11.cn/Article/details/gtygurcxya.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.vqdsnc.cn/Article/details/gtyfdnbqvs.html

[D11] 反转数组
来源：http://dali.yanxiufei.cn/Article/details/gtvyxggdkw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gtbbqbwtiw.html

PHP:  array_reverse($arr);
来源：http://dali.chenzaomai.com/Article/details/gteetzuvlc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daria6918.cn/Article/details/gtyxiyfikt.html

TS:   [...arr].reverse();
来源：http://dali.jqgufenzy.top/Article/details/gtmrdklpmj.html

Java: Collections.reverse(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzklklxxm.html

Go:   slices.Reverse(arr)
来源：http://dali.jiagoushi.top/Article/details/gtxhfzftdm.html

Ruby: arr.reverse
来源：http://dali.aibaodan.cn/Article/details/gtbxsvcgzt.html

C#:   list.Reverse();
来源：http://dali.daxiang520.top/Article/details/gtpxqrfiis.html

[D12] 查找元素下标
来源：http://dali.tanke756.top/Article/details/gterarisyo.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuanzx.com/Article/details/gtcaqikvvl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtxsjmkybu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.mhx1999.top/Article/details/gtewgktrzv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gtlqsclktm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.kuanghao11.cn/Article/details/gtauxkaqgr.html

Go:   slices.Index(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtqsznihpl.html

Ruby: arr.index(x)
来源：http://dali.shzxlz.cn/Article/details/gtupgjzjrg.html

C#:   list.IndexOf(x);
来源：http://dali.pycfn.com/Article/details/gtqhyefgmu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cheryme.top/Article/details/gteknkitsp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tianlin.xyz/Article/details/gtjorvhsog.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yonumen.top/Article/details/gtkicvlxgd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gttdoxkaxc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtiyrnxzmr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hysaishi.cn/Article/details/gtrkhsbfpy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tanke756.top/Article/details/gtfmxaofyk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cashguo.top/Article/details/gtojtktmse.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtemygowvy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hywenlv.cn/Article/details/gtfaftmztp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sufxvd.cn/Article/details/gtqpbdxpnc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tianlin.xyz/Article/details/gtzmuynycp.html

JS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gthcbxtqys.html

TS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gtyowrfffa.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ivvv.top/Article/details/gtfogxkoas.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gtdqpxhiey.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtexldqggb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtifyxsvdc.html

[D15] 去重
来源：http://dali.dianchejie.cn/Article/details/gtqlkxwude.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gtontmwsgf.html

PHP:  array_unique($arr);
来源：http://dali.yj20258888.top/Article/details/gtdrerswfa.html

JS:   [...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gtyvsbirqr.html

TS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtofheibtk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.svipenyu.cn/Article/details/gtdbjyldax.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.meibo888.top/Article/details/gtzfwmjzjw.html

Ruby: arr.uniq
来源：http://dali.havefunace.top/Article/details/gteisdxahx.html

C#:   list.Distinct().ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtygxcidiz.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gtiobmsgmm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtckjqpbys.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.havefunace.top/Article/details/gtclbqnpyx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gtxwfipgdp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gttvwvyyox.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guannengcc.top/Article/details/gtgtazdovy.html

Go:   // 手写循环累加
来源：http://dali.cheryme.top/Article/details/gtfbznwnny.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hywenlv.cn/Article/details/gtwtobwzli.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258.top/Article/details/gtjypvuxhd.html

[D17] 最大值与最小值
来源：http://dali.ydzc1.top/Article/details/gtbfdrefvc.html

Py:   max(arr);  min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtngdrbtrq.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuanzhike.top/Article/details/gtowxjivjl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jianghu66.top/Article/details/gtkwqaxuzl.html

TS:   Math.max(...arr);
来源：http://dali.jlsjyb.cn/Article/details/gtzdnithaq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shzxlz.cn/Article/details/gtdiunzdtt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shuidangran.top/Article/details/gtmzpqqelv.html

Ruby: arr.max;  arr.min
来源：http://dali.yvedp.cn/Article/details/gtsljtnysf.html

C#:   list.Max();  list.Min()
来源：http://dali.aizwys.cn/Article/details/gtzikvunjr.html

[D18] 扁平化嵌套数组
来源：http://dali.chenlongwang.top/Article/details/gtbdzzhmly.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guannengcc.top/Article/details/gtrdhrbeuh.html

PHP:  array_merge(...$nested);
来源：http://dali.hnqzz.top/Article/details/gtpnuogqte.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nwbrower.top/Article/details/gtrfkccaht.html

TS:   nested.flat();
来源：http://dali.vqdsnc.cn/Article/details/gtapkxkncd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xuanzx.com/Article/details/gtzghdskyy.html

Go:   // 手写双层循环
来源：http://dali.wangdashe.top/Article/details/gtadrbylfu.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gtmxprvgzh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtkqoxrogq.html

[D19] 按字段分组
来源：http://dali.meibo888.top/Article/details/gtcboulnds.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dianchejie.cn/Article/details/gtrybadpfo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zdqjudy.top/Article/details/gtbdejcelr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhongyouzk.top/Article/details/gtqvhrvfzr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.quarkkingdee.top/Article/details/gtsjcgfgny.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xinyue.icu/Article/details/gtoxlzlsbr.html

Go:   // 手写 map[string][]T
来源：http://dali.wangdashe.top/Article/details/gtnmctqksj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yueranfly.top/Article/details/gtqkibvxdt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jianghu66.top/Article/details/gtlhcszygn.html

[D20] 统计每个元素出现次数
来源：http://dali.gogol.net.cn/Article/details/gtidwyukoi.html

Py:   Counter(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtsbprypdf.html

PHP:  array_count_values($arr);
来源：http://dali.mhx1999.top/Article/details/gtwdvsybky.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gtyckgkcmy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gtsmexmpkh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sysykeji.top/Article/details/gttzeesomj.html

Go:   // 手写 map[T]int
来源：http://dali.hywenlv.cn/Article/details/gteagzfger.html

Ruby: arr.tally
来源：http://dali.xziqi.cn/Article/details/gtrjionsip.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dashuyun.cn/Article/details/gtdsnqjegu.html

[D21] 判断是否包含某元素
来源：http://dali.shzxlz.cn/Article/details/gtnlqzenlq.html

Py:   x in arr
来源：http://dali.quarkkingdee.top/Article/details/gtlmtqacbc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.iojbl.cn/Article/details/gtlvbhyizb.html

JS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtmrddvagb.html

TS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvlbmibx.html

Java: list.contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gteposjpfe.html

Go:   slices.Contains(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtuagwlyjw.html

Ruby: arr.include?(x)
来源：http://dali.yj202588.top/Article/details/gtryyvtthq.html

C#:   list.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gtupxjjsjh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aibaodan.cn/Article/details/gtqevuavvy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dianchejie.cn/Article/details/gtpuvrrobk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cheryme.top/Article/details/gtrqbjgrsl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.0kj1m.cn/Article/details/gtoiuvhnwi.html

TS:   [...arr];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsgoipax.html

Java: new ArrayList<>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtpngrxjnx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangshuangyany.cn/Article/details/gtuigzqixd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hfpthk.cn/Article/details/gtgotyjjro.html

C#:   new List<int>(list);
来源：http://dali.zdqjudy.top/Article/details/gtzsfucdur.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gtdzynnqmb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtgmudchvr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxinkj.top/Article/details/gtlxcsgvhi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtdzvqkmej.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gtjnlybjlg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.iojbl.cn/Article/details/gtgvrxqbfi.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gtiosonxtr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.c1oappe.top/Article/details/gthzbmaedc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hnxiangtu.top/Article/details/gtxzuwqzkc.html

[D24] 字典 / Map 基本操作
来源：http://dali.cashguo.top/Article/details/gtocourbtf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hfpthk.cn/Article/details/gtlurlrlvo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.guannengcc.top/Article/details/gtiqtqohjp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ehwqpu.com/Article/details/gtwurmpdmq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cheryme.top/Article/details/gtshqblqnn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnqzz.top/Article/details/gtnwzjmzda.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxinkj.top/Article/details/gtbkmbekck.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tianlin.xyz/Article/details/gtdktrjcrf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aibaodan.cn/Article/details/gtyxmhuxrc.html

[D25] Set 集合去重与交并差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsmgipvj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.daria6918.cn/Article/details/gtokgdmxat.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hfpthk.cn/Article/details/gtxvvrzusj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulklzunn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gzhubu.top/Article/details/gtzeubgmyv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgcoysqs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tian-w.cn/Article/details/gtynbxtkkv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhixingplan.top/Article/details/gthyrxdjjb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdicdxbow.html

[D26] 数组转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnwxazsu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgfzy.top/Article/details/gtjkjjlakn.html

PHP:  implode(", ", $arr);
来源：http://dali.cheryme.top/Article/details/gtyxksjjnn.html

JS:   arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gtxizkjwro.html

TS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gtebqhkgaz.html

Java: String.join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gtcfscfifa.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojauczlx.html

Ruby: arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gtutlsjepq.html

C#:   string.Join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtixjvmpoo.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtrulplbkr.html

E. 字符串处理
来源：http://dali.jianghu66.top/Article/details/gtceakfprq.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtlxaaufgh.html

[E01] 拼接字符串
来源：http://dali.daxiang520.top/Article/details/gtaohrcbik.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cqqwz.cn/Article/details/gtugpabuna.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxinkj.top/Article/details/gtlldwexnu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtyfmkhozl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gtznlbhcio.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.meibo888.top/Article/details/gtcznwqlfx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgufenzy.top/Article/details/gtjipzbvdh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nanxuanxn.top/Article/details/gtesmnbogi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtvcwozyum.html

[E02] 重复字符串
来源：http://dali.hysaishi.cn/Article/details/gtkthbidhp.html

Py:   "ab" * 3
来源：http://dali.cdnleiting.top/Article/details/gttvdkunyj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.pycfn.com/Article/details/gtyppglazi.html

JS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gthgjjrrjn.html

TS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtbeuedxhz.html

Java: "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtreptgsto.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nanxinkj.top/Article/details/gtgyxqjocs.html

Ruby: "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gtswtckwix.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.meibo888.top/Article/details/gtgkwmuxnd.html

[E03] 截取子串
来源：http://dali.tian-w.cn/Article/details/gtguhagqhi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dashuyun.cn/Article/details/gtzxfznord.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtocufkysw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtmbwtofvd.html

TS:   s.slice(1, 4)
来源：http://dali.316326.xyz/Article/details/gtksormkem.html

Java: s.substring(1, 4)
来源：http://dali.redwolf501.top/Article/details/gtqhlfzitg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gtrbkvzmvf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ydzc1.top/Article/details/gtbytsliow.html

C#:   s.Substring(1, 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndxvfwpu.html

[E04] 查找子串位置
来源：http://dali.tanke756.top/Article/details/gtxmuvotie.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gttejlmdkf.html

PHP:  strpos($s, "x");
来源：http://dali.iojbl.cn/Article/details/gtqkvmzvfd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gotoacloud.top/Article/details/gtieifsumb.html

TS:   s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gtdwmkmvzl.html

Java: s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtbgmodaxd.html

Go:   strings.Index(s, "x")
来源：http://dali.mhx1999.top/Article/details/gtjmcykwto.html

Ruby: s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gtyqazmsjq.html

C#:   s.IndexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtgwvgaebe.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnxiangtu.top/Article/details/gtkpztgexr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pycfn.com/Article/details/gtbwsridbd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.redwolf501.top/Article/details/gtvdlhjdbc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gtvwltvhkj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtrnvymmne.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gtovuiqotv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.aibaodan.cn/Article/details/gtddnxwgkb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hywenlv.cn/Article/details/gtlbbvofng.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yvedp.cn/Article/details/gthxgrkmrd.html


<!-- 参考信息 -->