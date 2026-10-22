代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.meibo888.top/Article/details/gtkhkygkkr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtqztfhsth.html

Java: // 无解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjktstcp.html

Go:   // 无解构
来源：http://dali.bjfxy.top/Article/details/gthftjyflt.html

Ruby: a, b = pair
来源：http://dali.cheryme.top/Article/details/gtnvqfrogk.html

C#:   var (a, b) = pair;
来源：http://dali.nwbrower.top/Article/details/gtklzspwhl.html

[C16] 函数 / 方法重载
来源：http://dali.andypj.xyz/Article/details/gthmdalzdb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhiwuduotai.top/Article/details/gtvgvismbd.html

PHP:  // 无重载
来源：http://dali.wangdashe.top/Article/details/gtqokdhimp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aibaodan.cn/Article/details/gtohefxwof.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnxiangtu.top/Article/details/gthirphpeo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenzaomai.com/Article/details/gtuvorlchd.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhongyouzk.top/Article/details/gtccwrwcvu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.9152youxi.cn/Article/details/gthfhvliex.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hysaishi.cn/Article/details/gthhwujkwj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtbmrzjiek.html

D. 数组 / 列表 / 集合
来源：http://dali.dashuyun.cn/Article/details/gtpegpdgsi.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtkpnafhhm.html

[D01] 创建数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gtielexdui.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xuetiantiany.cn/Article/details/gtkvhjdhzs.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cucudq.cn/Article/details/gtcercuygk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zdqjudy.top/Article/details/gtxznywjvj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xinyue.icu/Article/details/gtaclavjda.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tian-w.cn/Article/details/gtoiupmrvs.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuanzhike.top/Article/details/gtryjlrjeq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gotoacloud.top/Article/details/gtdqilvvrj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.316326.xyz/Article/details/gtzipxodyn.html

[D02] 追加元素到末尾
来源：http://dali.hysaishi.cn/Article/details/gtdhluimvz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cashguo.top/Article/details/gtdtziramu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj202588.top/Article/details/gtqueirkve.html

JS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gtlivqewtr.html

TS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gtexasrvwk.html

Java: list.add(4);
来源：http://dali.tianlin.xyz/Article/details/gtvrgfxoew.html

Go:   arr = append(arr, 4)
来源：http://dali.yuxming.cn/Article/details/gtuxwlczdl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yongpay.top/Article/details/gtsrvzbpha.html

C#:   list.Add(4);
来源：http://dali.hnxiangtu.top/Article/details/gtbeeboiuo.html

[D03] 在指定位置插入元素
来源：http://dali.aibaodan.cn/Article/details/gtdryvtrai.html

Py:   arr.insert(0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtoendymfr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jiagoushi.top/Article/details/gtuxjwwcnz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.havefunace.top/Article/details/gtajqchvuu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yongpay.top/Article/details/gtndlcbdkm.html

Java: list.add(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gttdcswrzk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258888.top/Article/details/gtvkestsbv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ppjwa.cn/Article/details/gtvlleyfsa.html

C#:   list.Insert(0, 0);
来源：http://dali.redwolf501.top/Article/details/gtvzdibvxq.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gtjjstfjvb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ppjwa.cn/Article/details/gtejdiatcx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtmqwsdlka.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jyoumei.cn/Article/details/gtlnlyslra.html

TS:   arr.splice(0, 1);
来源：http://dali.0kj1m.cn/Article/details/gtkynbokwv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.9152youxi.cn/Article/details/gtrndoqfar.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuetiantiany.cn/Article/details/gthylgyeua.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.havefunace.top/Article/details/gttgrgzlmc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258.top/Article/details/gtnfiilabo.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gtjbcrfrnz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gtocezdedk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipzphokx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtivvcsvzi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.0kj1m.cn/Article/details/gtwwmpueus.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.9152youxi.cn/Article/details/gtdahhyunr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtdcykqcqr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gteuznikci.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gtozbysdsx.html

[D06] 数组长度
来源：http://dali.dianchejie.cn/Article/details/gtzjzhxaoe.html

Py:   len(arr)
来源：http://dali.aizwys.cn/Article/details/gtgvuxlkaa.html

PHP:  count($arr);
来源：http://dali.sysykeji.top/Article/details/gtltiwfwks.html

JS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gtdhkduxqy.html

TS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gtkobeagej.html

Java: list.size();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctxhncdh.html

Go:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gttheofoyl.html

Ruby: arr.length; arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajdlyceu.html

C#:   list.Count;
来源：http://dali.9152youxi.cn/Article/details/gtsfjfltwt.html

[D07] 切片 / 取子数组
来源：http://dali.iojbl.cn/Article/details/gtgksjhpaa.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.iojbl.cn/Article/details/gtchfkzuvj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangdashe.top/Article/details/gtgccrunlc.html

JS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtvuqxvwwt.html

TS:   arr.slice(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gtdwplxrgi.html

Java: list.subList(1, 4);
来源：http://dali.hammf.cn/Article/details/gtkbhwlewh.html

Go:   arr[1:4]
来源：http://dali.9152youxi.cn/Article/details/gtrcfmoxot.html

Ruby: arr[1, 3]
来源：http://dali.xziqi.cn/Article/details/gtcbftfbxb.html

C#:   list.GetRange(1, 3);
来源：http://dali.gogol.net.cn/Article/details/gtcccruoyv.html

[D08] 合并两个数组
来源：http://dali.316326.xyz/Article/details/gtwlibqktr.html

Py:   a + b;  a.extend(b)
来源：http://dali.daria6918.cn/Article/details/gtvjczubxz.html

PHP:  array_merge($a, $b);
来源：http://dali.gogol.net.cn/Article/details/gtamnvduby.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.316326.xyz/Article/details/gtqpeppayc.html

TS:   [...a, ...b];
来源：http://dali.xuetiantiany.cn/Article/details/gtybnhlgur.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtvpifuvsf.html

Go:   append(a, b...)
来源：http://dali.yj20258888.top/Article/details/gtyjlcfunn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrndsdjvb.html

C#:   a.Concat(b).ToList()
来源：http://dali.ybcxt.top/Article/details/gtxrahuqes.html

[D09] 排序（升序）
来源：http://dali.jianghu66.top/Article/details/gtitpobaen.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gtlnslclhx.html

PHP:  sort($arr);
来源：http://dali.pycfn.com/Article/details/gtpqmcqbvn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangshuangyany.cn/Article/details/gtecttefyb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigufen.top/Article/details/gtnnntqklq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zycfv.cn/Article/details/gthodsyfvp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gtpwxoyzek.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gtnuiqqdch.html

C#:   list.Sort();
来源：http://dali.quarkkingdee.top/Article/details/gtpyhrgmml.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gtaulhygbk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtwzgbyazk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtxnjetczk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gtakbhlfus.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gtijcmnqhr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuetiantiany.cn/Article/details/gtoekcxdhn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cqqwz.cn/Article/details/gtgqevkkdq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yanxiufei.cn/Article/details/gtukgiycsy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cdnleiting.top/Article/details/gtzcqnppph.html

[D11] 反转数组
来源：http://dali.iojbl.cn/Article/details/gtevnxsjzq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cdnleiting.top/Article/details/gteejtursi.html

PHP:  array_reverse($arr);
来源：http://dali.ydzc1.top/Article/details/gtlooacyvp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.feifeiyinyue.top/Article/details/gtwdftkvxb.html

TS:   [...arr].reverse();
来源：http://dali.hnxiangtu.top/Article/details/gtullcqxme.html

Java: Collections.reverse(list);
来源：http://dali.yangfankeji.com/Article/details/gtpfzrxije.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258888.top/Article/details/gttiekglds.html

Ruby: arr.reverse
来源：http://dali.yonumen.top/Article/details/gtlldupkdo.html

C#:   list.Reverse();
来源：http://dali.mhx1999.top/Article/details/gtgpsxuvzb.html

[D12] 查找元素下标
来源：http://dali.daxiang520.top/Article/details/gteqksnpyp.html

Py:   arr.index(x);  x in arr
来源：http://dali.ydzc1.top/Article/details/gtwwrawynt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yonumen.top/Article/details/gtyowtarnv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gttegboylq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gtjfaynmuc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cdnleiting.top/Article/details/gtmqtxakzz.html

Go:   slices.Index(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtlpsfgncg.html

Ruby: arr.index(x)
来源：http://dali.cdnleiting.top/Article/details/gtdngcmqoy.html

C#:   list.IndexOf(x);
来源：http://dali.zycfv.cn/Article/details/gtacyijoan.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnqzz.top/Article/details/gtzdaidifg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hfpthk.cn/Article/details/gtddschffa.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.meibo888.top/Article/details/gtbwcukmob.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdubiool.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gtxcjreogh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zycfv.cn/Article/details/gtxvbykcnk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhiwuduotai.top/Article/details/gtufaoivus.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ppjwa.cn/Article/details/gtjdmpeorl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tanke756.top/Article/details/gtijtxvtpf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.9152youxi.cn/Article/details/gtfhrpvsln.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.bjfxy.top/Article/details/gtgilulszo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yonumen.top/Article/details/gtjbqacjkq.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtzucpkbgr.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhengqikj.top/Article/details/gtlylhsmce.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nwbrower.top/Article/details/gtgjwjfgio.html

Go:   // 手写循环
来源：http://dali.tian-w.cn/Article/details/gtebieqmvl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jianghu66.top/Article/details/gtltykljhf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtsaggooyo.html

[D15] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtpirwlbdk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqhxgroy.html

PHP:  array_unique($arr);
来源：http://dali.cucudq.cn/Article/details/gtjgorczsi.html

JS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtxwrjvyis.html

TS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtmvccwmyh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhgkgfcc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ivvv.top/Article/details/gtutwvyryl.html

Ruby: arr.uniq
来源：http://dali.hnxiangtu.top/Article/details/gtzsvufxqe.html

C#:   list.Distinct().ToList()
来源：http://dali.zhixingplan.top/Article/details/gtddclphat.html

[D16] 求和与平均值
来源：http://dali.ydzc1.top/Article/details/gtdntmiwxd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtczlxoxot.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daria6918.cn/Article/details/gthxoxdayl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.redwolf501.top/Article/details/gtzoxzxdnu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gtwcoawire.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.snrcjt.cn/Article/details/gtplavtnwl.html

Go:   // 手写循环累加
来源：http://dali.ppjwa.cn/Article/details/gtizlpfwdj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tian-w.cn/Article/details/gtewqpqdsn.html

C#:   list.Sum();  list.Average()
来源：http://dali.pengpengdd.cyou/Article/details/gtcntkgyfq.html

[D17] 最大值与最小值
来源：http://dali.zhoulong.xyz/Article/details/gtuabmafrh.html

Py:   max(arr);  min(arr)
来源：http://dali.zycfv.cn/Article/details/gtbngmmxbp.html

PHP:  max($arr);  min($arr);
来源：http://dali.jyoumei.cn/Article/details/gtvhhavltv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hfpthk.cn/Article/details/gtujbecuqz.html

TS:   Math.max(...arr);
来源：http://dali.ybcxt.top/Article/details/gtcwzbmsiu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgufenzy.top/Article/details/gtcsspnldw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gthharwqid.html

Ruby: arr.max;  arr.min
来源：http://dali.hysaishi.cn/Article/details/gtucsdnarc.html

C#:   list.Max();  list.Min()
来源：http://dali.hammf.cn/Article/details/gttfhusqqh.html

[D18] 扁平化嵌套数组
来源：http://dali.jiagoushi.top/Article/details/gthduibdro.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgfzy.top/Article/details/gtbunzjfgs.html

PHP:  array_merge(...$nested);
来源：http://dali.yonumen.top/Article/details/gtvyqxswki.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zdqjudy.top/Article/details/gtyoyugxrh.html

TS:   nested.flat();
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrvmxazy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtprrddlaj.html

Go:   // 手写双层循环
来源：http://dali.jianghu66.top/Article/details/gthtspzyru.html

Ruby: nested.flatten
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjovdykp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtmwgdxhlr.html

[D19] 按字段分组
来源：http://dali.jianghu66.top/Article/details/gtrxlzvebx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangdashe.top/Article/details/gtwwaxbakg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigufen.top/Article/details/gtcghpqufh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxuanxn.top/Article/details/gtmtuwkktn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gtrqvpmgon.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ppjwa.cn/Article/details/gtcrxxpcff.html

Go:   // 手写 map[string][]T
来源：http://dali.cdnleiting.top/Article/details/gtqtssqgug.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hfpthk.cn/Article/details/gtzvcthucm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.bjfxy.top/Article/details/gtunossefa.html

[D20] 统计每个元素出现次数
来源：http://dali.snrcjt.cn/Article/details/gtgirtrxxa.html

Py:   Counter(arr)
来源：http://dali.nwbrower.top/Article/details/gtzacqgxgj.html

PHP:  array_count_values($arr);
来源：http://dali.tanke756.top/Article/details/gtbbgcxwwi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gtunzkrpah.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gtemzisjes.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pycfn.com/Article/details/gtcixzvobf.html

Go:   // 手写 map[T]int
来源：http://dali.cdnleiting.top/Article/details/gtnoevwuyx.html

Ruby: arr.tally
来源：http://dali.yueranfly.top/Article/details/gtclcvteof.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yangfankeji.com/Article/details/gtjktjjvwl.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gtocaspync.html

Py:   x in arr
来源：http://dali.316326.xyz/Article/details/gtuqftamqa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gogol.net.cn/Article/details/gtvcetpviu.html

JS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtsistqkfp.html

TS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gtaoalubsj.html

Java: list.contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtxzwtoovc.html

Go:   slices.Contains(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtppbrsoqo.html

Ruby: arr.include?(x)
来源：http://dali.jinqigfzy.top/Article/details/gtlyxcmfac.html

C#:   list.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gtybniugze.html

[D22] 复制数组（避免共享引用）
来源：http://dali.guannengcc.top/Article/details/gtaqeldynn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.haohaochexian.top/Article/details/gtnyjxkuug.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhengqikj.top/Article/details/gtdtpueayg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shuidangran.top/Article/details/gtzbvsafzq.html

TS:   [...arr];
来源：http://dali.hnqzz.top/Article/details/gtpamdyqle.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigfzy.top/Article/details/gtskpkeivi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yvedp.cn/Article/details/gtukxgchvv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangdashe.top/Article/details/gtswrwpbng.html

C#:   new List<int>(list);
来源：http://dali.yvedp.cn/Article/details/gtjteqywvv.html

[D23] reduce 累积计算
来源：http://dali.quarkkingdee.top/Article/details/gtjpsslutw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.snrcjt.cn/Article/details/gtabrhoglz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtiekpppyu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gtktgvfqpz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gtruczckcg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aibaodan.cn/Article/details/gtequunqih.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gtojirszgj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shuidangran.top/Article/details/gtlcbwoggl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.mhx1999.top/Article/details/gtzodnwsku.html

[D24] 字典 / Map 基本操作
来源：http://dali.cheryme.top/Article/details/gtzbhpbqnj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shzxlz.cn/Article/details/gtymzmeavt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sweek.top/Article/details/gtotsrujfx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xziqi.cn/Article/details/gtswdcvuxg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtootdypbv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenlongwang.top/Article/details/gthvobvssd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.c1oappe.top/Article/details/gtqzvyrnjl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yueranfly.top/Article/details/gtloqrlfkg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tianlin.xyz/Article/details/gtnitkmtzr.html

[D25] Set 集合去重与交并差
来源：http://dali.wangdashe.top/Article/details/gtrqeukbzn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhixingplan.top/Article/details/gtujmffkft.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gtmwwhlvyq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yanxiufei.cn/Article/details/gtpzhyemhs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xinyue.icu/Article/details/gtlubjmfkb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuetiantiany.cn/Article/details/gthujxapmz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cucudq.cn/Article/details/gtubyzswzu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhengqikj.top/Article/details/gtzasviaur.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hnxiangtu.top/Article/details/gtsmdbxomy.html

[D26] 数组转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtvdhrxpmq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtourumboe.html

PHP:  implode(", ", $arr);
来源：http://dali.yuanzhike.top/Article/details/gtlkppmwua.html

JS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtctcutuhe.html

TS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtarlmjuea.html

Java: String.join(", ", list)
来源：http://dali.smart0.xyz/Article/details/gtafpraztq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jqgufenzy.top/Article/details/gtcchrnaht.html

Ruby: arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtaxjwbhvb.html

C#:   string.Join(", ", list)
来源：http://dali.bjfxy.top/Article/details/gtsllitwmz.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtfbabjpoo.html

E. 字符串处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxbcpsup.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtfplvktks.html

[E01] 拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtxwkhfind.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigufen.top/Article/details/gtujgbuztt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.9152youxi.cn/Article/details/gtmcocqzch.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gtzyygrvyr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gtuhhoqvof.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.guannengcc.top/Article/details/gtvklifybb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aibaodan.cn/Article/details/gtzcgbctji.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ppjwa.cn/Article/details/gtmpmxipds.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtpnhacczv.html

[E02] 重复字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmedgevr.html

Py:   "ab" * 3
来源：http://dali.meibo888.top/Article/details/gtohjfjogb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fengsongda.top/Article/details/gtssksubly.html

JS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtuodegymw.html

TS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gtzfvnuiuo.html

Java: "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtijlosobv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtdllmiwwr.html

Ruby: "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovjpxtsk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxinkj.top/Article/details/gtklrbviae.html

[E03] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gtnpluzohk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj202588.top/Article/details/gtudoblexk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtvkogieew.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtsqimdutf.html

TS:   s.slice(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtwzpsxwqk.html

Java: s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gttmzutafd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zdqjudy.top/Article/details/gtyxfllcnb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.aibaodan.cn/Article/details/gtyhtndkui.html

C#:   s.Substring(1, 3)
来源：http://dali.zhongyouzk.top/Article/details/gtrfakxmqx.html

[E04] 查找子串位置
来源：http://dali.xuanzx.com/Article/details/gtqxuqevrt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.havefunace.top/Article/details/gtnqhwjjup.html

PHP:  strpos($s, "x");
来源：http://dali.andypj.xyz/Article/details/gtewmaiazm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hfpthk.cn/Article/details/gtapxbysey.html

TS:   s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtmqbmmxrj.html

Java: s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gtinewtzye.html

Go:   strings.Index(s, "x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfdjbgtt.html

Ruby: s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gtfgmzyody.html

C#:   s.IndexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtntknbtcy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sweek.top/Article/details/gtaprprsrg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.bjfxy.top/Article/details/gtcnevxjgg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhengqikj.top/Article/details/gtxfpxilve.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrodcsuc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yuxming.cn/Article/details/gtksssakvk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gteclbopvf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xinyue.icu/Article/details/gtpqaxwtiy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258.top/Article/details/gtqwjxzavw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gtmrmxuhql.html


<!-- 参考信息 -->