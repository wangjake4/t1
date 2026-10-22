代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gt2luhtfiba.html

[R14] C 风格 for
来源：http://dali.nwbrower.top/Article/details/gt2ptaihhxk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guowangkeji.top/Article/details/gt2zffscndb.html

[R15] while 逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2rwqcruco.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxinkj.top/Article/details/gt2vgnqrawt.html

[R16] until 等待条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekceeqtu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gt2hiqblekt.html

[R17] 数组定义与取值
来源：http://dali.shangyingyoupin.top/Article/details/gt2ypdnzxtv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shzxlz.cn/Article/details/gt2ivalhkkz.html

[R18] 遍历数组
来源：http://dali.yonumen.top/Article/details/gt2ttusnzof.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.iojbl.cn/Article/details/gt2xmlprght.html

[R19] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gt2dzkbcymw.html

echo "${#arr[@]}"
来源：http://dali.dashuyun.cn/Article/details/gt2rkmqfrpo.html

[R20] 关联数组（字典）
来源：http://dali.xziqi.cn/Article/details/gt2recnmcfw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.9152youxi.cn/Article/details/gt2ebgetucr.html

[R21] 字符串长度
来源：http://dali.yj20258.top/Article/details/gt2hysnhmme.html

echo "${#s}"
来源：http://dali.nwbrower.top/Article/details/gt2emubelli.html

[R22] 截取子串
来源：http://dali.smart0.xyz/Article/details/gt2lkcvcgbr.html

echo "${s:0:5}"
来源：http://dali.9152youxi.cn/Article/details/gt2xxxijsos.html

[R23] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sfjjteib.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.quarkkingdee.top/Article/details/gt2ggcyaspo.html

[R24] 大小写转换
来源：http://dali.yj202588.top/Article/details/gt2nquwybpn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tianlin.xyz/Article/details/gt2fpnwiqaf.html

[R25] 去后缀 / 去前缀
来源：http://dali.hysaishi.cn/Article/details/gt2nmeogdji.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guannengcc.top/Article/details/gt2vxngwrbj.html

[R26] 命令替换
来源：http://dali.wangdashe.top/Article/details/gt2xsrqcasx.html

now=$(date +%F); echo "$now"
来源：http://dali.sxryk.cn/Article/details/gt2uzrgnllh.html

[R27] 算术展开
来源：http://dali.dashuyun.cn/Article/details/gt2eiwcufrs.html

echo $((1 + 2 * 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qrchmxvu.html

[R28] 浮点运算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rbezpude.html

echo "scale=2; 10/3" | bc
来源：http://dali.daria6918.cn/Article/details/gt2zqsmtasn.html

[R29] 定义函数
来源：http://dali.hammf.cn/Article/details/gt2bficyvka.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2xvcjhpht.html

[R30] 函数返回状态码
来源：http://dali.cucudq.cn/Article/details/gt2zcpvahzk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.c1oappe.top/Article/details/gt2amrlkcet.html

[R31] 局部变量
来源：http://dali.gaohongyu789.top/Article/details/gt2faycuzay.html

f() { local x=1; echo "$x"; }
来源：http://dali.dianchejie.cn/Article/details/gt2edlgbruz.html

[R32] 参数个数校验
来源：http://dali.yj202588.top/Article/details/gt2cgufpdwg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gt2nrxcdmep.html

[R33] 捕获错误并提示行号
来源：http://dali.cqqwz.cn/Article/details/gt2mnvcfoak.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cdnleiting.top/Article/details/gt2zvygkxsu.html

[R34] 退出时清理
来源：http://dali.xuetiantiany.cn/Article/details/gt2ijxroxsy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gt2aslitdqg.html

[R35] 后台执行并等待
来源：http://dali.bjfxy.top/Article/details/gt2vdunybro.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sysykeji.top/Article/details/gt2qqvxespe.html

[R36] 并发执行多个任务
来源：http://dali.bjfxy.top/Article/details/gt2bulpxkar.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dashuyun.cn/Article/details/gt2rxfspgwr.html

[R37] 把输出赋给变量
来源：http://dali.hammf.cn/Article/details/gt2hassqngk.html

files=$(ls -1)
来源：http://dali.yueranfly.top/Article/details/gt2rokaknxn.html

[R38] 管道串联
来源：http://dali.havefunace.top/Article/details/gt2uakwupiv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fzhhl.top/Article/details/gt2oeelipbq.html

[R39] 重定向标准输出与错误
来源：http://dali.jyoumei.cn/Article/details/gt2qoyuzkye.html

cmd > out.log 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gt2fkezeamk.html

[R40] 追加写日志
来源：http://dali.sysykeji.top/Article/details/gt2eqbqsobs.html

echo "log" >> out.log
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njncabzu.html

[R41] 丢弃输出
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hnrtczor.html

cmd >/dev/null 2>&1
来源：http://dali.ydzc1.top/Article/details/gt2qrqcmsfp.html

[R42] 输入重定向
来源：http://dali.andypj.xyz/Article/details/gt2futwognw.html

wc -l < a.txt
来源：http://dali.sufxvd.cn/Article/details/gt2dacinzqr.html

[R43] 按名字查找文件
来源：http://dali.gzhubu.top/Article/details/gt2lvwprspi.html

find . -name "*.log" -type f
来源：http://dali.gzhubu.top/Article/details/gt2ojqlkoxz.html

[R44] 按修改时间查找
来源：http://dali.tanke756.top/Article/details/gt2zgfnswqd.html

find . -mtime -7 -type f
来源：http://dali.cdnleiting.top/Article/details/gt2ltptmsio.html

[R45] 批量删除
来源：http://dali.shuidangran.top/Article/details/gt2zxpfqkmc.html

find . -name "*.tmp" -delete
来源：http://dali.cucudq.cn/Article/details/gt2zecncpay.html

[R46] 递归替换文件内容
来源：http://dali.cheryme.top/Article/details/gt2kmndbuvs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuetiantiany.cn/Article/details/gt2oojfsyfs.html

[R47] sed 单行替换
来源：http://dali.zhongyouzk.top/Article/details/gt2hfsycdgt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pycfn.com/Article/details/gt2uyijkdqo.html

[R48] awk 取指定列
来源：http://dali.sweek.top/Article/details/gt2npbhncwy.html

awk '{print $1, $3}' a.txt
来源：http://dali.c1oappe.top/Article/details/gt2ucuhbzld.html

[R49] awk 带条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbxhecmk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nwbrower.top/Article/details/gt2qdizghwu.html

[R50] awk 求和
来源：http://dali.mhx1999.top/Article/details/gt2crcjqqve.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.redwolf501.top/Article/details/gt2uswwmuox.html

[R51] 排序去重取前几
来源：http://dali.dashuyun.cn/Article/details/gt2yjcueeud.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gogol.net.cn/Article/details/gt2ioditzqd.html

[R52] 统计行数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vqhymavv.html

wc -l a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2nfnuuzph.html

[R53] 查看文件头与实时尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hnfgxkxj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cucudq.cn/Article/details/gt2oyrcsxco.html

[R54] 比较两个文件
来源：http://dali.jqgfzy.top/Article/details/gt2hvdzfizl.html

diff a.txt b.txt
来源：http://dali.redwolf501.top/Article/details/gt2jlkdrovi.html

[R55] 压缩与解压
来源：http://dali.sufxvd.cn/Article/details/gt2hihnsnko.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258888.top/Article/details/gt2wkpdfomg.html

[R56] 远程拷贝
来源：http://dali.ehwqpu.com/Article/details/gt2galvnzxv.html

scp file user@host:/path/
来源：http://dali.bjfxy.top/Article/details/gt2jfvkiopn.html

[R57] 远程执行命令
来源：http://dali.meibo888.top/Article/details/gt2zapfakwh.html

ssh user@host 'uptime'
来源：http://dali.vqdsnc.cn/Article/details/gt2tnswaxfn.html

[R58] 下载文件
来源：http://dali.bjfxy.top/Article/details/gt2hvwmaqsp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.9152youxi.cn/Article/details/gt2xlqmxddi.html

[R59] 发 POST JSON
来源：http://dali.yj20258888.top/Article/details/gt2afjuluwp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guannengcc.top/Article/details/gt2darunetu.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gt2bkmqebli.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.svipenyu.cn/Article/details/gt2cyecghlq.html

[R61] 磁盘占用
来源：http://dali.snrcjt.cn/Article/details/gt2kficflzq.html

df -h;  du -sh *
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gmyejctg.html

[R62] 找最占空间的文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2teibxkzq.html

du -ah . | sort -rh | head -10
来源：http://dali.quarkkingdee.top/Article/details/gt2hvnytzhf.html

[R63] 内存与进程
来源：http://dali.ehwqpu.com/Article/details/gt2siuhdbyg.html

free -h;  ps aux | grep nginx
来源：http://dali.quarkkingdee.top/Article/details/gt2tjhwdzsk.html

[R64] 结束进程
来源：http://dali.snrcjt.cn/Article/details/gt2gyxdriah.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zsaoliut.html

[R65] 查看端口占用
来源：http://dali.xylfe.cn/Article/details/gt2mjnkzeks.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ybcxt.top/Article/details/gt2acmvatlh.html

[R66] 定时任务
来源：http://dali.gogol.net.cn/Article/details/gt2vbhqjlle.html

crontab -e;  crontab -l
来源：http://dali.sufxvd.cn/Article/details/gt2tkiafvko.html

[R67] 生成随机十六进制串
来源：http://dali.yongpay.top/Article/details/gt2nxczhtuc.html

openssl rand -hex 16
来源：http://dali.pengpengdd.cyou/Article/details/gt2jdtczobr.html

[R68] 计算文件校验值
来源：http://dali.shuidangran.top/Article/details/gt2xxpzzpts.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhengqikj.top/Article/details/gt2ymsyeeml.html

[R69] 生成随机密码
来源：http://dali.feifeiyinyue.top/Article/details/gt2pbvdyfjx.html

head -c 16 /dev/urandom | base64
来源：http://dali.aibaodan.cn/Article/details/gt2dfhjhxiy.html

[R70] 时间戳与互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2afjaotvn.html

date +%s;  date -d @1700000000
来源：http://dali.zhixingplan.top/Article/details/gt2hzuupfvb.html

[R71] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gt2ezfxgpsi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hysaishi.cn/Article/details/gt2xtekwrrx.html

[R72] 等待端口就绪
来源：http://dali.guowangkeji.top/Article/details/gt2jdbovifp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gt2bslslxhz.html

[R73] 分割大日志
来源：http://dali.xylfe.cn/Article/details/gt2xlbndugm.html

split -l 1000 big.log part_
来源：http://dali.meibo888.top/Article/details/gt2rusmxrtz.html

[R74] 批量重命名
来源：http://dali.haohaochexian.top/Article/details/gt2vyxmeide.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhongyouzk.top/Article/details/gt2pxdauxyy.html

[R75] 导出环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2xcevasws.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pycfn.com/Article/details/gt2joycgrvg.html

[R76] 使用临时文件
来源：http://dali.dashuyun.cn/Article/details/gt2qxbetsrj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gt2gevwfynp.html

[R77] 读取用户输入
来源：http://dali.jiagoushi.top/Article/details/gt2hyidrvsx.html

read -rp "请输入: " ans
来源：http://dali.hammf.cn/Article/details/gt2vemfgkki.html

[R78] 交互式菜单
来源：http://dali.gaohongyu789.top/Article/details/gt2jcwwaojn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yongpay.top/Article/details/gt2trjvmlzp.html

[R79] 解析命令行选项
来源：http://dali.chenlongwang.top/Article/details/gt2asmuthap.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hfpthk.cn/Article/details/gt2iuplnyls.html

[R80] 查看脚本执行耗时
来源：http://dali.feifeiyinyue.top/Article/details/gt2afwobgvf.html

time ./run.sh
来源：http://dali.xuetiantiany.cn/Article/details/gt2xgagfmmq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2twyyetiq.html

S. C / C++ 专题
来源：http://dali.sysykeji.top/Article/details/gt2sjbkuzqb.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2xnycwjwz.html

[S01] C：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2zqwlbbpl.html

#include <stdio.h>
来源：http://dali.gzhubu.top/Article/details/gt2nlbngzau.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xinyue.icu/Article/details/gt2psnynytx.html

[S02] C：变量与格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gt2phjkkqyb.html

int a = 10; printf("%d\n", a);
来源：http://dali.yueranfly.top/Article/details/gt2whukzzeh.html

[S03] C：读入整数
来源：http://dali.ybcxt.top/Article/details/gt2muzpqrgy.html

int x; scanf("%d", &x);
来源：http://dali.jlsjyb.cn/Article/details/gt2zhnzprxc.html

[S04] C：字符串复制
来源：http://dali.cashguo.top/Article/details/gt2rslqipjq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj202588.top/Article/details/gt2hzdsxifo.html

[S05] C：字符串长度
来源：http://dali.yangfankeji.com/Article/details/gt2bilawosf.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2nhpgpknt.html

[S06] C：字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2femxpxmt.html

strcmp(a, b) == 0
来源：http://dali.svipenyu.cn/Article/details/gt2xsvhslfn.html

[S07] C：数组遍历求和
来源：http://dali.quarkkingdee.top/Article/details/gt2bdyqcvns.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xinyue.icu/Article/details/gt2bvvtofwk.html

[S08] C：动态内存分配与释放
来源：http://dali.xinyue.icu/Article/details/gt2zczspbfi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nwbrower.top/Article/details/gt2zprwkivp.html

[S09] C：结构体定义与初始化
来源：http://dali.aizwys.cn/Article/details/gt2bltpsrii.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenjidiqi.icu/Article/details/gt2swgfyixz.html

[S10] C：指针与解引用
来源：http://dali.daria6918.cn/Article/details/gt2tpzunxwn.html

int *p = &a;  *p = 5;
来源：http://dali.cucudq.cn/Article/details/gt2wfmtoutw.html

[S11] C：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gt2xsjdpyxs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpwbhbvp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cashguo.top/Article/details/gt2bcdhuvyj.html

fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gt2fxafzmfr.html

[S12] C：写文件
来源：http://dali.jinqigufen.top/Article/details/gt2qzligzgx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ifiydhtr.html

[S13] C：宏定义
来源：http://dali.jlsjyb.cn/Article/details/gt2resjbkne.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xylfe.cn/Article/details/gt2ymdalluy.html

[S14] C：枚举
来源：http://dali.9152youxi.cn/Article/details/gt2ekdpcebc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sxryk.cn/Article/details/gt2kcicceqo.html

[S15] C：类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2karjgkpo.html

(double) a / b
来源：http://dali.chenzaomai.com/Article/details/gt2ytrogzqe.html

[S16] C：位操作置位
来源：http://dali.zhiwuduotai.top/Article/details/gt2muangcqc.html

x |= (1 << 3);
来源：http://dali.sweek.top/Article/details/gt2kbuvuywl.html

[S17] C：安全拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gt2dryynnnr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daxiang520.top/Article/details/gt2mxabwlcm.html

[S18] C：命令行参数
来源：http://dali.cqqwz.cn/Article/details/gt2fbjcagzr.html

int main(int argc, char **argv)
来源：http://dali.dashuyun.cn/Article/details/gt2aoduonpu.html

[S19] C：快速排序
来源：http://dali.ydzc1.top/Article/details/gt2xdttkbyv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vvdqoyhs.html

[S20] C：二分查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdmlwpvf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gt2kaegeyet.html

[S21] C：字符类别判断
来源：http://dali.tianlin.xyz/Article/details/gt2mxpexpje.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yueranfly.top/Article/details/gt2iqemueco.html

[S22] C：字符串转数字
来源：http://dali.zdqjudy.top/Article/details/gt2evjuvaqh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gt2tdlrwzsh.html

[S23] C：随机数
来源：http://dali.tanke756.top/Article/details/gt2pghbvfpf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangshuangyany.cn/Article/details/gt2znixiokq.html

[S24] C：获取本地时间
来源：http://dali.gotoacloud.top/Article/details/gt2kyujzyvw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sweek.top/Article/details/gt2ropgfopz.html

[S25] C：内存拷贝
来源：http://dali.aibaodan.cn/Article/details/gt2fdkqwsxj.html

memcpy(dst, src, n);
来源：http://dali.andypj.xyz/Article/details/gt2cwdbaoys.html

[S26] C：内存清零
来源：http://dali.tian-w.cn/Article/details/gt2wqhcszmy.html

memset(a, 0, sizeof a);
来源：http://dali.hnxiangtu.top/Article/details/gt2jfwpsksh.html

[S27] C：定义常量
来源：http://dali.snrcjt.cn/Article/details/gt2dxoijwlt.html

const double PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gt2tuzduofi.html

[S28] C：静态变量
来源：http://dali.shuidangran.top/Article/details/gt2axwxfcjk.html

static int counter = 0;
来源：http://dali.jianghu66.top/Article/details/gt2jswyzega.html

[S29] C：变参函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xyqgzzmm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cashguo.top/Article/details/gt2vsbhparm.html

[S30] C：头文件保护
来源：http://dali.zhoulong.xyz/Article/details/gt2gcpiizsl.html

#ifndef X_H
来源：http://dali.wangdashe.top/Article/details/gt2rurigrax.html

#define X_H
来源：http://dali.nwbrower.top/Article/details/gt2haukahyj.html

#endif
来源：http://dali.0kj1m.cn/Article/details/gt2prebvtsd.html

[S31] C++：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2nlbfhvgj.html

#include <iostream>
来源：http://dali.0kj1m.cn/Article/details/gt2jnyehqyp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zlhaunqf.html

[S32] C++：字符串
来源：http://dali.sweek.top/Article/details/gt2djxrlvpd.html

std::string s = "hi";  s += "!";
来源：http://dali.yueranfly.top/Article/details/gt2vymponed.html

[S33] C++：vector 增删
来源：http://dali.xuanzx.com/Article/details/gt2xpugjmyn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cucudq.cn/Article/details/gt2ijapcqbf.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zfnloosn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gzhubu.top/Article/details/gt2vropbpyb.html

[S35] C++：map
来源：http://dali.quarkkingdee.top/Article/details/gt2lemdfpds.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2qwpvjxmu.html

[S36] C++：unordered_map
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfxrfjiq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2uwkbfmcv.html

[S37] C++：set
来源：http://dali.hysaishi.cn/Article/details/gt2qkxfipll.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guannengcc.top/Article/details/gt2tzaekhpe.html

[S38] C++：排序
来源：http://dali.jyoumei.cn/Article/details/gt2shathrkl.html

std::sort(v.begin(), v.end());
来源：http://dali.chenlongwang.top/Article/details/gt2fqrzpqbh.html

[S39] C++：自定义比较器排序
来源：http://dali.svipenyu.cn/Article/details/gt2omipgqmf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vhxqfkab.html

[S40] C++：查找元素
来源：http://dali.havefunace.top/Article/details/gt2jnhjyorg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2tlugoqnh.html

[S41] C++：类与构造函数
来源：http://dali.yanxiufei.cn/Article/details/gt2vzranolg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.snrcjt.cn/Article/details/gt2yjcuqbry.html

[S42] C++：继承与虚函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pizwvcrs.html

class B : public Base { public: void f() override {} };
来源：http://dali.kuanghao11.cn/Article/details/gt2icjjulzb.html

[S43] C++：智能指针
来源：http://dali.guowangkeji.top/Article/details/gt2kmaqtjtu.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgfzy.top/Article/details/gt2naarrkyl.html

[S44] C++：引用传参
来源：http://dali.cashguo.top/Article/details/gt2hmkvqqxk.html

void inc(int &x) { ++x; }
来源：http://dali.hammf.cn/Article/details/gt2hgdiiqac.html

[S45] C++：lambda
来源：http://dali.zhoulong.xyz/Article/details/gt2mrwedxfd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhengqikj.top/Article/details/gt2apibkowo.html

[S46] C++：函数模板
来源：http://dali.sweek.top/Article/details/gt2kcgleubz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenlongwang.top/Article/details/gt2hvbjepld.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2lgvebzit.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gt2uiqdkmre.html

[S48] C++：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gt2ddpspxnp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nwbrower.top/Article/details/gt2gkyuqzqo.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hcdwgmux.html

[S49] C++：写文件
来源：http://dali.gogol.net.cn/Article/details/gt2uahmcuxw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ovetxdcy.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gt2ptfqjkww.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xziqi.cn/Article/details/gt2avlrcatt.html

[S51] C++：显式类型转换
来源：http://dali.316326.xyz/Article/details/gt2vhzfdcha.html

static_cast<double>(a) / b
来源：http://dali.feifeiyinyue.top/Article/details/gt2zeoxsjcs.html

[S52] C++：const 与 noexcept
来源：http://dali.ybcxt.top/Article/details/gt2whtfgvja.html

int size() const noexcept { return n_; }
来源：http://dali.cashguo.top/Article/details/gt2lcbionqh.html

[S53] C++：移动语义
来源：http://dali.svipenyu.cn/Article/details/gt2nqcaqweq.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnehebsn.html

[S54] C++：异常处理
来源：http://dali.cdnleiting.top/Article/details/gt2yyijovzr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangdashe.top/Article/details/gt2oywkrwnz.html

[S55] C++：结构化绑定
来源：http://dali.nanxinkj.top/Article/details/gt2galbqxjy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2xyygkijd.html

[S56] C++：optional
来源：http://dali.ehwqpu.com/Article/details/gt2nkwafcgv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shzxlz.cn/Article/details/gt2flhonark.html

[S57] C++：编译期常量
来源：http://dali.sufxvd.cn/Article/details/gt2njdlrzno.html

constexpr int N = 10;
来源：http://dali.cqqwz.cn/Article/details/gt2oopjwiou.html

[S58] C++：命名空间
来源：http://dali.aizwys.cn/Article/details/gt2xzwvwits.html

namespace ns { int f() { return 1; } }
来源：http://dali.hysaishi.cn/Article/details/gt2oaqewxtp.html

[S59] C++：静态断言
来源：http://dali.pengpengdd.cyou/Article/details/gt2jqnglndr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.iojbl.cn/Article/details/gt2ddoaqeyw.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgufenzy.top/Article/details/gt2kbcxfpls.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gt2qbsjeowo.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2hfbpxzte.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gt2fyfyhgpd.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2uuxxzydu.html

[T01] Kotlin：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2byeomtrm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhumxdk.html

[T02] Kotlin：变量
来源：http://dali.0kj1m.cn/Article/details/gt2xfesuncd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sxryk.cn/Article/details/gt2htgohlha.html

[T03] Kotlin：字符串模板
来源：http://dali.zhiwuduotai.top/Article/details/gt2gbfpurwe.html

"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gxruibhd.html

[T04] Kotlin：空安全
来源：http://dali.ybcxt.top/Article/details/gt2qbvfikxr.html

val n: String? = null;  n?.length
来源：http://dali.yj202588.top/Article/details/gt2oykyorgc.html

[T05] Kotlin：when 表达式
来源：http://dali.tian-w.cn/Article/details/gt2qjokjyoe.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.aizwys.cn/Article/details/gt2ttoqgbry.html

[T06] Kotlin：集合映射
来源：http://dali.xuanzx.com/Article/details/gt2dxdkhgrq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2xemksvdp.html

[T07] Kotlin：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gt2ekegssxr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yonumen.top/Article/details/gt2djobogrw.html

[T08] Kotlin：数据类
来源：http://dali.bjfxy.top/Article/details/gt2rvkuvipb.html

data class User(val name: String, val age: Int)
来源：http://dali.daxiang520.top/Article/details/gt2upevhmkk.html

[T09] Kotlin：扩展函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2bzrdrepw.html

fun String.exclaim() = this + "!"
来源：http://dali.yangfankeji.com/Article/details/gt2fshhdiol.html

[T10] Kotlin：默认参数
来源：http://dali.tian-w.cn/Article/details/gt2meaobwiw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yongpay.top/Article/details/gt2vyffdika.html

[T11] Kotlin：协程
来源：http://dali.zhiwuduotai.top/Article/details/gt2onwywdir.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gt2xjllgxrd.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigufen.top/Article/details/gt2scewlynf.html

val (a, b) = Pair(1, 2)
来源：http://dali.c1oappe.top/Article/details/gt2azmacito.html

[T13] Kotlin：只读 Map
来源：http://dali.kuanghao11.cn/Article/details/gt2uuewazkc.html

val m = mapOf("a" to 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2teejpict.html

[T14] Kotlin：循环
来源：http://dali.ydzc1.top/Article/details/gt2fpcmxgra.html

for (i in 1..10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dawiqoto.html

[T15] Kotlin：接口
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mpbetcgi.html

interface Shape { fun area(): Double }
来源：http://dali.daria6918.cn/Article/details/gt2yqgjbzny.html

[T16] Swift：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2kpwcnrjk.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2neqfieft.html


<!-- 参考信息 -->