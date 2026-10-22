代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gtntiqhnjj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yangfankeji.com/Article/details/gtapxbivld.html

Java: // 无解构
来源：http://dali.hfpthk.cn/Article/details/gtdnufcjro.html

Go:   // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqezrkor.html

Ruby: a, b = pair
来源：http://dali.ybcxt.top/Article/details/gtliaexcjh.html

C#:   var (a, b) = pair;
来源：http://dali.xuanzx.com/Article/details/gtvmoejcjs.html

[C16] 函数 / 方法重载
来源：http://dali.andypj.xyz/Article/details/gtsbqwnhux.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gotoacloud.top/Article/details/gteycskkjk.html

PHP:  // 无重载
来源：http://dali.vqdsnc.cn/Article/details/gtbzwzlrki.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.mhx1999.top/Article/details/gtkcyrpvpg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cucudq.cn/Article/details/gtnieaiopb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tian-w.cn/Article/details/gtnyjaekvq.html

Go:   // 无重载：用不同函数名
来源：http://dali.cashguo.top/Article/details/gtiajtcxgf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.andypj.xyz/Article/details/gtwhqjrxhw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.redwolf501.top/Article/details/gtnoepxarl.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtqmjuvxfm.html

D. 数组 / 列表 / 集合
来源：http://dali.ivvv.top/Article/details/gtabodtxqh.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxvajdegg.html

[D01] 创建数组 / 列表
来源：http://dali.cqqwz.cn/Article/details/gtbjfwmjcv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sysykeji.top/Article/details/gtqjcjqpqp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgippvgk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hysaishi.cn/Article/details/gttkisrijx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cdnleiting.top/Article/details/gtasovjpvb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.havefunace.top/Article/details/gtsyfbsebq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jiagoushi.top/Article/details/gttiocrfbu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.9152youxi.cn/Article/details/gtyitvoivf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.smart0.xyz/Article/details/gtklhbarof.html

[D02] 追加元素到末尾
来源：http://dali.hnqzz.top/Article/details/gtsawkrykk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbmgqicn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ybcxt.top/Article/details/gtrqhujctm.html

JS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gtvizujapw.html

TS:   arr.push(4);
来源：http://dali.guannengcc.top/Article/details/gttaofznhz.html

Java: list.add(4);
来源：http://dali.jqgfzy.top/Article/details/gthskhgicm.html

Go:   arr = append(arr, 4)
来源：http://dali.wangdashe.top/Article/details/gtpkpusecx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hysaishi.cn/Article/details/gtjqfpwpef.html

C#:   list.Add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtcwuotzhg.html

[D03] 在指定位置插入元素
来源：http://dali.cheryme.top/Article/details/gtstfzpfmt.html

Py:   arr.insert(0, 0)
来源：http://dali.birdmap.top/Article/details/gtbchpuvvm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.meibo888.top/Article/details/gtxocqpejs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ehwqpu.com/Article/details/gtntorhsye.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sysykeji.top/Article/details/gtgalgpaer.html

Java: list.add(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gtsyssejtn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jyoumei.cn/Article/details/gtipawpwpv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhengqikj.top/Article/details/gtwyczosrx.html

C#:   list.Insert(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gtybfrbxek.html

[D04] 删除元素
来源：http://dali.sxryk.cn/Article/details/gtbyiiwmjz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tanke756.top/Article/details/gtqkewklpm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tian-w.cn/Article/details/gtsoeoneka.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guowangkeji.top/Article/details/gtklvvjzqh.html

TS:   arr.splice(0, 1);
来源：http://dali.gzhubu.top/Article/details/gtcxmhvmeb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pycfn.com/Article/details/gtltjzbmau.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkowqffme.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cheryme.top/Article/details/gtonhdnkhj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.svipenyu.cn/Article/details/gtecdilmpo.html

[D05] 访问与修改元素
来源：http://dali.tian-w.cn/Article/details/gtesljcxbl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtswxeudbc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gtnzowqrme.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gtjjtxyusv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.svipenyu.cn/Article/details/gtrxggltxz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.andypj.xyz/Article/details/gtpwszzxyl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtgsdyxcor.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gturbnivld.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtwhhonkkz.html

[D06] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gtpzmroczq.html

Py:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtxtiqiewm.html

PHP:  count($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtdqccrdzq.html

JS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gturwhkasq.html

TS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtygxahnwj.html

Java: list.size();
来源：http://dali.hfpthk.cn/Article/details/gtjnqldmvg.html

Go:   len(arr)
来源：http://dali.havefunace.top/Article/details/gtvhodsuhe.html

Ruby: arr.length; arr.size
来源：http://dali.aibaodan.cn/Article/details/gtevzybzsn.html

C#:   list.Count;
来源：http://dali.wangshuangyany.cn/Article/details/gtklmtplqr.html

[D07] 切片 / 取子数组
来源：http://dali.jqgfzy.top/Article/details/gteadwagqt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258.top/Article/details/gtvmvwombn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.redwolf501.top/Article/details/gtwixaevpz.html

JS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtqwwnjweo.html

TS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gttvlakzir.html

Java: list.subList(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gthpdqywjc.html

Go:   arr[1:4]
来源：http://dali.9152youxi.cn/Article/details/gtpxadptes.html

Ruby: arr[1, 3]
来源：http://dali.zhengqikj.top/Article/details/gtgnshgjdz.html

C#:   list.GetRange(1, 3);
来源：http://dali.zdqjudy.top/Article/details/gtsfqloozb.html

[D08] 合并两个数组
来源：http://dali.0kj1m.cn/Article/details/gtmffbhout.html

Py:   a + b;  a.extend(b)
来源：http://dali.ybcxt.top/Article/details/gtnofexpdh.html

PHP:  array_merge($a, $b);
来源：http://dali.hnqzz.top/Article/details/gtkvdnnhkh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zdqjudy.top/Article/details/gtmvrnqsxh.html

TS:   [...a, ...b];
来源：http://dali.yangfankeji.com/Article/details/gtbngaeaes.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ydzc1.top/Article/details/gtzmaunoco.html

Go:   append(a, b...)
来源：http://dali.316326.xyz/Article/details/gtceeegync.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zycfv.cn/Article/details/gtlzjcwdss.html

C#:   a.Concat(b).ToList()
来源：http://dali.daria6918.cn/Article/details/gtgydhbaqf.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmzqhpwv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gtjyiymdav.html

PHP:  sort($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtqiphpzxu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.9152youxi.cn/Article/details/gtakynesdj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shuidangran.top/Article/details/gtiqqxdqft.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hfpthk.cn/Article/details/gtuegsyhzz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gtmniduqui.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gtejjiqfso.html

C#:   list.Sort();
来源：http://dali.gzhubu.top/Article/details/gtwffubwmf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sysykeji.top/Article/details/gtbbehqxyk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gotoacloud.top/Article/details/gtyuqnyucr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.mhx1999.top/Article/details/gtzmzlbyfe.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtxwdrkzmh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gttycgwwlz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.316326.xyz/Article/details/gtlmhzzknf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tian-w.cn/Article/details/gtsillnfsx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dashuyun.cn/Article/details/gtebmggsdz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.havefunace.top/Article/details/gtltcucinj.html

[D11] 反转数组
来源：http://dali.sxryk.cn/Article/details/gtksmnajns.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nanxuanxn.top/Article/details/gtrlsmhjpm.html

PHP:  array_reverse($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtzfgiptea.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hongshengwenyu.top/Article/details/gtailnduwf.html

TS:   [...arr].reverse();
来源：http://dali.aizwys.cn/Article/details/gtaqpcyllo.html

Java: Collections.reverse(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtesimvlew.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258.top/Article/details/gtcljnbyby.html

Ruby: arr.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtdkfhhovb.html

C#:   list.Reverse();
来源：http://dali.iojbl.cn/Article/details/gtjuzmvqpo.html

[D12] 查找元素下标
来源：http://dali.mhx1999.top/Article/details/gtaedlkpfz.html

Py:   arr.index(x);  x in arr
来源：http://dali.9152youxi.cn/Article/details/gtgskclknu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.pycfn.com/Article/details/gtnkuonpcy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzivhlknw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gtawnoslwu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.feifeiyinyue.top/Article/details/gtfhuznsyd.html

Go:   slices.Index(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtbnfpvftq.html

Ruby: arr.index(x)
来源：http://dali.jinqigufen.top/Article/details/gtmzdckhrn.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258.top/Article/details/gtpzjgeyrb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.quarkkingdee.top/Article/details/gtsdaqagxv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cucudq.cn/Article/details/gtrsvyptva.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.haohaochexian.top/Article/details/gtdxcfolts.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gtwcmepsvu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xuanzx.com/Article/details/gtxtlkwtyq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.svipenyu.cn/Article/details/gtesmcvhku.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hysaishi.cn/Article/details/gtgduahaxx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sxryk.cn/Article/details/gtpvaztkxi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtvbnrdxcm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yangfankeji.com/Article/details/gtmzxcocwu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258888.top/Article/details/gtzneioufs.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yvedp.cn/Article/details/gtficmewvw.html

JS:   arr.map(x => x * 2)
来源：http://dali.guowangkeji.top/Article/details/gtbrwscpbk.html

TS:   arr.map(x => x * 2)
来源：http://dali.jianghu66.top/Article/details/gtrajsmhuy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258.top/Article/details/gtdtctysfk.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gtkrcsqbjx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.smart0.xyz/Article/details/gtxctvrpis.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sweek.top/Article/details/gttjnwayiw.html

[D15] 去重
来源：http://dali.dashuyun.cn/Article/details/gtvgoealqs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gtrbfkhzua.html

PHP:  array_unique($arr);
来源：http://dali.aizwys.cn/Article/details/gtkgrlsnvg.html

JS:   [...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gtwtbtoapx.html

TS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gtwutykpmr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenlongwang.top/Article/details/gtfojdvjkb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnqzz.top/Article/details/gtzknnemvn.html

Ruby: arr.uniq
来源：http://dali.birdmap.top/Article/details/gtmjbaodet.html

C#:   list.Distinct().ToList()
来源：http://dali.ybcxt.top/Article/details/gtijhngnvt.html

[D16] 求和与平均值
来源：http://dali.cashguo.top/Article/details/gtaagjcbvb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtoaaxcnjf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuanzhike.top/Article/details/gteufgcpwm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gtjcwwclgr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtannntrab.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatugzloh.html

Go:   // 手写循环累加
来源：http://dali.gaohongyu789.top/Article/details/gticfmzfvg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgfzy.top/Article/details/gtmkmxlajz.html

C#:   list.Sum();  list.Average()
来源：http://dali.fzhhl.top/Article/details/gthknpkitu.html

[D17] 最大值与最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrkqunxs.html

Py:   max(arr);  min(arr)
来源：http://dali.shuidangran.top/Article/details/gtlkzkzvnl.html

PHP:  max($arr);  min($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtvpzviids.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnxiangtu.top/Article/details/gteeatcvcy.html

TS:   Math.max(...arr);
来源：http://dali.havefunace.top/Article/details/gtzroezmvu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.0kj1m.cn/Article/details/gtrzpjcpli.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.wangdashe.top/Article/details/gtqsrxedqm.html

Ruby: arr.max;  arr.min
来源：http://dali.yonumen.top/Article/details/gtmwlhxcea.html

C#:   list.Max();  list.Min()
来源：http://dali.chenzaomai.com/Article/details/gtexiozefr.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gtlpkmqllp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yongpay.top/Article/details/gtmptsruwn.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigfzy.top/Article/details/gtbgqyycul.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.0kj1m.cn/Article/details/gtvczmhula.html

TS:   nested.flat();
来源：http://dali.ppjwa.cn/Article/details/gtetfqaaxy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtwbcuhzzm.html

Go:   // 手写双层循环
来源：http://dali.redwolf501.top/Article/details/gtetzwhvar.html

Ruby: nested.flatten
来源：http://dali.c1oappe.top/Article/details/gtzhugiblm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagcckaef.html

[D19] 按字段分组
来源：http://dali.feifeiyinyue.top/Article/details/gtzroersvq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fengsongda.top/Article/details/gtluzosqei.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jianghu66.top/Article/details/gtbeufcwon.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ydzc1.top/Article/details/gtrkxdsvco.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tanke756.top/Article/details/gtbaaylxwv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.svipenyu.cn/Article/details/gtkrihurpc.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258888.top/Article/details/gtimxkybvw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guowangkeji.top/Article/details/gtotcsddzp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.mhx1999.top/Article/details/gtwxyoezxe.html

[D20] 统计每个元素出现次数
来源：http://dali.havefunace.top/Article/details/gthcqtlidj.html

Py:   Counter(arr)
来源：http://dali.hysaishi.cn/Article/details/gthjmdifuk.html

PHP:  array_count_values($arr);
来源：http://dali.yvedp.cn/Article/details/gthymiynjk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gtsklnehmi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gtqhndarim.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlumlxtnd.html

Go:   // 手写 map[T]int
来源：http://dali.xziqi.cn/Article/details/gthmdadyfp.html

Ruby: arr.tally
来源：http://dali.xuanzx.com/Article/details/gtjamthszu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj202588.top/Article/details/gtkamyajlp.html

[D21] 判断是否包含某元素
来源：http://dali.vqdsnc.cn/Article/details/gtabsdcwtb.html

Py:   x in arr
来源：http://dali.c1oappe.top/Article/details/gtsnhzzrkr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtnkdomyvs.html

JS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtaghptrsc.html

TS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gtadvhaahh.html

Java: list.contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtowzjxedq.html

Go:   slices.Contains(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtdmycsqqr.html

Ruby: arr.include?(x)
来源：http://dali.zycfv.cn/Article/details/gtescckcnp.html

C#:   list.Contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtonevfhjr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.haohaochexian.top/Article/details/gtjhnxebvw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtxjgnteok.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yvedp.cn/Article/details/gtprkpryvc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtqjjacrgo.html

TS:   [...arr];
来源：http://dali.zhiwuduotai.top/Article/details/gteouszqrn.html

Java: new ArrayList<>(list);
来源：http://dali.xuanzx.com/Article/details/gtkupykrlg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tianlin.xyz/Article/details/gtxkomvism.html

Ruby: arr.dup;  arr.clone
来源：http://dali.9152youxi.cn/Article/details/gtvxvmowfs.html

C#:   new List<int>(list);
来源：http://dali.cqqwz.cn/Article/details/gtvnhgqkvw.html

[D23] reduce 累积计算
来源：http://dali.hammf.cn/Article/details/gttjiaorrq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zycfv.cn/Article/details/gtjhonptdp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guannengcc.top/Article/details/gtxvxpksdm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtuuwupufn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cqqwz.cn/Article/details/gtxcancimi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.snrcjt.cn/Article/details/gtemlbdveo.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gtymuvewfi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258888.top/Article/details/gtpwjkzahs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dianchejie.cn/Article/details/gtoxjjeicv.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangshuangyany.cn/Article/details/gtzlxoahjz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhiwuduotai.top/Article/details/gtdlekgugk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.vqdsnc.cn/Article/details/gtketpkwyg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ydzc1.top/Article/details/gtmgzowkzi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtffjbjrei.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenlongwang.top/Article/details/gtwrxiuxvt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuanzhike.top/Article/details/gtncqbhbzg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guowangkeji.top/Article/details/gtciyapupw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ppjwa.cn/Article/details/gtvrealuuk.html

[D25] Set 集合去重与交并差
来源：http://dali.zdqjudy.top/Article/details/gtoerizsuh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xziqi.cn/Article/details/gtjoqxkirw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.havefunace.top/Article/details/gtnvmykxit.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daxiang520.top/Article/details/gthtzqapxp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.birdmap.top/Article/details/gttbgvpfzb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.andypj.xyz/Article/details/gtpoachidq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ehwqpu.com/Article/details/gtlnupeboo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tianlin.xyz/Article/details/gtldxhbqac.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenlongwang.top/Article/details/gtfiadsopv.html

[D26] 数组转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtghcnmzyl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj202588.top/Article/details/gtbpjyncyu.html

PHP:  implode(", ", $arr);
来源：http://dali.xylfe.cn/Article/details/gttvcnevpj.html

JS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gtkoqcmonq.html

TS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtihylvccw.html

Java: String.join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gtkxiqtcon.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ybcxt.top/Article/details/gtlrwcspuw.html

Ruby: arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtosopmuxd.html

C#:   string.Join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gtnhvrckzf.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtbssrccsd.html

E. 字符串处理
来源：http://dali.cucudq.cn/Article/details/gtuwbakdvj.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtlfkyxoos.html

[E01] 拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtckdvsltb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhongyouzk.top/Article/details/gtmwxgrgrs.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guannengcc.top/Article/details/gtdxmwawak.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gtjvnbapzu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gtgnbjgpoj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jianghu66.top/Article/details/gttlktxzet.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hfpthk.cn/Article/details/gtzmlopwfm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhiwuduotai.top/Article/details/gtbeymhuar.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtjjjnidbl.html

[E02] 重复字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahujlrse.html

Py:   "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gtqzezsvpg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigfzy.top/Article/details/gtnnexhaqh.html

JS:   "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtlqanxyxq.html

TS:   "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gtcjbzjiit.html

Java: "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtzmiydkjf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.9152youxi.cn/Article/details/gturrkhjyj.html

Ruby: "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gtvwymesoi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nwbrower.top/Article/details/gtnfpuhnqo.html

[E03] 截取子串
来源：http://dali.ydzc1.top/Article/details/gthjxwywew.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jianghu66.top/Article/details/gtqckfcxof.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtcazglsbf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtefjuupsd.html

TS:   s.slice(1, 4)
来源：http://dali.cashguo.top/Article/details/gtydiimmde.html

Java: s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtvhdtszvt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpuamhdtf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxuanxn.top/Article/details/gtmgzrympn.html

C#:   s.Substring(1, 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtaxbdxvme.html

[E04] 查找子串位置
来源：http://dali.svipenyu.cn/Article/details/gtceepezht.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtecimpjrq.html

PHP:  strpos($s, "x");
来源：http://dali.pengpengdd.cyou/Article/details/gtgykzvanh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.snrcjt.cn/Article/details/gttsotajkx.html

TS:   s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtiekelbkf.html

Java: s.indexOf("x")
来源：http://dali.c1oappe.top/Article/details/gtbgctyaft.html

Go:   strings.Index(s, "x")
来源：http://dali.cqqwz.cn/Article/details/gtrozweecu.html

Ruby: s.index("x")
来源：http://dali.yuxming.cn/Article/details/gtzsimhtni.html

C#:   s.IndexOf("x")
来源：http://dali.havefunace.top/Article/details/gtpxtjzpmh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zdqjudy.top/Article/details/gtwxhoiiof.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrtjzmmo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.daria6918.cn/Article/details/gtelcecgxh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gtqlblhhgf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtwritvxas.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gtoqdhkzbj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cucudq.cn/Article/details/gtwhftybcp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sysykeji.top/Article/details/gtmrljkcie.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hammf.cn/Article/details/gtwtvgxmqa.html


<!-- 参考信息 -->