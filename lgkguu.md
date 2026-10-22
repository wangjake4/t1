代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gavjkzjd.html

[R08] 数值比较
来源：http://dali.fengsongda.top/Article/details/gt2jivogzdm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnxiangtu.top/Article/details/gt2obljhedg.html

[R09] 字符串比较
来源：http://dali.andypj.xyz/Article/details/gt2mmbkufvw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jlsjyb.cn/Article/details/gt2kvlhrtzp.html

[R10] 正则匹配
来源：http://dali.wangdashe.top/Article/details/gt2ofppzxfi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2xeiawjnx.html

[R11] case 多分支
来源：http://dali.chenjidiqi.icu/Article/details/gt2itrlsbtb.html

case "$1" in
来源：http://dali.iojbl.cn/Article/details/gt2bcaxkooo.html

start) echo "启动" ;;
来源：http://dali.yuanzhike.top/Article/details/gt2xvnmybdt.html

stop)  echo "停止" ;;
来源：http://dali.quarkkingdee.top/Article/details/gt2rrbboidh.html

*)     echo "未知命令" ;;
来源：http://dali.daxiang520.top/Article/details/gt2yjalcrgm.html

esac
来源：http://dali.yueranfly.top/Article/details/gt2ovusafww.html

[R12] for 遍历文件
来源：http://dali.jiagoushi.top/Article/details/gt2qjimtmfz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangdashe.top/Article/details/gt2kbujwzpl.html

[R13] for 计数循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fneeltzy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gt2vjbffrdr.html

[R14] C 风格 for
来源：http://dali.feifeiyinyue.top/Article/details/gt2ttoxkzwx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gt2glqnwjlr.html

[R15] while 逐行读文件
来源：http://dali.nwbrower.top/Article/details/gt2bhsnfbcl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqsrmufx.html

[R16] until 等待条件
来源：http://dali.yonumen.top/Article/details/gt2cvxhoqgs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gt2wtrhjwun.html

[R17] 数组定义与取值
来源：http://dali.redwolf501.top/Article/details/gt2peybovjz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yuxming.cn/Article/details/gt2twbobmfn.html

[R18] 遍历数组
来源：http://dali.hfpthk.cn/Article/details/gt2gqridpqy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xrjpouli.html

[R19] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gt2nkzmbebe.html

echo "${#arr[@]}"
来源：http://dali.daria6918.cn/Article/details/gt2huwqhlng.html

[R20] 关联数组（字典）
来源：http://dali.chenzaomai.com/Article/details/gt2xlzcowgv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pycfn.com/Article/details/gt2fxokqnhl.html

[R21] 字符串长度
来源：http://dali.meibo888.top/Article/details/gt2kjcdqqnx.html

echo "${#s}"
来源：http://dali.cashguo.top/Article/details/gt2wlddvdbf.html

[R22] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gt2kjzaxnfl.html

echo "${s:0:5}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2zxzizauc.html

[R23] 字符串替换
来源：http://dali.havefunace.top/Article/details/gt2iztftugg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sufxvd.cn/Article/details/gt2bapppqoo.html

[R24] 大小写转换
来源：http://dali.ydzc1.top/Article/details/gt2wyenrrru.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigfzy.top/Article/details/gt2zylkwoer.html

[R25] 去后缀 / 去前缀
来源：http://dali.hammf.cn/Article/details/gt2wuwwpihi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ppjwa.cn/Article/details/gt2uodtpenl.html

[R26] 命令替换
来源：http://dali.pycfn.com/Article/details/gt2lupzackn.html

now=$(date +%F); echo "$now"
来源：http://dali.cdnleiting.top/Article/details/gt2dtkewijg.html

[R27] 算术展开
来源：http://dali.nanxinkj.top/Article/details/gt2rbqssuoi.html

echo $((1 + 2 * 3))
来源：http://dali.wangdashe.top/Article/details/gt2chfjarst.html

[R28] 浮点运算
来源：http://dali.hnqzz.top/Article/details/gt2ztrthist.html

echo "scale=2; 10/3" | bc
来源：http://dali.gaohongyu789.top/Article/details/gt2vittsbto.html

[R29] 定义函数
来源：http://dali.yonumen.top/Article/details/gt2gicwclig.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.redwolf501.top/Article/details/gt2alecqrba.html

[R30] 函数返回状态码
来源：http://dali.yangfankeji.com/Article/details/gt2cjnbduyr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shangyingyoupin.top/Article/details/gt2utkmwwoj.html

[R31] 局部变量
来源：http://dali.sweek.top/Article/details/gt2lbetxgad.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhengqikj.top/Article/details/gt2ogmrqgre.html

[R32] 参数个数校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ruilypvw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gt2riivrrqu.html

[R33] 捕获错误并提示行号
来源：http://dali.c1oappe.top/Article/details/gt2hzoeebuz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkxdtib.html

[R34] 退出时清理
来源：http://dali.cheryme.top/Article/details/gt2dviwsgxt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gt2puhcdbsf.html

[R35] 后台执行并等待
来源：http://dali.fzhhl.top/Article/details/gt2gcbizyqk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hongshengwenyu.top/Article/details/gt2ezyvrjer.html

[R36] 并发执行多个任务
来源：http://dali.yueranfly.top/Article/details/gt2onevjwjr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xylfe.cn/Article/details/gt2godltmun.html

[R37] 把输出赋给变量
来源：http://dali.xziqi.cn/Article/details/gt2baxlwycr.html

files=$(ls -1)
来源：http://dali.nwbrower.top/Article/details/gt2dgaxqmpd.html

[R38] 管道串联
来源：http://dali.hnxiangtu.top/Article/details/gt2takhmmrj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.snrcjt.cn/Article/details/gt2llvaxbpt.html

[R39] 重定向标准输出与错误
来源：http://dali.cqqwz.cn/Article/details/gt2mmzfkpwu.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ytsgmxxc.html

[R40] 追加写日志
来源：http://dali.hysaishi.cn/Article/details/gt2uthfyxbe.html

echo "log" >> out.log
来源：http://dali.jiagoushi.top/Article/details/gt2rnrkbjla.html

[R41] 丢弃输出
来源：http://dali.bjfxy.top/Article/details/gt2iteoueyo.html

cmd >/dev/null 2>&1
来源：http://dali.shuidangran.top/Article/details/gt2lnulsvqj.html

[R42] 输入重定向
来源：http://dali.zhixingplan.top/Article/details/gt2zpvncasz.html

wc -l < a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2reyfyapi.html

[R43] 按名字查找文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2oprpyvas.html

find . -name "*.log" -type f
来源：http://dali.havefunace.top/Article/details/gt2yeglpbzb.html

[R44] 按修改时间查找
来源：http://dali.mhx1999.top/Article/details/gt2pxgubeqk.html

find . -mtime -7 -type f
来源：http://dali.jlsjyb.cn/Article/details/gt2pgauozoc.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gt2eppswlzb.html

find . -name "*.tmp" -delete
来源：http://dali.bjfxy.top/Article/details/gt2xmhpegex.html

[R46] 递归替换文件内容
来源：http://dali.haohaochexian.top/Article/details/gt2ysdrfizs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gzhubu.top/Article/details/gt2kdurxfbc.html

[R47] sed 单行替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2wwiwadic.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2qiitnahb.html

[R48] awk 取指定列
来源：http://dali.zhixingplan.top/Article/details/gt2grhunugl.html

awk '{print $1, $3}' a.txt
来源：http://dali.316326.xyz/Article/details/gt2ufjyhaol.html

[R49] awk 带条件
来源：http://dali.sxryk.cn/Article/details/gt2szmglzjq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhiwuduotai.top/Article/details/gt2rsephyqk.html

[R50] awk 求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kdnybock.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yueranfly.top/Article/details/gt2guzksrgb.html

[R51] 排序去重取前几
来源：http://dali.hnqzz.top/Article/details/gt2ogqxiozk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guowangkeji.top/Article/details/gt2duwwhavf.html

[R52] 统计行数
来源：http://dali.xuetiantiany.cn/Article/details/gt2lcupyivr.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyfzgid.html

[R53] 查看文件头与实时尾
来源：http://dali.0kj1m.cn/Article/details/gt2djlawgrp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tanke756.top/Article/details/gt2iszolvzi.html

[R54] 比较两个文件
来源：http://dali.gogol.net.cn/Article/details/gt2jvdgmslu.html

diff a.txt b.txt
来源：http://dali.haohaochexian.top/Article/details/gt2kixxpahc.html

[R55] 压缩与解压
来源：http://dali.ivvv.top/Article/details/gt2iluvfmqw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tian-w.cn/Article/details/gt2uqaohhoo.html

[R56] 远程拷贝
来源：http://dali.mhx1999.top/Article/details/gt2tdjjuxpe.html

scp file user@host:/path/
来源：http://dali.xziqi.cn/Article/details/gt2uvvmakqq.html

[R57] 远程执行命令
来源：http://dali.nanxuanxn.top/Article/details/gt2jtbnrjsg.html

ssh user@host 'uptime'
来源：http://dali.aibaodan.cn/Article/details/gt2blfgurlf.html

[R58] 下载文件
来源：http://dali.jqgfzy.top/Article/details/gt2swttcemd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ehwqpu.com/Article/details/gt2mjqzgxga.html

[R59] 发 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gt2qylmwwsy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258.top/Article/details/gt2roxkxxwi.html

[R60] 只看 HTTP 状态码
来源：http://dali.ehwqpu.com/Article/details/gt2fyrkcoej.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zeejiquc.html

[R61] 磁盘占用
来源：http://dali.feifeiyinyue.top/Article/details/gt2bvwrdsge.html

df -h;  du -sh *
来源：http://dali.xylfe.cn/Article/details/gt2gexhezjh.html

[R62] 找最占空间的文件
来源：http://dali.jqgfzy.top/Article/details/gt2ksenfsog.html

du -ah . | sort -rh | head -10
来源：http://dali.dianchejie.cn/Article/details/gt2nuvqlvym.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gt2sitxtlzf.html

free -h;  ps aux | grep nginx
来源：http://dali.wangdashe.top/Article/details/gt2tzklweka.html

[R64] 结束进程
来源：http://dali.hfpthk.cn/Article/details/gt2zisextbp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj202588.top/Article/details/gt2qktowjfw.html

[R65] 查看端口占用
来源：http://dali.aizwys.cn/Article/details/gt2nasgucib.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rhjllxqt.html

[R66] 定时任务
来源：http://dali.yonumen.top/Article/details/gt2digmajhc.html

crontab -e;  crontab -l
来源：http://dali.xuetiantiany.cn/Article/details/gt2vbphhjdg.html

[R67] 生成随机十六进制串
来源：http://dali.hysaishi.cn/Article/details/gt2srynlceo.html

openssl rand -hex 16
来源：http://dali.vqdsnc.cn/Article/details/gt2xcycojch.html

[R68] 计算文件校验值
来源：http://dali.jinqigfzy.top/Article/details/gt2chlagyja.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2pikmyfgl.html

[R69] 生成随机密码
来源：http://dali.svipenyu.cn/Article/details/gt2ocvnzozz.html

head -c 16 /dev/urandom | base64
来源：http://dali.shzxlz.cn/Article/details/gt2vinljlgs.html

[R70] 时间戳与互转
来源：http://dali.yj202588.top/Article/details/gt2tvwbreki.html

date +%s;  date -d @1700000000
来源：http://dali.zhixingplan.top/Article/details/gt2txptghmh.html

[R71] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gt2abbrlbqo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenlongwang.top/Article/details/gt2lellleju.html

[R72] 等待端口就绪
来源：http://dali.wangdashe.top/Article/details/gt2orgjlxxm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2zwtnbxni.html

[R73] 分割大日志
来源：http://dali.cucudq.cn/Article/details/gt2zqlggcfa.html

split -l 1000 big.log part_
来源：http://dali.yj20258.top/Article/details/gt2rgstnsgj.html

[R74] 批量重命名
来源：http://dali.chenlongwang.top/Article/details/gt2atwspqms.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuxming.cn/Article/details/gt2lpbefphq.html

[R75] 导出环境变量
来源：http://dali.chenzaomai.com/Article/details/gt2ewcxdmzy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnqzz.top/Article/details/gt2mcwneqww.html

[R76] 使用临时文件
来源：http://dali.yvedp.cn/Article/details/gt2herwmeju.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gt2gamuraak.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qlvxdogx.html

read -rp "请输入: " ans
来源：http://dali.mhx1999.top/Article/details/gt2etwalcxh.html

[R78] 交互式菜单
来源：http://dali.yongpay.top/Article/details/gt2geulqeul.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fengsongda.top/Article/details/gt2grbfuuvk.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gt2koaczhcp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aizwys.cn/Article/details/gt2ihdinmqa.html

[R80] 查看脚本执行耗时
来源：http://dali.sxryk.cn/Article/details/gt2tdahpopo.html

time ./run.sh
来源：http://dali.cqqwz.cn/Article/details/gt2tuixrsnm.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2imhzitmj.html

S. C / C++ 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tirfkuhy.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2idjdaqnb.html

[S01] C：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2wvqbcrsr.html

#include <stdio.h>
来源：http://dali.xylfe.cn/Article/details/gt2xfqcdpmp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sxryk.cn/Article/details/gt2vbnjkqjj.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigufen.top/Article/details/gt2ncaljpbw.html

int a = 10; printf("%d\n", a);
来源：http://dali.fzhhl.top/Article/details/gt2ntxnpsma.html

[S03] C：读入整数
来源：http://dali.dashuyun.cn/Article/details/gt2mexghvrz.html

int x; scanf("%d", &x);
来源：http://dali.xuanzx.com/Article/details/gt2inznxkxq.html

[S04] C：字符串复制
来源：http://dali.zycfv.cn/Article/details/gt2devoyrkm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yanxiufei.cn/Article/details/gt2rrfklrbm.html

[S05] C：字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2xwfovvdp.html

strlen(s)
来源：http://dali.0kj1m.cn/Article/details/gt2wwqaesyy.html

[S06] C：字符串比较
来源：http://dali.nanxinkj.top/Article/details/gt2ndkruxtz.html

strcmp(a, b) == 0
来源：http://dali.hammf.cn/Article/details/gt2mvzoljpo.html

[S07] C：数组遍历求和
来源：http://dali.andypj.xyz/Article/details/gt2jjrusnph.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dianchejie.cn/Article/details/gt2pdtoybxk.html

[S08] C：动态内存分配与释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ygjfcyvv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxuanxn.top/Article/details/gt2kgwefosl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhoulong.xyz/Article/details/gt2zxetujiw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.birdmap.top/Article/details/gt2fnjqigju.html

[S10] C：指针与解引用
来源：http://dali.tanke756.top/Article/details/gt2btfsoxyg.html

int *p = &a;  *p = 5;
来源：http://dali.svipenyu.cn/Article/details/gt2bfxvxabi.html

[S11] C：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gt2kxjklsgy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cheryme.top/Article/details/gt2aednqgwb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigfzy.top/Article/details/gt2dnlqoocc.html

fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gt2rewrmesh.html

[S12] C：写文件
来源：http://dali.snrcjt.cn/Article/details/gt2fibrobvv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.mhx1999.top/Article/details/gt2vlvpefhr.html

[S13] C：宏定义
来源：http://dali.gotoacloud.top/Article/details/gt2rntexxot.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ydzc1.top/Article/details/gt2rylubkgt.html

[S14] C：枚举
来源：http://dali.birdmap.top/Article/details/gt2xopxnhbm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sweek.top/Article/details/gt2ceauqrap.html

[S15] C：类型转换
来源：http://dali.guowangkeji.top/Article/details/gt2ulpmiwxi.html

(double) a / b
来源：http://dali.xinyue.icu/Article/details/gt2qvqwubju.html

[S16] C：位操作置位
来源：http://dali.chenzaomai.com/Article/details/gt2vffjivxj.html

x |= (1 << 3);
来源：http://dali.mhx1999.top/Article/details/gt2vgflkgfm.html

[S17] C：安全拼接字符串
来源：http://dali.bjfxy.top/Article/details/gt2ncmkbtop.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shuidangran.top/Article/details/gt2lfczkhwd.html

[S18] C：命令行参数
来源：http://dali.guowangkeji.top/Article/details/gt2cbiotbzz.html

int main(int argc, char **argv)
来源：http://dali.yj202588.top/Article/details/gt2xuyjqeia.html

[S19] C：快速排序
来源：http://dali.dianchejie.cn/Article/details/gt2hrwlpphk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gt2xlygwlst.html

[S20] C：二分查找
来源：http://dali.jqgfzy.top/Article/details/gt2mmxihfru.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gt2jpsjhtaw.html

[S21] C：字符类别判断
来源：http://dali.birdmap.top/Article/details/gt2uyzslrmx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.smart0.xyz/Article/details/gt2wzpzwagd.html

[S22] C：字符串转数字
来源：http://dali.gzhubu.top/Article/details/gt2rnyadqlw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ydzc1.top/Article/details/gt2xdyackhv.html

[S23] C：随机数
来源：http://dali.hysaishi.cn/Article/details/gt2iisgyipb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.0kj1m.cn/Article/details/gt2cqjkiqwd.html

[S24] C：获取本地时间
来源：http://dali.xziqi.cn/Article/details/gt2ljezgxun.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.birdmap.top/Article/details/gt2pvoelxwh.html

[S25] C：内存拷贝
来源：http://dali.tianlin.xyz/Article/details/gt2fjloebui.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gt2plwnawzb.html

[S26] C：内存清零
来源：http://dali.yonumen.top/Article/details/gt2sidjcdxn.html

memset(a, 0, sizeof a);
来源：http://dali.cheryme.top/Article/details/gt2bohtdmrn.html

[S27] C：定义常量
来源：http://dali.hnqzz.top/Article/details/gt2ogansapb.html

const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gt2zxeozgzh.html

[S28] C：静态变量
来源：http://dali.bjfxy.top/Article/details/gt2ygdlhvtr.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gt2dunfrosh.html

[S29] C：变参函数
来源：http://dali.guannengcc.top/Article/details/gt2sooipnsz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gzhubu.top/Article/details/gt2kndszzqv.html

[S30] C：头文件保护
来源：http://dali.dashuyun.cn/Article/details/gt2alrsfyxs.html

#ifndef X_H
来源：http://dali.sysykeji.top/Article/details/gt2bfkvzrwd.html

#define X_H
来源：http://dali.ehwqpu.com/Article/details/gt2mnfxrjfr.html

#endif
来源：http://dali.jiagoushi.top/Article/details/gt2mjrijntl.html

[S31] C++：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2hobnkkww.html

#include <iostream>
来源：http://dali.ydzc1.top/Article/details/gt2jjxgcbbs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ogrlgopv.html

[S32] C++：字符串
来源：http://dali.guowangkeji.top/Article/details/gt2ugcuhgrf.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258.top/Article/details/gt2yymfgyvd.html

[S33] C++：vector 增删
来源：http://dali.tianlin.xyz/Article/details/gt2vpwttusd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenzaomai.com/Article/details/gt2vgejsjos.html

[S34] C++：遍历 vector
来源：http://dali.fengsongda.top/Article/details/gt2zaagormk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.haohaochexian.top/Article/details/gt2ddfcszhz.html

[S35] C++：map
来源：http://dali.chenzaomai.com/Article/details/gt2ojweavnp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qwzpetto.html

[S36] C++：unordered_map
来源：http://dali.ehwqpu.com/Article/details/gt2rxhogkgh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2qxbokcja.html

[S37] C++：set
来源：http://dali.jinqigufen.top/Article/details/gt2tvugsngl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guowangkeji.top/Article/details/gt2eavnatjm.html

[S38] C++：排序
来源：http://dali.zhongyouzk.top/Article/details/gt2fihulozx.html

std::sort(v.begin(), v.end());
来源：http://dali.hywenlv.cn/Article/details/gt2rixfabmj.html

[S39] C++：自定义比较器排序
来源：http://dali.gzhubu.top/Article/details/gt2epfaizqz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ppjwa.cn/Article/details/gt2wlorwohb.html

[S40] C++：查找元素
来源：http://dali.zycfv.cn/Article/details/gt2pcavvwrw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sysykeji.top/Article/details/gt2dmdausfv.html

[S41] C++：类与构造函数
来源：http://dali.jinqigfzy.top/Article/details/gt2kpbozmpk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ydzc1.top/Article/details/gt2figtxbdj.html

[S42] C++：继承与虚函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2lhsbvncf.html

class B : public Base { public: void f() override {} };
来源：http://dali.hammf.cn/Article/details/gt2fdjwljxp.html

[S43] C++：智能指针
来源：http://dali.smart0.xyz/Article/details/gt2ogztobxo.html

auto p = std::make_unique<int>(5);
来源：http://dali.mhx1999.top/Article/details/gt2mvmxaqjz.html

[S44] C++：引用传参
来源：http://dali.chenzaomai.com/Article/details/gt2wuopkjrz.html

void inc(int &x) { ++x; }
来源：http://dali.tianlin.xyz/Article/details/gt2nfzegpex.html

[S45] C++：lambda
来源：http://dali.sxryk.cn/Article/details/gt2buhhmful.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hongshengwenyu.top/Article/details/gt2eqhlajbi.html

[S46] C++：函数模板
来源：http://dali.jinghuilouyu.cn/Article/details/gt2huqicykx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2qccldvru.html

[S47] C++：结构化绑定遍历
来源：http://dali.sysykeji.top/Article/details/gt2chmnyinn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenzaomai.com/Article/details/gt2gpoezvws.html

[S48] C++：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gt2qwuevyur.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ydzc1.top/Article/details/gt2huxzolzm.html

while (std::getline(in, line)) { }
来源：http://dali.chenlongwang.top/Article/details/gt2fxizxbhm.html

[S49] C++：写文件
来源：http://dali.zhoulong.xyz/Article/details/gt2usviswfk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgfzy.top/Article/details/gt2vmcvadqz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdbofda.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gt2arqswfxb.html

[S51] C++：显式类型转换
来源：http://dali.smart0.xyz/Article/details/gt2nythopvh.html

static_cast<double>(a) / b
来源：http://dali.andypj.xyz/Article/details/gt2cgklesqh.html

[S52] C++：const 与 noexcept
来源：http://dali.ppjwa.cn/Article/details/gt2xnemjxhm.html

int size() const noexcept { return n_; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rsdzyfsb.html

[S53] C++：移动语义
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxzbznni.html

std::vector<int> w = std::move(v);
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbmpegpv.html

[S54] C++：异常处理
来源：http://dali.yj202588.top/Article/details/gt2wulyojgl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aizwys.cn/Article/details/gt2torhzynq.html

[S55] C++：结构化绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iwtioimx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sufxvd.cn/Article/details/gt2yehswhem.html

[S56] C++：optional
来源：http://dali.jinqigufen.top/Article/details/gt2efknhmes.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj202588.top/Article/details/gt2vxrkebza.html

[S57] C++：编译期常量
来源：http://dali.smart0.xyz/Article/details/gt2gsmccbod.html

constexpr int N = 10;
来源：http://dali.zdqjudy.top/Article/details/gt2xybnqfif.html

[S58] C++：命名空间
来源：http://dali.chenlongwang.top/Article/details/gt2rawnzbjf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zycfv.cn/Article/details/gt2exftytdy.html

[S59] C++：静态断言
来源：http://dali.yanxiufei.cn/Article/details/gt2dyywhvyt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fzhhl.top/Article/details/gt2slpsvtwh.html

[S60] C++：遍历并删除元素
来源：http://dali.fengsongda.top/Article/details/gt2rwqmcuja.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.bjfxy.top/Article/details/gt2hzaizarr.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2ceqvxqfq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tanke756.top/Article/details/gt2etfgclel.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2dhqxhlqd.html

[T01] Kotlin：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2grjfrtju.html

println("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gt2jcltybut.html

[T02] Kotlin：变量
来源：http://dali.gzhubu.top/Article/details/gt2dqmzblue.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tian-w.cn/Article/details/gt2fazfstqa.html

[T03] Kotlin：字符串模板
来源：http://dali.chenjidiqi.icu/Article/details/gt2yzzsyoer.html

"值: $b"
来源：http://dali.cqqwz.cn/Article/details/gt2llpzevbq.html

[T04] Kotlin：空安全
来源：http://dali.dianchejie.cn/Article/details/gt2xuowlavg.html

val n: String? = null;  n?.length
来源：http://dali.jqgufenzy.top/Article/details/gt2eigcbzyf.html

[T05] Kotlin：when 表达式
来源：http://dali.daxiang520.top/Article/details/gt2gjeovatl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xziqi.cn/Article/details/gt2jujmeieg.html

[T06] Kotlin：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gt2wzudtlgu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fzhhl.top/Article/details/gt2lfduawkz.html

[T07] Kotlin：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gt2piffamuc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhixingplan.top/Article/details/gt2itukbedu.html

[T08] Kotlin：数据类
来源：http://dali.hnxiangtu.top/Article/details/gt2bcgwcerc.html

data class User(val name: String, val age: Int)
来源：http://dali.cdnleiting.top/Article/details/gt2wkhueygg.html


<!-- 参考信息 -->