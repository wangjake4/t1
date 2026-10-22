代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.yj202588.top/Article/details/gt2mckgzjid.html

PHP:  $u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gt2gwoufxmv.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2fcwnfcrp.html

TS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2nsufybvo.html

Java: u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gt2aydjxhxy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yanxiufei.cn/Article/details/gt2uuqjrvqj.html

Ruby: u.is_a?(User)
来源：http://dali.andypj.xyz/Article/details/gt2dadiuryz.html

C#:   u is User
来源：http://dali.xinyue.icu/Article/details/gt2zkaomsrg.html

[G14] 数据类 / record
来源：http://dali.tanke756.top/Article/details/gt2cxpajvcq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuetiantiany.cn/Article/details/gt2pcjfqwcn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gt2iaiziyyo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ydzc1.top/Article/details/gt2mnbwkeaw.html

TS:   type User = { name: string; age: number };
来源：http://dali.yanxiufei.cn/Article/details/gt2cytfeztk.html

Java: record User(String name, int age) {}
来源：http://dali.jyoumei.cn/Article/details/gt2rjryqymw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pengpengdd.cyou/Article/details/gt2iputecbz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenjidiqi.icu/Article/details/gt2ljbgitbu.html

C#:   record User(string Name, int Age);
来源：http://dali.gogol.net.cn/Article/details/gt2clvmrlpb.html

[G15] 枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2azzxnogw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cashguo.top/Article/details/gt2dtpmdaee.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cdnleiting.top/Article/details/gt2ncsxkmtc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258.top/Article/details/gt2uvrolhad.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2dmlcepwr.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhiwuduotai.top/Article/details/gt2bpivevpo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guowangkeji.top/Article/details/gt2pwusmihw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hysaishi.cn/Article/details/gt2jjkjekyh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2icyjsjnm.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gt2mhssqtyu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yongpay.top/Article/details/gt2wkqlzzun.html

PHP:  get_object_vars($obj);
来源：http://dali.aibaodan.cn/Article/details/gt2cqxbnrjt.html

JS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gt2ngdzzawa.html

TS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2amwyrrel.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.bjfxy.top/Article/details/gt2wnebnrkw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ehwqpu.com/Article/details/gt2iyjdnjrz.html

Ruby: obj.instance_variables
来源：http://dali.quarkkingdee.top/Article/details/gt2jdzewlwy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gt2azlhyizl.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gsjmkofb.html

H. 异常与错误处理
来源：http://dali.sysykeji.top/Article/details/gt2vptfgwir.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2uekmhfqh.html

[H01] try / catch 基础
来源：http://dali.tian-w.cn/Article/details/gt2roitgauv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenlongwang.top/Article/details/gt2qogljkqp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pycfn.com/Article/details/gt2oujevrwb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gt2frrwfjrz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gt2pydopbgu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.9152youxi.cn/Article/details/gt2vuinlhee.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.9152youxi.cn/Article/details/gt2ociyfrpy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jianghu66.top/Article/details/gt2nmidtmdz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sufxvd.cn/Article/details/gt2busmcaud.html

[H02] finally / ensure 收尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fojkavmw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fengsongda.top/Article/details/gt2jkcnwpnw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2lxxlnqnm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2vtykxabx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2wnxlfdcr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2jhjyahrm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daria6918.cn/Article/details/gt2qwvbskfc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nwbrower.top/Article/details/gt2zyygaztj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2bixvhgcs.html

[H03] 主动抛出异常
来源：http://dali.xinyue.icu/Article/details/gt2hookimlw.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhongyouzk.top/Article/details/gt2hpjdwhoh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2fywdwfdg.html

JS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gt2xcsmwply.html

TS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2vhlqduzb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2visjzpoq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hujsoslx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuanzhike.top/Article/details/gt2pujqqyjt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2kjfuulhe.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gt2zxqnzuql.html

Py:   class MyError(Exception): pass
来源：http://dali.jlsjyb.cn/Article/details/gt2gcvirnlm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gt2bdciibxp.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jontcqrr.html

TS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gt2tjjucaio.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gt2wgbgscei.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gdzzfeaf.html

Ruby: class MyError < StandardError; end
来源：http://dali.fzhhl.top/Article/details/gt2ojllkmon.html

C#:   class MyException : Exception {}
来源：http://dali.xinyue.icu/Article/details/gt2abonndci.html

[H05] 捕获特定类型
来源：http://dali.meibo888.top/Article/details/gt2pjugojvm.html

Py:   except ValueError as e:
来源：http://dali.feifeiyinyue.top/Article/details/gt2vfdnixlc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gaohongyu789.top/Article/details/gt2ushzzshb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gt2kxoxcezo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ujsfuhnh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fzhhl.top/Article/details/gt2xnoulgqc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jianghu66.top/Article/details/gt2lijnbgld.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gt2ljglerrm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2piioynur.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jiagoushi.top/Article/details/gt2epxrdpis.html

Py:   value = d.get("k") or default
来源：http://dali.yonumen.top/Article/details/gt2bvlbnzoa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gt2efaeudxc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gt2tzcosgli.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gt2rdchxdzt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnxiangtu.top/Article/details/gt2nmspqiun.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yongpay.top/Article/details/gt2dhqtqrhs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gotoacloud.top/Article/details/gt2jylqvtpr.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj202588.top/Article/details/gt2rpzxslnz.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hpigfbcb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jianghu66.top/Article/details/gt2ptvxdbxb.html

PHP:  assert($x > 0);
来源：http://dali.andypj.xyz/Article/details/gt2jlqsmhcn.html

JS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gt2ymuxoqed.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2fajldzte.html

Java: assert x > 0 : "必须为正";
来源：http://dali.feifeiyinyue.top/Article/details/gt2yyydiybw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxinkj.top/Article/details/gt2xfnlfkpw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pengpengdd.cyou/Article/details/gt2vqtpbynq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gt2bbltdzru.html

[H08] 获取错误信息与堆栈
来源：http://dali.svipenyu.cn/Article/details/gt2trobeqkp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aibaodan.cn/Article/details/gt2mnxvqwrw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xziqi.cn/Article/details/gt2gqeoiiaf.html

JS:   e.message;  e.stack
来源：http://dali.cucudq.cn/Article/details/gt2fuglmcmq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangdashe.top/Article/details/gt2onvzpzaw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guannengcc.top/Article/details/gt2grnjejsj.html

Go:   err.Error()
来源：http://dali.hnqzz.top/Article/details/gt2tvwuthpp.html

Ruby: e.message;  e.backtrace
来源：http://dali.xinyue.icu/Article/details/gt2dstwlkck.html

C#:   e.Message;  e.StackTrace
来源：http://dali.meibo888.top/Article/details/gt2dtmmofgx.html

[H09] 带错误码的异常
来源：http://dali.fzhhl.top/Article/details/gt2nvjqmpko.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.316326.xyz/Article/details/gt2sclzryrh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.havefunace.top/Article/details/gt2cvpqfleb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigufen.top/Article/details/gt2enrukxdw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cucudq.cn/Article/details/gt2vfhzaegg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pycfn.com/Article/details/gt2hmsxdvwx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hongshengwenyu.top/Article/details/gt2ebrmryhc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gt2btvmsuec.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gotoacloud.top/Article/details/gt2dmobuarl.html

[H10] 资源自动释放
来源：http://dali.yanxiufei.cn/Article/details/gt2ugybowjj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pengpengdd.cyou/Article/details/gt2fsmxnlbx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gaohongyu789.top/Article/details/gt2wqdbczho.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gt2dytafmdg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gt2mxhiuude.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhongyouzk.top/Article/details/gt2pbeaxplt.html

Go:   defer f.Close()
来源：http://dali.gotoacloud.top/Article/details/gt2xfqtyitk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gogol.net.cn/Article/details/gt2jitllyma.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2lytqamzc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2zrvxnfyc.html

I. 正则表达式
来源：http://dali.havefunace.top/Article/details/gt2zbuycflr.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2pxhalyro.html

[I01] 判断是否匹配
来源：http://dali.guannengcc.top/Article/details/gt2vftijgoe.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gt2xwysyxvd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tian-w.cn/Article/details/gt2yqavmhbg.html

JS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gt2ffvpwwtc.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gt2mrselzhe.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkfwxand.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.bjfxy.top/Article/details/gt2xezunehw.html

Ruby: s.match?(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gt2xypqmgkv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tianlin.xyz/Article/details/gt2oaikcgrj.html

[I02] 提取所有匹配
来源：http://dali.pycfn.com/Article/details/gt2kortybto.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2mcloovsb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fzhhl.top/Article/details/gt2wujlnrws.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jlsjyb.cn/Article/details/gt2uqvytbbo.html

TS:   s.match(/\d+/g)
来源：http://dali.tanke756.top/Article/details/gt2yzilucvn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuxming.cn/Article/details/gt2azxyzxuu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tanke756.top/Article/details/gt2djyszogh.html

Ruby: s.scan(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gt2gunfondf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sqmiewjg.html

[I03] 提取捕获分组
来源：http://dali.ivvv.top/Article/details/gt2teoqrxcs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sxryk.cn/Article/details/gt2apgragkw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xiivyaey.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.andypj.xyz/Article/details/gt2hspwkjjg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258.top/Article/details/gt2rbkpwjhc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258888.top/Article/details/gt2bmswbybp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xylfe.cn/Article/details/gt2avqraygn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2lbdsukst.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.haohaochexian.top/Article/details/gt2tjvzioso.html

[I04] 正则替换
来源：http://dali.jinqigufen.top/Article/details/gt2rftdzjos.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2dtvbtuvf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2zuofyfwd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2jpthtfeu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fengsongda.top/Article/details/gt2mqwkwxhh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2yllowgws.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.bjfxy.top/Article/details/gt2cungxbyn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2rounadte.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gt2fhlyhbpe.html

[I05] 按正则拆分
来源：http://dali.nanxinkj.top/Article/details/gt2jafnmrcg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2ylhanydz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2dccboasy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ptymdfhu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gt2mclwbhck.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2evukpcyt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gt2minsmehr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gt2mrwtkyqc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gogol.net.cn/Article/details/gt2eetzmuww.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhongyouzk.top/Article/details/gt2plugayxt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cheryme.top/Article/details/gt2usvkzpuv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yueranfly.top/Article/details/gt2genwlnzh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gt2duoossbj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wvicrsic.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gt2upypezvb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sxryk.cn/Article/details/gt2vkftayha.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.kuanghao11.cn/Article/details/gt2mslwbnfk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gt2ycqirhqi.html

[I07] 忽略大小写与多行模式
来源：http://dali.hysaishi.cn/Article/details/gt2zisyawqr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigufen.top/Article/details/gt2xsdrmjuw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sweek.top/Article/details/gt2kzrvchij.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.feifeiyinyue.top/Article/details/gt2prjnsayi.html

TS:   /error/gim
来源：http://dali.jlsjyb.cn/Article/details/gt2bghtbumc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yvedp.cn/Article/details/gt2zjvfoebo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sysykeji.top/Article/details/gt2qeghudzr.html

Ruby: s.scan(/error/i)
来源：http://dali.vqdsnc.cn/Article/details/gt2rbqlulop.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxinkj.top/Article/details/gt2dgxljnbj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hammf.cn/Article/details/gt2glttqaku.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pdferufl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xevtjqgh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gt2etcavnel.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gt2qzokwyau.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gt2qzvypano.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yueranfly.top/Article/details/gt2guwdhpiq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zdqjudy.top/Article/details/gt2xximrrtw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gt2ikihccml.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2sbmddnox.html

J. 日期与时间
来源：http://dali.yangfankeji.com/Article/details/gt2xofvwlhd.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2sdlweohi.html

[J01] 获取当前时间
来源：http://dali.sysykeji.top/Article/details/gt2mexygbsn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gt2creqaerb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gt2hpcqdkfk.html

JS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gt2fgbhedcr.html

TS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2zalhmlty.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenlongwang.top/Article/details/gt2bzjlhgmx.html

Go:   time.Now()
来源：http://dali.fzhhl.top/Article/details/gt2iuiasjok.html

Ruby: Time.now
来源：http://dali.fengsongda.top/Article/details/gt2boidcttg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.snrcjt.cn/Article/details/gt2whdvjpfo.html

[J02] 格式化输出
来源：http://dali.cashguo.top/Article/details/gt2zfyketnf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gt2fmbgnqpl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gt2sjuqpwxq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jlsjyb.cn/Article/details/gt2oyuolikm.html

TS:   d.toISOString()
来源：http://dali.gzhubu.top/Article/details/gt2krtzvjxy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.vqdsnc.cn/Article/details/gt2wvictdhf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jianghu66.top/Article/details/gt2kfgrezpz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnxiangtu.top/Article/details/gt2vvtxkyms.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yvedp.cn/Article/details/gt2fnnnpboc.html

[J03] 字符串解析为日期
来源：http://dali.zhiwuduotai.top/Article/details/gt2xuayjynr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgfzy.top/Article/details/gt2wbblendy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gzhubu.top/Article/details/gt2rjtofzzf.html

JS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2addzmubc.html

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2gqnujiji.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2geuivflt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2dihialit.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2dtqlgxdh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mugltegr.html

[J04] 时间戳与日期互转
来源：http://dali.sysykeji.top/Article/details/gt2xdsczvdq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258.top/Article/details/gt2srkaysgn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mwlhgdko.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.svipenyu.cn/Article/details/gt2qqgpyfyl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guannengcc.top/Article/details/gt2yoyukxyd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2smtvadpk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2ttogpayi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sweek.top/Article/details/gt2mddwvdjs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2pjorfwfb.html

[J05] 时间加减（加 7 天）
来源：http://dali.havefunace.top/Article/details/gt2hbbbyeyi.html

Py:   now + timedelta(days=7)
来源：http://dali.sufxvd.cn/Article/details/gt2fkqqhajw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxinkj.top/Article/details/gt2ecnogude.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gt2ynlctrgc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qyqnhxla.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xylfe.cn/Article/details/gt2lcyyurbz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gaohongyu789.top/Article/details/gt2kcpwdtgg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tianlin.xyz/Article/details/gt2xnhummjz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gzhubu.top/Article/details/gt2ywgwzexj.html

[J06] 计算两时间之差
来源：http://dali.hnqzz.top/Article/details/gt2vixfsuyq.html

Py:   (end - start).total_seconds()
来源：http://dali.zdqjudy.top/Article/details/gt2hdgchtfo.html

PHP:  $end->diff($start)->days;
来源：http://dali.cucudq.cn/Article/details/gt2sjoyvdef.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pycfn.com/Article/details/gt2rroeeuld.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vcxxbqav.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aizwys.cn/Article/details/gt2fdghngqd.html

Go:   end.Sub(start).Hours()
来源：http://dali.cashguo.top/Article/details/gt2ollrlfvp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuetiantiany.cn/Article/details/gt2jzvfbwmj.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hwsuhqxm.html

[J07] 比较两个日期
来源：http://dali.zhengqikj.top/Article/details/gt2ekqrtoii.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gt2tsiqaflr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aibaodan.cn/Article/details/gt2mnrfyvxd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gt2nfbhgudb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gt2fdxtsbrh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gt2pmvyxigt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yueranfly.top/Article/details/gt2uqbqkjhm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gt2korcowtf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gt2jjotyiwb.html

[J08] 提取年月日与星期
来源：http://dali.wangshuangyany.cn/Article/details/gt2qyvuxvyp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daria6918.cn/Article/details/gt2ffcaijpu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.pengpengdd.cyou/Article/details/gt2wqzrtbki.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgfzy.top/Article/details/gt2lwgrlfwu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2tejovbbd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yanxiufei.cn/Article/details/gt2ksqensno.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gogol.net.cn/Article/details/gt2jarjtrif.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhixingplan.top/Article/details/gt2awnvayae.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqlvjgre.html

[J09] 时区处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2pbhxonar.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.quarkkingdee.top/Article/details/gt2xvkcogdt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pycfn.com/Article/details/gt2nwctaquc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gt2dwnvssbi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gt2rfriiisu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.316326.xyz/Article/details/gt2kzlurpmg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dianchejie.cn/Article/details/gt2zuhugwqa.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xylfe.cn/Article/details/gt2saiugifh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cqqwz.cn/Article/details/gt2ujopuadu.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258888.top/Article/details/gt2azyvzzuk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxuanxn.top/Article/details/gt2vbrwoqmk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhiwuduotai.top/Article/details/gt2oyfbjsuv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shzxlz.cn/Article/details/gt2yshlmsws.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2rlqdmwxc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.mhx1999.top/Article/details/gt2smsawxvq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gotoacloud.top/Article/details/gt2ahakusio.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gt2wxuvmikq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wtkqkyqa.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2ukucbxcd.html

K. JSON 与序列化
来源：http://dali.guannengcc.top/Article/details/gt2zmoriles.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2jmrmervd.html

[K01] 对象转 JSON 字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2pfcltyyf.html


<!-- 参考信息 -->