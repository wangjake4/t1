代发 wailian999

f() { local x=1; echo "$x"; }
来源：http://dali.birdmap.top/Article/details/gt2kdqgywvj.html

[R32] 参数个数校验
来源：http://dali.sufxvd.cn/Article/details/gt2qfkzyjli.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gt2qjshlyai.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hfcbwqqq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yueranfly.top/Article/details/gt2taggqlrx.html

[R34] 退出时清理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xiuxmivf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yvedp.cn/Article/details/gt2aiaadyyr.html

[R35] 后台执行并等待
来源：http://dali.hnxiangtu.top/Article/details/gt2chqzjmem.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zdqjudy.top/Article/details/gt2tnrgolvr.html

[R36] 并发执行多个任务
来源：http://dali.ybcxt.top/Article/details/gt2higrtyhz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258888.top/Article/details/gt2rooxrpuw.html

[R37] 把输出赋给变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2turdvqjd.html

files=$(ls -1)
来源：http://dali.hammf.cn/Article/details/gt2xrdfqpvx.html

[R38] 管道串联
来源：http://dali.xinyue.icu/Article/details/gt2kyhnrzft.html

cat a.txt | grep -i error | wc -l
来源：http://dali.9152youxi.cn/Article/details/gt2lqclcxzi.html

[R39] 重定向标准输出与错误
来源：http://dali.jianghu66.top/Article/details/gt2nosnsqoc.html

cmd > out.log 2>&1
来源：http://dali.chenzaomai.com/Article/details/gt2gfiqxcgs.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fpiwkipo.html

echo "log" >> out.log
来源：http://dali.yongpay.top/Article/details/gt2shekclrb.html

[R41] 丢弃输出
来源：http://dali.0kj1m.cn/Article/details/gt2dwwpjruk.html

cmd >/dev/null 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gt2riwmlwfj.html

[R42] 输入重定向
来源：http://dali.yj20258.top/Article/details/gt2heydkkqn.html

wc -l < a.txt
来源：http://dali.sufxvd.cn/Article/details/gt2wqyviwcy.html

[R43] 按名字查找文件
来源：http://dali.yangfankeji.com/Article/details/gt2pdqxoehl.html

find . -name "*.log" -type f
来源：http://dali.wangdashe.top/Article/details/gt2dpfvapku.html

[R44] 按修改时间查找
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rnmvdbhd.html

find . -mtime -7 -type f
来源：http://dali.redwolf501.top/Article/details/gt2efrooycy.html

[R45] 批量删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qimvqxnj.html

find . -name "*.tmp" -delete
来源：http://dali.quarkkingdee.top/Article/details/gt2tuoxtbsb.html

[R46] 递归替换文件内容
来源：http://dali.316326.xyz/Article/details/gt2uqiemuig.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zycfv.cn/Article/details/gt2hcxvibnu.html

[R47] sed 单行替换
来源：http://dali.yj20258888.top/Article/details/gt2qziwgsxm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqnpnpfa.html

[R48] awk 取指定列
来源：http://dali.cdnleiting.top/Article/details/gt2ivqbkowk.html

awk '{print $1, $3}' a.txt
来源：http://dali.iojbl.cn/Article/details/gt2rvwvbcgy.html

[R49] awk 带条件
来源：http://dali.gzhubu.top/Article/details/gt2yggjyfhu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jiagoushi.top/Article/details/gt2nbruxujo.html

[R50] awk 求和
来源：http://dali.pycfn.com/Article/details/gt2ldtqntwe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxmtbqt.html

[R51] 排序去重取前几
来源：http://dali.jiagoushi.top/Article/details/gt2busesmpe.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pengpengdd.cyou/Article/details/gt2zdonhivk.html

[R52] 统计行数
来源：http://dali.meibo888.top/Article/details/gt2sppvymra.html

wc -l a.txt
来源：http://dali.nwbrower.top/Article/details/gt2ichgywwj.html

[R53] 查看文件头与实时尾
来源：http://dali.daria6918.cn/Article/details/gt2fbgsuwku.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ivvv.top/Article/details/gt2hjfuelwm.html

[R54] 比较两个文件
来源：http://dali.daxiang520.top/Article/details/gt2zzfmroke.html

diff a.txt b.txt
来源：http://dali.yuanzhike.top/Article/details/gt2mybkyqzu.html

[R55] 压缩与解压
来源：http://dali.cucudq.cn/Article/details/gt2auqnpvnp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fzhhl.top/Article/details/gt2vplnctro.html

[R56] 远程拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wsvgjthd.html

scp file user@host:/path/
来源：http://dali.chenlongwang.top/Article/details/gt2pkpkyvah.html

[R57] 远程执行命令
来源：http://dali.pycfn.com/Article/details/gt2tcmlhhqf.html

ssh user@host 'uptime'
来源：http://dali.hfpthk.cn/Article/details/gt2lmdxeodh.html

[R58] 下载文件
来源：http://dali.yonumen.top/Article/details/gt2giplknsi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zycfv.cn/Article/details/gt2eoajfwai.html

[R59] 发 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gt2hosdmcqz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangdashe.top/Article/details/gt2jzptsdii.html

[R60] 只看 HTTP 状态码
来源：http://dali.ehwqpu.com/Article/details/gt2jiiouweq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenzaomai.com/Article/details/gt2edcnjsnr.html

[R61] 磁盘占用
来源：http://dali.iojbl.cn/Article/details/gt2cawvjsqy.html

df -h;  du -sh *
来源：http://dali.zhixingplan.top/Article/details/gt2ytpxqnmt.html

[R62] 找最占空间的文件
来源：http://dali.snrcjt.cn/Article/details/gt2yriqokqd.html

du -ah . | sort -rh | head -10
来源：http://dali.yj202588.top/Article/details/gt2iyujrziv.html

[R63] 内存与进程
来源：http://dali.xuanzx.com/Article/details/gt2duuvmysp.html

free -h;  ps aux | grep nginx
来源：http://dali.cucudq.cn/Article/details/gt2mnebmobn.html

[R64] 结束进程
来源：http://dali.wangdashe.top/Article/details/gt2tgzprewz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnqzz.top/Article/details/gt2igicwuzx.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jytafegi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guannengcc.top/Article/details/gt2mucudsyl.html

[R66] 定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2adjawjeg.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hwdyssgp.html

[R67] 生成随机十六进制串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hzueoyba.html

openssl rand -hex 16
来源：http://dali.gzhubu.top/Article/details/gt2tvyyxbng.html

[R68] 计算文件校验值
来源：http://dali.ivvv.top/Article/details/gt2fqrscleg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aizwys.cn/Article/details/gt2rptlawui.html

[R69] 生成随机密码
来源：http://dali.yj202588.top/Article/details/gt2hbskhiku.html

head -c 16 /dev/urandom | base64
来源：http://dali.sysykeji.top/Article/details/gt2mbyocpft.html

[R70] 时间戳与互转
来源：http://dali.nanxuanxn.top/Article/details/gt2qonssdoj.html

date +%s;  date -d @1700000000
来源：http://dali.yuanzhike.top/Article/details/gt2lxdgbzbq.html

[R71] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gt2biwyypon.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shangyingyoupin.top/Article/details/gt2avokajcw.html

[R72] 等待端口就绪
来源：http://dali.jqgfzy.top/Article/details/gt2xcxujzlg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zdqjudy.top/Article/details/gt2jgjasywo.html

[R73] 分割大日志
来源：http://dali.andypj.xyz/Article/details/gt2veopwkwa.html

split -l 1000 big.log part_
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xmtzmqsu.html

[R74] 批量重命名
来源：http://dali.316326.xyz/Article/details/gt2pfktpeyh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nwbrower.top/Article/details/gt2msovskuu.html

[R75] 导出环境变量
来源：http://dali.dashuyun.cn/Article/details/gt2iaymeyef.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yangfankeji.com/Article/details/gt2lkkmfuoh.html

[R76] 使用临时文件
来源：http://dali.guannengcc.top/Article/details/gt2surcofgy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gt2alohtnqp.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cqgeolqs.html

read -rp "请输入: " ans
来源：http://dali.nanxuanxn.top/Article/details/gt2rklzpyfy.html

[R78] 交互式菜单
来源：http://dali.yangfankeji.com/Article/details/gt2ijrjmaan.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gotoacloud.top/Article/details/gt2hcbkbuda.html

[R79] 解析命令行选项
来源：http://dali.hywenlv.cn/Article/details/gt2qmoyzrqb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hysaishi.cn/Article/details/gt2wvzifysb.html

[R80] 查看脚本执行耗时
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2olvywatw.html

time ./run.sh
来源：http://dali.yvedp.cn/Article/details/gt2znifhdqq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2iyodvlrk.html

S. C / C++ 专题
来源：http://dali.yangfankeji.com/Article/details/gt2jhujtvdr.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2rfognmhc.html

[S01] C：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2qnuytmcf.html

#include <stdio.h>
来源：http://dali.jyoumei.cn/Article/details/gt2dmkoxtsd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yangfankeji.com/Article/details/gt2ljnpddwv.html

[S02] C：变量与格式化输出
来源：http://dali.daria6918.cn/Article/details/gt2nvfpqvjp.html

int a = 10; printf("%d\n", a);
来源：http://dali.feifeiyinyue.top/Article/details/gt2rjqvsmse.html

[S03] C：读入整数
来源：http://dali.cashguo.top/Article/details/gt2dadtapzf.html

int x; scanf("%d", &x);
来源：http://dali.yvedp.cn/Article/details/gt2xffvjbyy.html

[S04] C：字符串复制
来源：http://dali.dianchejie.cn/Article/details/gt2mqdgyubr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gogol.net.cn/Article/details/gt2rqsazwbe.html

[S05] C：字符串长度
来源：http://dali.ybcxt.top/Article/details/gt2zsrktngg.html

strlen(s)
来源：http://dali.ybcxt.top/Article/details/gt2xkvlqiyv.html

[S06] C：字符串比较
来源：http://dali.cashguo.top/Article/details/gt2xenqzdyv.html

strcmp(a, b) == 0
来源：http://dali.ydzc1.top/Article/details/gt2zpufxbzh.html

[S07] C：数组遍历求和
来源：http://dali.yj202588.top/Article/details/gt2aeftlgak.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shangyingyoupin.top/Article/details/gt2ipxiplnc.html

[S08] C：动态内存分配与释放
来源：http://dali.yonumen.top/Article/details/gt2bkpmgpuj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zycfv.cn/Article/details/gt2qpfpconw.html

[S09] C：结构体定义与初始化
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mfbxplvd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenjidiqi.icu/Article/details/gt2zonjcujn.html

[S10] C：指针与解引用
来源：http://dali.andypj.xyz/Article/details/gt2hljzqmrs.html

int *p = &a;  *p = 5;
来源：http://dali.hysaishi.cn/Article/details/gt2qhaxuumn.html

[S11] C：逐行读文件
来源：http://dali.cashguo.top/Article/details/gt2fomwlpzh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2byphtxpk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yanxiufei.cn/Article/details/gt2ytdpdxpt.html

fclose(f);
来源：http://dali.yuxming.cn/Article/details/gt2flehtcrt.html

[S12] C：写文件
来源：http://dali.nwbrower.top/Article/details/gt2klxyzyrp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gt2qtvxohcz.html

[S13] C：宏定义
来源：http://dali.jyoumei.cn/Article/details/gt2ggfaxjhz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xziqi.cn/Article/details/gt2bmtctmlv.html

[S14] C：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gt2mkhdnqyz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dianchejie.cn/Article/details/gt2oqkmbqtc.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gt2syujjsbf.html

(double) a / b
来源：http://dali.zhongyouzk.top/Article/details/gt2sneuvspx.html

[S16] C：位操作置位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lmvsjpas.html

x |= (1 << 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lckkjwqd.html

[S17] C：安全拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2ubkzjlrp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aibaodan.cn/Article/details/gt2vvfmwcjy.html

[S18] C：命令行参数
来源：http://dali.yueranfly.top/Article/details/gt2jfozibik.html

int main(int argc, char **argv)
来源：http://dali.jianghu66.top/Article/details/gt2sxhwzlnd.html

[S19] C：快速排序
来源：http://dali.havefunace.top/Article/details/gt2ysbnretj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rkierlen.html

[S20] C：二分查找
来源：http://dali.vqdsnc.cn/Article/details/gt2jpplcrou.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gt2agrrmqdz.html

[S21] C：字符类别判断
来源：http://dali.birdmap.top/Article/details/gt2dzrfmsww.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.havefunace.top/Article/details/gt2hxvjiboo.html

[S22] C：字符串转数字
来源：http://dali.svipenyu.cn/Article/details/gt2dsvytekh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.quarkkingdee.top/Article/details/gt2qaoabxbv.html

[S23] C：随机数
来源：http://dali.tianlin.xyz/Article/details/gt2uvsvhwbd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yongpay.top/Article/details/gt2mcwadcta.html

[S24] C：获取本地时间
来源：http://dali.vqdsnc.cn/Article/details/gt2wacbojum.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yongpay.top/Article/details/gt2teklrdjv.html

[S25] C：内存拷贝
来源：http://dali.smart0.xyz/Article/details/gt2kzazzjgn.html

memcpy(dst, src, n);
来源：http://dali.sysykeji.top/Article/details/gt2udfwbojg.html

[S26] C：内存清零
来源：http://dali.yanxiufei.cn/Article/details/gt2wacsmfjm.html

memset(a, 0, sizeof a);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zkcfamdk.html

[S27] C：定义常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2snvbwdre.html

const double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gt2ffkrezkm.html

[S28] C：静态变量
来源：http://dali.yanxiufei.cn/Article/details/gt2esfghtpk.html

static int counter = 0;
来源：http://dali.ppjwa.cn/Article/details/gt2auhnzfoe.html

[S29] C：变参函数
来源：http://dali.yueranfly.top/Article/details/gt2ykxgopkc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ppjwa.cn/Article/details/gt2bcapdfib.html

[S30] C：头文件保护
来源：http://dali.cqqwz.cn/Article/details/gt2yvfgmvrc.html

#ifndef X_H
来源：http://dali.gaohongyu789.top/Article/details/gt2jcskqtjl.html

#define X_H
来源：http://dali.xylfe.cn/Article/details/gt2ydhomyro.html

#endif
来源：http://dali.snrcjt.cn/Article/details/gt2wovtqxpm.html

[S31] C++：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2tkupbheo.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmiwiql.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2nkeszndx.html

[S32] C++：字符串
来源：http://dali.cdnleiting.top/Article/details/gt2yebxtqza.html

std::string s = "hi";  s += "!";
来源：http://dali.svipenyu.cn/Article/details/gt2ijrjujfn.html

[S33] C++：vector 增删
来源：http://dali.jqgfzy.top/Article/details/gt2sqbpigos.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.c1oappe.top/Article/details/gt2jmmcxwbm.html

[S34] C++：遍历 vector
来源：http://dali.nanxuanxn.top/Article/details/gt2hzajclik.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guowangkeji.top/Article/details/gt2skomlkih.html

[S35] C++：map
来源：http://dali.9152youxi.cn/Article/details/gt2efnkjyde.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2vrczugjn.html

[S36] C++：unordered_map
来源：http://dali.pycfn.com/Article/details/gt2iyzglqss.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gt2fnbwvcrg.html

[S37] C++：set
来源：http://dali.xuanzx.com/Article/details/gt2hwdbkdyd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dqowaqou.html

[S38] C++：排序
来源：http://dali.hnxiangtu.top/Article/details/gt2zcfylckf.html

std::sort(v.begin(), v.end());
来源：http://dali.ppjwa.cn/Article/details/gt2olyqfyqc.html

[S39] C++：自定义比较器排序
来源：http://dali.gaohongyu789.top/Article/details/gt2hhjawryg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.feifeiyinyue.top/Article/details/gt2vaczpaip.html

[S40] C++：查找元素
来源：http://dali.daria6918.cn/Article/details/gt2dfdyeayd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhixingplan.top/Article/details/gt2bzfoiwwb.html

[S41] C++：类与构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2yfikyrdp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnxiangtu.top/Article/details/gt2icfoqmhg.html

[S42] C++：继承与虚函数
来源：http://dali.zycfv.cn/Article/details/gt2xmuaxqcx.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zkbwtbze.html

[S43] C++：智能指针
来源：http://dali.chenlongwang.top/Article/details/gt2ctmiugal.html

auto p = std::make_unique<int>(5);
来源：http://dali.gaohongyu789.top/Article/details/gt2mxfdvlwb.html

[S44] C++：引用传参
来源：http://dali.shzxlz.cn/Article/details/gt2bqqqijqv.html

void inc(int &x) { ++x; }
来源：http://dali.tianlin.xyz/Article/details/gt2jztamuje.html

[S45] C++：lambda
来源：http://dali.316326.xyz/Article/details/gt2etnuajop.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258888.top/Article/details/gt2ydhliyxp.html

[S46] C++：函数模板
来源：http://dali.snrcjt.cn/Article/details/gt2skkqvydf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.bjfxy.top/Article/details/gt2bewbpylh.html

[S47] C++：结构化绑定遍历
来源：http://dali.cqqwz.cn/Article/details/gt2gjsguhqd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ffcjnnwu.html

[S48] C++：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gt2ctiewwgs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ujzxgfep.html

while (std::getline(in, line)) { }
来源：http://dali.zdqjudy.top/Article/details/gt2zbfmorcc.html

[S49] C++：写文件
来源：http://dali.c1oappe.top/Article/details/gt2uicwrbnt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2klgbpusc.html

[S50] C++：格式化数字
来源：http://dali.zhiwuduotai.top/Article/details/gt2nutrsrey.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gt2htdszfag.html

[S51] C++：显式类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2tnspcagv.html

static_cast<double>(a) / b
来源：http://dali.ehwqpu.com/Article/details/gt2glenlcwz.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigufen.top/Article/details/gt2wjgjkdro.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybatnegj.html

[S53] C++：移动语义
来源：http://dali.ppjwa.cn/Article/details/gt2ragxchiw.html

std::vector<int> w = std::move(v);
来源：http://dali.xinyue.icu/Article/details/gt2avexjjyz.html

[S54] C++：异常处理
来源：http://dali.nanxinkj.top/Article/details/gt2zfwlkiin.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenlongwang.top/Article/details/gt2upweztzg.html

[S55] C++：结构化绑定
来源：http://dali.smart0.xyz/Article/details/gt2xayamztr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xziucgga.html

[S56] C++：optional
来源：http://dali.ydzc1.top/Article/details/gt2ycdssimv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guannengcc.top/Article/details/gt2qnxaztnc.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mamqimga.html

constexpr int N = 10;
来源：http://dali.iojbl.cn/Article/details/gt2bvsmtcyf.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yuuiqffz.html

namespace ns { int f() { return 1; } }
来源：http://dali.sufxvd.cn/Article/details/gt2cxszqfwj.html

[S59] C++：静态断言
来源：http://dali.feifeiyinyue.top/Article/details/gt2qhravyzb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gaohongyu789.top/Article/details/gt2uonmzqns.html

[S60] C++：遍历并删除元素
来源：http://dali.yangfankeji.com/Article/details/gt2olplhrmb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhixingplan.top/Article/details/gt2ohpwqkbi.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2oxqjthzl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shuidangran.top/Article/details/gt2zytmyqzb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2aoqlvdkn.html

[T01] Kotlin：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2hapxrzej.html

println("Hello")
来源：http://dali.chenzaomai.com/Article/details/gt2dfaxmafb.html

[T02] Kotlin：变量
来源：http://dali.jqgfzy.top/Article/details/gt2ujdpnxxu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yvedp.cn/Article/details/gt2olmciecn.html

[T03] Kotlin：字符串模板
来源：http://dali.daria6918.cn/Article/details/gt2rkkopmms.html

"值: $b"
来源：http://dali.wangshuangyany.cn/Article/details/gt2aizhvewg.html

[T04] Kotlin：空安全
来源：http://dali.hfpthk.cn/Article/details/gt2pmrvoadr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ropetzcw.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258.top/Article/details/gt2cowkllrt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.bjfxy.top/Article/details/gt2grfgjatk.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gt2edczexnu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.meibo888.top/Article/details/gt2oawacsyr.html

[T07] Kotlin：集合过滤
来源：http://dali.shangyingyoupin.top/Article/details/gt2ydqxttfw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gt2cejopsur.html

[T08] Kotlin：数据类
来源：http://dali.hammf.cn/Article/details/gt2pkksnxsc.html

data class User(val name: String, val age: Int)
来源：http://dali.sysykeji.top/Article/details/gt2dwahanrt.html

[T09] Kotlin：扩展函数
来源：http://dali.sxryk.cn/Article/details/gt2fzwtfvyb.html

fun String.exclaim() = this + "!"
来源：http://dali.yanxiufei.cn/Article/details/gt2ylhjuacq.html

[T10] Kotlin：默认参数
来源：http://dali.tanke756.top/Article/details/gt2mnfqaivt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhongyouzk.top/Article/details/gt2jaetrxpw.html

[T11] Kotlin：协程
来源：http://dali.daria6918.cn/Article/details/gt2ahszlbox.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jlsjyb.cn/Article/details/gt2bqecgssg.html

[T12] Kotlin：解构声明
来源：http://dali.havefunace.top/Article/details/gt2gcmmsolz.html

val (a, b) = Pair(1, 2)
来源：http://dali.316326.xyz/Article/details/gt2uxuwsonx.html

[T13] Kotlin：只读 Map
来源：http://dali.redwolf501.top/Article/details/gt2nvimdbye.html

val m = mapOf("a" to 1)
来源：http://dali.meibo888.top/Article/details/gt2lnljisup.html

[T14] Kotlin：循环
来源：http://dali.quarkkingdee.top/Article/details/gt2gmbvrjwo.html

for (i in 1..10) println(i)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tqwdvkvk.html

[T15] Kotlin：接口
来源：http://dali.daria6918.cn/Article/details/gt2owvtbmgw.html

interface Shape { fun area(): Double }
来源：http://dali.jlsjyb.cn/Article/details/gt2cjsxrpfd.html

[T16] Swift：Hello World
来源：http://dali.yongpay.top/Article/details/gt2kfbkyisg.html

print("Hello")
来源：http://dali.jiagoushi.top/Article/details/gt2uxsilclx.html

[T17] Swift：变量与常量
来源：http://dali.andypj.xyz/Article/details/gt2ozcsyuzu.html

var a = 1;  let b = 2
来源：http://dali.shuidangran.top/Article/details/gt2iwytgalr.html

[T18] Swift：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wuuhodvg.html

"值: \(b)"
来源：http://dali.yvedp.cn/Article/details/gt2bvwupaul.html

[T19] Swift：可选绑定
来源：http://dali.chenzaomai.com/Article/details/gt2xmcytsbg.html

if let n = opt { print(n) }
来源：http://dali.zhengqikj.top/Article/details/gt2lsmetwdv.html

[T20] Swift：数组操作
来源：http://dali.yangfankeji.com/Article/details/gt2yifuhdiu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.quarkkingdee.top/Article/details/gt2pbyiwekw.html

[T21] Swift：遍历
来源：http://dali.gzhubu.top/Article/details/gt2ohtkmpyh.html

for x in a { print(x) }
来源：http://dali.yangfankeji.com/Article/details/gt2tciomlpf.html

[T22] Swift：字典
来源：http://dali.dashuyun.cn/Article/details/gt2auvpcujh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cqqwz.cn/Article/details/gt2sexchcxj.html

[T23] Swift：函数
来源：http://dali.xinyue.icu/Article/details/gt2ivzkfxjd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guowangkeji.top/Article/details/gt2pmeilwas.html

[T24] Swift：闭包
来源：http://dali.yueranfly.top/Article/details/gt2xdstblfk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuanzx.com/Article/details/gt2bgwjalgt.html

[T25] Swift：结构体
来源：http://dali.yvedp.cn/Article/details/gt2dbogfudb.html

struct P { var x: Int }
来源：http://dali.xziqi.cn/Article/details/gt2bylpkkvv.html

[T26] Swift：类与重写
来源：http://dali.zhengqikj.top/Article/details/gt2kdfhjuat.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ejehwmin.html

[T27] Swift：错误处理
来源：http://dali.jinqigufen.top/Article/details/gt2jcavtowv.html

do { try f() } catch { print(error) }
来源：http://dali.hfpthk.cn/Article/details/gt2qfrdqmvm.html

[T28] Swift：枚举
来源：http://dali.jqgfzy.top/Article/details/gt2qkyfpnam.html

enum Color { case red, green }
来源：http://dali.yj202588.top/Article/details/gt2bkfjltyq.html

[T29] Swift：guard 提前返回
来源：http://dali.cucudq.cn/Article/details/gt2wiizfswl.html

guard let x = opt else { return }
来源：http://dali.xuanzx.com/Article/details/gt2adaaxtxh.html

[T30] Swift：协议
来源：http://dali.xuanzx.com/Article/details/gt2lyebbprw.html

protocol Shape { func area() -> Double }
来源：http://dali.gotoacloud.top/Article/details/gt2tmuahfwv.html

[T31] Lua：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2lbtuvzjp.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ghpomjko.html

[T32] Lua：局部变量
来源：http://dali.nwbrower.top/Article/details/gt2uoiakpwd.html

local a = 1
来源：http://dali.tian-w.cn/Article/details/gt2qndgrzik.html

[T33] Lua：表（数组）
来源：http://dali.xuetiantiany.cn/Article/details/gt2cupfskfv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenzaomai.com/Article/details/gt2nxjrncen.html

[T34] Lua：遍历表
来源：http://dali.tian-w.cn/Article/details/gt2gbppwhbm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.andypj.xyz/Article/details/gt2jeebgulq.html


<!-- 参考信息 -->