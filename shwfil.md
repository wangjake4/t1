代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jyoumei.cn/Article/details/gt2vczbqqmv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.bjfxy.top/Article/details/gt2bzlnmbgc.html

Java: // 无解构
来源：http://dali.wangshuangyany.cn/Article/details/gt2ggamqibg.html

Go:   // 无解构
来源：http://dali.9152youxi.cn/Article/details/gt2paubkukc.html

Ruby: a, b = pair
来源：http://dali.gotoacloud.top/Article/details/gt2cvbllova.html

C#:   var (a, b) = pair;
来源：http://dali.gotoacloud.top/Article/details/gt2qiuhwrsx.html

[C16] 函数 / 方法重载
来源：http://dali.redwolf501.top/Article/details/gt2grvkordz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuanzhike.top/Article/details/gt2uwvstage.html

PHP:  // 无重载
来源：http://dali.ydzc1.top/Article/details/gt2tpdjatil.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shzxlz.cn/Article/details/gt2pfpmybum.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ppjwa.cn/Article/details/gt2rcpecttq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2buboodyw.html

Go:   // 无重载：用不同函数名
来源：http://dali.pengpengdd.cyou/Article/details/gt2uxtjmctq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hysaishi.cn/Article/details/gt2kanacftj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj20258.top/Article/details/gt2rtrrlkkv.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2fmlijjjp.html

D. 数组 / 列表 / 集合
来源：http://dali.sxryk.cn/Article/details/gt2qsithmob.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2fusbkjcy.html

[D01] 创建数组 / 列表
来源：http://dali.meibo888.top/Article/details/gt2oajeiexb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xuanzx.com/Article/details/gt2jfxvytlu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ehwqpu.com/Article/details/gt2fzhzmjqf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gt2lozxvydw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangdashe.top/Article/details/gt2sttmmwjb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigufen.top/Article/details/gt2ulztazoq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.9152youxi.cn/Article/details/gt2xymekiyn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jianghu66.top/Article/details/gt2bcxflqgj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daxiang520.top/Article/details/gt2feffipcu.html

[D02] 追加元素到末尾
来源：http://dali.hywenlv.cn/Article/details/gt2aiaqvsoi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgfzy.top/Article/details/gt2mxxpnuyz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhixingplan.top/Article/details/gt2mgyovmmh.html

JS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gt2ncietpeg.html

TS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hrytqhcx.html

Java: list.add(4);
来源：http://dali.zycfv.cn/Article/details/gt2yqvdngcv.html

Go:   arr = append(arr, 4)
来源：http://dali.xinyue.icu/Article/details/gt2svlcyyih.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2opeavusl.html

C#:   list.Add(4);
来源：http://dali.gzhubu.top/Article/details/gt2harrnntl.html

[D03] 在指定位置插入元素
来源：http://dali.ehwqpu.com/Article/details/gt2uividkff.html

Py:   arr.insert(0, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2iugwmxbc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenlongwang.top/Article/details/gt2hthurkhb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cheryme.top/Article/details/gt2uzvgjcwi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jyoumei.cn/Article/details/gt2krysxkco.html

Java: list.add(0, 0);
来源：http://dali.hammf.cn/Article/details/gt2kmuslmjx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.meibo888.top/Article/details/gt2qbuxazzg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shzxlz.cn/Article/details/gt2ydkdypap.html

C#:   list.Insert(0, 0);
来源：http://dali.ydzc1.top/Article/details/gt2qovlbzef.html

[D04] 删除元素
来源：http://dali.yonumen.top/Article/details/gt2jqcrrsow.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.havefunace.top/Article/details/gt2yvnikfff.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tvonhbmy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xylfe.cn/Article/details/gt2luhhrzxi.html

TS:   arr.splice(0, 1);
来源：http://dali.quarkkingdee.top/Article/details/gt2zzndaxzt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.meibo888.top/Article/details/gt2semokamm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guowangkeji.top/Article/details/gt2ivrtufzd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cucudq.cn/Article/details/gt2htzssjan.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.meibo888.top/Article/details/gt2cjmpaxjf.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gt2yndtglep.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gt2qsybtlgv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gt2fcebobyt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gt2ogfxwhpx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.quarkkingdee.top/Article/details/gt2xxizkezp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hfpthk.cn/Article/details/gt2jmicpjcl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gt2zsknsrxp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gt2fvwobzby.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.316326.xyz/Article/details/gt2xcazxpso.html

[D06] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gt2wtgjfbpw.html

Py:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gt2rbcppyqn.html

PHP:  count($arr);
来源：http://dali.yvedp.cn/Article/details/gt2xovnxvrq.html

JS:   arr.length
来源：http://dali.yj20258.top/Article/details/gt2xqdlxuee.html

TS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gt2bpaxoaeb.html

Java: list.size();
来源：http://dali.zhixingplan.top/Article/details/gt2uzdyrwzg.html

Go:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2ynoksger.html

Ruby: arr.length; arr.size
来源：http://dali.quarkkingdee.top/Article/details/gt2nihuagwa.html

C#:   list.Count;
来源：http://dali.tian-w.cn/Article/details/gt2kvtyjpzc.html

[D07] 切片 / 取子数组
来源：http://dali.wangdashe.top/Article/details/gt2kzfyjpjn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zdqjudy.top/Article/details/gt2iwydnpia.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sxryk.cn/Article/details/gt2auchrrzt.html

JS:   arr.slice(1, 4);
来源：http://dali.havefunace.top/Article/details/gt2zchdqdny.html

TS:   arr.slice(1, 4);
来源：http://dali.mhx1999.top/Article/details/gt2bmlitmtc.html

Java: list.subList(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gt2diqtjrfz.html

Go:   arr[1:4]
来源：http://dali.guowangkeji.top/Article/details/gt2srfwnkmw.html

Ruby: arr[1, 3]
来源：http://dali.nanxinkj.top/Article/details/gt2ffkghabh.html

C#:   list.GetRange(1, 3);
来源：http://dali.316326.xyz/Article/details/gt2himrycoh.html

[D08] 合并两个数组
来源：http://dali.iojbl.cn/Article/details/gt2hgcjxjdw.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhoulong.xyz/Article/details/gt2ligspzoo.html

PHP:  array_merge($a, $b);
来源：http://dali.cheryme.top/Article/details/gt2mjnnndad.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sysykeji.top/Article/details/gt2luzqioif.html

TS:   [...a, ...b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hpvgzubv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yongpay.top/Article/details/gt2aikggfmy.html

Go:   append(a, b...)
来源：http://dali.zhoulong.xyz/Article/details/gt2xotnslds.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guannengcc.top/Article/details/gt2mfjbwesv.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2owaskhoh.html

[D09] 排序（升序）
来源：http://dali.sysykeji.top/Article/details/gt2vyhuxspu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gt2vonnfzef.html

PHP:  sort($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2arohasmh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yangfankeji.com/Article/details/gt2jpxncuiw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhoulong.xyz/Article/details/gt2ogpqyzyu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gt2waqzycyf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2lkpkqugf.html

Ruby: arr.sort
来源：http://dali.dianchejie.cn/Article/details/gt2grqydhhg.html

C#:   list.Sort();
来源：http://dali.snrcjt.cn/Article/details/gt2kkhcvzfi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenzaomai.com/Article/details/gt2rtxgwuek.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.redwolf501.top/Article/details/gt2suyttyqh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gt2wvqxhtmq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.c1oappe.top/Article/details/gt2xwgetgmw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gt2xvwrzewn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gogol.net.cn/Article/details/gt2atzslpyv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhengqikj.top/Article/details/gt2meqpkctv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.0kj1m.cn/Article/details/gt2hmqpvtyu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sysykeji.top/Article/details/gt2wkorhole.html

[D11] 反转数组
来源：http://dali.0kj1m.cn/Article/details/gt2puxkvxxi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daria6918.cn/Article/details/gt2lukgaqya.html

PHP:  array_reverse($arr);
来源：http://dali.yj20258888.top/Article/details/gt2xkmowlqt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.meibo888.top/Article/details/gt2uulxactj.html

TS:   [...arr].reverse();
来源：http://dali.guannengcc.top/Article/details/gt2kaqnzklw.html

Java: Collections.reverse(list);
来源：http://dali.redwolf501.top/Article/details/gt2dfihiwrb.html

Go:   slices.Reverse(arr)
来源：http://dali.cucudq.cn/Article/details/gt2qrvqlrou.html

Ruby: arr.reverse
来源：http://dali.zdqjudy.top/Article/details/gt2vhvfjvam.html

C#:   list.Reverse();
来源：http://dali.sweek.top/Article/details/gt2nvvejjig.html

[D12] 查找元素下标
来源：http://dali.ivvv.top/Article/details/gt2ihfafnpk.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhengqikj.top/Article/details/gt2wwprgprf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xinyue.icu/Article/details/gt2nwduzgmy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gt2abjsdmku.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gt2topmzmqh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenjidiqi.icu/Article/details/gt2vxnpfmzh.html

Go:   slices.Index(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gt2ntkoassb.html

Ruby: arr.index(x)
来源：http://dali.guowangkeji.top/Article/details/gt2rdqqasca.html

C#:   list.IndexOf(x);
来源：http://dali.zycfv.cn/Article/details/gt2enkvkfam.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jyoumei.cn/Article/details/gt2qllxhmpj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hammf.cn/Article/details/gt2vdoupvcr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.c1oappe.top/Article/details/gt2ixpqtlpr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gt2eadtumhg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.9152youxi.cn/Article/details/gt2jptieebg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2hskdjqzd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cashguo.top/Article/details/gt2pcchrwmp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258.top/Article/details/gt2kgruocxi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yonumen.top/Article/details/gt2vfndwduo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dianchejie.cn/Article/details/gt2gxbkcouv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shzxlz.cn/Article/details/gt2tcrvidtx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenzaomai.com/Article/details/gt2ixsxekpp.html

JS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gt2znlmakgh.html

TS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gt2zygmgait.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.9152youxi.cn/Article/details/gt2cjclzrko.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2tzipegnh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2baqcbwmm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2nvttinjv.html

[D15] 去重
来源：http://dali.yangfankeji.com/Article/details/gt2beqltkxh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gt2disouqsv.html

PHP:  array_unique($arr);
来源：http://dali.zycfv.cn/Article/details/gt2nlmbpdzx.html

JS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gt2lwblkwxj.html

TS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gt2bfwglrli.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhengqikj.top/Article/details/gt2oagvkwbv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuanzhike.top/Article/details/gt2wmwsylco.html

Ruby: arr.uniq
来源：http://dali.cucudq.cn/Article/details/gt2ufxdcuyi.html

C#:   list.Distinct().ToList()
来源：http://dali.ydzc1.top/Article/details/gt2mjntnjxi.html

[D16] 求和与平均值
来源：http://dali.yangfankeji.com/Article/details/gt2gftmxhcs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fengsongda.top/Article/details/gt2dxpcmwdy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2syaijnfi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2djqzdfop.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2rygdmutk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yueranfly.top/Article/details/gt2fefsahxp.html

Go:   // 手写循环累加
来源：http://dali.yj20258.top/Article/details/gt2valffeak.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.andypj.xyz/Article/details/gt2pqdpypfs.html

C#:   list.Sum();  list.Average()
来源：http://dali.hysaishi.cn/Article/details/gt2jyszspfo.html

[D17] 最大值与最小值
来源：http://dali.xziqi.cn/Article/details/gt2ojdutavn.html

Py:   max(arr);  min(arr)
来源：http://dali.shuidangran.top/Article/details/gt2lpnjbiru.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhdaitmg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gt2peuwteam.html

TS:   Math.max(...arr);
来源：http://dali.aibaodan.cn/Article/details/gt2wzupodji.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sufxvd.cn/Article/details/gt2vkgwkxrd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2cmvdguwl.html

Ruby: arr.max;  arr.min
来源：http://dali.cucudq.cn/Article/details/gt2mtfyfviu.html

C#:   list.Max();  list.Min()
来源：http://dali.yuxming.cn/Article/details/gt2jqdhsbuw.html

[D18] 扁平化嵌套数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubsxwytk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aizwys.cn/Article/details/gt2kwsekmqp.html

PHP:  array_merge(...$nested);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xdepghig.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cdnleiting.top/Article/details/gt2uxpfgrfi.html

TS:   nested.flat();
来源：http://dali.zycfv.cn/Article/details/gt2elgbvphi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xuanzx.com/Article/details/gt2skiytgcw.html

Go:   // 手写双层循环
来源：http://dali.hnxiangtu.top/Article/details/gt2ujynputd.html

Ruby: nested.flatten
来源：http://dali.jqgufenzy.top/Article/details/gt2ccglcxvh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2iurrsczq.html

[D19] 按字段分组
来源：http://dali.yueranfly.top/Article/details/gt2dankowva.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.iojbl.cn/Article/details/gt2dbtpwnod.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shangyingyoupin.top/Article/details/gt2cnhwhksl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shzxlz.cn/Article/details/gt2tvvjbjwg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.meibo888.top/Article/details/gt2mcjwmsta.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.bjfxy.top/Article/details/gt2tyomputf.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgfzy.top/Article/details/gt2rbznqzgo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xylfe.cn/Article/details/gt2sleyewww.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgfzy.top/Article/details/gt2dgrenivc.html

[D20] 统计每个元素出现次数
来源：http://dali.yuxming.cn/Article/details/gt2fmbpxktg.html

Py:   Counter(arr)
来源：http://dali.ivvv.top/Article/details/gt2olbikadk.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gt2padkelzo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gt2cbwhtwif.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gt2dyrzgxsd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnqzz.top/Article/details/gt2vhxodksx.html

Go:   // 手写 map[T]int
来源：http://dali.hywenlv.cn/Article/details/gt2ktghddla.html

Ruby: arr.tally
来源：http://dali.gaohongyu789.top/Article/details/gt2sqdmybcl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hnxiangtu.top/Article/details/gt2aguqbqfu.html

[D21] 判断是否包含某元素
来源：http://dali.ydzc1.top/Article/details/gt2dgsejads.html

Py:   x in arr
来源：http://dali.ehwqpu.com/Article/details/gt2avmvoxpo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xziqi.cn/Article/details/gt2pozrjene.html

JS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gt2hpmjbksd.html

TS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gt2erkcpdjt.html

Java: list.contains(x)
来源：http://dali.fengsongda.top/Article/details/gt2tkkzzulg.html

Go:   slices.Contains(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2xvfirjar.html

Ruby: arr.include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mnyhichz.html

C#:   list.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gt2ndzsegny.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daria6918.cn/Article/details/gt2idtqrslf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2ounashcl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ybcxt.top/Article/details/gt2dlxffxfd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2qmabisox.html

TS:   [...arr];
来源：http://dali.chenjidiqi.icu/Article/details/gt2novdrtxp.html

Java: new ArrayList<>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wrbaapke.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.birdmap.top/Article/details/gt2wqeavcdq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gzhubu.top/Article/details/gt2glegjxtr.html

C#:   new List<int>(list);
来源：http://dali.tianlin.xyz/Article/details/gt2tvaedzsc.html

[D23] reduce 累积计算
来源：http://dali.birdmap.top/Article/details/gt2ixxzdnoc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2luvwnrjd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hammf.cn/Article/details/gt2gzhyklvm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zxcukoop.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gt2vrvyjajk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sufxvd.cn/Article/details/gt2mfshvvsx.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gt2adumhaxf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.snrcjt.cn/Article/details/gt2jmpmggwv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cqqwz.cn/Article/details/gt2diqqbege.html

[D24] 字典 / Map 基本操作
来源：http://dali.shangyingyoupin.top/Article/details/gt2uoyfqlbt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xuanzx.com/Article/details/gt2uoajhina.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cashguo.top/Article/details/gt2ssrjgzuj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.havefunace.top/Article/details/gt2hupgzcyd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2sohrnhkb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258888.top/Article/details/gt2ugtqwoqb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tianlin.xyz/Article/details/gt2iluxqyvl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangshuangyany.cn/Article/details/gt2blqkbqby.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guowangkeji.top/Article/details/gt2zcceojey.html

[D25] Set 集合去重与交并差
来源：http://dali.wangdashe.top/Article/details/gt2sferzdfr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.daria6918.cn/Article/details/gt2drbrsjug.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zycfv.cn/Article/details/gt2jbesvdgf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hnqzz.top/Article/details/gt2kghcpnue.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hywenlv.cn/Article/details/gt2tfcbepal.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj20258888.top/Article/details/gt2pabpvsbt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gt2raqnxkdc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2nrorpqmt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cdnleiting.top/Article/details/gt2jhyfssyn.html

[D26] 数组转字符串
来源：http://dali.sweek.top/Article/details/gt2ertjftrx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangdashe.top/Article/details/gt2xsjfegup.html

PHP:  implode(", ", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2jxfdhpqs.html

JS:   arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gt2dyhgrwye.html

TS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gt2meckzzpw.html

Java: String.join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gt2wpyfcjry.html

Go:   strings.Join(strs, ", ")
来源：http://dali.c1oappe.top/Article/details/gt2wjtqhomv.html

Ruby: arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gt2uinwpqws.html

C#:   string.Join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gt2tfzyvqno.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2evdzxiur.html

E. 字符串处理
来源：http://dali.chenlongwang.top/Article/details/gt2ktjrmlue.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2xqdtelfx.html

[E01] 拼接字符串
来源：http://dali.sxryk.cn/Article/details/gt2lpfrmchq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tianlin.xyz/Article/details/gt2xafebdvz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnxiangtu.top/Article/details/gt2vrfojckg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gt2lcmaaaxo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sxryk.cn/Article/details/gt2xkyprlxb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xinyue.icu/Article/details/gt2kytuwamk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sysykeji.top/Article/details/gt2wmxfmhju.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jlsjyb.cn/Article/details/gt2tbsjcudj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2mhlwoafx.html

[E02] 重复字符串
来源：http://dali.yonumen.top/Article/details/gt2wbxcddyq.html

Py:   "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wkqohpqh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sufxvd.cn/Article/details/gt2nxhnzfau.html

JS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gt2vtefegle.html

TS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gt2likjgmvv.html

Java: "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gt2hmlzygjg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dianchejie.cn/Article/details/gt2ryhwqncw.html

Ruby: "ab" * 3
来源：http://dali.chenlongwang.top/Article/details/gt2auncxshm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zycfv.cn/Article/details/gt2ftojymbz.html

[E03] 截取子串
来源：http://dali.cashguo.top/Article/details/gt2gmwjazve.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.aibaodan.cn/Article/details/gt2fuapanbu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gt2ylulavtj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gt2llxqrzfp.html

TS:   s.slice(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gt2qcbtxtvv.html

Java: s.substring(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gt2hnzmknhl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuanzhike.top/Article/details/gt2wmrallzn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jyoumei.cn/Article/details/gt2shjtmsdd.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dkoaxybd.html

[E04] 查找子串位置
来源：http://dali.guowangkeji.top/Article/details/gt2eiatwmrr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cheryme.top/Article/details/gt2khwsicdq.html

PHP:  strpos($s, "x");
来源：http://dali.ybcxt.top/Article/details/gt2qcvqurpb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhongyouzk.top/Article/details/gt2umxlbdve.html

TS:   s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xqsspkta.html

Java: s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gt2ehwqsptt.html

Go:   strings.Index(s, "x")
来源：http://dali.jiagoushi.top/Article/details/gt2ovlfliha.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gt2yqmywyiv.html

C#:   s.IndexOf("x")
来源：http://dali.xziqi.cn/Article/details/gt2rrreaadd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rtkdnsdq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zveqpvon.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnqzz.top/Article/details/gt2hrgryweb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2tfhqnzex.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2yyokrrzl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gt2bgleuxla.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.quarkkingdee.top/Article/details/gt2kialchux.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.fengsongda.top/Article/details/gt2euwbhejv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gt2rnevgqwk.html


<!-- 参考信息 -->