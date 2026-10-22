代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.xuanzx.com/Article/details/gt2kvzoirvg.html

[G15] 枚举
来源：http://dali.dashuyun.cn/Article/details/gt2rpbrvapz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.quarkkingdee.top/Article/details/gt2kprvlcgu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.haohaochexian.top/Article/details/gt2ibonjsze.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.9152youxi.cn/Article/details/gt2dotovpij.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gt2tsvywyzo.html

Java: enum Color { RED, GREEN }
来源：http://dali.xylfe.cn/Article/details/gt2lzqbnxzv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnqzz.top/Article/details/gt2ytfrmjda.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cheryme.top/Article/details/gt2ojdvlbhm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gt2wvbsjlbx.html

[G16] 对象转数组 / 字典
来源：http://dali.havefunace.top/Article/details/gt2xiqyoyfo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hammf.cn/Article/details/gt2qqlkrcnh.html

PHP:  get_object_vars($obj);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijlqmjrh.html

JS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gt2jqykfmst.html

TS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gt2portbxjr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhixingplan.top/Article/details/gt2onrvflry.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aibaodan.cn/Article/details/gt2qrsvqpjy.html

Ruby: obj.instance_variables
来源：http://dali.gotoacloud.top/Article/details/gt2jfayxwhu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gt2nyqryohf.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2dkoapwmx.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2egfznjnt.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2snjkqmov.html

[H01] try / catch 基础
来源：http://dali.chenjidiqi.icu/Article/details/gt2fujqrmiu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nkmpcgtb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zdqjudy.top/Article/details/gt2qankxcvx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gt2fnqemmbx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dtybahxx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shuidangran.top/Article/details/gt2dowosyrl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxuanxn.top/Article/details/gt2ojmnbnrs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gt2jpuuuufx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.svipenyu.cn/Article/details/gt2yrkdchax.html

[H02] finally / ensure 收尾
来源：http://dali.haohaochexian.top/Article/details/gt2boaxbfnh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuxming.cn/Article/details/gt2ufjnxvic.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2qcuhakjt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2jjolpglj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2hbdysgka.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2tucwfxhu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gt2bprxjwcb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.redwolf501.top/Article/details/gt2heppzdhr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2byunuzwz.html

[H03] 主动抛出异常
来源：http://dali.gotoacloud.top/Article/details/gt2bileetdi.html

Py:   raise ValueError("错误信息")
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdtqyzxv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2robgbizv.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2ijedbvmo.html

TS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2jpnlkazu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2xurqsoow.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jlsjyb.cn/Article/details/gt2xcvfjhiw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gt2ijarnobq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gt2phkujjbo.html

[H04] 自定义异常类型
来源：http://dali.redwolf501.top/Article/details/gt2msgftvke.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gt2fvdghnar.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gt2qcjidjpb.html

JS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gt2hgdrwpyl.html

TS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gt2fvmpcivn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gt2fvrcvccm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhongyouzk.top/Article/details/gt2ggpmerre.html

Ruby: class MyError < StandardError; end
来源：http://dali.yueranfly.top/Article/details/gt2yumjwddo.html

C#:   class MyException : Exception {}
来源：http://dali.aizwys.cn/Article/details/gt2omyuxxup.html

[H05] 捕获特定类型
来源：http://dali.gotoacloud.top/Article/details/gt2iirrlqmj.html

Py:   except ValueError as e:
来源：http://dali.aizwys.cn/Article/details/gt2koojsxhc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dashuyun.cn/Article/details/gt2fivkntlq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xkvfsbpr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2hfmbovub.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2vetgvfgp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fbzzvbvo.html

Ruby: rescue ArgumentError => e
来源：http://dali.sxryk.cn/Article/details/gt2cfywurqw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gt2ssvkoydi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenjidiqi.icu/Article/details/gt2cmutesln.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangtech.top/Article/details/gt2frkfcscx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gt2unodiuqd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gt2ijnayttv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gt2vapuwbtp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gogol.net.cn/Article/details/gt2erwvooxk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj202588.top/Article/details/gt2hlbtcfon.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ybcxt.top/Article/details/gt2nczpxfkc.html

C#:   obj?.A?.B ?? default
来源：http://dali.yueranfly.top/Article/details/gt2dxuftefb.html

[H07] 断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qvusqfcu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gzhubu.top/Article/details/gt2ffmthrfa.html

PHP:  assert($x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2qarqwlcg.html

JS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2ixzeujnz.html

TS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gt2fqbztipa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shangyingyoupin.top/Article/details/gt2lcqscxiv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sufxvd.cn/Article/details/gt2gmstzxpj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258888.top/Article/details/gt2nasfxnke.html

C#:   Debug.Assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gt2flgndrkw.html

[H08] 获取错误信息与堆栈
来源：http://dali.xylfe.cn/Article/details/gt2jbppkoxs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hammf.cn/Article/details/gt2wahranfq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.quarkkingdee.top/Article/details/gt2nxwsnbzp.html

JS:   e.message;  e.stack
来源：http://dali.nanxinkj.top/Article/details/gt2tbpyuqep.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zdqjudy.top/Article/details/gt2mtroefaa.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhixingplan.top/Article/details/gt2gmrwiexk.html

Go:   err.Error()
来源：http://dali.cheryme.top/Article/details/gt2jmemdpyp.html

Ruby: e.message;  e.backtrace
来源：http://dali.tanke756.top/Article/details/gt2ykmyhtnj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pycfn.com/Article/details/gt2hnhozkge.html

[H09] 带错误码的异常
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gkjnseoe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangdashe.top/Article/details/gt2gdyfuuud.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhengqikj.top/Article/details/gt2pshmaigc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gotoacloud.top/Article/details/gt2wwuhyzlf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenlongwang.top/Article/details/gt2ncuzsngu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.316326.xyz/Article/details/gt2noavoqof.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vvcasowx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ekowqjph.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhixingplan.top/Article/details/gt2pteieetk.html

[H10] 资源自动释放
来源：http://dali.cdnleiting.top/Article/details/gt2rbteioyx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yangfankeji.com/Article/details/gt2zwhhkewg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sxryk.cn/Article/details/gt2opxiagfp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gt2kimzbazk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2splbznpo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.c1oappe.top/Article/details/gt2mepvimtd.html

Go:   defer f.Close()
来源：http://dali.shuidangran.top/Article/details/gt2glqizepg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.vqdsnc.cn/Article/details/gt2sdciovrf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2onpvzifv.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2scyfafns.html

I. 正则表达式
来源：http://dali.chenzaomai.com/Article/details/gt2ewfjoiag.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2xaetdkue.html

[I01] 判断是否匹配
来源：http://dali.iojbl.cn/Article/details/gt2qmfpjzzd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gt2vqatobgm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2okuxbcdd.html

JS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gt2jftmhlus.html

TS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gt2saxjupyz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.kuanghao11.cn/Article/details/gt2ignyqfds.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ivvv.top/Article/details/gt2zlkcefst.html

Ruby: s.match?(/\d+/)
来源：http://dali.cashguo.top/Article/details/gt2zfbcnwhu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgfzy.top/Article/details/gt2apsprfsm.html

[I02] 提取所有匹配
来源：http://dali.hammf.cn/Article/details/gt2liwyreth.html

Py:   re.findall(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gt2gkhkomgw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cucudq.cn/Article/details/gt2zcqeqoln.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.vqdsnc.cn/Article/details/gt2myyvivzj.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258888.top/Article/details/gt2idnisadk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.daxiang520.top/Article/details/gt2tunhozfy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gt2wosklmfr.html

Ruby: s.scan(/\d+/)
来源：http://dali.ivvv.top/Article/details/gt2bgdfygfe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ohyngecq.html

[I03] 提取捕获分组
来源：http://dali.jinqigfzy.top/Article/details/gt2jootyrly.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2rzlpvzgx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2awrfpajt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.c1oappe.top/Article/details/gt2rvfxjwse.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangdashe.top/Article/details/gt2hogoefdu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cqqwz.cn/Article/details/gt2ljbwnspv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.smart0.xyz/Article/details/gt2ymjqyhzb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nwbrower.top/Article/details/gt2emuvwrjo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sysykeji.top/Article/details/gt2pdbcqscn.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbjanal.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuanzhike.top/Article/details/gt2gzyxakum.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2lqxniigp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2baqcofpp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gt2djdudxvi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gt2aatzbqnz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.fengsongda.top/Article/details/gt2kzeovsvn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2znokrxmx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gt2xxhfvbao.html

[I05] 按正则拆分
来源：http://dali.zhengqikj.top/Article/details/gt2wdlcqksb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tianlin.xyz/Article/details/gt2uhnrxrjj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2pzbpphdo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gt2uioddhly.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gt2hjxlaixd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.redwolf501.top/Article/details/gt2beozjzml.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sxryk.cn/Article/details/gt2mwnbtrrr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gt2gsfrbnga.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dianchejie.cn/Article/details/gt2hiupprzg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yanxiufei.cn/Article/details/gt2cvlfzcpq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gt2rtqfxvth.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pycfn.com/Article/details/gt2uittkaax.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gt2gdmvulqd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gt2tayhmjxv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gt2mhnwpsxn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cucudq.cn/Article/details/gt2nrfhqtdn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hywenlv.cn/Article/details/gt2jajsdfnw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cjgrnjtr.html

[I07] 忽略大小写与多行模式
来源：http://dali.tianlin.xyz/Article/details/gt2bknhrmrz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fczvmizu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gt2nhbcnowi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.kuanghao11.cn/Article/details/gt2zvmuphns.html

TS:   /error/gim
来源：http://dali.sweek.top/Article/details/gt2ureupkza.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cheryme.top/Article/details/gt2pgnmwlco.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.bjfxy.top/Article/details/gt2xbftsoyo.html

Ruby: s.scan(/error/i)
来源：http://dali.zhongyouzk.top/Article/details/gt2giilavhi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aibaodan.cn/Article/details/gt2bpmepzmv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.havefunace.top/Article/details/gt2kerjtlna.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gzhubu.top/Article/details/gt2tcqxnyvq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gt2lnabsudx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gt2yojscoci.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gt2buundbmj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwiiakam.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2smsgvudw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuanzx.com/Article/details/gt2ihdcwgpb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gt2letimxwa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2olranjzd.html

J. 日期与时间
来源：http://dali.bjfxy.top/Article/details/gt2spdglgck.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2pgpyhqsb.html

[J01] 获取当前时间
来源：http://dali.jlsjyb.cn/Article/details/gt2zdczrkgr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vljhhrjr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gt2urupooop.html

JS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gt2wwddltpx.html

TS:   new Date();  Date.now()
来源：http://dali.yangfankeji.com/Article/details/gt2bhhhtkmw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxuanxn.top/Article/details/gt2dlpjhass.html

Go:   time.Now()
来源：http://dali.iojbl.cn/Article/details/gt2bopkqtxy.html

Ruby: Time.now
来源：http://dali.316326.xyz/Article/details/gt2liqeqypu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yangfankeji.com/Article/details/gt2lvwsjyxo.html

[J02] 格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2cukvexvt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gt2sslvowvx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gt2ttbpcxmx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gotoacloud.top/Article/details/gt2fgmwcvvm.html

TS:   d.toISOString()
来源：http://dali.kuanghao11.cn/Article/details/gt2mcnofuyr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ydzc1.top/Article/details/gt2ebzruecn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgfzy.top/Article/details/gt2xingulko.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gt2bttpjnvw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jyoumei.cn/Article/details/gt2zrzdvmvj.html

[J03] 字符串解析为日期
来源：http://dali.yj202588.top/Article/details/gt2knmbyzpf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.redwolf501.top/Article/details/gt2wxkyfyte.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shangyingyoupin.top/Article/details/gt2rygvtelt.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2xfhojvds.html

TS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2ehksaylx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gt2lrzjgiux.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2szpgjxyx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2fzkinvrr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigfzy.top/Article/details/gt2hycckxxg.html

[J04] 时间戳与日期互转
来源：http://dali.zdqjudy.top/Article/details/gt2ebjpmygc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj202588.top/Article/details/gt2nrfywalf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xinyue.icu/Article/details/gt2carqrptd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guannengcc.top/Article/details/gt2dbfclwks.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tian-w.cn/Article/details/gt2pfidknyt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2dqeevdxo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2jdhfqlbl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gt2grjlgkuj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.316326.xyz/Article/details/gt2chxjsole.html

[J05] 时间加减（加 7 天）
来源：http://dali.havefunace.top/Article/details/gt2yeanmihj.html

Py:   now + timedelta(days=7)
来源：http://dali.mhx1999.top/Article/details/gt2qpiutazt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fengsongda.top/Article/details/gt2dlpkxbrn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gt2kohrdifs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gt2kpzxywtg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xezxnvdb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aibaodan.cn/Article/details/gt2vgdfmjbf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258.top/Article/details/gt2eoycmyve.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj202588.top/Article/details/gt2daidrflx.html

[J06] 计算两时间之差
来源：http://dali.havefunace.top/Article/details/gt2hptacxut.html

Py:   (end - start).total_seconds()
来源：http://dali.mhx1999.top/Article/details/gt2edobekkm.html

PHP:  $end->diff($start)->days;
来源：http://dali.smart0.xyz/Article/details/gt2bmuxbmqs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuxming.cn/Article/details/gt2ydzzkgzt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhoulong.xyz/Article/details/gt2ksiqqwce.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hammf.cn/Article/details/gt2bojkmamb.html

Go:   end.Sub(start).Hours()
来源：http://dali.fzhhl.top/Article/details/gt2mjelfzbc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dianchejie.cn/Article/details/gt2arxqthmo.html

C#:   (end - start).TotalSeconds
来源：http://dali.yanxiufei.cn/Article/details/gt2pqgvdpef.html

[J07] 比较两个日期
来源：http://dali.bjfxy.top/Article/details/gt2elxdqoaw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gt2gxoqwjne.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cdnleiting.top/Article/details/gt2qrqtcyex.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gt2yerolgeb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gt2ydvyybme.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.kuanghao11.cn/Article/details/gt2ylcllyow.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhixingplan.top/Article/details/gt2dvhpzkdm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gt2qekjriwk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gt2idecskcd.html

[J08] 提取年月日与星期
来源：http://dali.yj202588.top/Article/details/gt2jezqiqyd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jlsjyb.cn/Article/details/gt2mxmxosym.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tianlin.xyz/Article/details/gt2escjmfxf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qxklywop.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daxiang520.top/Article/details/gt2eynseqnv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigufen.top/Article/details/gt2bijienju.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.snrcjt.cn/Article/details/gt2zftglner.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dianchejie.cn/Article/details/gt2bpowzhfa.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.316326.xyz/Article/details/gt2mebpgikl.html

[J09] 时区处理
来源：http://dali.hongshengwenyu.top/Article/details/gt2qxunvyfo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dashuyun.cn/Article/details/gt2mohlovzk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.snrcjt.cn/Article/details/gt2bposfuut.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gt2vglnkhns.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gt2lsdqdbrg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.9152youxi.cn/Article/details/gt2gymtjtax.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.9152youxi.cn/Article/details/gt2etnihblf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.quarkkingdee.top/Article/details/gt2corbrzto.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangdashe.top/Article/details/gt2dmxdsejg.html

[J10] 取今天 / 本月第一天
来源：http://dali.fengsongda.top/Article/details/gt2majldxvb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgfzy.top/Article/details/gt2npustywl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jyoumei.cn/Article/details/gt2uusdzvij.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhvsoohy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cucudq.cn/Article/details/gt2vwkaiamv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gt2wrxwjwdr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.mhx1999.top/Article/details/gt2knygohaf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuetiantiany.cn/Article/details/gt2heolitgd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2akxuqowo.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2mkqmhabi.html

K. JSON 与序列化
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jxftwxnl.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2ivubpolp.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxinkj.top/Article/details/gt2bdscoivl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gt2tohifths.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2riicsbis.html

JS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gt2smnpjoyn.html

TS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2smiicysq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigfzy.top/Article/details/gt2ndwtrgmq.html

Go:   json.Marshal(obj)
来源：http://dali.hammf.cn/Article/details/gt2ncvmfayh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuanzx.com/Article/details/gt2rnhykhfv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2zogikxof.html

[K02] JSON 字符串转对象
来源：http://dali.jianghu66.top/Article/details/gt2bxwmmggm.html

Py:   json.loads(s)
来源：http://dali.zycfv.cn/Article/details/gt2nwssgrmo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sysykeji.top/Article/details/gt2zdnrioae.html

JS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gt2xqhkstbm.html

TS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gt2crlbpvjq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yueranfly.top/Article/details/gt2gdxvavsl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gt2qcbiuzyh.html

Ruby: JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rkgkdmxl.html


<!-- 参考信息 -->