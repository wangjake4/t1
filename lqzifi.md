代发 wailian999

PHP:  // 无重载
来源：http://dali.zhoulong.xyz/Article/details/gtbijqasii.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.9152youxi.cn/Article/details/gtmuxqzuwr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.daria6918.cn/Article/details/gteqnuulqc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tianlin.xyz/Article/details/gtyekweomx.html

Go:   // 无重载：用不同函数名
来源：http://dali.sufxvd.cn/Article/details/gthaxclgjc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sysykeji.top/Article/details/gttsbylqrb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tian-w.cn/Article/details/gttyjqbhkz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtvwxvzula.html

D. 数组 / 列表 / 集合
来源：http://dali.ppjwa.cn/Article/details/gtouhpcthm.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtlxdxgrca.html

[D01] 创建数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gtsfqhxbdb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.feifeiyinyue.top/Article/details/gtkpjjxnmj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyouicetu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ybcxt.top/Article/details/gtwnzgttzr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jqgufenzy.top/Article/details/gtsonigkjf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guowangkeji.top/Article/details/gtjrfejfxk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenlongwang.top/Article/details/gtvrtgjjgv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinqigfzy.top/Article/details/gtdmbacotu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nanxuanxn.top/Article/details/gtlgjbpdrv.html

[D02] 追加元素到末尾
来源：http://dali.tanke756.top/Article/details/gtdqvuuhfy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjbtfokg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hywenlv.cn/Article/details/gtmsjxjgnt.html

JS:   arr.push(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtjkhyddnv.html

TS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gtdilbrumz.html

Java: list.add(4);
来源：http://dali.sxryk.cn/Article/details/gtfjjfytjy.html

Go:   arr = append(arr, 4)
来源：http://dali.ehwqpu.com/Article/details/gtjfeilzij.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gogol.net.cn/Article/details/gtsubzubwa.html

C#:   list.Add(4);
来源：http://dali.shzxlz.cn/Article/details/gttkywinrr.html

[D03] 在指定位置插入元素
来源：http://dali.xylfe.cn/Article/details/gtuuaaccve.html

Py:   arr.insert(0, 0)
来源：http://dali.zycfv.cn/Article/details/gtsvpuvvhl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shuidangran.top/Article/details/gtuhvtqaxe.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangtech.top/Article/details/gtifoovezc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shuidangran.top/Article/details/gtcmdvlmgf.html

Java: list.add(0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtqtiorxwr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yueranfly.top/Article/details/gtyhlfmsny.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ivvv.top/Article/details/gtbebngjsi.html

C#:   list.Insert(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtqafqcvok.html

[D04] 删除元素
来源：http://dali.iojbl.cn/Article/details/gtoklluogy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sysykeji.top/Article/details/gtrwkilwzc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gotoacloud.top/Article/details/gthbxrbydl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fzhhl.top/Article/details/gtfxbpusgm.html

TS:   arr.splice(0, 1);
来源：http://dali.tanke756.top/Article/details/gtlmjbuxfx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shuidangran.top/Article/details/gtcsitkouh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jiagoushi.top/Article/details/gtifavisue.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj20258888.top/Article/details/gtzeloygfg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nwbrower.top/Article/details/gtfnufxgmo.html

[D05] 访问与修改元素
来源：http://dali.vqdsnc.cn/Article/details/gttjqyixdu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gtacuyrpln.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gtpqqjcxae.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gtijrdlloq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sweek.top/Article/details/gtbudeuyza.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.havefunace.top/Article/details/gtonxemmkt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gtlcvlmrhs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gtneovlrej.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gtlefvmmuo.html

[D06] 数组长度
来源：http://dali.cheryme.top/Article/details/gtllvylyfu.html

Py:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gtdowuifpu.html

PHP:  count($arr);
来源：http://dali.guowangkeji.top/Article/details/gtholymqyr.html

JS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gtphdvpycc.html

TS:   arr.length
来源：http://dali.hywenlv.cn/Article/details/gtmsjttbon.html

Java: list.size();
来源：http://dali.havefunace.top/Article/details/gtydhjhhgg.html

Go:   len(arr)
来源：http://dali.wangdashe.top/Article/details/gtitavhtmi.html

Ruby: arr.length; arr.size
来源：http://dali.zhengqikj.top/Article/details/gtyknjrehp.html

C#:   list.Count;
来源：http://dali.zycfv.cn/Article/details/gtdzdohkpm.html

[D07] 切片 / 取子数组
来源：http://dali.316326.xyz/Article/details/gtcbnuexbj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.meibo888.top/Article/details/gtrcxatekg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.guowangkeji.top/Article/details/gtomlvcnnf.html

JS:   arr.slice(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqyintwe.html

TS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gthnjpqtzl.html

Java: list.subList(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtwjndqjrl.html

Go:   arr[1:4]
来源：http://dali.chenjidiqi.icu/Article/details/gtpmwjrwju.html

Ruby: arr[1, 3]
来源：http://dali.aibaodan.cn/Article/details/gtpsmcqviu.html

C#:   list.GetRange(1, 3);
来源：http://dali.cucudq.cn/Article/details/gtcxvprhfp.html

[D08] 合并两个数组
来源：http://dali.shangyingyoupin.top/Article/details/gtxmmppiea.html

Py:   a + b;  a.extend(b)
来源：http://dali.guannengcc.top/Article/details/gtobzfkpju.html

PHP:  array_merge($a, $b);
来源：http://dali.tanke756.top/Article/details/gthlwgwlna.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xinyue.icu/Article/details/gthfttmpgx.html

TS:   [...a, ...b];
来源：http://dali.9152youxi.cn/Article/details/gtiehnvznw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ydzc1.top/Article/details/gtmplihnvc.html

Go:   append(a, b...)
来源：http://dali.chenzaomai.com/Article/details/gtorxcgnrq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.9152youxi.cn/Article/details/gtvtoxkoor.html

C#:   a.Concat(b).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtkphzhqdm.html

[D09] 排序（升序）
来源：http://dali.smart0.xyz/Article/details/gtqjkhohit.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gtxxawbjuy.html

PHP:  sort($arr);
来源：http://dali.nwbrower.top/Article/details/gtndcvpgay.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenjidiqi.icu/Article/details/gtprytnoov.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenzaomai.com/Article/details/gthvrmbrtu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoraapasm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gtwfftfoql.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gtvbpspczc.html

C#:   list.Sort();
来源：http://dali.wangdashe.top/Article/details/gtwcfiemdg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnhkkdqw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.c1oappe.top/Article/details/gtyuzauzqz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cheryme.top/Article/details/gtxlrfdtwn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gtortklkur.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gtrfttqtuy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cheryme.top/Article/details/gtuvjqpzpp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.svipenyu.cn/Article/details/gtpwsdyllq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hammf.cn/Article/details/gtjblccgkc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.meibo888.top/Article/details/gttbccxgjg.html

[D11] 反转数组
来源：http://dali.cashguo.top/Article/details/gtifscnnyn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgufenzy.top/Article/details/gtpiayfatc.html

PHP:  array_reverse($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtkgsmrkoo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenlongwang.top/Article/details/gtjtllkzrf.html

TS:   [...arr].reverse();
来源：http://dali.ehwqpu.com/Article/details/gtmwebzbrr.html

Java: Collections.reverse(list);
来源：http://dali.jinqigfzy.top/Article/details/gthdodxdkp.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gtobxytrsk.html

Ruby: arr.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtblfgwrum.html

C#:   list.Reverse();
来源：http://dali.smart0.xyz/Article/details/gtnpgffurb.html

[D12] 查找元素下标
来源：http://dali.ybcxt.top/Article/details/gtzmjciyfd.html

Py:   arr.index(x);  x in arr
来源：http://dali.havefunace.top/Article/details/gthznjcrfh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jianghu66.top/Article/details/gtyvivleia.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gtozzspbed.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gthjedxcij.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.bjfxy.top/Article/details/gtqrjviyuw.html

Go:   slices.Index(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtwxtqfklf.html

Ruby: arr.index(x)
来源：http://dali.fengsongda.top/Article/details/gteacodasu.html

C#:   list.IndexOf(x);
来源：http://dali.redwolf501.top/Article/details/gtqxtwvhfe.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhengqikj.top/Article/details/gtzmuyvrzv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hywenlv.cn/Article/details/gtjqgnjrrs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigfzy.top/Article/details/gtyijvvgbv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gthxyujyjf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtwlasrwod.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sweek.top/Article/details/gtiqftxcqf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258.top/Article/details/gthckbsbwy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxuanxn.top/Article/details/gtfahwacxc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuxming.cn/Article/details/gtqqpjpgtk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.9152youxi.cn/Article/details/gtdihqmcny.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nanxinkj.top/Article/details/gtsbvaxrwp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.smart0.xyz/Article/details/gthumxixne.html

JS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gtobtmpute.html

TS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gtchttrear.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ppjwa.cn/Article/details/gtejmrhido.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gtqsftmenp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ydzc1.top/Article/details/gtxvdhhkzz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtcvqsyebx.html

[D15] 去重
来源：http://dali.zhixingplan.top/Article/details/gtzvkooiid.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gtlkiyxglg.html

PHP:  array_unique($arr);
来源：http://dali.bjfxy.top/Article/details/gtghjcqpph.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gtuuatusxc.html

TS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddsyikxz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhixingplan.top/Article/details/gtvqtectub.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cashguo.top/Article/details/gtciopncmm.html

Ruby: arr.uniq
来源：http://dali.nwbrower.top/Article/details/gtpwjhzzth.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxinkj.top/Article/details/gtydpayvjt.html

[D16] 求和与平均值
来源：http://dali.ehwqpu.com/Article/details/gthogiwmzm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtfxxmflrc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.svipenyu.cn/Article/details/gthgrvvedd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtnzpogaap.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gtwtritvyo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhajlvan.html

Go:   // 手写循环累加
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpweghgv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gtrtcmcvym.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuxming.cn/Article/details/gtklojuego.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gtlmnehlfo.html

Py:   max(arr);  min(arr)
来源：http://dali.iojbl.cn/Article/details/gtqzqklevk.html

PHP:  max($arr);  min($arr);
来源：http://dali.hywenlv.cn/Article/details/gtjdodvlxk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtakhkccpv.html

TS:   Math.max(...arr);
来源：http://dali.zhengqikj.top/Article/details/gtynblrcdv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gaohongyu789.top/Article/details/gtqvbxhtkl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cheryme.top/Article/details/gtqslelcay.html

Ruby: arr.max;  arr.min
来源：http://dali.yanxiufei.cn/Article/details/gtcplvvmop.html

C#:   list.Max();  list.Min()
来源：http://dali.shzxlz.cn/Article/details/gtatodltvs.html

[D18] 扁平化嵌套数组
来源：http://dali.aibaodan.cn/Article/details/gtzopvocij.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fengsongda.top/Article/details/gtghoryyia.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgufenzy.top/Article/details/gtcqhfejvx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj202588.top/Article/details/gtcrdzftty.html

TS:   nested.flat();
来源：http://dali.yuanzhike.top/Article/details/gtyfqalfvk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guannengcc.top/Article/details/gtzdsqhqgl.html

Go:   // 手写双层循环
来源：http://dali.meibo888.top/Article/details/gthhqmdmqy.html

Ruby: nested.flatten
来源：http://dali.ydzc1.top/Article/details/gtkyhoiius.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtaezjjszj.html

[D19] 按字段分组
来源：http://dali.redwolf501.top/Article/details/gtiqgksfmm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sweek.top/Article/details/gtbpfrxckr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yongpay.top/Article/details/gtxfhlzzim.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.c1oappe.top/Article/details/gtygehxpwu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gtcuiazhdo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.birdmap.top/Article/details/gtaggtoguq.html

Go:   // 手写 map[string][]T
来源：http://dali.yj202588.top/Article/details/gtfinddxcj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxinkj.top/Article/details/gtbkbofodb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhixingplan.top/Article/details/gtcoqoqliq.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258.top/Article/details/gtzkbdsqvv.html

Py:   Counter(arr)
来源：http://dali.svipenyu.cn/Article/details/gtlmetnehl.html

PHP:  array_count_values($arr);
来源：http://dali.gotoacloud.top/Article/details/gteqcnyemz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gtnyrjtqch.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gtzvucclob.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.bjfxy.top/Article/details/gtrfrlftzi.html

Go:   // 手写 map[T]int
来源：http://dali.dianchejie.cn/Article/details/gtggzrxswq.html

Ruby: arr.tally
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkowmbtxv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fzhhl.top/Article/details/gtjlvqtowu.html

[D21] 判断是否包含某元素
来源：http://dali.chenzaomai.com/Article/details/gtermpibvj.html

Py:   x in arr
来源：http://dali.zhoulong.xyz/Article/details/gtvalqyxgp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aibaodan.cn/Article/details/gtepubsduy.html

JS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gtvlzntkkr.html

TS:   arr.includes(x)
来源：http://dali.shuidangran.top/Article/details/gthovevpmc.html

Java: list.contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtmadzvaoh.html

Go:   slices.Contains(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtefbgmjpz.html

Ruby: arr.include?(x)
来源：http://dali.dianchejie.cn/Article/details/gtoshhbkyg.html

C#:   list.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gtevdreglg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tanke756.top/Article/details/gtunjwzccj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xylfe.cn/Article/details/gtpujnsbtw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxinkj.top/Article/details/gthndcmryj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cucudq.cn/Article/details/gtffjphzzt.html

TS:   [...arr];
来源：http://dali.cashguo.top/Article/details/gtverynuhp.html

Java: new ArrayList<>(list);
来源：http://dali.gzhubu.top/Article/details/gtkvaxloht.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xylfe.cn/Article/details/gtwboqzgao.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sufxvd.cn/Article/details/gtccwjjcsh.html

C#:   new List<int>(list);
来源：http://dali.zhengqikj.top/Article/details/gtximxjkmm.html

[D23] reduce 累积计算
来源：http://dali.gogol.net.cn/Article/details/gtqaocqjyw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guannengcc.top/Article/details/gtchoczamk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtvgljtkjy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gtduypreuy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gtjiicxjlh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqthpfghi.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gthyievfun.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ppjwa.cn/Article/details/gtkhdbrgwj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hfpthk.cn/Article/details/gtevphdfao.html

[D24] 字典 / Map 基本操作
来源：http://dali.vqdsnc.cn/Article/details/gtzavtlwbd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhengqikj.top/Article/details/gtkvsmeqzz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dashuyun.cn/Article/details/gtjrbzkzik.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hfpthk.cn/Article/details/gtxukpoiib.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtcbhtrwqs.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenzaomai.com/Article/details/gtrwitiudd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigfzy.top/Article/details/gtbsspdpxu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtesiwtmbj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tanke756.top/Article/details/gteezqszmb.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxinkj.top/Article/details/gtwkfkqefc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuanzx.com/Article/details/gtrqbnnzsy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dashuyun.cn/Article/details/gtslupwgii.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.havefunace.top/Article/details/gtrraoxxzj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj202588.top/Article/details/gtjhmiraix.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gtbftzneli.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gtdzimcega.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.redwolf501.top/Article/details/gtprmwyzjb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guannengcc.top/Article/details/gtptkkjvsi.html

[D26] 数组转字符串
来源：http://dali.xinyue.icu/Article/details/gtpqmndhfm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ehwqpu.com/Article/details/gtjyotgnvx.html

PHP:  implode(", ", $arr);
来源：http://dali.wangdashe.top/Article/details/gtroluusys.html

JS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtoxrmrxrz.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwtzbrhz.html

Java: String.join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gtiegwtbes.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yueranfly.top/Article/details/gtotmuzmeu.html

Ruby: arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtmdnkiqmu.html

C#:   string.Join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gtxqclyumt.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gthomedmgp.html

E. 字符串处理
来源：http://dali.tianlin.xyz/Article/details/gtstdnugnm.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtjsbvuvic.html

[E01] 拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtqtwjuxvr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hfpthk.cn/Article/details/gtdbrpvslc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.snrcjt.cn/Article/details/gtdtpsngkr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gtojdvztzc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gtznuujoof.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.smart0.xyz/Article/details/gtpcobmugg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.kuanghao11.cn/Article/details/gtqiioekye.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhengqikj.top/Article/details/gtnrznlkga.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtuzwkbbgd.html

[E02] 重复字符串
来源：http://dali.bjfxy.top/Article/details/gtxlscqkuw.html

Py:   "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gtqzlprhkd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yanxiufei.cn/Article/details/gtzvzntigs.html

JS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtlewxtyaw.html

TS:   "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gtrmdexwad.html

Java: "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gtjyswixnr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.aibaodan.cn/Article/details/gtwezxpivd.html

Ruby: "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gtyqsartro.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jiagoushi.top/Article/details/gtsvvjyemd.html

[E03] 截取子串
来源：http://dali.yongpay.top/Article/details/gtlvvzfkbj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hammf.cn/Article/details/gtgfuulsou.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtrstcwprf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtbtbcipux.html

TS:   s.slice(1, 4)
来源：http://dali.ivvv.top/Article/details/gtfvjvyooe.html

Java: s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtkeajiigk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.haohaochexian.top/Article/details/gtaoqhdbil.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.svipenyu.cn/Article/details/gtjaynyghs.html

C#:   s.Substring(1, 3)
来源：http://dali.xuanzx.com/Article/details/gtfearagrz.html

[E04] 查找子串位置
来源：http://dali.shzxlz.cn/Article/details/gtfoagadit.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgourbeph.html

PHP:  strpos($s, "x");
来源：http://dali.jyoumei.cn/Article/details/gtfmyjwgus.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yueranfly.top/Article/details/gtvrjfoogp.html

TS:   s.indexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gtvjyqlkgu.html

Java: s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtgjnlifws.html

Go:   strings.Index(s, "x")
来源：http://dali.316326.xyz/Article/details/gtnanqblnl.html

Ruby: s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gttgelbcuu.html

C#:   s.IndexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxfysycf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgfzy.top/Article/details/gtrjwrpdev.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxinkj.top/Article/details/gtjwtnnywn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuanzhike.top/Article/details/gtzbckezsz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtamyppzkp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hywenlv.cn/Article/details/gtshcgwora.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtoxwunbkg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sysykeji.top/Article/details/gtuhruhoiu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gogol.net.cn/Article/details/gtxezvghfa.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtubyzpwhg.html

[E06] 替换子串
来源：http://dali.yongpay.top/Article/details/gtdebelzoj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggfopihx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gotoacloud.top/Article/details/gtwkkrfmok.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtgopsmrkw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtifouttve.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtktmajlec.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gtvvpydofn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gthfxchjmy.html


<!-- 参考信息 -->