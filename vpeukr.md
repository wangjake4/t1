代发 wailian999

[H03] 主动抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gt2opsppeje.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhixingplan.top/Article/details/gt2bwwondom.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2ejpaqbua.html

JS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2lharhvfd.html

TS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ltqcscgz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2zoupnvrt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sufxvd.cn/Article/details/gt2eprkhqid.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jianghu66.top/Article/details/gt2kuwnivic.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2dmliqhjl.html

[H04] 自定义异常类型
来源：http://dali.316326.xyz/Article/details/gt2egfcneyz.html

Py:   class MyError(Exception): pass
来源：http://dali.pengpengdd.cyou/Article/details/gt2smatcsax.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gt2ybjljkbc.html

JS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gt2wrqxvpew.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2krcrxwst.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gt2lqkuirqg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gt2dxjkybxj.html

Ruby: class MyError < StandardError; end
来源：http://dali.nwbrower.top/Article/details/gt2ohhhhwgu.html

C#:   class MyException : Exception {}
来源：http://dali.zhengqikj.top/Article/details/gt2ipnyudpq.html

[H05] 捕获特定类型
来源：http://dali.tanke756.top/Article/details/gt2rirmbhoh.html

Py:   except ValueError as e:
来源：http://dali.iojbl.cn/Article/details/gt2mugkakhg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gt2evvckdeu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gt2wovfjrtt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2wisrptsq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tanke756.top/Article/details/gt2zmvsjdub.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxuanxn.top/Article/details/gt2lbmbppjh.html

Ruby: rescue ArgumentError => e
来源：http://dali.hongshengwenyu.top/Article/details/gt2ncesvowx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yueranfly.top/Article/details/gt2vywhnigz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gt2yokybcsd.html

Py:   value = d.get("k") or default
来源：http://dali.xinyue.icu/Article/details/gt2toupugev.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gt2gjvtlhjw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gt2mvirohlu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gt2voipdfpl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.havefunace.top/Article/details/gt2wsnjvjar.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhongyouzk.top/Article/details/gt2ljmrwckt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gzhubu.top/Article/details/gt2anaylqmt.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kdssmpet.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gt2dujnzwgc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yvedp.cn/Article/details/gt2mecofonb.html

PHP:  assert($x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2mklhnxgg.html

JS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cpxesucb.html

TS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2eppqgrvp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mxlinfwf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gogol.net.cn/Article/details/gt2lkevszdx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhixingplan.top/Article/details/gt2nycpynoc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2okjddjrw.html

[H08] 获取错误信息与堆栈
来源：http://dali.dashuyun.cn/Article/details/gt2gthbggbm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.quarkkingdee.top/Article/details/gt2nvablkwt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gt2xdtiqilk.html

JS:   e.message;  e.stack
来源：http://dali.jlsjyb.cn/Article/details/gt2kyhissrm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgfzy.top/Article/details/gt2eaascnfo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shangyingyoupin.top/Article/details/gt2uxflkkch.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gt2jqrjzpox.html

Ruby: e.message;  e.backtrace
来源：http://dali.pengpengdd.cyou/Article/details/gt2kgyxmlji.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258.top/Article/details/gt2oofoskux.html

[H09] 带错误码的异常
来源：http://dali.gaohongyu789.top/Article/details/gt2uvcwycuo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sysykeji.top/Article/details/gt2djnrpxoy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dashuyun.cn/Article/details/gt2ushbkoxg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ydzc1.top/Article/details/gt2grjmfihg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shzxlz.cn/Article/details/gt2bxtfugua.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2exaofbvs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.vqdsnc.cn/Article/details/gt2kkgssxzl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dianchejie.cn/Article/details/gt2tzlnsong.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnxiangtu.top/Article/details/gt2wejesruo.html

[H10] 资源自动释放
来源：http://dali.quarkkingdee.top/Article/details/gt2yltzespi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenlongwang.top/Article/details/gt2gymsgtch.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.mhx1999.top/Article/details/gt2desvcwmj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gt2rvqfaepi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gt2xqoeeyzy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nwbrower.top/Article/details/gt2psozcbxt.html

Go:   defer f.Close()
来源：http://dali.gotoacloud.top/Article/details/gt2ilzxdsjh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shangyingyoupin.top/Article/details/gt2orusswfo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2yvuenplr.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2jqimulfh.html

I. 正则表达式
来源：http://dali.gotoacloud.top/Article/details/gt2nvgckjok.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2rqqmaztj.html

[I01] 判断是否匹配
来源：http://dali.xinyue.icu/Article/details/gt2jhqpcqor.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2hdzyikjn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2jckzwxrk.html

JS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dpjfmbnx.html

TS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gt2einiebsx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jiagoushi.top/Article/details/gt2fdwafwds.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2etamyxpq.html

Ruby: s.match?(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gt2hbmchyzo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.birdmap.top/Article/details/gt2fglmthey.html

[I02] 提取所有匹配
来源：http://dali.jyoumei.cn/Article/details/gt2dfwbpndh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gt2kambjdgm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shuidangran.top/Article/details/gt2foblzbfa.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnqzz.top/Article/details/gt2peugncaq.html

TS:   s.match(/\d+/g)
来源：http://dali.c1oappe.top/Article/details/gt2alogrded.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2iewmmqzc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xskxibsc.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gt2ijfpcaxp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2vtxjgytx.html

[I03] 提取捕获分组
来源：http://dali.tianlin.xyz/Article/details/gt2asjkrshj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aibaodan.cn/Article/details/gt2tnrajqpo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigufen.top/Article/details/gt2frebswto.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2ogvnhrhx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gzhubu.top/Article/details/gt2ndkegxwm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aizwys.cn/Article/details/gt2cwyoplex.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sweek.top/Article/details/gt2uvcrtelm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cheryme.top/Article/details/gt2rkldcphl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhengqikj.top/Article/details/gt2pwttvmvo.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gt2tshgbgts.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2dnthxhrq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.havefunace.top/Article/details/gt2slfrovel.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2ebgrxuld.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yjgkhktl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fwbfunwd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.smart0.xyz/Article/details/gt2jospxhjf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aizwys.cn/Article/details/gt2nbkbgpmv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kiawbjra.html

[I05] 按正则拆分
来源：http://dali.316326.xyz/Article/details/gt2azxrdoum.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2mwhtrmzz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2xycivbje.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gt2eswitrps.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gt2riuvkdmq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gt2owaxzfrx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gt2waosqcnt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gt2cnxugrdd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.9152youxi.cn/Article/details/gt2pwwnngxn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.meibo888.top/Article/details/gt2kkvrtmti.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cnsjcdrc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.svipenyu.cn/Article/details/gt2lavgajbi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gt2sqhyftxg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gt2nbudpjzz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gt2lyygggkc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258.top/Article/details/gt2bnlyxzbk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.smart0.xyz/Article/details/gt2pdifolor.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gt2vbvgeuop.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhengqikj.top/Article/details/gt2zjfchspf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tian-w.cn/Article/details/gt2pfhwymiv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bkdkdpai.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dianchejie.cn/Article/details/gt2tdnmlhuq.html

TS:   /error/gim
来源：http://dali.jianghu66.top/Article/details/gt2nhnnubhl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.kuanghao11.cn/Article/details/gt2ezvvceye.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenzaomai.com/Article/details/gt2kphwtnzn.html

Ruby: s.scan(/error/i)
来源：http://dali.ybcxt.top/Article/details/gt2dccsssdt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dashuyun.cn/Article/details/gt2hzjliafc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhengqikj.top/Article/details/gt2tejuzulc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ptykldim.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gt2faflrbyc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gt2punkhrzn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gt2quabftfj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gt2odmgigwh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.quarkkingdee.top/Article/details/gt2imyouysg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cucudq.cn/Article/details/gt2wpssfcyd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gt2mqngsozn.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2ujqkjzzh.html

J. 日期与时间
来源：http://dali.yuanzhike.top/Article/details/gt2ckxroqwh.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2umnvnoie.html

[J01] 获取当前时间
来源：http://dali.smart0.xyz/Article/details/gt2idxbafvn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.havefunace.top/Article/details/gt2tuxqibjy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gt2gsywntcf.html

JS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gt2szjeukwo.html

TS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xtkwfxur.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fzhhl.top/Article/details/gt2levaphid.html

Go:   time.Now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2swdcbrea.html

Ruby: Time.now
来源：http://dali.zycfv.cn/Article/details/gt2piqgeifr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yueranfly.top/Article/details/gt2xfbcxfri.html

[J02] 格式化输出
来源：http://dali.sxryk.cn/Article/details/gt2ehvujabn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gt2bdeulnzz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gt2cjelztmb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jlsjyb.cn/Article/details/gt2woqajycw.html

TS:   d.toISOString()
来源：http://dali.vqdsnc.cn/Article/details/gt2gofivrpe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zdqjudy.top/Article/details/gt2ypqodmbu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hammf.cn/Article/details/gt2xcllzhdx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gt2kaleehcp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yueranfly.top/Article/details/gt2inkkudzj.html

[J03] 字符串解析为日期
来源：http://dali.chenlongwang.top/Article/details/gt2gnluaoyy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzcsaby.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhongyouzk.top/Article/details/gt2vaabzodj.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2shyodrjm.html

TS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2xdhpexam.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2ggcqznpn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2boishccc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2irqkpuye.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cashguo.top/Article/details/gt2hweajsvv.html

[J04] 时间戳与日期互转
来源：http://dali.daxiang520.top/Article/details/gt2rzakoxog.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hywenlv.cn/Article/details/gt2ovgkygtt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gzhubu.top/Article/details/gt2ftprkfpa.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.kuanghao11.cn/Article/details/gt2ocxybmot.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tianlin.xyz/Article/details/gt2rqwsbflz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2wywbkyqb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.andypj.xyz/Article/details/gt2hszqspkl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hksignla.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gotoacloud.top/Article/details/gt2wghbxiow.html

[J05] 时间加减（加 7 天）
来源：http://dali.shangyingyoupin.top/Article/details/gt2wpyzjtfx.html

Py:   now + timedelta(days=7)
来源：http://dali.hammf.cn/Article/details/gt2mcethlso.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ovnkucgk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gt2koynujvi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gt2jhhlaktb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.redwolf501.top/Article/details/gt2suepjdgd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.quarkkingdee.top/Article/details/gt2mwklyfzo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cashguo.top/Article/details/gt2xqaqrbul.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zpgcagga.html

[J06] 计算两时间之差
来源：http://dali.fzhhl.top/Article/details/gt2iielmgxr.html

Py:   (end - start).total_seconds()
来源：http://dali.quarkkingdee.top/Article/details/gt2pfsmgepe.html

PHP:  $end->diff($start)->days;
来源：http://dali.aibaodan.cn/Article/details/gt2pbphopug.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigufen.top/Article/details/gt2mjqhvhhz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhiwuduotai.top/Article/details/gt2gktivamn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhongyouzk.top/Article/details/gt2ciqiqxnd.html

Go:   end.Sub(start).Hours()
来源：http://dali.jlsjyb.cn/Article/details/gt2qfmcgcyb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenjidiqi.icu/Article/details/gt2ficmigwe.html

C#:   (end - start).TotalSeconds
来源：http://dali.guannengcc.top/Article/details/gt2rdkftnit.html

[J07] 比较两个日期
来源：http://dali.aibaodan.cn/Article/details/gt2yxsifgjf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gt2holyvohm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hfpthk.cn/Article/details/gt2setshmgw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gt2ppmqpkyk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gt2jjdcehrh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zycfv.cn/Article/details/gt2fyaytdow.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cdnleiting.top/Article/details/gt2jjgfmnaa.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gt2ucaksfgp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gt2igpepawq.html

[J08] 提取年月日与星期
来源：http://dali.nanxinkj.top/Article/details/gt2jercypdi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cucudq.cn/Article/details/gt2goldyuyb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guowangkeji.top/Article/details/gt2szvyeaga.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sufxvd.cn/Article/details/gt2wdmsyrmw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sysykeji.top/Article/details/gt2ztomfkhn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tian-w.cn/Article/details/gt2brrzscwc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangdashe.top/Article/details/gt2rjcmzoqn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yueranfly.top/Article/details/gt2topmjtzw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gotoacloud.top/Article/details/gt2nsclenjc.html

[J09] 时区处理
来源：http://dali.quarkkingdee.top/Article/details/gt2djjwnefr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hfpthk.cn/Article/details/gt2gffbxwdz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zdqjudy.top/Article/details/gt2jlxtwsen.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gt2hktpcgiv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gt2nohgmjqw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gogol.net.cn/Article/details/gt2mvlyfbgm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xinyue.icu/Article/details/gt2dpnxnaue.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ehwqpu.com/Article/details/gt2zngwhwxr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yonumen.top/Article/details/gt2uoyqhtsk.html

[J10] 取今天 / 本月第一天
来源：http://dali.316326.xyz/Article/details/gt2ohxwkojx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuanzx.com/Article/details/gt2hsyooaqy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.316326.xyz/Article/details/gt2tngsnmht.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hysaishi.cn/Article/details/gt2agrhdpxc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2dvuubgqn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gt2gqogwkkn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuanzx.com/Article/details/gt2rlknlrgu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhongyouzk.top/Article/details/gt2espiuypu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xinyue.icu/Article/details/gt2ifypuyeq.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2mgkvuhvt.html

K. JSON 与序列化
来源：http://dali.nanxinkj.top/Article/details/gt2vxyhtyoe.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2gyamgakl.html

[K01] 对象转 JSON 字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2qacehkrv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gt2rjvyvvbs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gt2toaudiku.html

JS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2banbetck.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gt2gnqetoge.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gogol.net.cn/Article/details/gt2vulxhvxt.html

Go:   json.Marshal(obj)
来源：http://dali.mhx1999.top/Article/details/gt2lhzswfee.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xinyue.icu/Article/details/gt2ycmqozbt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2nnrcbfqw.html

[K02] JSON 字符串转对象
来源：http://dali.nwbrower.top/Article/details/gt2ldiivguu.html

Py:   json.loads(s)
来源：http://dali.zycfv.cn/Article/details/gt2eyobyyca.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhixingplan.top/Article/details/gt2xfbvhozq.html

JS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gt2qnnrkimp.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdddwqi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gponhuku.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gt2mirureua.html

Ruby: JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2hxzunjxn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cqqwz.cn/Article/details/gt2wwvxyyma.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tanke756.top/Article/details/gt2pltcftmm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gt2bnwynxmi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vthkhjkv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2cvdwusnr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gt2varofitg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xfsesdbe.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hysaishi.cn/Article/details/gt2hvtdgdeb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oeqjtcyq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenlongwang.top/Article/details/gt2yhlmjrgy.html

[K04] 读取 JSON 文件
来源：http://dali.jlsjyb.cn/Article/details/gt2zaybmzae.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.havefunace.top/Article/details/gt2quhvvyhm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irzyqrxg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gt2zeyxfiup.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gt2ohbpgmhi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gt2wnzjmqsa.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gt2eoxqgdun.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2azjfhvlz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.smart0.xyz/Article/details/gt2ssdlkvbv.html

[K05] 深拷贝对象
来源：http://dali.quarkkingdee.top/Article/details/gt2ukcqqfeh.html

Py:   copy.deepcopy(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qspfulgp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxuanxn.top/Article/details/gt2mqtyrfik.html

JS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gt2azrbzxyw.html

TS:   structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2zmwnhdry.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jianghu66.top/Article/details/gt2bbfvsjqc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dashuyun.cn/Article/details/gt2qwdfrhhy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gogol.net.cn/Article/details/gt2esfhaoxp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tianlin.xyz/Article/details/gt2bevkdmpl.html

[K06] 解析 URL 查询串
来源：http://dali.daxiang520.top/Article/details/gt2rhzhimie.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xinyue.icu/Article/details/gt2ftboutjv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hysaishi.cn/Article/details/gt2peubpgao.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gt2xduqhajx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gt2maipniqc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tanke756.top/Article/details/gt2uznhwwwe.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sghxqtzw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gt2hkxxafzn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gt2cskymbxk.html

[K07] 进制转换
来源：http://dali.yonumen.top/Article/details/gt2xfpjkkno.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xwwpfxbf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cucudq.cn/Article/details/gt2ittganen.html


<!-- 参考信息 -->