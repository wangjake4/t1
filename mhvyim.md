代发 wailian999

esac
来源：http://dali.zdqjudy.top/Article/details/gt2tbtaklpq.html

[R12] for 遍历文件
来源：http://dali.xuanzx.com/Article/details/gt2efzwsdjt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guowangkeji.top/Article/details/gt2xksqrivb.html

[R13] for 计数循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2uidqvqev.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gt2itzypfic.html

[R14] C 风格 for
来源：http://dali.kuanghao11.cn/Article/details/gt2rtffpzqs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gt2wrboqjfa.html

[R15] while 逐行读文件
来源：http://dali.cashguo.top/Article/details/gt2hztmilzz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2vdewfemq.html

[R16] until 等待条件
来源：http://dali.jinqigfzy.top/Article/details/gt2rridbsxw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2hryifygl.html

[R17] 数组定义与取值
来源：http://dali.fzhhl.top/Article/details/gt2qjmaorqj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cashguo.top/Article/details/gt2fywyqzxf.html

[R18] 遍历数组
来源：http://dali.iojbl.cn/Article/details/gt2fhccnyez.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dashuyun.cn/Article/details/gt2cvxpaefd.html

[R19] 数组长度
来源：http://dali.xylfe.cn/Article/details/gt2hrsnvpfz.html

echo "${#arr[@]}"
来源：http://dali.smart0.xyz/Article/details/gt2ptmnwtzo.html

[R20] 关联数组（字典）
来源：http://dali.svipenyu.cn/Article/details/gt2cubkohqb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fzhhl.top/Article/details/gt2onpxkoal.html

[R21] 字符串长度
来源：http://dali.jiagoushi.top/Article/details/gt2ikpcfjit.html

echo "${#s}"
来源：http://dali.sweek.top/Article/details/gt2ymjdxltz.html

[R22] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jtkvktms.html

echo "${s:0:5}"
来源：http://dali.yj20258.top/Article/details/gt2aawndaeu.html

[R23] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gt2rejzxmgu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2sevdnwmk.html

[R24] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gt2bchlneiv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.meibo888.top/Article/details/gt2dmjnaryv.html

[R25] 去后缀 / 去前缀
来源：http://dali.jianghu66.top/Article/details/gt2irvbiabg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.smart0.xyz/Article/details/gt2vzyblahr.html

[R26] 命令替换
来源：http://dali.daxiang520.top/Article/details/gt2vdpqsnow.html

now=$(date +%F); echo "$now"
来源：http://dali.dianchejie.cn/Article/details/gt2kgmttpbn.html

[R27] 算术展开
来源：http://dali.zhoulong.xyz/Article/details/gt2rdaclupy.html

echo $((1 + 2 * 3))
来源：http://dali.zhongyouzk.top/Article/details/gt2gdsjkfpi.html

[R28] 浮点运算
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wiihignn.html

echo "scale=2; 10/3" | bc
来源：http://dali.jianghu66.top/Article/details/gt2ujrfqyna.html

[R29] 定义函数
来源：http://dali.yj20258888.top/Article/details/gt2fjusevqe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhixingplan.top/Article/details/gt2qlxjyxvg.html

[R30] 函数返回状态码
来源：http://dali.guannengcc.top/Article/details/gt2wzxjaqdg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.haohaochexian.top/Article/details/gt2cesovfhb.html

[R31] 局部变量
来源：http://dali.guannengcc.top/Article/details/gt2iumjckti.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2krhhmyjr.html

[R32] 参数个数校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2snbxbqip.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gt2bjwehxym.html

[R33] 捕获错误并提示行号
来源：http://dali.xuanzx.com/Article/details/gt2dbxzkfhc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuetiantiany.cn/Article/details/gt2gxxqamed.html

[R34] 退出时清理
来源：http://dali.hysaishi.cn/Article/details/gt2ewgecewo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gt2fxqckwyd.html

[R35] 后台执行并等待
来源：http://dali.cqqwz.cn/Article/details/gt2vhazggfr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sufxvd.cn/Article/details/gt2lanodits.html

[R36] 并发执行多个任务
来源：http://dali.xylfe.cn/Article/details/gt2tgtqbtdp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.feifeiyinyue.top/Article/details/gt2exokmafk.html

[R37] 把输出赋给变量
来源：http://dali.sufxvd.cn/Article/details/gt2lxzfwttu.html

files=$(ls -1)
来源：http://dali.jqgfzy.top/Article/details/gt2ivfjidzk.html

[R38] 管道串联
来源：http://dali.xziqi.cn/Article/details/gt2fjrjzajc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhixingplan.top/Article/details/gt2ylgrgyze.html

[R39] 重定向标准输出与错误
来源：http://dali.ehwqpu.com/Article/details/gt2enzlopbk.html

cmd > out.log 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gt2rjgmphnf.html

[R40] 追加写日志
来源：http://dali.zhixingplan.top/Article/details/gt2sdwrwzmg.html

echo "log" >> out.log
来源：http://dali.shanyushiyangtech.top/Article/details/gt2chlxyokw.html

[R41] 丢弃输出
来源：http://dali.jinqigfzy.top/Article/details/gt2mfszkykj.html

cmd >/dev/null 2>&1
来源：http://dali.yonumen.top/Article/details/gt2wyaazmdy.html

[R42] 输入重定向
来源：http://dali.nanxinkj.top/Article/details/gt2oajhsrni.html

wc -l < a.txt
来源：http://dali.yvedp.cn/Article/details/gt2jhsxlubp.html

[R43] 按名字查找文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fzqsgyvw.html

find . -name "*.log" -type f
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jmwrcszl.html

[R44] 按修改时间查找
来源：http://dali.jianghu66.top/Article/details/gt2rntpeoko.html

find . -mtime -7 -type f
来源：http://dali.haohaochexian.top/Article/details/gt2jenkqqbu.html

[R45] 批量删除
来源：http://dali.shuidangran.top/Article/details/gt2jnynyfnw.html

find . -name "*.tmp" -delete
来源：http://dali.cqqwz.cn/Article/details/gt2dceoshhr.html

[R46] 递归替换文件内容
来源：http://dali.guowangkeji.top/Article/details/gt2iotdfjxo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenjidiqi.icu/Article/details/gt2ifkmhjli.html

[R47] sed 单行替换
来源：http://dali.nanxuanxn.top/Article/details/gt2xexskwkx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ivvv.top/Article/details/gt2wedzycqb.html

[R48] awk 取指定列
来源：http://dali.fzhhl.top/Article/details/gt2uiprfhrq.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2iptrbwed.html

[R49] awk 带条件
来源：http://dali.fengsongda.top/Article/details/gt2ccxelycm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.kuanghao11.cn/Article/details/gt2ehnwfhxj.html

[R50] awk 求和
来源：http://dali.aibaodan.cn/Article/details/gt2lgejjkcu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj202588.top/Article/details/gt2qrmsgfaz.html

[R51] 排序去重取前几
来源：http://dali.jinqigfzy.top/Article/details/gt2rmbeiumk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxuanxn.top/Article/details/gt2qvypileu.html

[R52] 统计行数
来源：http://dali.zhongyouzk.top/Article/details/gt2hzhmubyi.html

wc -l a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2bzgqcegy.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258.top/Article/details/gt2dpuzdahy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxuanxn.top/Article/details/gt2ibejxttu.html

[R54] 比较两个文件
来源：http://dali.wangdashe.top/Article/details/gt2sheyepwu.html

diff a.txt b.txt
来源：http://dali.iojbl.cn/Article/details/gt2kvnwnuen.html

[R55] 压缩与解压
来源：http://dali.yj202588.top/Article/details/gt2nqfntsjb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhengqikj.top/Article/details/gt2hcalchoo.html

[R56] 远程拷贝
来源：http://dali.zdqjudy.top/Article/details/gt2hoxigeme.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gt2dzkaavri.html

[R57] 远程执行命令
来源：http://dali.hnqzz.top/Article/details/gt2hrkwgyhv.html

ssh user@host 'uptime'
来源：http://dali.shangyingyoupin.top/Article/details/gt2jptfodug.html

[R58] 下载文件
来源：http://dali.zhoulong.xyz/Article/details/gt2mkgjqvxt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ydzc1.top/Article/details/gt2etqaajcb.html

[R59] 发 POST JSON
来源：http://dali.ydzc1.top/Article/details/gt2bextquuv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ivvv.top/Article/details/gt2ykplowdb.html

[R60] 只看 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gt2xrlrhdje.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zycfv.cn/Article/details/gt2mqotngvi.html

[R61] 磁盘占用
来源：http://dali.hywenlv.cn/Article/details/gt2dtpkicft.html

df -h;  du -sh *
来源：http://dali.gotoacloud.top/Article/details/gt2jngqwwhl.html

[R62] 找最占空间的文件
来源：http://dali.fzhhl.top/Article/details/gt2trpouvka.html

du -ah . | sort -rh | head -10
来源：http://dali.hnxiangtu.top/Article/details/gt2qbfmszhv.html

[R63] 内存与进程
来源：http://dali.vqdsnc.cn/Article/details/gt2syfayayf.html

free -h;  ps aux | grep nginx
来源：http://dali.yanxiufei.cn/Article/details/gt2oyauzahv.html

[R64] 结束进程
来源：http://dali.quarkkingdee.top/Article/details/gt2wmyoppmx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xwmldndr.html

[R65] 查看端口占用
来源：http://dali.snrcjt.cn/Article/details/gt2ondolvcq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yanxiufei.cn/Article/details/gt2rbyhpxzl.html

[R66] 定时任务
来源：http://dali.pengpengdd.cyou/Article/details/gt2shwycpra.html

crontab -e;  crontab -l
来源：http://dali.yj202588.top/Article/details/gt2okzkishu.html

[R67] 生成随机十六进制串
来源：http://dali.zhiwuduotai.top/Article/details/gt2bwxouzlo.html

openssl rand -hex 16
来源：http://dali.ydzc1.top/Article/details/gt2jhxvisjl.html

[R68] 计算文件校验值
来源：http://dali.c1oappe.top/Article/details/gt2zhpoqneh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2jqjpepmj.html

[R69] 生成随机密码
来源：http://dali.yueranfly.top/Article/details/gt2fmtzwkyd.html

head -c 16 /dev/urandom | base64
来源：http://dali.jiagoushi.top/Article/details/gt2bsrhcppd.html

[R70] 时间戳与互转
来源：http://dali.havefunace.top/Article/details/gt2raydxxzs.html

date +%s;  date -d @1700000000
来源：http://dali.pycfn.com/Article/details/gt2kehtmrcv.html

[R71] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gt2iqdptlgs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tvhravey.html

[R72] 等待端口就绪
来源：http://dali.guannengcc.top/Article/details/gt2vgjaihfy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gt2qxeotqvj.html

[R73] 分割大日志
来源：http://dali.jqgufenzy.top/Article/details/gt2xayblwxv.html

split -l 1000 big.log part_
来源：http://dali.yvedp.cn/Article/details/gt2oljfcyri.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rudedtod.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aywqnlfv.html

[R75] 导出环境变量
来源：http://dali.zdqjudy.top/Article/details/gt2odudtgid.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.smart0.xyz/Article/details/gt2uotmpbdq.html

[R76] 使用临时文件
来源：http://dali.hnqzz.top/Article/details/gt2xskwvkwz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gt2blxrauhn.html

[R77] 读取用户输入
来源：http://dali.dianchejie.cn/Article/details/gt2fkiyyibs.html

read -rp "请输入: " ans
来源：http://dali.havefunace.top/Article/details/gt2nzgtqtxk.html

[R78] 交互式菜单
来源：http://dali.zycfv.cn/Article/details/gt2ldejyoyi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2glfzprrp.html

[R79] 解析命令行选项
来源：http://dali.gzhubu.top/Article/details/gt2sfreyxxf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yonumen.top/Article/details/gt2jokexfnf.html

[R80] 查看脚本执行耗时
来源：http://dali.gotoacloud.top/Article/details/gt2iipksqzb.html

time ./run.sh
来源：http://dali.pengpengdd.cyou/Article/details/gt2chwriaoh.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ixsjfmjr.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gt2pwvaztoj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2jcnvucse.html

[S01] C：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2qdeubqkj.html

#include <stdio.h>
来源：http://dali.yongpay.top/Article/details/gt2zesiyvlq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hywenlv.cn/Article/details/gt2eayonbcz.html

[S02] C：变量与格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gt2rigfjarx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhiwuduotai.top/Article/details/gt2igbwmfeb.html

[S03] C：读入整数
来源：http://dali.ydzc1.top/Article/details/gt2uvihevln.html

int x; scanf("%d", &x);
来源：http://dali.birdmap.top/Article/details/gt2ltzukblk.html

[S04] C：字符串复制
来源：http://dali.yangfankeji.com/Article/details/gt2gtxfajpp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2dbvcbziy.html

[S05] C：字符串长度
来源：http://dali.sxryk.cn/Article/details/gt2fdevutbz.html

strlen(s)
来源：http://dali.hnqzz.top/Article/details/gt2zharaddu.html

[S06] C：字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2wudcxkvx.html

strcmp(a, b) == 0
来源：http://dali.dianchejie.cn/Article/details/gt2ykgkdwfe.html

[S07] C：数组遍历求和
来源：http://dali.redwolf501.top/Article/details/gt2wdwaewyg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xinyue.icu/Article/details/gt2umldnxpr.html

[S08] C：动态内存分配与释放
来源：http://dali.jianghu66.top/Article/details/gt2ipfkgcym.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuanzx.com/Article/details/gt2ysmxzumw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhixingplan.top/Article/details/gt2yhxlgvqc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sweek.top/Article/details/gt2wfdurctd.html

[S10] C：指针与解引用
来源：http://dali.ybcxt.top/Article/details/gt2ckqonneo.html

int *p = &a;  *p = 5;
来源：http://dali.sysykeji.top/Article/details/gt2wqbcmaim.html

[S11] C：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gt2oulingod.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yvedp.cn/Article/details/gt2xydywory.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nwbrower.top/Article/details/gt2xhozetcj.html

fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gt2xkcafyvg.html

[S12] C：写文件
来源：http://dali.cdnleiting.top/Article/details/gt2ongpwexh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jianghu66.top/Article/details/gt2mflqusqa.html

[S13] C：宏定义
来源：http://dali.yuxming.cn/Article/details/gt2vnqktjks.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tianlin.xyz/Article/details/gt2mzznlnsi.html

[S14] C：枚举
来源：http://dali.wangdashe.top/Article/details/gt2hyktmrwn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daria6918.cn/Article/details/gt2gflhmszy.html

[S15] C：类型转换
来源：http://dali.sysykeji.top/Article/details/gt2imvcrbvn.html

(double) a / b
来源：http://dali.dashuyun.cn/Article/details/gt2jnnsouvo.html

[S16] C：位操作置位
来源：http://dali.gotoacloud.top/Article/details/gt2ewdzacyh.html

x |= (1 << 3);
来源：http://dali.pycfn.com/Article/details/gt2tmlaqscr.html

[S17] C：安全拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gt2epeeedno.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xziqi.cn/Article/details/gt2vlmgvvvx.html

[S18] C：命令行参数
来源：http://dali.tanke756.top/Article/details/gt2crkbxlps.html

int main(int argc, char **argv)
来源：http://dali.nanxuanxn.top/Article/details/gt2hcxgbxex.html

[S19] C：快速排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xypgtiro.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gt2pmlqlmhd.html

[S20] C：二分查找
来源：http://dali.316326.xyz/Article/details/gt2hwylluhr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gt2ynumiukp.html

[S21] C：字符类别判断
来源：http://dali.iojbl.cn/Article/details/gt2zopegamr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ehwqpu.com/Article/details/gt2ergmqgdd.html

[S22] C：字符串转数字
来源：http://dali.jianghu66.top/Article/details/gt2sdklnakk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fzhhl.top/Article/details/gt2oiqszkhc.html

[S23] C：随机数
来源：http://dali.ppjwa.cn/Article/details/gt2ssznefdn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhongyouzk.top/Article/details/gt2lcgsmjiq.html

[S24] C：获取本地时间
来源：http://dali.zhiwuduotai.top/Article/details/gt2rwckifyq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yangfankeji.com/Article/details/gt2qfhtjlql.html

[S25] C：内存拷贝
来源：http://dali.yongpay.top/Article/details/gt2ihffhdiu.html

memcpy(dst, src, n);
来源：http://dali.svipenyu.cn/Article/details/gt2ewvmhkde.html

[S26] C：内存清零
来源：http://dali.zhengqikj.top/Article/details/gt2zrtigwjd.html

memset(a, 0, sizeof a);
来源：http://dali.kuanghao11.cn/Article/details/gt2gjsgcvki.html

[S27] C：定义常量
来源：http://dali.shangyingyoupin.top/Article/details/gt2jlirtagf.html

const double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gt2kbpltszi.html

[S28] C：静态变量
来源：http://dali.yuanzhike.top/Article/details/gt2ywbthtti.html

static int counter = 0;
来源：http://dali.feifeiyinyue.top/Article/details/gt2srncmtvo.html

[S29] C：变参函数
来源：http://dali.yvedp.cn/Article/details/gt2jrubsbic.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hnobgpgy.html

[S30] C：头文件保护
来源：http://dali.shuidangran.top/Article/details/gt2atkourgr.html

#ifndef X_H
来源：http://dali.hongshengwenyu.top/Article/details/gt2imzgpkli.html

#define X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cnxmullp.html

#endif
来源：http://dali.dashuyun.cn/Article/details/gt2uptoaszn.html

[S31] C++：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2xkeevizu.html

#include <iostream>
来源：http://dali.jinqigufen.top/Article/details/gt2svtgeauh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shuidangran.top/Article/details/gt2qlfuooss.html

[S32] C++：字符串
来源：http://dali.chenzaomai.com/Article/details/gt2gegvpgwd.html

std::string s = "hi";  s += "!";
来源：http://dali.sxryk.cn/Article/details/gt2zyhzkadu.html

[S33] C++：vector 增删
来源：http://dali.sxryk.cn/Article/details/gt2mmbqccby.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hafybgie.html

[S34] C++：遍历 vector
来源：http://dali.bjfxy.top/Article/details/gt2pcbgerjk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jqgfzy.top/Article/details/gt2nqlsxnfn.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gt2oilckqtk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2frspislr.html

[S36] C++：unordered_map
来源：http://dali.dashuyun.cn/Article/details/gt2niolbwwl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ejibzxtc.html

[S37] C++：set
来源：http://dali.0kj1m.cn/Article/details/gt2khhlivtb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.c1oappe.top/Article/details/gt2iphndkqb.html

[S38] C++：排序
来源：http://dali.zhengqikj.top/Article/details/gt2glxikyoq.html

std::sort(v.begin(), v.end());
来源：http://dali.shzxlz.cn/Article/details/gt2wdonmznu.html

[S39] C++：自定义比较器排序
来源：http://dali.shuidangran.top/Article/details/gt2cvawvnwn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tanke756.top/Article/details/gt2qlsxrpfg.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gt2jgjnatfa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.fzhhl.top/Article/details/gt2zxfoeizc.html

[S41] C++：类与构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2qnqchheu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.quarkkingdee.top/Article/details/gt2uazxxnpd.html

[S42] C++：继承与虚函数
来源：http://dali.c1oappe.top/Article/details/gt2qlxlgmsp.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zfsaionz.html

[S43] C++：智能指针
来源：http://dali.sweek.top/Article/details/gt2awhefcrw.html

auto p = std::make_unique<int>(5);
来源：http://dali.gzhubu.top/Article/details/gt2hfiaoqxu.html

[S44] C++：引用传参
来源：http://dali.ybcxt.top/Article/details/gt2rwtyitwe.html

void inc(int &x) { ++x; }
来源：http://dali.jqgfzy.top/Article/details/gt2iesxgpms.html

[S45] C++：lambda
来源：http://dali.shuidangran.top/Article/details/gt2dhjknrrs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hysaishi.cn/Article/details/gt2jcbgpyhs.html

[S46] C++：函数模板
来源：http://dali.jinqigufen.top/Article/details/gt2gtxjxaoz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gotoacloud.top/Article/details/gt2uaopqjfk.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258.top/Article/details/gt2stqzbfpn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dianchejie.cn/Article/details/gt2cbniapxl.html

[S48] C++：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gt2pclsjawl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.redwolf501.top/Article/details/gt2hxpggafk.html

while (std::getline(in, line)) { }
来源：http://dali.yj202588.top/Article/details/gt2ggbvdkxp.html

[S49] C++：写文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rexlfigq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sxryk.cn/Article/details/gt2gervuovf.html

[S50] C++：格式化数字
来源：http://dali.shangyingyoupin.top/Article/details/gt2wotrtiss.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2jkawsyya.html

[S51] C++：显式类型转换
来源：http://dali.zhongyouzk.top/Article/details/gt2geqkheqy.html

static_cast<double>(a) / b
来源：http://dali.cucudq.cn/Article/details/gt2pyyyqefi.html

[S52] C++：const 与 noexcept
来源：http://dali.gzhubu.top/Article/details/gt2uqwideva.html

int size() const noexcept { return n_; }
来源：http://dali.havefunace.top/Article/details/gt2hyfxbswi.html

[S53] C++：移动语义
来源：http://dali.shzxlz.cn/Article/details/gt2cwyxfmfi.html

std::vector<int> w = std::move(v);
来源：http://dali.yj202588.top/Article/details/gt2cgeydrmk.html

[S54] C++：异常处理
来源：http://dali.xziqi.cn/Article/details/gt2nawffqjq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jyoumei.cn/Article/details/gt2iexcuouf.html

[S55] C++：结构化绑定
来源：http://dali.havefunace.top/Article/details/gt2rmitcqlw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yonumen.top/Article/details/gt2ncgklryn.html

[S56] C++：optional
来源：http://dali.bjfxy.top/Article/details/gt2vxyhkntc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gzhubu.top/Article/details/gt2kkshsfdm.html

[S57] C++：编译期常量
来源：http://dali.jiagoushi.top/Article/details/gt2rjrlqrqh.html

constexpr int N = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vzhmmpdq.html

[S58] C++：命名空间
来源：http://dali.wangshuangyany.cn/Article/details/gt2dlytrehw.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuanzhike.top/Article/details/gt2hvxgycki.html

[S59] C++：静态断言
来源：http://dali.zdqjudy.top/Article/details/gt2ynkfywhs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwgqeoom.html

[S60] C++：遍历并删除元素
来源：http://dali.xuanzx.com/Article/details/gt2thlaeuzr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yjbfcxjk.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2lbcgyuxu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.meibo888.top/Article/details/gt2wpvncmcy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2vappwwbr.html

[T01] Kotlin：Hello World
来源：http://dali.316326.xyz/Article/details/gt2phfubllo.html

println("Hello")
来源：http://dali.sweek.top/Article/details/gt2zsnwjgpv.html

[T02] Kotlin：变量
来源：http://dali.jyoumei.cn/Article/details/gt2jcdzzwxc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fengsongda.top/Article/details/gt2vuidfeuw.html

[T03] Kotlin：字符串模板
来源：http://dali.jianghu66.top/Article/details/gt2nofuwzxz.html

"值: $b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wpwrqzdv.html

[T04] Kotlin：空安全
来源：http://dali.0kj1m.cn/Article/details/gt2srvnbbmp.html

val n: String? = null;  n?.length
来源：http://dali.ydzc1.top/Article/details/gt2pmhswsfn.html

[T05] Kotlin：when 表达式
来源：http://dali.cashguo.top/Article/details/gt2chsejafv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nwbrower.top/Article/details/gt2petrntye.html

[T06] Kotlin：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zsakveky.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.redwolf501.top/Article/details/gt2rpjytfjd.html

[T07] Kotlin：集合过滤
来源：http://dali.hysaishi.cn/Article/details/gt2hoxpdlry.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gaohongyu789.top/Article/details/gt2jenglceu.html

[T08] Kotlin：数据类
来源：http://dali.yj20258888.top/Article/details/gt2rfldeuzd.html

data class User(val name: String, val age: Int)
来源：http://dali.vqdsnc.cn/Article/details/gt2qwvuprnq.html

[T09] Kotlin：扩展函数
来源：http://dali.pycfn.com/Article/details/gt2yhqigbkj.html

fun String.exclaim() = this + "!"
来源：http://dali.pycfn.com/Article/details/gt2xwbvjunv.html

[T10] Kotlin：默认参数
来源：http://dali.cashguo.top/Article/details/gt2jwtshfku.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jlsjyb.cn/Article/details/gt2gevaqkpj.html

[T11] Kotlin：协程
来源：http://dali.jqgfzy.top/Article/details/gt2efofpbzz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ivvv.top/Article/details/gt2fnsrgvkz.html

[T12] Kotlin：解构声明
来源：http://dali.feifeiyinyue.top/Article/details/gt2jbryjutn.html

val (a, b) = Pair(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gt2bgtokavj.html

[T13] Kotlin：只读 Map
来源：http://dali.yueranfly.top/Article/details/gt2yaiuqjkx.html

val m = mapOf("a" to 1)
来源：http://dali.yangfankeji.com/Article/details/gt2wjwdsjvi.html

[T14] Kotlin：循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2qdnmdbfy.html

for (i in 1..10) println(i)
来源：http://dali.hfpthk.cn/Article/details/gt2ovpejhgs.html


<!-- 参考信息 -->