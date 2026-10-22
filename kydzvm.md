代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.dashuyun.cn/Article/details/gt2lrdsgklo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.iojbl.cn/Article/details/gt2hepzxron.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yonumen.top/Article/details/gt2imetsxqw.html

[Q89] 判断表是否存在
来源：http://dali.yj202588.top/Article/details/gt2tcjvrqig.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gaohongyu789.top/Article/details/gt2wvzifnco.html

[Q90] 生成序号列
来源：http://dali.9152youxi.cn/Article/details/gt2ptxdvieu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cucudq.cn/Article/details/gt2rldqvqce.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2jycopxsb.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gt2nexljvpx.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2itgjmiiw.html

[R01] shebang 与严格模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nypsifuf.html

#!/usr/bin/env bash
来源：http://dali.andypj.xyz/Article/details/gt2udzmqckg.html

set -euo pipefail
来源：http://dali.yanxiufei.cn/Article/details/gt2ejyqtkmq.html

[R02] 变量赋值与使用
来源：http://dali.hnxiangtu.top/Article/details/gt2qxohsjwz.html

name="Tom"; echo "$name"
来源：http://dali.hongshengwenyu.top/Article/details/gt2evbjjmfz.html

[R03] 只读变量
来源：http://dali.jqgfzy.top/Article/details/gt2kplxzwjq.html

readonly PI=3.14
来源：http://dali.cucudq.cn/Article/details/gt2ssekymvn.html

[R04] 位置参数
来源：http://dali.yj20258.top/Article/details/gt2jvjdinaa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yueranfly.top/Article/details/gt2fqbofqol.html

[R05] 参数默认值
来源：http://dali.zhiwuduotai.top/Article/details/gt2ksdcnkus.html

name="${1:-default}"
来源：http://dali.sweek.top/Article/details/gt2ocuxgzac.html

[R06] 判断命令是否存在
来源：http://dali.nwbrower.top/Article/details/gt2wxgocmxz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gt2masquqab.html

[R07] if 判断文件
来源：http://dali.shuidangran.top/Article/details/gt2kcayexqd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pycfn.com/Article/details/gt2qrtbymfl.html

[R08] 数值比较
来源：http://dali.pycfn.com/Article/details/gt2rfgliwcl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sufxvd.cn/Article/details/gt2cntgyfes.html

[R09] 字符串比较
来源：http://dali.gotoacloud.top/Article/details/gt2pcovdmmq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2srdldsto.html

[R10] 正则匹配
来源：http://dali.hywenlv.cn/Article/details/gt2sgprfgek.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.havefunace.top/Article/details/gt2oufecekq.html

[R11] case 多分支
来源：http://dali.sweek.top/Article/details/gt2uomhjcba.html

case "$1" in
来源：http://dali.nwbrower.top/Article/details/gt2acjepois.html

start) echo "启动" ;;
来源：http://dali.daxiang520.top/Article/details/gt2vlzmbqll.html

stop)  echo "停止" ;;
来源：http://dali.ehwqpu.com/Article/details/gt2gtmqjneu.html

*)     echo "未知命令" ;;
来源：http://dali.aibaodan.cn/Article/details/gt2tsrwflgp.html

esac
来源：http://dali.yj20258.top/Article/details/gt2biwtvfui.html

[R12] for 遍历文件
来源：http://dali.kuanghao11.cn/Article/details/gt2rfkszxru.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yangfankeji.com/Article/details/gt2hmdgutuh.html

[R13] for 计数循环
来源：http://dali.tianlin.xyz/Article/details/gt2lwkniwvc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gt2vrwfujyd.html

[R14] C 风格 for
来源：http://dali.sysykeji.top/Article/details/gt2cozvrdct.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jqgufenzy.top/Article/details/gt2cmljbilq.html

[R15] while 逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gt2kmnkmxpw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zdqjudy.top/Article/details/gt2odyixrwx.html

[R16] until 等待条件
来源：http://dali.ehwqpu.com/Article/details/gt2kevlzucu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2fueafjvk.html

[R17] 数组定义与取值
来源：http://dali.guannengcc.top/Article/details/gt2ufgtlfea.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigfzy.top/Article/details/gt2uhvzctpz.html

[R18] 遍历数组
来源：http://dali.tian-w.cn/Article/details/gt2gmdvarvb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sswbgzts.html

[R19] 数组长度
来源：http://dali.redwolf501.top/Article/details/gt2xxqusipt.html

echo "${#arr[@]}"
来源：http://dali.zycfv.cn/Article/details/gt2qmvvejme.html

[R20] 关联数组（字典）
来源：http://dali.jqgfzy.top/Article/details/gt2amszgvhq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gzhubu.top/Article/details/gt2smkwkgli.html

[R21] 字符串长度
来源：http://dali.yj20258.top/Article/details/gt2wcxtxsrf.html

echo "${#s}"
来源：http://dali.yj20258888.top/Article/details/gt2xopdamze.html

[R22] 截取子串
来源：http://dali.daria6918.cn/Article/details/gt2vsdhmdar.html

echo "${s:0:5}"
来源：http://dali.zhengqikj.top/Article/details/gt2srdfikoo.html

[R23] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gt2ranqlcnj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sxryk.cn/Article/details/gt2jiwrilve.html

[R24] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gt2pqvcrxln.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cheryme.top/Article/details/gt2wncvkiyw.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigfzy.top/Article/details/gt2aqrayjpe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gogol.net.cn/Article/details/gt2etsdrcmi.html

[R26] 命令替换
来源：http://dali.havefunace.top/Article/details/gt2ocqdpjrt.html

now=$(date +%F); echo "$now"
来源：http://dali.zhoulong.xyz/Article/details/gt2ooumvaze.html

[R27] 算术展开
来源：http://dali.hammf.cn/Article/details/gt2sysuximi.html

echo $((1 + 2 * 3))
来源：http://dali.ybcxt.top/Article/details/gt2hobdjfhx.html

[R28] 浮点运算
来源：http://dali.0kj1m.cn/Article/details/gt2apalcrsd.html

echo "scale=2; 10/3" | bc
来源：http://dali.shuidangran.top/Article/details/gt2rfzdntym.html

[R29] 定义函数
来源：http://dali.nwbrower.top/Article/details/gt2cybhovjn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gohhmqur.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gt2liismtjy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.svipenyu.cn/Article/details/gt2vzstxcai.html

[R31] 局部变量
来源：http://dali.jianghu66.top/Article/details/gt2xshqkdwe.html

f() { local x=1; echo "$x"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2nsqqjfrg.html

[R32] 参数个数校验
来源：http://dali.cheryme.top/Article/details/gt2buqixuxh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ehwqpu.com/Article/details/gt2gzbmfnem.html

[R33] 捕获错误并提示行号
来源：http://dali.ehwqpu.com/Article/details/gt2yjnpetdt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jrweuepv.html

[R34] 退出时清理
来源：http://dali.jinqigfzy.top/Article/details/gt2cmrpyzoo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gt2lrlzqnhl.html

[R35] 后台执行并等待
来源：http://dali.jinqigufen.top/Article/details/gt2pmcwrvnn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.snrcjt.cn/Article/details/gt2gkmcayec.html

[R36] 并发执行多个任务
来源：http://dali.hnqzz.top/Article/details/gt2mzxxrdpd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhixingplan.top/Article/details/gt2ycgtzaed.html

[R37] 把输出赋给变量
来源：http://dali.cheryme.top/Article/details/gt2nonanndi.html

files=$(ls -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ynjxpphq.html

[R38] 管道串联
来源：http://dali.hywenlv.cn/Article/details/gt2tntxuluc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2modgnasn.html

[R39] 重定向标准输出与错误
来源：http://dali.xylfe.cn/Article/details/gt2hkmrabne.html

cmd > out.log 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gt2oqirnubk.html

[R40] 追加写日志
来源：http://dali.zycfv.cn/Article/details/gt2vacnutxm.html

echo "log" >> out.log
来源：http://dali.gaohongyu789.top/Article/details/gt2bddeshrj.html

[R41] 丢弃输出
来源：http://dali.mhx1999.top/Article/details/gt2opdgpvmm.html

cmd >/dev/null 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gt2rpnsmkab.html

[R42] 输入重定向
来源：http://dali.bjfxy.top/Article/details/gt2hdejpkxf.html

wc -l < a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqidkykd.html

[R43] 按名字查找文件
来源：http://dali.gzhubu.top/Article/details/gt2fttaluup.html

find . -name "*.log" -type f
来源：http://dali.feifeiyinyue.top/Article/details/gt2nsudetpy.html

[R44] 按修改时间查找
来源：http://dali.316326.xyz/Article/details/gt2whcuwopi.html

find . -mtime -7 -type f
来源：http://dali.fengsongda.top/Article/details/gt2qytcybgx.html

[R45] 批量删除
来源：http://dali.dianchejie.cn/Article/details/gt2zhdwlmxg.html

find . -name "*.tmp" -delete
来源：http://dali.yvedp.cn/Article/details/gt2uilhcyxb.html

[R46] 递归替换文件内容
来源：http://dali.yvedp.cn/Article/details/gt2auzxpjlu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangdashe.top/Article/details/gt2dmiiabra.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sqnxmwex.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2jneiiqcy.html

[R48] awk 取指定列
来源：http://dali.yj20258.top/Article/details/gt2jocwalvv.html

awk '{print $1, $3}' a.txt
来源：http://dali.ivvv.top/Article/details/gt2exnebqcj.html

[R49] awk 带条件
来源：http://dali.ybcxt.top/Article/details/gt2xlrdzgxs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnqzz.top/Article/details/gt2jorfuvwk.html

[R50] awk 求和
来源：http://dali.feifeiyinyue.top/Article/details/gt2tycqwmst.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.smart0.xyz/Article/details/gt2sacrxlrc.html

[R51] 排序去重取前几
来源：http://dali.ivvv.top/Article/details/gt2abiegdyu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sufxvd.cn/Article/details/gt2jdntbgkq.html

[R52] 统计行数
来源：http://dali.zhengqikj.top/Article/details/gt2morzdvdx.html

wc -l a.txt
来源：http://dali.tanke756.top/Article/details/gt2ulqawyfh.html

[R53] 查看文件头与实时尾
来源：http://dali.9152youxi.cn/Article/details/gt2mmbaxkky.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yanxiufei.cn/Article/details/gt2vpfogycp.html

[R54] 比较两个文件
来源：http://dali.hywenlv.cn/Article/details/gt2uhpcvyvz.html

diff a.txt b.txt
来源：http://dali.yvedp.cn/Article/details/gt2deecwhws.html

[R55] 压缩与解压
来源：http://dali.fzhhl.top/Article/details/gt2ndivwzuk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jyoumei.cn/Article/details/gt2fcpikvcs.html

[R56] 远程拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxamhdbi.html

scp file user@host:/path/
来源：http://dali.dianchejie.cn/Article/details/gt2jvlickty.html

[R57] 远程执行命令
来源：http://dali.guowangkeji.top/Article/details/gt2qpyxmuhb.html

ssh user@host 'uptime'
来源：http://dali.chenlongwang.top/Article/details/gt2ludzxgip.html

[R58] 下载文件
来源：http://dali.kuanghao11.cn/Article/details/gt2niezpyim.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigufen.top/Article/details/gt2znvtbhvf.html

[R59] 发 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gt2raheofga.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tian-w.cn/Article/details/gt2vklwjkrr.html

[R60] 只看 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gt2rtikufpi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.feifeiyinyue.top/Article/details/gt2tfqzcjdy.html

[R61] 磁盘占用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sltlbvjn.html

df -h;  du -sh *
来源：http://dali.xuetiantiany.cn/Article/details/gt2ndtuspwl.html

[R62] 找最占空间的文件
来源：http://dali.gzhubu.top/Article/details/gt2ltfdzwsb.html

du -ah . | sort -rh | head -10
来源：http://dali.hysaishi.cn/Article/details/gt2ccharujo.html

[R63] 内存与进程
来源：http://dali.shangyingyoupin.top/Article/details/gt2gaekawzi.html

free -h;  ps aux | grep nginx
来源：http://dali.zycfv.cn/Article/details/gt2drgxccdn.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hixcttcn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.fzhhl.top/Article/details/gt2mslqdlcr.html

[R65] 查看端口占用
来源：http://dali.yangfankeji.com/Article/details/gt2hdyijulr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daria6918.cn/Article/details/gt2zafwsuvo.html

[R66] 定时任务
来源：http://dali.shzxlz.cn/Article/details/gt2jggwkajj.html

crontab -e;  crontab -l
来源：http://dali.mhx1999.top/Article/details/gt2ztrwopbg.html

[R67] 生成随机十六进制串
来源：http://dali.fzhhl.top/Article/details/gt2cjwglrsj.html

openssl rand -hex 16
来源：http://dali.fzhhl.top/Article/details/gt2hanpsgpa.html

[R68] 计算文件校验值
来源：http://dali.yj202588.top/Article/details/gt2vzttatar.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yongpay.top/Article/details/gt2nfvsffbb.html

[R69] 生成随机密码
来源：http://dali.redwolf501.top/Article/details/gt2exdlvptn.html

head -c 16 /dev/urandom | base64
来源：http://dali.gogol.net.cn/Article/details/gt2pcsjnenz.html

[R70] 时间戳与互转
来源：http://dali.dianchejie.cn/Article/details/gt2ujiwfumo.html

date +%s;  date -d @1700000000
来源：http://dali.xuetiantiany.cn/Article/details/gt2dgooqztd.html

[R71] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gt2jpffiufw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jianghu66.top/Article/details/gt2bzvfviii.html

[R72] 等待端口就绪
来源：http://dali.guannengcc.top/Article/details/gt2jhqozlmc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gt2ecgfwrcf.html

[R73] 分割大日志
来源：http://dali.hnxiangtu.top/Article/details/gt2oigqzrmb.html

split -l 1000 big.log part_
来源：http://dali.xylfe.cn/Article/details/gt2fmxinejn.html

[R74] 批量重命名
来源：http://dali.sysykeji.top/Article/details/gt2lgophxhu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2thwsjgel.html

[R75] 导出环境变量
来源：http://dali.chenlongwang.top/Article/details/gt2ykobgiph.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ybcxt.top/Article/details/gt2bsuxnvcj.html

[R76] 使用临时文件
来源：http://dali.chenlongwang.top/Article/details/gt2ouihkaxl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gt2wuijqmpq.html

[R77] 读取用户输入
来源：http://dali.pengpengdd.cyou/Article/details/gt2uwebqhnz.html

read -rp "请输入: " ans
来源：http://dali.316326.xyz/Article/details/gt2isihjmwk.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mhlcrvww.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yangfankeji.com/Article/details/gt2xpubjjgz.html

[R79] 解析命令行选项
来源：http://dali.jinqigufen.top/Article/details/gt2hccaouwy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgfzy.top/Article/details/gt2idbipjgq.html

[R80] 查看脚本执行耗时
来源：http://dali.cdnleiting.top/Article/details/gt2rptitooo.html

time ./run.sh
来源：http://dali.guowangkeji.top/Article/details/gt2oybegzhl.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2zpfkucag.html

S. C / C++ 专题
来源：http://dali.xuetiantiany.cn/Article/details/gt2kdazujsh.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2onedvzpw.html

[S01] C：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2tiaccljg.html

#include <stdio.h>
来源：http://dali.redwolf501.top/Article/details/gt2nhtuwcca.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.kuanghao11.cn/Article/details/gt2bccfnmnp.html

[S02] C：变量与格式化输出
来源：http://dali.tian-w.cn/Article/details/gt2ryjhdbcl.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qhuyscft.html

[S03] C：读入整数
来源：http://dali.chenjidiqi.icu/Article/details/gt2wcqydqof.html

int x; scanf("%d", &x);
来源：http://dali.0kj1m.cn/Article/details/gt2ccrtlrcb.html

[S04] C：字符串复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twfajpkn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xziqi.cn/Article/details/gt2eyomazzq.html

[S05] C：字符串长度
来源：http://dali.jiagoushi.top/Article/details/gt2mehfjpqr.html

strlen(s)
来源：http://dali.sysykeji.top/Article/details/gt2zwtzsvbo.html

[S06] C：字符串比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2qvpappkg.html

strcmp(a, b) == 0
来源：http://dali.chenzaomai.com/Article/details/gt2fdnmebqh.html

[S07] C：数组遍历求和
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oahkbvow.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgufenzy.top/Article/details/gt2lbicxqbu.html

[S08] C：动态内存分配与释放
来源：http://dali.jiagoushi.top/Article/details/gt2fdauybya.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvillztx.html

[S09] C：结构体定义与初始化
来源：http://dali.zhengqikj.top/Article/details/gt2pxzuszuy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.svipenyu.cn/Article/details/gt2yfqncihz.html

[S10] C：指针与解引用
来源：http://dali.daxiang520.top/Article/details/gt2yqyymofq.html

int *p = &a;  *p = 5;
来源：http://dali.cqqwz.cn/Article/details/gt2usbzdcwa.html

[S11] C：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2vsemjhdj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.snrcjt.cn/Article/details/gt2wgtditvl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj202588.top/Article/details/gt2fzqskrcp.html

fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gt2kaqnnmqj.html

[S12] C：写文件
来源：http://dali.aizwys.cn/Article/details/gt2szikyehe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.316326.xyz/Article/details/gt2idmhzwoe.html

[S13] C：宏定义
来源：http://dali.andypj.xyz/Article/details/gt2kejbsyrp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daxiang520.top/Article/details/gt2vagcvoxg.html

[S14] C：枚举
来源：http://dali.nwbrower.top/Article/details/gt2vholuxuo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.haohaochexian.top/Article/details/gt2ldszyvdp.html

[S15] C：类型转换
来源：http://dali.jianghu66.top/Article/details/gt2rcvgjghk.html

(double) a / b
来源：http://dali.vqdsnc.cn/Article/details/gt2iilgxfbo.html

[S16] C：位操作置位
来源：http://dali.tian-w.cn/Article/details/gt2bnisawqn.html

x |= (1 << 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oglbiilr.html

[S17] C：安全拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gt2eqxkabnp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cdnleiting.top/Article/details/gt2mhksfbex.html

[S18] C：命令行参数
来源：http://dali.sysykeji.top/Article/details/gt2gnignckk.html

int main(int argc, char **argv)
来源：http://dali.kuanghao11.cn/Article/details/gt2sgkrweeb.html

[S19] C：快速排序
来源：http://dali.aizwys.cn/Article/details/gt2tltgtyqs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gt2ydjevqck.html

[S20] C：二分查找
来源：http://dali.ybcxt.top/Article/details/gt2phoyqdrw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gt2gmrrdrht.html

[S21] C：字符类别判断
来源：http://dali.0kj1m.cn/Article/details/gt2bmppymjs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daria6918.cn/Article/details/gt2tozeweug.html

[S22] C：字符串转数字
来源：http://dali.xuetiantiany.cn/Article/details/gt2zcqxqjre.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jiagoushi.top/Article/details/gt2zwhsvege.html

[S23] C：随机数
来源：http://dali.tian-w.cn/Article/details/gt2fosgzywh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuanzhike.top/Article/details/gt2utawbqah.html

[S24] C：获取本地时间
来源：http://dali.birdmap.top/Article/details/gt2zagighxm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yueranfly.top/Article/details/gt2uezzwffd.html

[S25] C：内存拷贝
来源：http://dali.hfpthk.cn/Article/details/gt2kredabnm.html

memcpy(dst, src, n);
来源：http://dali.gogol.net.cn/Article/details/gt2mlbgbmjn.html

[S26] C：内存清零
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rorqsfkz.html

memset(a, 0, sizeof a);
来源：http://dali.gaohongyu789.top/Article/details/gt2wivsdvpn.html

[S27] C：定义常量
来源：http://dali.jinqigfzy.top/Article/details/gt2smhtwimh.html

const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gt2dfjsapys.html

[S28] C：静态变量
来源：http://dali.yj20258888.top/Article/details/gt2shkeiahf.html

static int counter = 0;
来源：http://dali.sxryk.cn/Article/details/gt2xuhmwhvt.html

[S29] C：变参函数
来源：http://dali.mhx1999.top/Article/details/gt2jjfooftp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gt2gphxbtav.html

[S30] C：头文件保护
来源：http://dali.jiagoushi.top/Article/details/gt2auivmeip.html

#ifndef X_H
来源：http://dali.ppjwa.cn/Article/details/gt2jwvvaaix.html

#define X_H
来源：http://dali.cucudq.cn/Article/details/gt2zjapnizf.html

#endif
来源：http://dali.pycfn.com/Article/details/gt2xxhkolaa.html

[S31] C++：Hello World
来源：http://dali.cashguo.top/Article/details/gt2tznneoiq.html

#include <iostream>
来源：http://dali.xinyue.icu/Article/details/gt2eghagfrq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yongpay.top/Article/details/gt2dcbylhuy.html

[S32] C++：字符串
来源：http://dali.zhengqikj.top/Article/details/gt2yirsuzhb.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2obgiofit.html

[S33] C++：vector 增删
来源：http://dali.0kj1m.cn/Article/details/gt2mlfbhiqb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xuanzx.com/Article/details/gt2oeiwbvpt.html

[S34] C++：遍历 vector
来源：http://dali.havefunace.top/Article/details/gt2pnaxjlry.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.iojbl.cn/Article/details/gt2gvmgjsle.html

[S35] C++：map
来源：http://dali.bjfxy.top/Article/details/gt2yqtdawfi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gt2biaapnes.html

[S36] C++：unordered_map
来源：http://dali.quarkkingdee.top/Article/details/gt2uskznkcf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2ljdvhbml.html

[S37] C++：set
来源：http://dali.snrcjt.cn/Article/details/gt2lfsolzrf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gzhubu.top/Article/details/gt2vsddlrir.html

[S38] C++：排序
来源：http://dali.andypj.xyz/Article/details/gt2vilajupo.html

std::sort(v.begin(), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gt2mpfrxibf.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258888.top/Article/details/gt2evcdaoxm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangdashe.top/Article/details/gt2qjwqbhfh.html

[S40] C++：查找元素
来源：http://dali.cashguo.top/Article/details/gt2cpibdtur.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jyoumei.cn/Article/details/gt2scvputud.html

[S41] C++：类与构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2wrjmffhi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cucudq.cn/Article/details/gt2fbkirtmv.html

[S42] C++：继承与虚函数
来源：http://dali.jlsjyb.cn/Article/details/gt2fqpluexm.html

class B : public Base { public: void f() override {} };
来源：http://dali.yuxming.cn/Article/details/gt2pfaakzni.html

[S43] C++：智能指针
来源：http://dali.yuanzhike.top/Article/details/gt2bphwegib.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgufenzy.top/Article/details/gt2lwatbbjz.html

[S44] C++：引用传参
来源：http://dali.tian-w.cn/Article/details/gt2zmdthpmw.html

void inc(int &x) { ++x; }
来源：http://dali.xylfe.cn/Article/details/gt2qaytrfqa.html

[S45] C++：lambda
来源：http://dali.hongshengwenyu.top/Article/details/gt2sicihejq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gt2cspjehnr.html

[S46] C++：函数模板
来源：http://dali.birdmap.top/Article/details/gt2huxxuepv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.9152youxi.cn/Article/details/gt2fcmlfjnh.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhixingplan.top/Article/details/gt2ckcllrvj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangdashe.top/Article/details/gt2fijniodf.html

[S48] C++：逐行读文件
来源：http://dali.yj202588.top/Article/details/gt2sdpdrtif.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hywenlv.cn/Article/details/gt2nwmdlmua.html

while (std::getline(in, line)) { }
来源：http://dali.hfpthk.cn/Article/details/gt2zwpfyzkk.html

[S49] C++：写文件
来源：http://dali.nanxuanxn.top/Article/details/gt2vqwjsvvy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.c1oappe.top/Article/details/gt2rywrbivq.html

[S50] C++：格式化数字
来源：http://dali.iojbl.cn/Article/details/gt2bpcnpshb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guannengcc.top/Article/details/gt2hmrmrkyj.html

[S51] C++：显式类型转换
来源：http://dali.snrcjt.cn/Article/details/gt2rztrwwlt.html

static_cast<double>(a) / b
来源：http://dali.zhengqikj.top/Article/details/gt2urrfwmgo.html

[S52] C++：const 与 noexcept
来源：http://dali.havefunace.top/Article/details/gt2usnqemnk.html

int size() const noexcept { return n_; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2doeefljs.html

[S53] C++：移动语义
来源：http://dali.quarkkingdee.top/Article/details/gt2iujpnnod.html

std::vector<int> w = std::move(v);
来源：http://dali.andypj.xyz/Article/details/gt2crlkvqzo.html

[S54] C++：异常处理
来源：http://dali.zhengqikj.top/Article/details/gt2ikqbtefh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aibaodan.cn/Article/details/gt2ekwcxxhd.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vutasrcr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhixingplan.top/Article/details/gt2drxiuopu.html

[S56] C++：optional
来源：http://dali.snrcjt.cn/Article/details/gt2zljwkxkm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pycfn.com/Article/details/gt2tbdfvkvg.html

[S57] C++：编译期常量
来源：http://dali.zdqjudy.top/Article/details/gt2euvyzqmv.html

constexpr int N = 10;
来源：http://dali.chenzaomai.com/Article/details/gt2vpwaqplp.html

[S58] C++：命名空间
来源：http://dali.yvedp.cn/Article/details/gt2ccmxwrgm.html


<!-- 参考信息 -->