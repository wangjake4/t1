代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2dxnzbhwv.html

[R18] 遍历数组
来源：http://dali.yuxming.cn/Article/details/gt2ykyhwmjz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigufen.top/Article/details/gt2quzitmro.html

[R19] 数组长度
来源：http://dali.wangdashe.top/Article/details/gt2ekpjvcsd.html

echo "${#arr[@]}"
来源：http://dali.daxiang520.top/Article/details/gt2olanarya.html

[R20] 关联数组（字典）
来源：http://dali.hfpthk.cn/Article/details/gt2nzfijerg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gt2irhkhgrd.html

[R21] 字符串长度
来源：http://dali.aizwys.cn/Article/details/gt2siukckip.html

echo "${#s}"
来源：http://dali.hnqzz.top/Article/details/gt2sgmqulci.html

[R22] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gt2tglmejmq.html

echo "${s:0:5}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2unwsxjgt.html

[R23] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2htqhddkm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigfzy.top/Article/details/gt2nbaqyfjo.html

[R24] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gt2dyjsqinh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.vqdsnc.cn/Article/details/gt2qqrzvvrc.html

[R25] 去后缀 / 去前缀
来源：http://dali.dashuyun.cn/Article/details/gt2cbpshoiy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zycfv.cn/Article/details/gt2dyqxhfcc.html

[R26] 命令替换
来源：http://dali.guannengcc.top/Article/details/gt2raxfiasz.html

now=$(date +%F); echo "$now"
来源：http://dali.hfpthk.cn/Article/details/gt2zjamihca.html

[R27] 算术展开
来源：http://dali.smart0.xyz/Article/details/gt2pqqykuqf.html

echo $((1 + 2 * 3))
来源：http://dali.zhongyouzk.top/Article/details/gt2vnqxcocd.html

[R28] 浮点运算
来源：http://dali.yuanzhike.top/Article/details/gt2dcsksfyr.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnqzz.top/Article/details/gt2qqnyjdxu.html

[R29] 定义函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2toecbuke.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gotoacloud.top/Article/details/gt2xtyyuxvv.html

[R30] 函数返回状态码
来源：http://dali.wangdashe.top/Article/details/gt2cooyescx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pycfn.com/Article/details/gt2nxkcpoyy.html

[R31] 局部变量
来源：http://dali.cqqwz.cn/Article/details/gt2zcyxfkzw.html

f() { local x=1; echo "$x"; }
来源：http://dali.tanke756.top/Article/details/gt2hynxeeuo.html

[R32] 参数个数校验
来源：http://dali.svipenyu.cn/Article/details/gt2jmwcxflq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gt2alledejo.html

[R33] 捕获错误并提示行号
来源：http://dali.ehwqpu.com/Article/details/gt2yobycjwg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.redwolf501.top/Article/details/gt2ouzdylfd.html

[R34] 退出时清理
来源：http://dali.shangyingyoupin.top/Article/details/gt2hhebmiii.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gt2elmzzavv.html

[R35] 后台执行并等待
来源：http://dali.havefunace.top/Article/details/gt2haupcdeu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.smart0.xyz/Article/details/gt2cyglotvi.html

[R36] 并发执行多个任务
来源：http://dali.jqgufenzy.top/Article/details/gt2esvejolh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yonumen.top/Article/details/gt2mplfpypa.html

[R37] 把输出赋给变量
来源：http://dali.wangdashe.top/Article/details/gt2eihktyuc.html

files=$(ls -1)
来源：http://dali.jiagoushi.top/Article/details/gt2nnqnuyax.html

[R38] 管道串联
来源：http://dali.redwolf501.top/Article/details/gt2eldjoaxd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jxhdnnqo.html

[R39] 重定向标准输出与错误
来源：http://dali.cashguo.top/Article/details/gt2qvlpkpjy.html

cmd > out.log 2>&1
来源：http://dali.fengsongda.top/Article/details/gt2rbywprta.html

[R40] 追加写日志
来源：http://dali.xuetiantiany.cn/Article/details/gt2ussxqwmz.html

echo "log" >> out.log
来源：http://dali.ybcxt.top/Article/details/gt2attqghfw.html

[R41] 丢弃输出
来源：http://dali.wangdashe.top/Article/details/gt2nbcgwxnk.html

cmd >/dev/null 2>&1
来源：http://dali.smart0.xyz/Article/details/gt2lnauosnp.html

[R42] 输入重定向
来源：http://dali.daria6918.cn/Article/details/gt2uyndaquw.html

wc -l < a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2dmrxqhkf.html

[R43] 按名字查找文件
来源：http://dali.9152youxi.cn/Article/details/gt2hakeodco.html

find . -name "*.log" -type f
来源：http://dali.hnqzz.top/Article/details/gt2hlrzcied.html

[R44] 按修改时间查找
来源：http://dali.zhoulong.xyz/Article/details/gt2vytzwdfh.html

find . -mtime -7 -type f
来源：http://dali.feifeiyinyue.top/Article/details/gt2gpudnnsn.html

[R45] 批量删除
来源：http://dali.tianlin.xyz/Article/details/gt2hepbhems.html

find . -name "*.tmp" -delete
来源：http://dali.dashuyun.cn/Article/details/gt2fenmenek.html

[R46] 递归替换文件内容
来源：http://dali.zhengqikj.top/Article/details/gt2jshbfxrq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhengqikj.top/Article/details/gt2twbtyxsx.html

[R47] sed 单行替换
来源：http://dali.nanxinkj.top/Article/details/gt2hxxribky.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2wacjhfmc.html

[R48] awk 取指定列
来源：http://dali.yonumen.top/Article/details/gt2gkttcbgk.html

awk '{print $1, $3}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2uiscfmwy.html

[R49] awk 带条件
来源：http://dali.andypj.xyz/Article/details/gt2eruolxyc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.pycfn.com/Article/details/gt2iyvqiint.html

[R50] awk 求和
来源：http://dali.hywenlv.cn/Article/details/gt2zisytjak.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2efqwuozs.html

[R51] 排序去重取前几
来源：http://dali.jqgufenzy.top/Article/details/gt2isddtgig.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yueranfly.top/Article/details/gt2dfiuhzgc.html

[R52] 统计行数
来源：http://dali.zdqjudy.top/Article/details/gt2cqzisquy.html

wc -l a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2mjtsspay.html

[R53] 查看文件头与实时尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rjzvyihm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.daxiang520.top/Article/details/gt2iyuwgpgp.html

[R54] 比较两个文件
来源：http://dali.xziqi.cn/Article/details/gt2rpcijjyp.html

diff a.txt b.txt
来源：http://dali.c1oappe.top/Article/details/gt2tguzmuak.html

[R55] 压缩与解压
来源：http://dali.ehwqpu.com/Article/details/gt2ioysvlfo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aibaodan.cn/Article/details/gt2agwyflnr.html

[R56] 远程拷贝
来源：http://dali.haohaochexian.top/Article/details/gt2hixzesmo.html

scp file user@host:/path/
来源：http://dali.sweek.top/Article/details/gt2ukeodtst.html

[R57] 远程执行命令
来源：http://dali.yueranfly.top/Article/details/gt2bginmqpe.html

ssh user@host 'uptime'
来源：http://dali.xuanzx.com/Article/details/gt2yrandusx.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2bdmixomc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xuetiantiany.cn/Article/details/gt2qqxjcqyo.html

[R59] 发 POST JSON
来源：http://dali.mhx1999.top/Article/details/gt2kaiwiewp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhengqikj.top/Article/details/gt2nfsbrdki.html

[R60] 只看 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gt2zhozkiox.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinqigfzy.top/Article/details/gt2tncdvxee.html

[R61] 磁盘占用
来源：http://dali.cdnleiting.top/Article/details/gt2otxzbhtd.html

df -h;  du -sh *
来源：http://dali.iojbl.cn/Article/details/gt2pgsbqwnd.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmvqcuob.html

du -ah . | sort -rh | head -10
来源：http://dali.ybcxt.top/Article/details/gt2ascnxibh.html

[R63] 内存与进程
来源：http://dali.jinqigufen.top/Article/details/gt2njoxvtbl.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xaqnxjpi.html

[R64] 结束进程
来源：http://dali.aibaodan.cn/Article/details/gt2awpqitdl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jyoumei.cn/Article/details/gt2fvlnsxha.html

[R65] 查看端口占用
来源：http://dali.wangdashe.top/Article/details/gt2yihxiibq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgfzy.top/Article/details/gt2qoidyvhx.html

[R66] 定时任务
来源：http://dali.hongshengwenyu.top/Article/details/gt2jvcaxmir.html

crontab -e;  crontab -l
来源：http://dali.zhoulong.xyz/Article/details/gt2qbwomjje.html

[R67] 生成随机十六进制串
来源：http://dali.chenlongwang.top/Article/details/gt2zkadhier.html

openssl rand -hex 16
来源：http://dali.feifeiyinyue.top/Article/details/gt2fwtlqbou.html

[R68] 计算文件校验值
来源：http://dali.jqgufenzy.top/Article/details/gt2zqcdibkm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2rzrullsw.html

[R69] 生成随机密码
来源：http://dali.smart0.xyz/Article/details/gt2rzxnhdqu.html

head -c 16 /dev/urandom | base64
来源：http://dali.yongpay.top/Article/details/gt2umphngjp.html

[R70] 时间戳与互转
来源：http://dali.iojbl.cn/Article/details/gt2lefwkbfy.html

date +%s;  date -d @1700000000
来源：http://dali.hammf.cn/Article/details/gt2dsnoxmmu.html

[R71] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ytvqwpcc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jlsjyb.cn/Article/details/gt2tjwpufcr.html

[R72] 等待端口就绪
来源：http://dali.iojbl.cn/Article/details/gt2bnkfxkie.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tzunrjrt.html

[R73] 分割大日志
来源：http://dali.gzhubu.top/Article/details/gt2rrptdnji.html

split -l 1000 big.log part_
来源：http://dali.aibaodan.cn/Article/details/gt2hzcgumko.html

[R74] 批量重命名
来源：http://dali.jinqigfzy.top/Article/details/gt2vlwytcwr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuanzhike.top/Article/details/gt2vaugakyz.html

[R75] 导出环境变量
来源：http://dali.shzxlz.cn/Article/details/gt2bjitogdj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hysaishi.cn/Article/details/gt2yuqepzec.html

[R76] 使用临时文件
来源：http://dali.fengsongda.top/Article/details/gt2wcznyoev.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gt2swybzrcv.html

[R77] 读取用户输入
来源：http://dali.daria6918.cn/Article/details/gt2qfbcapty.html

read -rp "请输入: " ans
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjfjoiyt.html

[R78] 交互式菜单
来源：http://dali.pycfn.com/Article/details/gt2nqpsfged.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj202588.top/Article/details/gt2kqpipqpv.html

[R79] 解析命令行选项
来源：http://dali.hongshengwenyu.top/Article/details/gt2dnfdafrd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zdqjudy.top/Article/details/gt2xlebvrzi.html

[R80] 查看脚本执行耗时
来源：http://dali.cashguo.top/Article/details/gt2wjdcdbyl.html

time ./run.sh
来源：http://dali.cucudq.cn/Article/details/gt2smgktzpk.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rpybhpuv.html

S. C / C++ 专题
来源：http://dali.jinqigufen.top/Article/details/gt2rbsjnhlt.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2dhucxixx.html

[S01] C：Hello World
来源：http://dali.316326.xyz/Article/details/gt2cgrzhhbo.html

#include <stdio.h>
来源：http://dali.ppjwa.cn/Article/details/gt2ewkobzut.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fengsongda.top/Article/details/gt2qyjaftra.html

[S02] C：变量与格式化输出
来源：http://dali.0kj1m.cn/Article/details/gt2kwttwomn.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258888.top/Article/details/gt2xgxveqcz.html

[S03] C：读入整数
来源：http://dali.hywenlv.cn/Article/details/gt2ghbgsjxc.html

int x; scanf("%d", &x);
来源：http://dali.guannengcc.top/Article/details/gt2szhoxjsq.html

[S04] C：字符串复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mjkhtmhg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hhtpxngw.html

[S05] C：字符串长度
来源：http://dali.cdnleiting.top/Article/details/gt2djzegtvl.html

strlen(s)
来源：http://dali.xziqi.cn/Article/details/gt2essqwbvq.html

[S06] C：字符串比较
来源：http://dali.yj20258.top/Article/details/gt2sruqdedq.html

strcmp(a, b) == 0
来源：http://dali.ydzc1.top/Article/details/gt2hdichgrr.html

[S07] C：数组遍历求和
来源：http://dali.quarkkingdee.top/Article/details/gt2tqmwryzk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.316326.xyz/Article/details/gt2lxrmnzgr.html

[S08] C：动态内存分配与释放
来源：http://dali.yonumen.top/Article/details/gt2yayzeuwj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cheryme.top/Article/details/gt2ahmadsnx.html

[S09] C：结构体定义与初始化
来源：http://dali.meibo888.top/Article/details/gt2odoiswnp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cucudq.cn/Article/details/gt2szykzhgz.html

[S10] C：指针与解引用
来源：http://dali.yvedp.cn/Article/details/gt2bnlupwws.html

int *p = &a;  *p = 5;
来源：http://dali.redwolf501.top/Article/details/gt2yidkvzec.html

[S11] C：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gt2aioujbxc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxuanxn.top/Article/details/gt2ebyqwjxt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tianlin.xyz/Article/details/gt2szixpoxw.html

fclose(f);
来源：http://dali.yueranfly.top/Article/details/gt2gdtnexvr.html

[S12] C：写文件
来源：http://dali.yangfankeji.com/Article/details/gt2xwicelkm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gt2nqwrcbey.html

[S13] C：宏定义
来源：http://dali.shuidangran.top/Article/details/gt2rqectzvn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.vqdsnc.cn/Article/details/gt2xbkjanir.html

[S14] C：枚举
来源：http://dali.daria6918.cn/Article/details/gt2nfrgnkbi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ydzc1.top/Article/details/gt2afesfqkj.html

[S15] C：类型转换
来源：http://dali.xziqi.cn/Article/details/gt2msiadrsr.html

(double) a / b
来源：http://dali.zycfv.cn/Article/details/gt2gocvxzgq.html

[S16] C：位操作置位
来源：http://dali.yangfankeji.com/Article/details/gt2vdxyuzqn.html

x |= (1 << 3);
来源：http://dali.zhengqikj.top/Article/details/gt2zrxedwtd.html

[S17] C：安全拼接字符串
来源：http://dali.yueranfly.top/Article/details/gt2ermdynlq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.316326.xyz/Article/details/gt2fpdzuujs.html

[S18] C：命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2ymikfxjm.html

int main(int argc, char **argv)
来源：http://dali.andypj.xyz/Article/details/gt2glqoxreq.html

[S19] C：快速排序
来源：http://dali.shzxlz.cn/Article/details/gt2vssllqso.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gt2jklbiiwv.html

[S20] C：二分查找
来源：http://dali.xinyue.icu/Article/details/gt2fdwpcemg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gt2qjkdjxak.html

[S21] C：字符类别判断
来源：http://dali.gogol.net.cn/Article/details/gt2jgbrdpfv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nwbrower.top/Article/details/gt2kjtydfqg.html

[S22] C：字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gt2hdgssiho.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sysykeji.top/Article/details/gt2nfbcnvxy.html

[S23] C：随机数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2omvvuver.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.redwolf501.top/Article/details/gt2zpnscrwd.html

[S24] C：获取本地时间
来源：http://dali.yonumen.top/Article/details/gt2pgbovhcy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gt2zlxofzxj.html

[S25] C：内存拷贝
来源：http://dali.daxiang520.top/Article/details/gt2xvsikgez.html

memcpy(dst, src, n);
来源：http://dali.hywenlv.cn/Article/details/gt2vohbsstf.html

[S26] C：内存清零
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zjvpkkxb.html

memset(a, 0, sizeof a);
来源：http://dali.gotoacloud.top/Article/details/gt2bbvcyytb.html

[S27] C：定义常量
来源：http://dali.jlsjyb.cn/Article/details/gt2xcsremfi.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gt2iptekpww.html

[S28] C：静态变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rwgalykd.html

static int counter = 0;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ojpeataq.html

[S29] C：变参函数
来源：http://dali.shzxlz.cn/Article/details/gt2hnxlaomh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gzhubu.top/Article/details/gt2xoairhlg.html

[S30] C：头文件保护
来源：http://dali.hysaishi.cn/Article/details/gt2vzpirwia.html

#ifndef X_H
来源：http://dali.gotoacloud.top/Article/details/gt2srsvdaaj.html

#define X_H
来源：http://dali.dashuyun.cn/Article/details/gt2pfwjbxys.html

#endif
来源：http://dali.gzhubu.top/Article/details/gt2jcryndmm.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2yunygnkv.html

#include <iostream>
来源：http://dali.redwolf501.top/Article/details/gt2wnjratwj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.snrcjt.cn/Article/details/gt2zvtfjghs.html

[S32] C++：字符串
来源：http://dali.tianlin.xyz/Article/details/gt2wxazkddv.html

std::string s = "hi";  s += "!";
来源：http://dali.redwolf501.top/Article/details/gt2amzcjstx.html

[S33] C++：vector 增删
来源：http://dali.quarkkingdee.top/Article/details/gt2gwuhajdb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuanzhike.top/Article/details/gt2vxfbgfle.html

[S34] C++：遍历 vector
来源：http://dali.yj202588.top/Article/details/gt2kixxcvqp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sufxvd.cn/Article/details/gt2yskiajpw.html

[S35] C++：map
来源：http://dali.quarkkingdee.top/Article/details/gt2qfmqlgpo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gt2bimbfxly.html

[S36] C++：unordered_map
来源：http://dali.hnxiangtu.top/Article/details/gt2hpnmktqc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2sdihxvkc.html

[S37] C++：set
来源：http://dali.fzhhl.top/Article/details/gt2osbqfgut.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pycfn.com/Article/details/gt2dcyxtqex.html

[S38] C++：排序
来源：http://dali.chenzaomai.com/Article/details/gt2xcrazjrz.html

std::sort(v.begin(), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gt2rlbmywal.html

[S39] C++：自定义比较器排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ygoycybq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jlsjyb.cn/Article/details/gt2xjvqwwwx.html

[S40] C++：查找元素
来源：http://dali.xziqi.cn/Article/details/gt2bohbeese.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2inqmnasd.html

[S41] C++：类与构造函数
来源：http://dali.mhx1999.top/Article/details/gt2ewemyzvj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dashuyun.cn/Article/details/gt2uyapwmjw.html

[S42] C++：继承与虚函数
来源：http://dali.yueranfly.top/Article/details/gt2tdwuqlgj.html

class B : public Base { public: void f() override {} };
来源：http://dali.jianghu66.top/Article/details/gt2obbuoprq.html

[S43] C++：智能指针
来源：http://dali.hywenlv.cn/Article/details/gt2wzkhigfi.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258.top/Article/details/gt2hoycwqjr.html

[S44] C++：引用传参
来源：http://dali.jinghuilouyu.cn/Article/details/gt2otmtyzon.html

void inc(int &x) { ++x; }
来源：http://dali.hywenlv.cn/Article/details/gt2gwsgpjtj.html

[S45] C++：lambda
来源：http://dali.gaohongyu789.top/Article/details/gt2ysvecfsn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jyoumei.cn/Article/details/gt2zohmacjc.html

[S46] C++：函数模板
来源：http://dali.tian-w.cn/Article/details/gt2hihevytq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.c1oappe.top/Article/details/gt2rwznmkpf.html

[S47] C++：结构化绑定遍历
来源：http://dali.ehwqpu.com/Article/details/gt2kzsmkdbc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ivvv.top/Article/details/gt2kimybfwp.html

[S48] C++：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gt2rcdvnwhu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yanxiufei.cn/Article/details/gt2hfgvfcoh.html

while (std::getline(in, line)) { }
来源：http://dali.tian-w.cn/Article/details/gt2yjjnfvxp.html

[S49] C++：写文件
来源：http://dali.guannengcc.top/Article/details/gt2fjhctfyl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sweek.top/Article/details/gt2bcejouhi.html

[S50] C++：格式化数字
来源：http://dali.chenlongwang.top/Article/details/gt2hpisrflb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.andypj.xyz/Article/details/gt2jmzomrvo.html

[S51] C++：显式类型转换
来源：http://dali.daria6918.cn/Article/details/gt2ewrvombl.html

static_cast<double>(a) / b
来源：http://dali.316326.xyz/Article/details/gt2rbmihjeo.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gt2wtnfztag.html

int size() const noexcept { return n_; }
来源：http://dali.iojbl.cn/Article/details/gt2mhnthvrl.html

[S53] C++：移动语义
来源：http://dali.jqgfzy.top/Article/details/gt2aoxofzef.html

std::vector<int> w = std::move(v);
来源：http://dali.jyoumei.cn/Article/details/gt2xpkyuekd.html

[S54] C++：异常处理
来源：http://dali.shuidangran.top/Article/details/gt2gxcebwjs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnxiangtu.top/Article/details/gt2sklmodtg.html

[S55] C++：结构化绑定
来源：http://dali.yonumen.top/Article/details/gt2gexzrpvn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2odfotbwh.html

[S56] C++：optional
来源：http://dali.ivvv.top/Article/details/gt2vsjybpga.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.svipenyu.cn/Article/details/gt2qtaarsju.html

[S57] C++：编译期常量
来源：http://dali.jlsjyb.cn/Article/details/gt2mukrmdzo.html

constexpr int N = 10;
来源：http://dali.vqdsnc.cn/Article/details/gt2prajfajn.html

[S58] C++：命名空间
来源：http://dali.mhx1999.top/Article/details/gt2oybcvery.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangdashe.top/Article/details/gt2nkjjvurl.html

[S59] C++：静态断言
来源：http://dali.nanxuanxn.top/Article/details/gt2cgevgeuf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rhivpsnb.html

[S60] C++：遍历并删除元素
来源：http://dali.mhx1999.top/Article/details/gt2idhownqq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gzhubu.top/Article/details/gt2lkpwgumc.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2joyuxyyr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yueranfly.top/Article/details/gt2wddgzjrn.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2dciroacf.html

[T01] Kotlin：Hello World
来源：http://dali.316326.xyz/Article/details/gt2glkfzjhe.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gt2nnyngwpf.html

[T02] Kotlin：变量
来源：http://dali.yj202588.top/Article/details/gt2yzlucgdt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhiwuduotai.top/Article/details/gt2tgpzsmhv.html

[T03] Kotlin：字符串模板
来源：http://dali.bjfxy.top/Article/details/gt2pyplozyw.html

"值: $b"
来源：http://dali.shangyingyoupin.top/Article/details/gt2uqlgdexi.html

[T04] Kotlin：空安全
来源：http://dali.c1oappe.top/Article/details/gt2gbigsofa.html

val n: String? = null;  n?.length
来源：http://dali.svipenyu.cn/Article/details/gt2nugbllrl.html

[T05] Kotlin：when 表达式
来源：http://dali.yj202588.top/Article/details/gt2yxjllnro.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tianlin.xyz/Article/details/gt2mxnnhskq.html

[T06] Kotlin：集合映射
来源：http://dali.ivvv.top/Article/details/gt2rkvflzas.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.meibo888.top/Article/details/gt2afyvqlqs.html

[T07] Kotlin：集合过滤
来源：http://dali.iojbl.cn/Article/details/gt2irarlxbj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.bjfxy.top/Article/details/gt2ltvpyuko.html

[T08] Kotlin：数据类
来源：http://dali.birdmap.top/Article/details/gt2fkwhvufo.html

data class User(val name: String, val age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uacxpbzl.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxinkj.top/Article/details/gt2etvbqciq.html

fun String.exclaim() = this + "!"
来源：http://dali.xuetiantiany.cn/Article/details/gt2npvahcul.html

[T10] Kotlin：默认参数
来源：http://dali.ybcxt.top/Article/details/gt2siqsrqfn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhiwuduotai.top/Article/details/gt2rjiojzcj.html

[T11] Kotlin：协程
来源：http://dali.nanxinkj.top/Article/details/gt2madzwois.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigufen.top/Article/details/gt2hpqxysuk.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigfzy.top/Article/details/gt2zmqtxutg.html

val (a, b) = Pair(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2mgnsosmh.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gt2pmlqmntc.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258888.top/Article/details/gt2ifyznnhv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2czsorplc.html

for (i in 1..10) println(i)
来源：http://dali.yj20258.top/Article/details/gt2ggbqxqeb.html

[T15] Kotlin：接口
来源：http://dali.yongpay.top/Article/details/gt2jltvnamu.html

interface Shape { fun area(): Double }
来源：http://dali.gaohongyu789.top/Article/details/gt2hbrapcdz.html

[T16] Swift：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2flpruxpk.html

print("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pjgzburq.html

[T17] Swift：变量与常量
来源：http://dali.pycfn.com/Article/details/gt2wkhnsvzs.html

var a = 1;  let b = 2
来源：http://dali.9152youxi.cn/Article/details/gt2vumlptek.html

[T18] Swift：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gt2kufxnilg.html

"值: \(b)"
来源：http://dali.yanxiufei.cn/Article/details/gt2aoxxtnnp.html

[T19] Swift：可选绑定
来源：http://dali.svipenyu.cn/Article/details/gt2osrlaqth.html

if let n = opt { print(n) }
来源：http://dali.havefunace.top/Article/details/gt2lrrrhtey.html

[T20] Swift：数组操作
来源：http://dali.0kj1m.cn/Article/details/gt2gryifwda.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhengqikj.top/Article/details/gt2rhkpjklv.html


<!-- 参考信息 -->