代发 wailian999

Ruby: a, b = pair
来源：http://dali.fengsongda.top/Article/details/gt2phsvaukk.html

C#:   var (a, b) = pair;
来源：http://dali.c1oappe.top/Article/details/gt2uymdexcg.html

[C16] 函数 / 方法重载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dzudldym.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xziqi.cn/Article/details/gt2uzacseoy.html

PHP:  // 无重载
来源：http://dali.cheryme.top/Article/details/gt2ctxpssio.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.snrcjt.cn/Article/details/gt2ovvcldvv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shuidangran.top/Article/details/gt2mzxixtrs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuanzx.com/Article/details/gt2whrwgmjd.html

Go:   // 无重载：用不同函数名
来源：http://dali.cdnleiting.top/Article/details/gt2cgknhgbc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tianlin.xyz/Article/details/gt2wjlymjid.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wjlprfod.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2ysrrbblo.html

D. 数组 / 列表 / 集合
来源：http://dali.nwbrower.top/Article/details/gt2niqtxfnv.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ihqboibz.html

[D01] 创建数组 / 列表
来源：http://dali.chenlongwang.top/Article/details/gt2pleujyui.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hysaishi.cn/Article/details/gt2vvsrnufl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.guowangkeji.top/Article/details/gt2odoighdv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.snrcjt.cn/Article/details/gt2lxyvcwfb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.andypj.xyz/Article/details/gt2ozacdbdl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenjidiqi.icu/Article/details/gt2ekswedhe.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hfpthk.cn/Article/details/gt2xtottcwh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nwbrower.top/Article/details/gt2jeqdmyny.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuanzx.com/Article/details/gt2sggzvlfq.html

[D02] 追加元素到末尾
来源：http://dali.ppjwa.cn/Article/details/gt2ftuablha.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrvrvlc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yvedp.cn/Article/details/gt2ecfnqaez.html

JS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gt2jwfcbicp.html

TS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gt2roullhvh.html

Java: list.add(4);
来源：http://dali.yonumen.top/Article/details/gt2kioztgel.html

Go:   arr = append(arr, 4)
来源：http://dali.chenlongwang.top/Article/details/gt2hlpojwaa.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tian-w.cn/Article/details/gt2eblggxke.html

C#:   list.Add(4);
来源：http://dali.pycfn.com/Article/details/gt2esljmabt.html

[D03] 在指定位置插入元素
来源：http://dali.haohaochexian.top/Article/details/gt2jxiwjnqc.html

Py:   arr.insert(0, 0)
来源：http://dali.yj202588.top/Article/details/gt2otnbnsdw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.bjfxy.top/Article/details/gt2iilppiyq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.9152youxi.cn/Article/details/gt2avdprqrm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhixingplan.top/Article/details/gt2bmawaasp.html

Java: list.add(0, 0);
来源：http://dali.yueranfly.top/Article/details/gt2iozcuyhx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ehwqpu.com/Article/details/gt2cvrosaks.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hywenlv.cn/Article/details/gt2vcingkde.html

C#:   list.Insert(0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2ddccbtpr.html

[D04] 删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cjukwfqs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xziqi.cn/Article/details/gt2vvzxdtlp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yvedp.cn/Article/details/gt2fcfuelbo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sysykeji.top/Article/details/gt2xdyumkug.html

TS:   arr.splice(0, 1);
来源：http://dali.jlsjyb.cn/Article/details/gt2foiabyun.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hfpthk.cn/Article/details/gt2ywfvujmt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zycfv.cn/Article/details/gt2dznuyuif.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuxming.cn/Article/details/gt2zpemdodz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zdqjudy.top/Article/details/gt2zobgqqtr.html

[D05] 访问与修改元素
来源：http://dali.tian-w.cn/Article/details/gt2kfdccgki.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qhjbfwab.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gt2daedghvm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gt2rebfdxen.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcysyqv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ybcxt.top/Article/details/gt2ivrdzdpa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mrwvrbfo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gt2mndrygww.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gt2opzakitp.html

[D06] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gt2rfolhikh.html

Py:   len(arr)
来源：http://dali.tanke756.top/Article/details/gt2ebvnvqym.html

PHP:  count($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2hpcthcrc.html

JS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gt2pkrggshq.html

TS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gt2wqetxyhz.html

Java: list.size();
来源：http://dali.cheryme.top/Article/details/gt2wyaxhghb.html

Go:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2bkdeygmi.html

Ruby: arr.length; arr.size
来源：http://dali.aibaodan.cn/Article/details/gt2jdjkjvxr.html

C#:   list.Count;
来源：http://dali.andypj.xyz/Article/details/gt2zhsgvidb.html

[D07] 切片 / 取子数组
来源：http://dali.snrcjt.cn/Article/details/gt2yuwmaqen.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ybcxt.top/Article/details/gt2gtnxezbz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cucudq.cn/Article/details/gt2ueqkrzsk.html

JS:   arr.slice(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gt2pheilsww.html

TS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gt2hapowxiq.html

Java: list.subList(1, 4);
来源：http://dali.shuidangran.top/Article/details/gt2ivptinhm.html

Go:   arr[1:4]
来源：http://dali.quarkkingdee.top/Article/details/gt2rxyupiql.html

Ruby: arr[1, 3]
来源：http://dali.yvedp.cn/Article/details/gt2bjmvbnmf.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigufen.top/Article/details/gt2zygkghen.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mancpndo.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnxiangtu.top/Article/details/gt2bodvsrdx.html

PHP:  array_merge($a, $b);
来源：http://dali.xziqi.cn/Article/details/gt2ujunreku.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cashguo.top/Article/details/gt2gfnunkkd.html

TS:   [...a, ...b];
来源：http://dali.zhixingplan.top/Article/details/gt2cqdttmjw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinqigufen.top/Article/details/gt2kemlostn.html

Go:   append(a, b...)
来源：http://dali.pycfn.com/Article/details/gt2zmdceigu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgoramvl.html

C#:   a.Concat(b).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2xiymifng.html

[D09] 排序（升序）
来源：http://dali.yuanzhike.top/Article/details/gt2hhnepxmw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvaodich.html

PHP:  sort($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2tfzwcnrq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fzhhl.top/Article/details/gt2fqerfxcg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhiwuduotai.top/Article/details/gt2brlsiitk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenzaomai.com/Article/details/gt2uitcoqko.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2izftewea.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gt2jlabwswj.html

C#:   list.Sort();
来源：http://dali.chenlongwang.top/Article/details/gt2nilqxkqf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.meibo888.top/Article/details/gt2rzdyfnwo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zdqjudy.top/Article/details/gt2dgycooir.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shzxlz.cn/Article/details/gt2evjqsqdi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gt2rhvwxehn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gt2unhjszpz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangdashe.top/Article/details/gt2oekhxzcx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cdnleiting.top/Article/details/gt2hyzbezip.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sufxvd.cn/Article/details/gt2vuvjodth.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zdqjudy.top/Article/details/gt2fylaykil.html

[D11] 反转数组
来源：http://dali.guowangkeji.top/Article/details/gt2pfbtrrgw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.vqdsnc.cn/Article/details/gt2fgajrvle.html

PHP:  array_reverse($arr);
来源：http://dali.yuxming.cn/Article/details/gt2mxzvegph.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pengpengdd.cyou/Article/details/gt2iliwabhu.html

TS:   [...arr].reverse();
来源：http://dali.guowangkeji.top/Article/details/gt2jdjapvqm.html

Java: Collections.reverse(list);
来源：http://dali.guowangkeji.top/Article/details/gt2flyzkgnh.html

Go:   slices.Reverse(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2wjaqxbsu.html

Ruby: arr.reverse
来源：http://dali.316326.xyz/Article/details/gt2xelxnbov.html

C#:   list.Reverse();
来源：http://dali.cqqwz.cn/Article/details/gt2fknbrnfq.html

[D12] 查找元素下标
来源：http://dali.wangshuangyany.cn/Article/details/gt2nfwapibj.html

Py:   arr.index(x);  x in arr
来源：http://dali.nanxinkj.top/Article/details/gt2bpenybzg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gogol.net.cn/Article/details/gt2rimiqgye.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gxeslvpl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gt2piaonpzw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fzhhl.top/Article/details/gt2gpqkvlju.html

Go:   slices.Index(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2zcizvckc.html

Ruby: arr.index(x)
来源：http://dali.shzxlz.cn/Article/details/gt2apjdjiod.html

C#:   list.IndexOf(x);
来源：http://dali.wangdashe.top/Article/details/gt2plzutjyg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fengsongda.top/Article/details/gt2xruplwxd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dashuyun.cn/Article/details/gt2dxzziwyf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2bpmdzqvj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2muekpnsb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gt2aonxdtqc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fengsongda.top/Article/details/gt2xwzzicst.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigfzy.top/Article/details/gt2fnizptty.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxuanxn.top/Article/details/gt2ekrmjtzb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2szpqdunl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dashuyun.cn/Article/details/gt2ktbiprdz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.svipenyu.cn/Article/details/gt2vfcuhlpa.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.fzhhl.top/Article/details/gt2kjaxulrr.html

JS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2fnntratb.html

TS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gt2gmyjilni.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2ijeueizf.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gt2flkyubte.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2vwigilzc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.havefunace.top/Article/details/gt2jkxmhpnk.html

[D15] 去重
来源：http://dali.havefunace.top/Article/details/gt2qejsrihj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cucudq.cn/Article/details/gt2tiomepqw.html

PHP:  array_unique($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2adzyekza.html

JS:   [...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dzkztsnp.html

TS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gt2cpnkesmr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhiwuduotai.top/Article/details/gt2psfpwznq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tianlin.xyz/Article/details/gt2pcogsjaf.html

Ruby: arr.uniq
来源：http://dali.jinqigfzy.top/Article/details/gt2pljrhjnp.html

C#:   list.Distinct().ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2xofegjeq.html

[D16] 求和与平均值
来源：http://dali.dashuyun.cn/Article/details/gt2uspdtwfu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjftlcd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hammf.cn/Article/details/gt2niglaosd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gt2udiuqzwd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2hqomoxqm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.haohaochexian.top/Article/details/gt2jkzupxmj.html

Go:   // 手写循环累加
来源：http://dali.cqqwz.cn/Article/details/gt2ixdgiixc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tanke756.top/Article/details/gt2yqerwwfq.html

C#:   list.Sum();  list.Average()
来源：http://dali.jianghu66.top/Article/details/gt2ezmuyzzy.html

[D17] 最大值与最小值
来源：http://dali.mhx1999.top/Article/details/gt2eydhkkwb.html

Py:   max(arr);  min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qmogxigq.html

PHP:  max($arr);  min($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2kmiwmutr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangdashe.top/Article/details/gt2xcvjismu.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gt2zorbavhj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yueranfly.top/Article/details/gt2qyoazgqz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2ltvrubsr.html

Ruby: arr.max;  arr.min
来源：http://dali.guannengcc.top/Article/details/gt2hykurlfz.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgfzy.top/Article/details/gt2pqovfgkn.html

[D18] 扁平化嵌套数组
来源：http://dali.hammf.cn/Article/details/gt2udzqphmc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.smart0.xyz/Article/details/gt2ckoxkezs.html

PHP:  array_merge(...$nested);
来源：http://dali.yueranfly.top/Article/details/gt2idqtgzde.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cheryme.top/Article/details/gt2ypmiowpz.html

TS:   nested.flat();
来源：http://dali.ehwqpu.com/Article/details/gt2zfajndfa.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2zigvptos.html

Go:   // 手写双层循环
来源：http://dali.smart0.xyz/Article/details/gt2oinjwypv.html

Ruby: nested.flatten
来源：http://dali.yonumen.top/Article/details/gt2fwacazdt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyrjnzt.html

[D19] 按字段分组
来源：http://dali.xylfe.cn/Article/details/gt2xjpbffks.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.9152youxi.cn/Article/details/gt2laxrdawf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.redwolf501.top/Article/details/gt2pzpkqewi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aibaodan.cn/Article/details/gt2nugucfyy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.andypj.xyz/Article/details/gt2echhwant.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.0kj1m.cn/Article/details/gt2qgwoytdx.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjjmjou.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cucudq.cn/Article/details/gt2iskpmyff.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.9152youxi.cn/Article/details/gt2ytdciula.html

[D20] 统计每个元素出现次数
来源：http://dali.havefunace.top/Article/details/gt2wpbmqagp.html

Py:   Counter(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2aacjmwit.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2jhgagkpp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gt2qzdxvqhf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gt2gxalurvf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.aibaodan.cn/Article/details/gt2oswigska.html

Go:   // 手写 map[T]int
来源：http://dali.zdqjudy.top/Article/details/gt2eupwffem.html

Ruby: arr.tally
来源：http://dali.xziqi.cn/Article/details/gt2jkgtwamz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.birdmap.top/Article/details/gt2bjapxlin.html

[D21] 判断是否包含某元素
来源：http://dali.havefunace.top/Article/details/gt2karlbmin.html

Py:   x in arr
来源：http://dali.svipenyu.cn/Article/details/gt2szgirzgw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hysaishi.cn/Article/details/gt2ejrpynfk.html

JS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gt2otruwafw.html

TS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gt2ytovzjpp.html

Java: list.contains(x)
来源：http://dali.andypj.xyz/Article/details/gt2farucvgx.html

Go:   slices.Contains(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2miewrubw.html

Ruby: arr.include?(x)
来源：http://dali.nwbrower.top/Article/details/gt2nowjjhvn.html

C#:   list.Contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dqjdjrva.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cashguo.top/Article/details/gt2gptvsixa.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2otscxuft.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.iojbl.cn/Article/details/gt2eyoczahk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gzhubu.top/Article/details/gt2lroxokmu.html

TS:   [...arr];
来源：http://dali.kuanghao11.cn/Article/details/gt2rtdonluv.html

Java: new ArrayList<>(list);
来源：http://dali.quarkkingdee.top/Article/details/gt2pphjdmru.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tianlin.xyz/Article/details/gt2qjlgfqck.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnxiangtu.top/Article/details/gt2hswrcknm.html

C#:   new List<int>(list);
来源：http://dali.yanxiufei.cn/Article/details/gt2tjvqukdi.html

[D23] reduce 累积计算
来源：http://dali.nwbrower.top/Article/details/gt2rabektke.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhgybhue.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daxiang520.top/Article/details/gt2btlrthwj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2bubazzxi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aylitcvq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xinyue.icu/Article/details/gt2aaxwwwzs.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gt2wmigpyhk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj202588.top/Article/details/gt2zlibjqro.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xziqi.cn/Article/details/gt2bsrxfbwv.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wuuwnisb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zdqjudy.top/Article/details/gt2rkextlxc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mybafjqq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yvedp.cn/Article/details/gt2xgvaazfv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yonumen.top/Article/details/gt2blizzmhy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cheryme.top/Article/details/gt2xgwmtgxb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxinkj.top/Article/details/gt2yoebdpma.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zdqjudy.top/Article/details/gt2qouazaxz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ehwqpu.com/Article/details/gt2scrknlrr.html

[D25] Set 集合去重与交并差
来源：http://dali.ydzc1.top/Article/details/gt2dugiejod.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cashguo.top/Article/details/gt2iwxhsvas.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pycfn.com/Article/details/gt2zologmvf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2ihikjcco.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.mhx1999.top/Article/details/gt2rfnwulvq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cdnleiting.top/Article/details/gt2dyxnwhvj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ehwqpu.com/Article/details/gt2ykymzzta.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.dianchejie.cn/Article/details/gt2tqwxcntf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sysykeji.top/Article/details/gt2wmukpsnn.html

[D26] 数组转字符串
来源：http://dali.xziqi.cn/Article/details/gt2njlztuhc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2rlejqirm.html

PHP:  implode(", ", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ngxtugis.html

JS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pptbdkmd.html

TS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gt2deidoyuz.html

Java: String.join(", ", list)
来源：http://dali.smart0.xyz/Article/details/gt2gascbzru.html

Go:   strings.Join(strs, ", ")
来源：http://dali.0kj1m.cn/Article/details/gt2nanxyfop.html

Ruby: arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gt2ycdkdovg.html

C#:   string.Join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gt2rlstqivc.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2xxcariyw.html

E. 字符串处理
来源：http://dali.iojbl.cn/Article/details/gt2udwhdpxq.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2xusrjhxf.html

[E01] 拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2zotrxmyr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.quarkkingdee.top/Article/details/gt2onoqjhfl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhengqikj.top/Article/details/gt2hvuprhha.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gt2ppaskmmh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gt2gpbglrwj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.kuanghao11.cn/Article/details/gt2qpbkzlth.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shuidangran.top/Article/details/gt2zzfcdnpt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.feifeiyinyue.top/Article/details/gt2uobubdij.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2rdcezkbb.html

[E02] 重复字符串
来源：http://dali.sysykeji.top/Article/details/gt2pzlwoqas.html

Py:   "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gt2zpigqsjf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2tpslmwco.html

JS:   "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gt2xckmsldh.html

TS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gt2igufmmpl.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zjjvkoqa.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2lmilmhrx.html

Ruby: "ab" * 3
来源：http://dali.tanke756.top/Article/details/gt2qgadeidi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sweek.top/Article/details/gt2pxicyogx.html

[E03] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gt2wzuwccir.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yanxiufei.cn/Article/details/gt2pjprcsww.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gt2ittnrwcn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yspclvsd.html

TS:   s.slice(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gt2wowhutkd.html

Java: s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gt2yhowwkze.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sxryk.cn/Article/details/gt2oavkyzyn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tianlin.xyz/Article/details/gt2wzlwqkkx.html

C#:   s.Substring(1, 3)
来源：http://dali.yvedp.cn/Article/details/gt2pkczkkru.html

[E04] 查找子串位置
来源：http://dali.9152youxi.cn/Article/details/gt2vjkudsdk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.c1oappe.top/Article/details/gt2uomjbukm.html

PHP:  strpos($s, "x");
来源：http://dali.jyoumei.cn/Article/details/gt2kjawuenr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigfzy.top/Article/details/gt2rccmhxnl.html

TS:   s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gt2lblxiqtd.html

Java: s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gt2jrhctamb.html

Go:   strings.Index(s, "x")
来源：http://dali.cdnleiting.top/Article/details/gt2qcrxbcxf.html

Ruby: s.index("x")
来源：http://dali.snrcjt.cn/Article/details/gt2khaujzdz.html

C#:   s.IndexOf("x")
来源：http://dali.sxryk.cn/Article/details/gt2vbbysnyi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hfpthk.cn/Article/details/gt2ieshcfql.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenzaomai.com/Article/details/gt2pexplqrp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tanke756.top/Article/details/gt2hbqiuwgk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gt2nvrywwgx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bwfmgulu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gt2uhzervce.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.haohaochexian.top/Article/details/gt2hnuojjgn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj202588.top/Article/details/gt2fiojfuoo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ftmsrehp.html

[E06] 替换子串
来源：http://dali.0kj1m.cn/Article/details/gt2joqitdsi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2pbltxvfs.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zycfv.cn/Article/details/gt2ygfudojw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gt2hqbsziwv.html


<!-- 参考信息 -->