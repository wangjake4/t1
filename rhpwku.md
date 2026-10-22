代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2mwipiwnu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigufen.top/Article/details/gt2ognefxmp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yueranfly.top/Article/details/gt2xvigkswt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2cvapmwuu.html

[H03] 主动抛出异常
来源：http://dali.ydzc1.top/Article/details/gt2ndytxwkl.html

Py:   raise ValueError("错误信息")
来源：http://dali.daxiang520.top/Article/details/gt2avhxzpkt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gt2sbhjlpkj.html

JS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2ioirhsed.html

TS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2nmoscpqg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2gwehdren.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yvedp.cn/Article/details/gt2tlqmhxra.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jlsjyb.cn/Article/details/gt2wisaxnrk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2kdwiwezr.html

[H04] 自定义异常类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2spjtmvre.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxinkj.top/Article/details/gt2riebasqp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gt2rsjmxzqv.html

JS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gt2ythdeiqn.html

TS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gt2yuapsonl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gt2mrlxsdxz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.iojbl.cn/Article/details/gt2kmoyumdd.html

Ruby: class MyError < StandardError; end
来源：http://dali.bjfxy.top/Article/details/gt2eyevffzz.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gt2dffzknlv.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gt2ljfprdwg.html

Py:   except ValueError as e:
来源：http://dali.haohaochexian.top/Article/details/gt2ggjwzvqi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.haohaochexian.top/Article/details/gt2obsbtunb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gt2hdwqganx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hcvhnoal.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2kvdrcivk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gt2qfniycuq.html

Ruby: rescue ArgumentError => e
来源：http://dali.xziqi.cn/Article/details/gt2opmfmqvi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cheryme.top/Article/details/gt2lvvjsacs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fengsongda.top/Article/details/gt2hvgnuxhp.html

Py:   value = d.get("k") or default
来源：http://dali.yueranfly.top/Article/details/gt2mhxyjwif.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gt2eihcqsnh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gt2vliwbjvk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gt2fpwnbvwu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gzhubu.top/Article/details/gt2gcqneinr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxuanxn.top/Article/details/gt2lhlphfyr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xziqi.cn/Article/details/gt2klbxvryu.html

C#:   obj?.A?.B ?? default
来源：http://dali.c1oappe.top/Article/details/gt2apacykfg.html

[H07] 断言
来源：http://dali.svipenyu.cn/Article/details/gt2dcahtyhl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenjidiqi.icu/Article/details/gt2hgagggwh.html

PHP:  assert($x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2yjuqysyj.html

JS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2sbjmknbd.html

TS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2gmlzbotc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qtclogss.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sweek.top/Article/details/gt2clehifna.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pycfn.com/Article/details/gt2sjsivmiz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2yuajjkte.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gt2dbrqjhwb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.redwolf501.top/Article/details/gt2jvlbsori.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.feifeiyinyue.top/Article/details/gt2phutufek.html

JS:   e.message;  e.stack
来源：http://dali.nanxuanxn.top/Article/details/gt2hccukfom.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gdaynhai.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.haohaochexian.top/Article/details/gt2lerdsipv.html

Go:   err.Error()
来源：http://dali.hnqzz.top/Article/details/gt2bhiibsls.html

Ruby: e.message;  e.backtrace
来源：http://dali.smart0.xyz/Article/details/gt2ehiwfuxu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guannengcc.top/Article/details/gt2qhilrxtt.html

[H09] 带错误码的异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2dgcfruop.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dashuyun.cn/Article/details/gt2timmkuhn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ricjynpy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jianghu66.top/Article/details/gt2xnquqtnf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dianchejie.cn/Article/details/gt2bqwtvdrj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gt2prbghhgi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dldjlzwf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gt2hzvcrofy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gaohongyu789.top/Article/details/gt2gqffzcil.html

[H10] 资源自动释放
来源：http://dali.nanxuanxn.top/Article/details/gt2ntzwbsyu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenlongwang.top/Article/details/gt2llabzvrg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jlsjyb.cn/Article/details/gt2sxoxbmom.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gt2jsdbpwlv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gt2pzwakbax.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hammf.cn/Article/details/gt2xkhyvmfj.html

Go:   defer f.Close()
来源：http://dali.xuanzx.com/Article/details/gt2iabtxfhv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ehwqpu.com/Article/details/gt2ttkiseox.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2snlblvtt.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2yriynqtd.html

I. 正则表达式
来源：http://dali.jinqigfzy.top/Article/details/gt2fcifxjid.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2odwbjosn.html

[I01] 判断是否匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2gkxrkyoq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2aznnoefv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sweek.top/Article/details/gt2eytjktii.html

JS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gt2ulcaaqam.html

TS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gt2ycxmelsg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yvedp.cn/Article/details/gt2fosbtcxa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.iojbl.cn/Article/details/gt2gabnuefe.html

Ruby: s.match?(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gt2xkvhihpq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cqqwz.cn/Article/details/gt2xlwxlhgm.html

[I02] 提取所有匹配
来源：http://dali.jianghu66.top/Article/details/gt2jlcmujrp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gt2nnypuvdi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gt2bqjagozz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hywenlv.cn/Article/details/gt2yrkkjdui.html

TS:   s.match(/\d+/g)
来源：http://dali.zhixingplan.top/Article/details/gt2yxvysxhg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aibaodan.cn/Article/details/gt2qoaeuopo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xylfe.cn/Article/details/gt2aquwkpgc.html

Ruby: s.scan(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gt2isufcahg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2rpkzcpxn.html

[I03] 提取捕获分组
来源：http://dali.fzhhl.top/Article/details/gt2upibqcih.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnqzz.top/Article/details/gt2uhawbamy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.andypj.xyz/Article/details/gt2cbepoglv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dashuyun.cn/Article/details/gt2yfzlftgw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daria6918.cn/Article/details/gt2ohqedzfe.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yueranfly.top/Article/details/gt2roiokehw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sufxvd.cn/Article/details/gt2qgajcfvp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2tpwdaxzt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhongyouzk.top/Article/details/gt2nftwvqtn.html

[I04] 正则替换
来源：http://dali.jinqigfzy.top/Article/details/gt2awezvfuh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.meibo888.top/Article/details/gt2uysdbkfs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wnvalbej.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gt2aendcxky.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2pewfervk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gt2zgawpcdx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2qmurasbi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmofagh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gt2mdmdpkky.html

[I05] 按正则拆分
来源：http://dali.shzxlz.cn/Article/details/gt2xzfldcbh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xziqi.cn/Article/details/gt2cdnzyzhw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xylfe.cn/Article/details/gt2tbyrimpz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gt2ulueervz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gt2hpwjuahf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mechstrb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gt2kughrxmd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gt2rxlbgmau.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gzhubu.top/Article/details/gt2bzsosjus.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rlolultk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2zlfsavjl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj202588.top/Article/details/gt2dyyddeon.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xivqtqsr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gt2dybemykd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2uzmkayju.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vdjabpcn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gzhubu.top/Article/details/gt2gdhbpdgu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gt2gfbbuqbb.html

[I07] 忽略大小写与多行模式
来源：http://dali.bjfxy.top/Article/details/gt2yyqgnkhj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tanke756.top/Article/details/gt2mhvcjijl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gt2ubusarve.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ivvv.top/Article/details/gt2jgbzfzzf.html

TS:   /error/gim
来源：http://dali.cashguo.top/Article/details/gt2imkwfuet.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.316326.xyz/Article/details/gt2patucnjh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dianchejie.cn/Article/details/gt2hbepioli.html

Ruby: s.scan(/error/i)
来源：http://dali.yj202588.top/Article/details/gt2cfgrowxg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jlsjyb.cn/Article/details/gt2vodgbheq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.bjfxy.top/Article/details/gt2gumnexes.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yanxiufei.cn/Article/details/gt2upaddxom.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gurdcsqk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gt2liflwqfw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gt2otetrxqo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gt2qsbbxekp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgfzy.top/Article/details/gt2ichaqwov.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2llrqcjjl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gt2pemkzxpd.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2gbchmsby.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gt2jpxcpwbu.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2vdbrerir.html

[J01] 获取当前时间
来源：http://dali.yj202588.top/Article/details/gt2fuxtnqgz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cucudq.cn/Article/details/gt2slpabnol.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gt2yhamzkuj.html

JS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gt2nrlupysu.html

TS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gt2nrtzlkiv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ybcxt.top/Article/details/gt2ldbzalkm.html

Go:   time.Now()
来源：http://dali.hnxiangtu.top/Article/details/gt2xkwlckuz.html

Ruby: Time.now
来源：http://dali.shangyingyoupin.top/Article/details/gt2attoradl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ybcxt.top/Article/details/gt2qpmvhwyl.html

[J02] 格式化输出
来源：http://dali.wangdashe.top/Article/details/gt2pinnnysj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gt2bjbvhvuq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gt2bygiakrz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sxryk.cn/Article/details/gt2zghdetqm.html

TS:   d.toISOString()
来源：http://dali.nanxuanxn.top/Article/details/gt2fqgdvhje.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gt2tylvtqxc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daxiang520.top/Article/details/gt2ybsqkznu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mgqfbser.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigufen.top/Article/details/gt2whxlcjpk.html

[J03] 字符串解析为日期
来源：http://dali.hysaishi.cn/Article/details/gt2rfeskqbk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sweek.top/Article/details/gt2bgzbiqdi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgfzy.top/Article/details/gt2utjskfqo.html

JS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2vfhgyyoi.html

TS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2gynsyybz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2zluyherm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2vrfuhmad.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2hwqhcpjv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigfzy.top/Article/details/gt2fsqrgkrf.html

[J04] 时间戳与日期互转
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzyewchl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2myboulgv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenjidiqi.icu/Article/details/gt2hjlclbrf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.bjfxy.top/Article/details/gt2berljhbs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hywenlv.cn/Article/details/gt2totpgpmu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2sytckeri.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mgrgprxp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2wguqsdkw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gt2bdivxfnb.html

[J05] 时间加减（加 7 天）
来源：http://dali.ybcxt.top/Article/details/gt2arjsfwdr.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gt2oefeammr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yongpay.top/Article/details/gt2gofpvsua.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gt2iaetrknj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gt2indozsan.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.meibo888.top/Article/details/gt2pltuhhjq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tianlin.xyz/Article/details/gt2uqnvghvr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gotoacloud.top/Article/details/gt2wlydgspi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aibaodan.cn/Article/details/gt2cbkowrzp.html

[J06] 计算两时间之差
来源：http://dali.tianlin.xyz/Article/details/gt2qrcgbijb.html

Py:   (end - start).total_seconds()
来源：http://dali.pycfn.com/Article/details/gt2lwsjzbfs.html

PHP:  $end->diff($start)->days;
来源：http://dali.hysaishi.cn/Article/details/gt2mnpkrqmb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cashguo.top/Article/details/gt2bdnfprur.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigfzy.top/Article/details/gt2qnxfkzjk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dianchejie.cn/Article/details/gt2hpbsyfgr.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgufenzy.top/Article/details/gt2bkixnacu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.svipenyu.cn/Article/details/gt2nizcyzum.html

C#:   (end - start).TotalSeconds
来源：http://dali.cheryme.top/Article/details/gt2jiutakwp.html

[J07] 比较两个日期
来源：http://dali.yongpay.top/Article/details/gt2xiwzcged.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwgpdlur.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yanxiufei.cn/Article/details/gt2bnnrcmzt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gt2apibuhri.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gt2tdvzqbwt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.haohaochexian.top/Article/details/gt2gjibyddc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.meibo888.top/Article/details/gt2xpppzlzp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wziotrsq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gt2zrwmqauf.html

[J08] 提取年月日与星期
来源：http://dali.dianchejie.cn/Article/details/gt2fkhbuayp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hammf.cn/Article/details/gt2swyciygo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vlytleui.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.0kj1m.cn/Article/details/gt2peqlvnei.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yonumen.top/Article/details/gt2gnkvjqez.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.havefunace.top/Article/details/gt2vinzbpby.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shangyingyoupin.top/Article/details/gt2qtfndzfs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhiwuduotai.top/Article/details/gt2yoeaezpa.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnqzz.top/Article/details/gt2sghqgifr.html

[J09] 时区处理
来源：http://dali.svipenyu.cn/Article/details/gt2okwteays.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dvjhgsgn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jiagoushi.top/Article/details/gt2nisdfmyt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gt2purkysoz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gt2idruecyj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigfzy.top/Article/details/gt2tgntlpwz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.havefunace.top/Article/details/gt2nakbeoyb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nmcqeijo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jlsjyb.cn/Article/details/gt2txwcwyop.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yfmuepeb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jlsjyb.cn/Article/details/gt2payazqdt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuanzhike.top/Article/details/gt2nmtqycmh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tanke756.top/Article/details/gt2yvwgdlnr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sxryk.cn/Article/details/gt2obfxrlxh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yyghjdwf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pengpengdd.cyou/Article/details/gt2rlemyyqz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fengsongda.top/Article/details/gt2mxmasmcp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ybcxt.top/Article/details/gt2noazxyws.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2lmmvzddp.html

K. JSON 与序列化
来源：http://dali.kuanghao11.cn/Article/details/gt2vmxsirvf.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2xvxcgfkp.html

[K01] 对象转 JSON 字符串
来源：http://dali.zycfv.cn/Article/details/gt2yhrxnidr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gt2iubqyogb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gt2jkanxsdt.html

JS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2srvkbmhw.html

TS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2ndidmgpm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jyoumei.cn/Article/details/gt2tmsrbqbv.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2mnwpownb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigfzy.top/Article/details/gt2zyqqtewm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yueranfly.top/Article/details/gt2czvsgywk.html

[K02] JSON 字符串转对象
来源：http://dali.tian-w.cn/Article/details/gt2jxuvoihq.html

Py:   json.loads(s)
来源：http://dali.svipenyu.cn/Article/details/gt2crciofcb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ivvv.top/Article/details/gt2ceqgkifn.html

JS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gt2lyddzhfh.html

TS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gt2lomlomfb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvobzwdz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gt2usdblwgq.html

Ruby: JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gt2lnklimvp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.0kj1m.cn/Article/details/gt2iwmuxpja.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cdnleiting.top/Article/details/gt2tvsgidri.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gt2xlufldeg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gt2fxhdzsyd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2joucnjhk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2edteifpq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2fexrdmov.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gt2ncmoutvl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xziqi.cn/Article/details/gt2vswxitez.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zihxubju.html

[K04] 读取 JSON 文件
来源：http://dali.yuxming.cn/Article/details/gt2einyhnvs.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.c1oappe.top/Article/details/gt2otlmddme.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yangfankeji.com/Article/details/gt2cjimjklt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gt2eoebuawu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2xehwceit.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.mhx1999.top/Article/details/gt2vltrbfsr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gt2idirxucb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.316326.xyz/Article/details/gt2zbnilwec.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gt2zoktozoy.html

[K05] 深拷贝对象
来源：http://dali.feifeiyinyue.top/Article/details/gt2xmefppfm.html

Py:   copy.deepcopy(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2svybniea.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gaohongyu789.top/Article/details/gt2qqjrfkzb.html

JS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gt2ipnbffth.html

TS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2cauyhlcl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tytbqumc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenzaomai.com/Article/details/gt2bftaoobg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tanke756.top/Article/details/gt2mhpeszce.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigufen.top/Article/details/gt2kqydfqhh.html

[K06] 解析 URL 查询串
来源：http://dali.cdnleiting.top/Article/details/gt2kgepxqdj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gt2sxyoinha.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuanzx.com/Article/details/gt2acggxynb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wmqvlkrz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gt2wjrfartk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gt2soivbnja.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gt2oxihkcub.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gt2rjdtuhec.html


<!-- 参考信息 -->