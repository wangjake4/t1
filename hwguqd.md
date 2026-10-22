代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dianchejie.cn/Article/details/gt2ryrujpak.html

[Q90] 生成序号列
来源：http://dali.yanxiufei.cn/Article/details/gt2uvaezpbv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aibaodan.cn/Article/details/gt2vhuodvlw.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2tetynmor.html

R. Bash 专题
来源：http://dali.nanxinkj.top/Article/details/gt2bovflgil.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2pqnfdjzq.html

[R01] shebang 与严格模式
来源：http://dali.shzxlz.cn/Article/details/gt2jmddwlzg.html

#!/usr/bin/env bash
来源：http://dali.andypj.xyz/Article/details/gt2touwguud.html

set -euo pipefail
来源：http://dali.nanxuanxn.top/Article/details/gt2qgwlmkvu.html

[R02] 变量赋值与使用
来源：http://dali.vqdsnc.cn/Article/details/gt2hlesjuuk.html

name="Tom"; echo "$name"
来源：http://dali.zhoulong.xyz/Article/details/gt2fauqwjnd.html

[R03] 只读变量
来源：http://dali.gaohongyu789.top/Article/details/gt2rkwefjmv.html

readonly PI=3.14
来源：http://dali.yvedp.cn/Article/details/gt2mrzanomt.html

[R04] 位置参数
来源：http://dali.cheryme.top/Article/details/gt2dhmezutg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tanke756.top/Article/details/gt2nizbcpen.html

[R05] 参数默认值
来源：http://dali.yongpay.top/Article/details/gt2cypkojcq.html

name="${1:-default}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sktrsifa.html

[R06] 判断命令是否存在
来源：http://dali.hnxiangtu.top/Article/details/gt2xweooaxg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2uttmctgt.html

[R07] if 判断文件
来源：http://dali.zdqjudy.top/Article/details/gt2ndpuwtih.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigfzy.top/Article/details/gt2qmhlccmh.html

[R08] 数值比较
来源：http://dali.zhengqikj.top/Article/details/gt2qdhekclz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenzaomai.com/Article/details/gt2kbtsdzrk.html

[R09] 字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qzzvhtyt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258.top/Article/details/gt2pobbjevs.html

[R10] 正则匹配
来源：http://dali.hammf.cn/Article/details/gt2nlmcfvfg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tanke756.top/Article/details/gt2rkbmxuyw.html

[R11] case 多分支
来源：http://dali.yj20258888.top/Article/details/gt2ysqutsmq.html

case "$1" in
来源：http://dali.andypj.xyz/Article/details/gt2suoonxvu.html

start) echo "启动" ;;
来源：http://dali.daria6918.cn/Article/details/gt2uselviqa.html

stop)  echo "停止" ;;
来源：http://dali.cucudq.cn/Article/details/gt2skvircib.html

*)     echo "未知命令" ;;
来源：http://dali.andypj.xyz/Article/details/gt2yivtqbxp.html

esac
来源：http://dali.yanxiufei.cn/Article/details/gt2bxnfsdog.html

[R12] for 遍历文件
来源：http://dali.cashguo.top/Article/details/gt2mfzsyjhh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xziqi.cn/Article/details/gt2crcreqqp.html

[R13] for 计数循环
来源：http://dali.tianlin.xyz/Article/details/gt2jrvqeyux.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gt2oxrhqgin.html

[R14] C 风格 for
来源：http://dali.jlsjyb.cn/Article/details/gt2jvrhpsqs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gt2wrydjqsc.html

[R15] while 逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gt2njulfopr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xziqi.cn/Article/details/gt2wzeuqvdl.html

[R16] until 等待条件
来源：http://dali.jianghu66.top/Article/details/gt2ufuolgcd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2ifxkrazn.html

[R17] 数组定义与取值
来源：http://dali.cheryme.top/Article/details/gt2cdjsjise.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yangfankeji.com/Article/details/gt2eojexwdn.html

[R18] 遍历数组
来源：http://dali.cheryme.top/Article/details/gt2aefuxiba.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yueranfly.top/Article/details/gt2tcdglvqf.html

[R19] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2edolggnm.html

echo "${#arr[@]}"
来源：http://dali.chenzaomai.com/Article/details/gt2tzjshivg.html

[R20] 关联数组（字典）
来源：http://dali.yj202588.top/Article/details/gt2rgqmcxyz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gt2owndedpx.html

[R21] 字符串长度
来源：http://dali.jiagoushi.top/Article/details/gt2kysctcam.html

echo "${#s}"
来源：http://dali.sysykeji.top/Article/details/gt2etpcrqru.html

[R22] 截取子串
来源：http://dali.shuidangran.top/Article/details/gt2durrnuut.html

echo "${s:0:5}"
来源：http://dali.nwbrower.top/Article/details/gt2anfchrcs.html

[R23] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gt2tzxzpljc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gotoacloud.top/Article/details/gt2holjytut.html

[R24] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gt2cjmhlltz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenlongwang.top/Article/details/gt2pvjjqrav.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuetiantiany.cn/Article/details/gt2iulzdryj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.c1oappe.top/Article/details/gt2yutkbqwu.html

[R26] 命令替换
来源：http://dali.guowangkeji.top/Article/details/gt2toihnsrv.html

now=$(date +%F); echo "$now"
来源：http://dali.tanke756.top/Article/details/gt2jmulzlvd.html

[R27] 算术展开
来源：http://dali.hysaishi.cn/Article/details/gt2kvhpzkir.html

echo $((1 + 2 * 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njxhczlm.html

[R28] 浮点运算
来源：http://dali.hnqzz.top/Article/details/gt2vezyjltm.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iydoecfw.html

[R29] 定义函数
来源：http://dali.svipenyu.cn/Article/details/gt2koawfphx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhoulong.xyz/Article/details/gt2dumcsuwz.html

[R30] 函数返回状态码
来源：http://dali.nanxinkj.top/Article/details/gt2mdoomkvb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gzhubu.top/Article/details/gt2jcntdbos.html

[R31] 局部变量
来源：http://dali.pycfn.com/Article/details/gt2npvxkqso.html

f() { local x=1; echo "$x"; }
来源：http://dali.daria6918.cn/Article/details/gt2ypjhgzme.html

[R32] 参数个数校验
来源：http://dali.snrcjt.cn/Article/details/gt2kfbkkjne.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gt2aljuyglo.html

[R33] 捕获错误并提示行号
来源：http://dali.sweek.top/Article/details/gt2womjzlpu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhiwuduotai.top/Article/details/gt2gphydfzx.html

[R34] 退出时清理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nqswsdox.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gt2pkwwrwdv.html

[R35] 后台执行并等待
来源：http://dali.vqdsnc.cn/Article/details/gt2hmwtrtbr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenlongwang.top/Article/details/gt2ojzxieog.html

[R36] 并发执行多个任务
来源：http://dali.yueranfly.top/Article/details/gt2nxrthxrc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.snrcjt.cn/Article/details/gt2myjkukqy.html

[R37] 把输出赋给变量
来源：http://dali.meibo888.top/Article/details/gt2yxxlmhth.html

files=$(ls -1)
来源：http://dali.nwbrower.top/Article/details/gt2vcoeyxgp.html

[R38] 管道串联
来源：http://dali.tian-w.cn/Article/details/gt2qghidcci.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hfpthk.cn/Article/details/gt2kujxddfz.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258888.top/Article/details/gt2imuzqpvz.html

cmd > out.log 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gt2tlydjkbo.html

[R40] 追加写日志
来源：http://dali.jinqigfzy.top/Article/details/gt2opcovbsd.html

echo "log" >> out.log
来源：http://dali.vqdsnc.cn/Article/details/gt2kiivltff.html

[R41] 丢弃输出
来源：http://dali.fzhhl.top/Article/details/gt2cvbixosy.html

cmd >/dev/null 2>&1
来源：http://dali.ppjwa.cn/Article/details/gt2skwciulx.html

[R42] 输入重定向
来源：http://dali.cqqwz.cn/Article/details/gt2bffnjrdf.html

wc -l < a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rprkvrro.html

[R43] 按名字查找文件
来源：http://dali.yj20258888.top/Article/details/gt2pjrsajpu.html

find . -name "*.log" -type f
来源：http://dali.ivvv.top/Article/details/gt2riagaoch.html

[R44] 按修改时间查找
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zndvnzmq.html

find . -mtime -7 -type f
来源：http://dali.zhongyouzk.top/Article/details/gt2dtlblcsr.html

[R45] 批量删除
来源：http://dali.yj20258888.top/Article/details/gt2gkfdqbhb.html

find . -name "*.tmp" -delete
来源：http://dali.xuetiantiany.cn/Article/details/gt2hiquirhs.html

[R46] 递归替换文件内容
来源：http://dali.aibaodan.cn/Article/details/gt2uvxteeer.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cdnleiting.top/Article/details/gt2tfogesvn.html

[R47] sed 单行替换
来源：http://dali.cdnleiting.top/Article/details/gt2pvywslxk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fzhhl.top/Article/details/gt2ofqtlfib.html

[R48] awk 取指定列
来源：http://dali.iojbl.cn/Article/details/gt2sufhpcvj.html

awk '{print $1, $3}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2rcpkckjz.html

[R49] awk 带条件
来源：http://dali.haohaochexian.top/Article/details/gt2jtqyzzar.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tian-w.cn/Article/details/gt2sebezwdz.html

[R50] awk 求和
来源：http://dali.jqgufenzy.top/Article/details/gt2ksxsqmeq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daxiang520.top/Article/details/gt2fisyemyp.html

[R51] 排序去重取前几
来源：http://dali.xylfe.cn/Article/details/gt2pjwxeevs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ybcxt.top/Article/details/gt2gksmernw.html

[R52] 统计行数
来源：http://dali.tian-w.cn/Article/details/gt2udiwctbi.html

wc -l a.txt
来源：http://dali.ivvv.top/Article/details/gt2bkegtoly.html

[R53] 查看文件头与实时尾
来源：http://dali.sysykeji.top/Article/details/gt2fovgmgox.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgfzy.top/Article/details/gt2sdsmtapt.html

[R54] 比较两个文件
来源：http://dali.aizwys.cn/Article/details/gt2rindanee.html

diff a.txt b.txt
来源：http://dali.daxiang520.top/Article/details/gt2xrdgqwrt.html

[R55] 压缩与解压
来源：http://dali.yueranfly.top/Article/details/gt2ljthmqrc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cpnzayxa.html

[R56] 远程拷贝
来源：http://dali.daxiang520.top/Article/details/gt2lptphhqc.html

scp file user@host:/path/
来源：http://dali.bjfxy.top/Article/details/gt2dxlkigkl.html

[R57] 远程执行命令
来源：http://dali.guannengcc.top/Article/details/gt2sttyndrv.html

ssh user@host 'uptime'
来源：http://dali.pengpengdd.cyou/Article/details/gt2pdrhzpdm.html

[R58] 下载文件
来源：http://dali.yongpay.top/Article/details/gt2gdljksxk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.meibo888.top/Article/details/gt2udysojit.html

[R59] 发 POST JSON
来源：http://dali.0kj1m.cn/Article/details/gt2daquzsce.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jqgufenzy.top/Article/details/gt2edxxkjvw.html

[R60] 只看 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2haptkyxs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hywenlv.cn/Article/details/gt2gflqusnh.html

[R61] 磁盘占用
来源：http://dali.yvedp.cn/Article/details/gt2izksobkt.html

df -h;  du -sh *
来源：http://dali.guannengcc.top/Article/details/gt2larpdyet.html

[R62] 找最占空间的文件
来源：http://dali.nwbrower.top/Article/details/gt2hwzabvry.html

du -ah . | sort -rh | head -10
来源：http://dali.haohaochexian.top/Article/details/gt2dwdavmgx.html

[R63] 内存与进程
来源：http://dali.jyoumei.cn/Article/details/gt2qnwsthfb.html

free -h;  ps aux | grep nginx
来源：http://dali.gaohongyu789.top/Article/details/gt2ohbsfwsc.html

[R64] 结束进程
来源：http://dali.yj202588.top/Article/details/gt2thhbtakx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tian-w.cn/Article/details/gt2khmvmojx.html

[R65] 查看端口占用
来源：http://dali.0kj1m.cn/Article/details/gt2rlshloye.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shuidangran.top/Article/details/gt2dwtyzgpl.html

[R66] 定时任务
来源：http://dali.zycfv.cn/Article/details/gt2fczxchzw.html

crontab -e;  crontab -l
来源：http://dali.chenlongwang.top/Article/details/gt2mufsdvvh.html

[R67] 生成随机十六进制串
来源：http://dali.gogol.net.cn/Article/details/gt2xgdvsjat.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ocasripj.html

[R68] 计算文件校验值
来源：http://dali.nanxinkj.top/Article/details/gt2wniuehsq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oaxwikzg.html

[R69] 生成随机密码
来源：http://dali.jyoumei.cn/Article/details/gt2pvhkralr.html

head -c 16 /dev/urandom | base64
来源：http://dali.jianghu66.top/Article/details/gt2tzzoyfrq.html

[R70] 时间戳与互转
来源：http://dali.xylfe.cn/Article/details/gt2arilenho.html

date +%s;  date -d @1700000000
来源：http://dali.jianghu66.top/Article/details/gt2idinevws.html

[R71] 日期格式化
来源：http://dali.daxiang520.top/Article/details/gt2ogygxakm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tian-w.cn/Article/details/gt2gozfnwtu.html

[R72] 等待端口就绪
来源：http://dali.shangyingyoupin.top/Article/details/gt2woqixbwy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gt2rlxtagfx.html

[R73] 分割大日志
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hixpdcig.html

split -l 1000 big.log part_
来源：http://dali.jlsjyb.cn/Article/details/gt2wewqudve.html

[R74] 批量重命名
来源：http://dali.tanke756.top/Article/details/gt2spljsucs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yonumen.top/Article/details/gt2sszxpqqa.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gt2hvuncfbd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2etrttlca.html

[R76] 使用临时文件
来源：http://dali.dashuyun.cn/Article/details/gt2mfhavavs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gt2idvgpxhi.html

[R77] 读取用户输入
来源：http://dali.hnqzz.top/Article/details/gt2qubxzsbl.html

read -rp "请输入: " ans
来源：http://dali.jinqigufen.top/Article/details/gt2inaoehek.html

[R78] 交互式菜单
来源：http://dali.cdnleiting.top/Article/details/gt2vefzvsmv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenzaomai.com/Article/details/gt2afkskkvd.html

[R79] 解析命令行选项
来源：http://dali.cheryme.top/Article/details/gt2xojopamf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2emndtesb.html

[R80] 查看脚本执行耗时
来源：http://dali.dianchejie.cn/Article/details/gt2hrfgtlhn.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gt2ouvhlqvg.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2pzwfeliw.html

S. C / C++ 专题
来源：http://dali.jiagoushi.top/Article/details/gt2iormmwug.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2zvvymyyq.html

[S01] C：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2rawihyme.html

#include <stdio.h>
来源：http://dali.gogol.net.cn/Article/details/gt2lhnsqvkh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhixingplan.top/Article/details/gt2glftfjiu.html

[S02] C：变量与格式化输出
来源：http://dali.hammf.cn/Article/details/gt2quchsxff.html

int a = 10; printf("%d\n", a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vrdkjbam.html

[S03] C：读入整数
来源：http://dali.c1oappe.top/Article/details/gt2kytasrww.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycoxmizk.html

[S04] C：字符串复制
来源：http://dali.fengsongda.top/Article/details/gt2qgtsomma.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2cfwbbabb.html

[S05] C：字符串长度
来源：http://dali.yonumen.top/Article/details/gt2rxwgtuml.html

strlen(s)
来源：http://dali.c1oappe.top/Article/details/gt2wwclwatn.html

[S06] C：字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2esxfvoyg.html

strcmp(a, b) == 0
来源：http://dali.316326.xyz/Article/details/gt2oguwvypl.html

[S07] C：数组遍历求和
来源：http://dali.meibo888.top/Article/details/gt2beltllqo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fzhhl.top/Article/details/gt2dlawonhl.html

[S08] C：动态内存分配与释放
来源：http://dali.guannengcc.top/Article/details/gt2jpmzczgg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gzhubu.top/Article/details/gt2ropkqfzo.html

[S09] C：结构体定义与初始化
来源：http://dali.ybcxt.top/Article/details/gt2miopccsq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenlongwang.top/Article/details/gt2kdqfdcdq.html

[S10] C：指针与解引用
来源：http://dali.svipenyu.cn/Article/details/gt2bfiwbgep.html

int *p = &a;  *p = 5;
来源：http://dali.shuidangran.top/Article/details/gt2oplwivyc.html

[S11] C：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gt2quqnbffh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yueranfly.top/Article/details/gt2mokalhpm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.c1oappe.top/Article/details/gt2visezeer.html

fclose(f);
来源：http://dali.ydzc1.top/Article/details/gt2hlimineb.html

[S12] C：写文件
来源：http://dali.daria6918.cn/Article/details/gt2eyfqtvrv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daxiang520.top/Article/details/gt2zjqfihkz.html

[S13] C：宏定义
来源：http://dali.zhengqikj.top/Article/details/gt2lzrnylrp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ydzc1.top/Article/details/gt2ccbiwbjb.html

[S14] C：枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kncvanrk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aizwys.cn/Article/details/gt2prqjfifx.html

[S15] C：类型转换
来源：http://dali.hnqzz.top/Article/details/gt2bxukzvvl.html

(double) a / b
来源：http://dali.aizwys.cn/Article/details/gt2tnhtxebg.html

[S16] C：位操作置位
来源：http://dali.daria6918.cn/Article/details/gt2clyraufk.html

x |= (1 << 3);
来源：http://dali.shuidangran.top/Article/details/gt2vyrqzjet.html

[S17] C：安全拼接字符串
来源：http://dali.tanke756.top/Article/details/gt2umkonhyl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cdnleiting.top/Article/details/gt2zwedxvyq.html

[S18] C：命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2kquccwrg.html

int main(int argc, char **argv)
来源：http://dali.xinyue.icu/Article/details/gt2rmitfqyl.html

[S19] C：快速排序
来源：http://dali.svipenyu.cn/Article/details/gt2yzxueywe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gt2flzwydls.html

[S20] C：二分查找
来源：http://dali.hammf.cn/Article/details/gt2kschnlin.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gt2ennmjpxh.html

[S21] C：字符类别判断
来源：http://dali.gzhubu.top/Article/details/gt2atguyyrg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhpnobl.html

[S22] C：字符串转数字
来源：http://dali.hfpthk.cn/Article/details/gt2tncclzeh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ivvv.top/Article/details/gt2yjkvapxb.html

[S23] C：随机数
来源：http://dali.nanxuanxn.top/Article/details/gt2yxvdfkmc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gotoacloud.top/Article/details/gt2fdgypakw.html

[S24] C：获取本地时间
来源：http://dali.yj20258.top/Article/details/gt2xwlubmoe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.0kj1m.cn/Article/details/gt2jryfcrau.html

[S25] C：内存拷贝
来源：http://dali.nwbrower.top/Article/details/gt2kpbrmqut.html

memcpy(dst, src, n);
来源：http://dali.zhengqikj.top/Article/details/gt2jgybeokj.html

[S26] C：内存清零
来源：http://dali.daxiang520.top/Article/details/gt2vmkcleku.html

memset(a, 0, sizeof a);
来源：http://dali.zdqjudy.top/Article/details/gt2tnbjclsv.html

[S27] C：定义常量
来源：http://dali.316326.xyz/Article/details/gt2fgqneamv.html

const double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gt2tzhgvtbo.html

[S28] C：静态变量
来源：http://dali.sysykeji.top/Article/details/gt2qqvggtmp.html

static int counter = 0;
来源：http://dali.yj20258.top/Article/details/gt2apaykjmb.html

[S29] C：变参函数
来源：http://dali.jlsjyb.cn/Article/details/gt2zuufzfan.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gotoacloud.top/Article/details/gt2gtolxyez.html

[S30] C：头文件保护
来源：http://dali.zhiwuduotai.top/Article/details/gt2obtqmlvv.html

#ifndef X_H
来源：http://dali.xuanzx.com/Article/details/gt2stpevzjd.html

#define X_H
来源：http://dali.yueranfly.top/Article/details/gt2mpbszotx.html

#endif
来源：http://dali.xziqi.cn/Article/details/gt2zacmnzmr.html

[S31] C++：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2vlujxlij.html

#include <iostream>
来源：http://dali.vqdsnc.cn/Article/details/gt2kygadzyc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.haohaochexian.top/Article/details/gt2zsdvrbrq.html

[S32] C++：字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2nkrsvxov.html

std::string s = "hi";  s += "!";
来源：http://dali.cheryme.top/Article/details/gt2fqscocqd.html

[S33] C++：vector 增删
来源：http://dali.chenjidiqi.icu/Article/details/gt2tuaxdvko.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cucudq.cn/Article/details/gt2pirujdru.html

[S34] C++：遍历 vector
来源：http://dali.jianghu66.top/Article/details/gt2lflnhlyz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sweek.top/Article/details/gt2hiqvtknl.html

[S35] C++：map
来源：http://dali.shanyushiyangtech.top/Article/details/gt2olcuzawb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gt2knvgrlvk.html

[S36] C++：unordered_map
来源：http://dali.birdmap.top/Article/details/gt2ezkllxub.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gt2hknovobr.html

[S37] C++：set
来源：http://dali.svipenyu.cn/Article/details/gt2edfibphl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jqgfzy.top/Article/details/gt2dwvmdvbj.html

[S38] C++：排序
来源：http://dali.yanxiufei.cn/Article/details/gt2zeduxfsf.html

std::sort(v.begin(), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gt2wtjmhzpk.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgufenzy.top/Article/details/gt2virqbcde.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.0kj1m.cn/Article/details/gt2uctjykku.html

[S40] C++：查找元素
来源：http://dali.aizwys.cn/Article/details/gt2cfnmoqxb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yueranfly.top/Article/details/gt2pbegejce.html

[S41] C++：类与构造函数
来源：http://dali.guannengcc.top/Article/details/gt2gryoasyh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.vqdsnc.cn/Article/details/gt2aldmcxsi.html

[S42] C++：继承与虚函数
来源：http://dali.cashguo.top/Article/details/gt2ctttplpk.html

class B : public Base { public: void f() override {} };
来源：http://dali.quarkkingdee.top/Article/details/gt2azucvtxz.html

[S43] C++：智能指针
来源：http://dali.hammf.cn/Article/details/gt2utzolakh.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxuanxn.top/Article/details/gt2bllmsknq.html

[S44] C++：引用传参
来源：http://dali.0kj1m.cn/Article/details/gt2qrsozbds.html

void inc(int &x) { ++x; }
来源：http://dali.jqgufenzy.top/Article/details/gt2uvszepxz.html

[S45] C++：lambda
来源：http://dali.guowangkeji.top/Article/details/gt2yfvbrhlq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.haohaochexian.top/Article/details/gt2mfkasspa.html

[S46] C++：函数模板
来源：http://dali.ppjwa.cn/Article/details/gt2tgphcuhg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenlongwang.top/Article/details/gt2mjvzedjf.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhengqikj.top/Article/details/gt2wambaiit.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuertftc.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ebpijzzt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jiagoushi.top/Article/details/gt2kvjewuqx.html

while (std::getline(in, line)) { }
来源：http://dali.snrcjt.cn/Article/details/gt2ucnorfoe.html

[S49] C++：写文件
来源：http://dali.zhixingplan.top/Article/details/gt2mfrgtaim.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2klvqbixc.html

[S50] C++：格式化数字
来源：http://dali.cqqwz.cn/Article/details/gt2ivwbosdk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gt2twpdrrem.html

[S51] C++：显式类型转换
来源：http://dali.hnqzz.top/Article/details/gt2bzzoevdu.html

static_cast<double>(a) / b
来源：http://dali.nwbrower.top/Article/details/gt2vhyokjug.html

[S52] C++：const 与 noexcept
来源：http://dali.zycfv.cn/Article/details/gt2yglyzdrl.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigfzy.top/Article/details/gt2mamoavwx.html

[S53] C++：移动语义
来源：http://dali.guannengcc.top/Article/details/gt2ijqmavgy.html

std::vector<int> w = std::move(v);
来源：http://dali.hywenlv.cn/Article/details/gt2oosyqyqa.html

[S54] C++：异常处理
来源：http://dali.hammf.cn/Article/details/gt2thqbaupk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.iojbl.cn/Article/details/gt2icjqufkb.html

[S55] C++：结构化绑定
来源：http://dali.tanke756.top/Article/details/gt2oiflzzmm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daxiang520.top/Article/details/gt2mnmidrsm.html

[S56] C++：optional
来源：http://dali.zycfv.cn/Article/details/gt2jtwhqkbq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.wangdashe.top/Article/details/gt2mgzesdwl.html

[S57] C++：编译期常量
来源：http://dali.zycfv.cn/Article/details/gt2iitatnuy.html

constexpr int N = 10;
来源：http://dali.xziqi.cn/Article/details/gt2echaialj.html

[S58] C++：命名空间
来源：http://dali.nanxuanxn.top/Article/details/gt2fbsvgvfn.html

namespace ns { int f() { return 1; } }
来源：http://dali.shuidangran.top/Article/details/gt2thukbcvm.html

[S59] C++：静态断言
来源：http://dali.cqqwz.cn/Article/details/gt2orxlsvrj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jiagoushi.top/Article/details/gt2rayznakw.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hstobcdi.html


<!-- 参考信息 -->