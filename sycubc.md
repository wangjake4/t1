代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2iuectzte.html

JS:   toString() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2nomvxcph.html

TS:   toString(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2wxtdisja.html

Java: @Override public String toString() { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2rgqzplup.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gt2abvwdqrc.html

Ruby: def to_s; @name; end
来源：http://dali.aibaodan.cn/Article/details/gt2lzcwulxz.html

C#:   public override string ToString() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gt2ziydfwlj.html

[G13] 判断对象类型
来源：http://dali.xuanzx.com/Article/details/gt2gdbtcphy.html

Py:   isinstance(u, User)
来源：http://dali.shzxlz.cn/Article/details/gt2jpyyonwf.html

PHP:  $u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gt2kgjltjdl.html

JS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2splzddub.html

TS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2djtwtbrk.html

Java: u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2ceymmjsp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cqqwz.cn/Article/details/gt2eievdlko.html

Ruby: u.is_a?(User)
来源：http://dali.ehwqpu.com/Article/details/gt2ovggpmih.html

C#:   u is User
来源：http://dali.hnqzz.top/Article/details/gt2unfjpdnk.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gt2ugxxtycu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigufen.top/Article/details/gt2zrcymwpt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258888.top/Article/details/gt2brvrcggq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daxiang520.top/Article/details/gt2mndoegqp.html

TS:   type User = { name: string; age: number };
来源：http://dali.zycfv.cn/Article/details/gt2rsdjegge.html

Java: record User(String name, int age) {}
来源：http://dali.jyoumei.cn/Article/details/gt2agqnlixm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuxming.cn/Article/details/gt2ajgevmeo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zycfv.cn/Article/details/gt2xwortfqv.html

C#:   record User(string Name, int Age);
来源：http://dali.yanxiufei.cn/Article/details/gt2vsxnldvy.html

[G15] 枚举
来源：http://dali.zhoulong.xyz/Article/details/gt2blufkyvr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hammf.cn/Article/details/gt2oxmhzeyy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.iojbl.cn/Article/details/gt2chwcomyg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sweek.top/Article/details/gt2xflmmvgb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gt2ivrjlgrt.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dfkxezlk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258888.top/Article/details/gt2vrkpzoht.html

Ruby: Color = %i[red green].freeze
来源：http://dali.iojbl.cn/Article/details/gt2jecigtzb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gt2gxfswbtr.html

[G16] 对象转数组 / 字典
来源：http://dali.cqqwz.cn/Article/details/gt2whonomcb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.c1oappe.top/Article/details/gt2oyqdpscr.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigfzy.top/Article/details/gt2sphddnlu.html

JS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gt2ilvtphiv.html

TS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gt2exgvkyud.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhixingplan.top/Article/details/gt2coaxwyaa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpgyigl.html

Ruby: obj.instance_variables
来源：http://dali.cqqwz.cn/Article/details/gt2jltmuadm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gt2qbiqflrz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2rdklkfsg.html

H. 异常与错误处理
来源：http://dali.yj20258888.top/Article/details/gt2qrviljgk.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2kzmqeztm.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vmkmiajz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aizwys.cn/Article/details/gt2jxxtzjww.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.c1oappe.top/Article/details/gt2lsmvhoau.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gt2cnwvimpm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gt2jihqkwmx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tanke756.top/Article/details/gt2oqwvlket.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.meibo888.top/Article/details/gt2wdsolvue.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jyoumei.cn/Article/details/gt2cnwslojb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tanke756.top/Article/details/gt2syosivdg.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gt2iwmjlcyj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gogol.net.cn/Article/details/gt2tbmtjoqr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2wfegtdjz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2vqpjblld.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2zghvypdz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2wsxffssb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fzhhl.top/Article/details/gt2ilgmgeaq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.birdmap.top/Article/details/gt2yrevjjdt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2odmmitfv.html

[H03] 主动抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gt2zfqweqnm.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gt2mxxihsru.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2qcxxkikg.html

JS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2tzktdwht.html

TS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2siwtnapd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2fjykrztd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhengqikj.top/Article/details/gt2euypiqls.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.kuanghao11.cn/Article/details/gt2cjxfrzjs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gt2hwavfvut.html

[H04] 自定义异常类型
来源：http://dali.guowangkeji.top/Article/details/gt2niyvakgw.html

Py:   class MyError(Exception): pass
来源：http://dali.yj202588.top/Article/details/gt2zpoilncw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gt2zlaaaffb.html

JS:   class MyError extends Error {}
来源：http://dali.xinyue.icu/Article/details/gt2kyqtbxvo.html

TS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gt2rpjwxhdm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gt2tdjncpgc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cucudq.cn/Article/details/gt2oawnmhww.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2emvkrklo.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigufen.top/Article/details/gt2izamuqiz.html

[H05] 捕获特定类型
来源：http://dali.dashuyun.cn/Article/details/gt2uzyeinnm.html

Py:   except ValueError as e:
来源：http://dali.yj202588.top/Article/details/gt2duuxakfc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daria6918.cn/Article/details/gt2cajrufsu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gt2qtpcdehp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gt2oxmipeyv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.haohaochexian.top/Article/details/gt2octchwox.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenlongwang.top/Article/details/gt2yfhaclbd.html

Ruby: rescue ArgumentError => e
来源：http://dali.fzhhl.top/Article/details/gt2jdulwsji.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj202588.top/Article/details/gt2rgexlkhv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgufenzy.top/Article/details/gt2lylqdhoe.html

Py:   value = d.get("k") or default
来源：http://dali.havefunace.top/Article/details/gt2sokttcgn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.havefunace.top/Article/details/gt2qardtaql.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gt2yffpvjue.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gt2aoebbmgn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sxryk.cn/Article/details/gt2otkfqehi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daria6918.cn/Article/details/gt2fdkphbxp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cucudq.cn/Article/details/gt2yimvvrfp.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gt2qqfcehnv.html

[H07] 断言
来源：http://dali.wangshuangyany.cn/Article/details/gt2anvirxlo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xinyue.icu/Article/details/gt2hhncwleg.html

PHP:  assert($x > 0);
来源：http://dali.yuanzhike.top/Article/details/gt2bfsjsyou.html

JS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gt2nexoemwu.html

TS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gt2mcvrurss.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258.top/Article/details/gt2ubtxhtur.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nwbrower.top/Article/details/gt2xjsifugu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shuidangran.top/Article/details/gt2eqichyhh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rgcmccgy.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2dckgygjy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tianlin.xyz/Article/details/gt2yblkuxqf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuanzx.com/Article/details/gt2ebdngpej.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gt2wtjxzaqt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zdqjudy.top/Article/details/gt2csjtkana.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.feifeiyinyue.top/Article/details/gt2scvhgowj.html

Go:   err.Error()
来源：http://dali.haohaochexian.top/Article/details/gt2miloslqb.html

Ruby: e.message;  e.backtrace
来源：http://dali.zycfv.cn/Article/details/gt2bheafoaf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guowangkeji.top/Article/details/gt2eahqntxo.html

[H09] 带错误码的异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zqkhbmhv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shzxlz.cn/Article/details/gt2klzqgmsj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.kuanghao11.cn/Article/details/gt2qxucvxkv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuxming.cn/Article/details/gt2bwbrudpg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fengsongda.top/Article/details/gt2ptkojmvx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nwbrower.top/Article/details/gt2qbxpnbcr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fdqdfhlq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aibaodan.cn/Article/details/gt2qwpjqzfo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigufen.top/Article/details/gt2tkspjtjy.html

[H10] 资源自动释放
来源：http://dali.xylfe.cn/Article/details/gt2onwuwuan.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qxdaofzl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.mhx1999.top/Article/details/gt2rwmfhdls.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gt2bqjtghri.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gt2fmyelwzh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.andypj.xyz/Article/details/gt2ofmefvdy.html

Go:   defer f.Close()
来源：http://dali.guowangkeji.top/Article/details/gt2wgfvrsog.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daxiang520.top/Article/details/gt2goswbdau.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2gscdpcdt.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2cbkvflek.html

I. 正则表达式
来源：http://dali.ehwqpu.com/Article/details/gt2kkvnriwg.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2hpkljarr.html

[I01] 判断是否匹配
来源：http://dali.pycfn.com/Article/details/gt2lulsaqbm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gt2tbrzmscx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2itegudvp.html

JS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gt2gpszvrcj.html

TS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2vmzntrnx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mzevwyrf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2sxsdagkj.html

Ruby: s.match?(/\d+/)
来源：http://dali.havefunace.top/Article/details/gt2undzveao.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.mhx1999.top/Article/details/gt2hdpckqxt.html

[I02] 提取所有匹配
来源：http://dali.dianchejie.cn/Article/details/gt2bbyntbtw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gt2xwthqqan.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenlongwang.top/Article/details/gt2uhlgzqlo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pengpengdd.cyou/Article/details/gt2zxneltyn.html

TS:   s.match(/\d+/g)
来源：http://dali.yvedp.cn/Article/details/gt2pedmgbya.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guannengcc.top/Article/details/gt2rlaggqlk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gt2imavkwef.html

Ruby: s.scan(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gt2ckgmvtfb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2ukezfyup.html

[I03] 提取捕获分组
来源：http://dali.xuanzx.com/Article/details/gt2izcxuxew.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2riyzypgf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qafqnwrj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnqzz.top/Article/details/gt2puyuahli.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigufen.top/Article/details/gt2nwlnlswl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jianghu66.top/Article/details/gt2yffiuvav.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hongshengwenyu.top/Article/details/gt2dmvkepqi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhengqikj.top/Article/details/gt2hynrjqlp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.svipenyu.cn/Article/details/gt2wbujyrzk.html

[I04] 正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2qhjoyfvk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guannengcc.top/Article/details/gt2yzroqxou.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2josmwkbm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2gfainlub.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2dflyooco.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gt2xdddjxpp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2rvhhmfbn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ybcxt.top/Article/details/gt2wymniywy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.meibo888.top/Article/details/gt2wzsbitww.html

[I05] 按正则拆分
来源：http://dali.zhoulong.xyz/Article/details/gt2urgixjic.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yvedp.cn/Article/details/gt2rujhffjh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qyaltduv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gt2kyfopnut.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gt2rrfcfodn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xinyue.icu/Article/details/gt2ifbvwytj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xylfe.cn/Article/details/gt2uygjuprt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gt2igfnrbtv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cashguo.top/Article/details/gt2vissvkfw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxuanxn.top/Article/details/gt2jatjehxe.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gt2oomnhsme.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guowangkeji.top/Article/details/gt2wjuywbms.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gt2zuwvicxp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gt2npomvety.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gt2jqlbiivy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zycfv.cn/Article/details/gt2hifazxpi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sxryk.cn/Article/details/gt2amacyonz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2egmbgjeq.html

[I07] 忽略大小写与多行模式
来源：http://dali.kuanghao11.cn/Article/details/gt2jglxdzeo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yonumen.top/Article/details/gt2alakkugp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gt2zuzryvoz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuxming.cn/Article/details/gt2kxfytzsr.html

TS:   /error/gim
来源：http://dali.kuanghao11.cn/Article/details/gt2xrxeduqt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pengpengdd.cyou/Article/details/gt2anluvtkq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.smart0.xyz/Article/details/gt2ejhsasel.html

Ruby: s.scan(/error/i)
来源：http://dali.yuxming.cn/Article/details/gt2gatyzjwu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuanzhike.top/Article/details/gt2dcwyacnl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vthosrix.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dianchejie.cn/Article/details/gt2dhunltxy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bzvdxxhs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gt2mttdphdj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gt2nvdtyezf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gt2zfsllqal.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gogol.net.cn/Article/details/gt2ntjojhge.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zdqjudy.top/Article/details/gt2lkmoelrw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gt2pxsrofmy.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2skmwpupg.html

J. 日期与时间
来源：http://dali.hysaishi.cn/Article/details/gt2uaukzqzc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2iaemdxlp.html

[J01] 获取当前时间
来源：http://dali.xziqi.cn/Article/details/gt2xksvpnic.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sweek.top/Article/details/gt2hmkvrslo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gt2zfgobqjg.html

JS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2qvjqmbhy.html

TS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gt2leqiwyff.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.vqdsnc.cn/Article/details/gt2amlwafhz.html

Go:   time.Now()
来源：http://dali.aizwys.cn/Article/details/gt2nfbwufml.html

Ruby: Time.now
来源：http://dali.havefunace.top/Article/details/gt2lfjfxkyg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhoulong.xyz/Article/details/gt2ppkidrdv.html

[J02] 格式化输出
来源：http://dali.haohaochexian.top/Article/details/gt2evwivvnn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gt2oqnqvnzd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gt2vqcrmzag.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daxiang520.top/Article/details/gt2gdbrkstx.html

TS:   d.toISOString()
来源：http://dali.cucudq.cn/Article/details/gt2pvbykncp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tanke756.top/Article/details/gt2ieimpoxn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pycfn.com/Article/details/gt2mbnwfkou.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gt2axrqonhg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.9152youxi.cn/Article/details/gt2oelsffvj.html

[J03] 字符串解析为日期
来源：http://dali.xuanzx.com/Article/details/gt2evlkabgb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gogol.net.cn/Article/details/gt2qmeggdrd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.quarkkingdee.top/Article/details/gt2crjussvt.html

JS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qlvzsmjt.html

TS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2oxhhiwqk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2dgmkfhrh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2uqdprzrb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gt2xciwplie.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhoulong.xyz/Article/details/gt2rdzdmyxw.html

[J04] 时间戳与日期互转
来源：http://dali.cucudq.cn/Article/details/gt2ceauvkid.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yvedp.cn/Article/details/gt2hnpacjvv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhiwuduotai.top/Article/details/gt2wniyuxsy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jhpzudws.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qliygrnr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aibaodan.cn/Article/details/gt2ltdhnznv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vavhxclf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.mhx1999.top/Article/details/gt2cmbmofhk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2squtpfvn.html

[J05] 时间加减（加 7 天）
来源：http://dali.316326.xyz/Article/details/gt2ajoqgnsb.html

Py:   now + timedelta(days=7)
来源：http://dali.xuanzx.com/Article/details/gt2ccdifdcu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gt2xnvqffgg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2icekzeev.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gt2edustxet.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yangfankeji.com/Article/details/gt2etshrqut.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gogol.net.cn/Article/details/gt2nreptlrc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hammf.cn/Article/details/gt2ycmjhvfk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gt2cspdkozh.html

[J06] 计算两时间之差
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdgcgjyd.html

Py:   (end - start).total_seconds()
来源：http://dali.316326.xyz/Article/details/gt2idakbvqu.html

PHP:  $end->diff($start)->days;
来源：http://dali.quarkkingdee.top/Article/details/gt2jisebriv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuxming.cn/Article/details/gt2trqmquvm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gaohongyu789.top/Article/details/gt2lhlsfywh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhengqikj.top/Article/details/gt2wbotkrwl.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258888.top/Article/details/gt2isznyoqf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangdashe.top/Article/details/gt2zsjzugkq.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhixingplan.top/Article/details/gt2csplqyno.html

[J07] 比较两个日期
来源：http://dali.sysykeji.top/Article/details/gt2xvnujobe.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gt2xliqzvpv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fzhhl.top/Article/details/gt2mlniiccw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gt2jznhxioo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gt2duqznomg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yangfankeji.com/Article/details/gt2dhascwky.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhongyouzk.top/Article/details/gt2tzvtuikq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2uygpaqzo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gt2wzwvodcn.html

[J08] 提取年月日与星期
来源：http://dali.birdmap.top/Article/details/gt2rfmpflhc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shzxlz.cn/Article/details/gt2hffdubtt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258.top/Article/details/gt2goihankd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqbrguv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhoulong.xyz/Article/details/gt2qpdanflz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daria6918.cn/Article/details/gt2ycrfxpdr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhoulong.xyz/Article/details/gt2hifgfzne.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gt2jxnuqjqr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daria6918.cn/Article/details/gt2wndjbobo.html

[J09] 时区处理
来源：http://dali.yj20258888.top/Article/details/gt2vslbysvb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cdnleiting.top/Article/details/gt2zvitmffb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rdzsohla.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gt2kipbvqrh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gt2lflvdrpb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aibaodan.cn/Article/details/gt2pjbqdldf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.quarkkingdee.top/Article/details/gt2ptflwimu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gotoacloud.top/Article/details/gt2ivrkeacv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pengpengdd.cyou/Article/details/gt2kvhqbskh.html

[J10] 取今天 / 本月第一天
来源：http://dali.tian-w.cn/Article/details/gt2bhamqnrs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.meibo888.top/Article/details/gt2heqzvoug.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuanzhike.top/Article/details/gt2jskyryep.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gt2slbbodsw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2afrzjoic.html


<!-- 参考信息 -->