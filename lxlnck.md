代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.zhiwuduotai.top/Article/details/gt2qnobcekr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hfpthk.cn/Article/details/gt2dgjjeten.html

[Q87] JSON 字段做条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tbxrdsfv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daxiang520.top/Article/details/gt2iopqxytr.html

[Q88] 行转列（条件聚合）
来源：http://dali.gogol.net.cn/Article/details/gt2exyygwlp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.meibo888.top/Article/details/gt2zcjurmeb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2wanghmsb.html

[Q89] 判断表是否存在
来源：http://dali.hfpthk.cn/Article/details/gt2qjonvgnn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxuanxn.top/Article/details/gt2xhtwihzr.html

[Q90] 生成序号列
来源：http://dali.9152youxi.cn/Article/details/gt2layubjho.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cheryme.top/Article/details/gt2zyrtbaoi.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2eymjebly.html

R. Bash 专题
来源：http://dali.hnxiangtu.top/Article/details/gt2iqkwxjtx.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ununotvp.html

[R01] shebang 与严格模式
来源：http://dali.birdmap.top/Article/details/gt2pefyblzc.html

#!/usr/bin/env bash
来源：http://dali.xuanzx.com/Article/details/gt2gtvkwrvq.html

set -euo pipefail
来源：http://dali.yj20258888.top/Article/details/gt2dkaowgpr.html

[R02] 变量赋值与使用
来源：http://dali.jqgufenzy.top/Article/details/gt2ttrjczkn.html

name="Tom"; echo "$name"
来源：http://dali.birdmap.top/Article/details/gt2vrtavpli.html

[R03] 只读变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2ihsxstrb.html

readonly PI=3.14
来源：http://dali.meibo888.top/Article/details/gt2nenihppb.html

[R04] 位置参数
来源：http://dali.ehwqpu.com/Article/details/gt2mfosgzzf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj202588.top/Article/details/gt2otszvoxd.html

[R05] 参数默认值
来源：http://dali.fengsongda.top/Article/details/gt2jdhwcsyn.html

name="${1:-default}"
来源：http://dali.jiagoushi.top/Article/details/gt2zzitjros.html

[R06] 判断命令是否存在
来源：http://dali.xuanzx.com/Article/details/gt2xfozczwi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gt2qwmqadme.html

[R07] if 判断文件
来源：http://dali.zhongyouzk.top/Article/details/gt2bodrlktk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2xyonnjge.html

[R08] 数值比较
来源：http://dali.0kj1m.cn/Article/details/gt2fxetkfam.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zbobnkfj.html

[R09] 字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gt2vjhmczvo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cfcydzcw.html

[R10] 正则匹配
来源：http://dali.chenlongwang.top/Article/details/gt2bsvvewzo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gt2tmgtvoxh.html

[R11] case 多分支
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldbtcujr.html

case "$1" in
来源：http://dali.hywenlv.cn/Article/details/gt2fmtmkzhv.html

start) echo "启动" ;;
来源：http://dali.yanxiufei.cn/Article/details/gt2toboiuil.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gt2knkdhphj.html

*)     echo "未知命令" ;;
来源：http://dali.hnxiangtu.top/Article/details/gt2nieyvcnx.html

esac
来源：http://dali.yj202588.top/Article/details/gt2nxpyjzbg.html

[R12] for 遍历文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2cnlrwidj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pycfn.com/Article/details/gt2uabjapdp.html

[R13] for 计数循环
来源：http://dali.nanxinkj.top/Article/details/gt2uyvznxdz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pybiibcd.html

[R14] C 风格 for
来源：http://dali.yueranfly.top/Article/details/gt2sebkohwp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bnjytwhe.html

[R15] while 逐行读文件
来源：http://dali.fengsongda.top/Article/details/gt2yjdrytay.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zycfv.cn/Article/details/gt2qkaafdux.html

[R16] until 等待条件
来源：http://dali.xziqi.cn/Article/details/gt2okauylkz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gt2rdzlzcin.html

[R17] 数组定义与取值
来源：http://dali.zhoulong.xyz/Article/details/gt2effadrjv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aizwys.cn/Article/details/gt2xrzsmvqe.html

[R18] 遍历数组
来源：http://dali.zhixingplan.top/Article/details/gt2jlsyujta.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2fpscjtqn.html

[R19] 数组长度
来源：http://dali.xinyue.icu/Article/details/gt2pnyvusqj.html

echo "${#arr[@]}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2dapcdpha.html

[R20] 关联数组（字典）
来源：http://dali.ivvv.top/Article/details/gt2dexxfjav.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pycfn.com/Article/details/gt2rjqpmgra.html

[R21] 字符串长度
来源：http://dali.yvedp.cn/Article/details/gt2joyugmoi.html

echo "${#s}"
来源：http://dali.dashuyun.cn/Article/details/gt2jbslwuyh.html

[R22] 截取子串
来源：http://dali.havefunace.top/Article/details/gt2kqyykzhl.html

echo "${s:0:5}"
来源：http://dali.vqdsnc.cn/Article/details/gt2buehovyb.html

[R23] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gt2aptnkosg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cdnleiting.top/Article/details/gt2mqbxfaky.html

[R24] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gt2ofymxcpg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbhnyjck.html

[R25] 去后缀 / 去前缀
来源：http://dali.yongpay.top/Article/details/gt2vmjgpmrf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuanzhike.top/Article/details/gt2owojnwaa.html

[R26] 命令替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2fmpdclhd.html

now=$(date +%F); echo "$now"
来源：http://dali.yanxiufei.cn/Article/details/gt2pipcxjbg.html

[R27] 算术展开
来源：http://dali.ybcxt.top/Article/details/gt2lguagfvq.html

echo $((1 + 2 * 3))
来源：http://dali.xinyue.icu/Article/details/gt2yacaokud.html

[R28] 浮点运算
来源：http://dali.jyoumei.cn/Article/details/gt2sebodhjd.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bkcvebkn.html

[R29] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gt2xmocxlqp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangdashe.top/Article/details/gt2gjmgydom.html

[R30] 函数返回状态码
来源：http://dali.bjfxy.top/Article/details/gt2chnuqvba.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.guannengcc.top/Article/details/gt2eaovfvmt.html

[R31] 局部变量
来源：http://dali.yj20258888.top/Article/details/gt2qlxoijuh.html

f() { local x=1; echo "$x"; }
来源：http://dali.hywenlv.cn/Article/details/gt2mduiwapu.html

[R32] 参数个数校验
来源：http://dali.jinqigufen.top/Article/details/gt2vbisgplb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.meibo888.top/Article/details/gt2wzphcwws.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgfzy.top/Article/details/gt2roauiija.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinghuilouyu.cn/Article/details/gt2njldyvmg.html

[R34] 退出时清理
来源：http://dali.hongshengwenyu.top/Article/details/gt2onyhnucq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gt2nqgtnejc.html

[R35] 后台执行并等待
来源：http://dali.jinqigfzy.top/Article/details/gt2qakxkkng.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xuanzx.com/Article/details/gt2hmjyijku.html

[R36] 并发执行多个任务
来源：http://dali.guowangkeji.top/Article/details/gt2tkyomqor.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenjidiqi.icu/Article/details/gt2ahnscsgr.html

[R37] 把输出赋给变量
来源：http://dali.xziqi.cn/Article/details/gt2pjexfefe.html

files=$(ls -1)
来源：http://dali.redwolf501.top/Article/details/gt2xuhrtlge.html

[R38] 管道串联
来源：http://dali.fzhhl.top/Article/details/gt2fgfusvni.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guowangkeji.top/Article/details/gt2xxgwflaw.html

[R39] 重定向标准输出与错误
来源：http://dali.ivvv.top/Article/details/gt2yoxhogml.html

cmd > out.log 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gt2jifwpycz.html

[R40] 追加写日志
来源：http://dali.zdqjudy.top/Article/details/gt2suxdknzq.html

echo "log" >> out.log
来源：http://dali.jinqigufen.top/Article/details/gt2dqbetxvu.html

[R41] 丢弃输出
来源：http://dali.fzhhl.top/Article/details/gt2wvfascpj.html

cmd >/dev/null 2>&1
来源：http://dali.zycfv.cn/Article/details/gt2isqohzop.html

[R42] 输入重定向
来源：http://dali.dashuyun.cn/Article/details/gt2klpdyksi.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gt2twfpprhs.html

[R43] 按名字查找文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2zkepqtrc.html

find . -name "*.log" -type f
来源：http://dali.shangyingyoupin.top/Article/details/gt2ikbaxpuo.html

[R44] 按修改时间查找
来源：http://dali.ydzc1.top/Article/details/gt2puvrnylw.html

find . -mtime -7 -type f
来源：http://dali.pengpengdd.cyou/Article/details/gt2xfdtirdb.html

[R45] 批量删除
来源：http://dali.yj20258888.top/Article/details/gt2aflgwoun.html

find . -name "*.tmp" -delete
来源：http://dali.snrcjt.cn/Article/details/gt2mytfgtbg.html

[R46] 递归替换文件内容
来源：http://dali.xziqi.cn/Article/details/gt2unmfmcyj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhongyouzk.top/Article/details/gt2qcwspbvy.html

[R47] sed 单行替换
来源：http://dali.cdnleiting.top/Article/details/gt2ujqyvuhz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj202588.top/Article/details/gt2otoqnfwf.html

[R48] awk 取指定列
来源：http://dali.nanxuanxn.top/Article/details/gt2dyfhbwms.html

awk '{print $1, $3}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2rfkguauh.html

[R49] awk 带条件
来源：http://dali.cdnleiting.top/Article/details/gt2taembzuk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guowangkeji.top/Article/details/gt2imrxglgr.html

[R50] awk 求和
来源：http://dali.fzhhl.top/Article/details/gt2wupevabd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj202588.top/Article/details/gt2dedseojk.html

[R51] 排序去重取前几
来源：http://dali.iojbl.cn/Article/details/gt2eeahugnn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.feifeiyinyue.top/Article/details/gt2olagmnyp.html

[R52] 统计行数
来源：http://dali.fengsongda.top/Article/details/gt2zeyhhzpq.html

wc -l a.txt
来源：http://dali.nanxinkj.top/Article/details/gt2pcwxtdxh.html

[R53] 查看文件头与实时尾
来源：http://dali.hfpthk.cn/Article/details/gt2lylmbhsj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ivvv.top/Article/details/gt2bbdbduor.html

[R54] 比较两个文件
来源：http://dali.jinqigufen.top/Article/details/gt2ibpuusxr.html

diff a.txt b.txt
来源：http://dali.dianchejie.cn/Article/details/gt2edukdvpe.html

[R55] 压缩与解压
来源：http://dali.dashuyun.cn/Article/details/gt2xuqgcouf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hfpthk.cn/Article/details/gt2jlqqqlot.html

[R56] 远程拷贝
来源：http://dali.meibo888.top/Article/details/gt2gncfckeb.html

scp file user@host:/path/
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgaabixd.html

[R57] 远程执行命令
来源：http://dali.jianghu66.top/Article/details/gt2qulwylqb.html

ssh user@host 'uptime'
来源：http://dali.yuxming.cn/Article/details/gt2zldcpmdh.html

[R58] 下载文件
来源：http://dali.svipenyu.cn/Article/details/gt2zpqnyxpv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gt2yejcbiaq.html

[R59] 发 POST JSON
来源：http://dali.sweek.top/Article/details/gt2puljslyf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cashguo.top/Article/details/gt2uzswvqqf.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gt2wpelqjry.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.bjfxy.top/Article/details/gt2ifrpxkgq.html

[R61] 磁盘占用
来源：http://dali.havefunace.top/Article/details/gt2yvwyqoce.html

df -h;  du -sh *
来源：http://dali.9152youxi.cn/Article/details/gt2smcdzjby.html

[R62] 找最占空间的文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2ldpslovy.html

du -ah . | sort -rh | head -10
来源：http://dali.yuxming.cn/Article/details/gt2myqagnti.html

[R63] 内存与进程
来源：http://dali.havefunace.top/Article/details/gt2ihdnjzhp.html

free -h;  ps aux | grep nginx
来源：http://dali.vqdsnc.cn/Article/details/gt2icxynsci.html

[R64] 结束进程
来源：http://dali.ydzc1.top/Article/details/gt2lmshhwmm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yangfankeji.com/Article/details/gt2hdjmjftv.html

[R65] 查看端口占用
来源：http://dali.guowangkeji.top/Article/details/gt2iiomnure.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fengsongda.top/Article/details/gt2ryofderw.html

[R66] 定时任务
来源：http://dali.hnxiangtu.top/Article/details/gt2uutwcwqs.html

crontab -e;  crontab -l
来源：http://dali.smart0.xyz/Article/details/gt2lywlxpyj.html

[R67] 生成随机十六进制串
来源：http://dali.cqqwz.cn/Article/details/gt2gztdarkk.html

openssl rand -hex 16
来源：http://dali.redwolf501.top/Article/details/gt2krhazsvz.html

[R68] 计算文件校验值
来源：http://dali.xylfe.cn/Article/details/gt2dgmgyayi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigufen.top/Article/details/gt2zxzpstcb.html

[R69] 生成随机密码
来源：http://dali.hysaishi.cn/Article/details/gt2bwoprtur.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abbgjnvb.html

[R70] 时间戳与互转
来源：http://dali.daria6918.cn/Article/details/gt2bfjobxzw.html

date +%s;  date -d @1700000000
来源：http://dali.meibo888.top/Article/details/gt2yjkeqdgw.html

[R71] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yysuoapi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yongpay.top/Article/details/gt2hwvgemlp.html

[R72] 等待端口就绪
来源：http://dali.gotoacloud.top/Article/details/gt2gfyczwmu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gt2jutoinnc.html

[R73] 分割大日志
来源：http://dali.andypj.xyz/Article/details/gt2ygiipckf.html

split -l 1000 big.log part_
来源：http://dali.guannengcc.top/Article/details/gt2vfpkqonr.html

[R74] 批量重命名
来源：http://dali.snrcjt.cn/Article/details/gt2cxgvjdkr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgfzy.top/Article/details/gt2fhwkiykk.html

[R75] 导出环境变量
来源：http://dali.yvedp.cn/Article/details/gt2jgnuaexv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.feifeiyinyue.top/Article/details/gt2wsrhhlen.html

[R76] 使用临时文件
来源：http://dali.yvedp.cn/Article/details/gt2rnebxrms.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zusacfff.html

[R77] 读取用户输入
来源：http://dali.c1oappe.top/Article/details/gt2gjwhxxoy.html

read -rp "请输入: " ans
来源：http://dali.fzhhl.top/Article/details/gt2hkzxcedd.html

[R78] 交互式菜单
来源：http://dali.pycfn.com/Article/details/gt2fywlxbnv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fengsongda.top/Article/details/gt2umwdqwsj.html

[R79] 解析命令行选项
来源：http://dali.gotoacloud.top/Article/details/gt2ugckfjyv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zdqjudy.top/Article/details/gt2hvndspka.html

[R80] 查看脚本执行耗时
来源：http://dali.jinghuilouyu.cn/Article/details/gt2reaswesp.html

time ./run.sh
来源：http://dali.zhiwuduotai.top/Article/details/gt2cyxdyosi.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2ykshzjkw.html

S. C / C++ 专题
来源：http://dali.chenzaomai.com/Article/details/gt2qaowlprk.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2rfygbkir.html

[S01] C：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2czohxeii.html

#include <stdio.h>
来源：http://dali.ehwqpu.com/Article/details/gt2aeihtcfe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fzhhl.top/Article/details/gt2mhlxintk.html

[S02] C：变量与格式化输出
来源：http://dali.iojbl.cn/Article/details/gt2ulhjwapp.html

int a = 10; printf("%d\n", a);
来源：http://dali.hywenlv.cn/Article/details/gt2bgnbglqo.html

[S03] C：读入整数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2clpcmrpq.html

int x; scanf("%d", &x);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ezjxptve.html

[S04] C：字符串复制
来源：http://dali.sufxvd.cn/Article/details/gt2migxdooh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2twtmdzah.html

[S05] C：字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hpxixikv.html

strlen(s)
来源：http://dali.hammf.cn/Article/details/gt2fgdskcbh.html

[S06] C：字符串比较
来源：http://dali.ppjwa.cn/Article/details/gt2bbhuvvgf.html

strcmp(a, b) == 0
来源：http://dali.xinyue.icu/Article/details/gt2xhwqseiu.html

[S07] C：数组遍历求和
来源：http://dali.zhoulong.xyz/Article/details/gt2gngogaje.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gzhubu.top/Article/details/gt2mglqkybb.html

[S08] C：动态内存分配与释放
来源：http://dali.xziqi.cn/Article/details/gt2nrsdsbpp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shuidangran.top/Article/details/gt2vmceclcj.html

[S09] C：结构体定义与初始化
来源：http://dali.9152youxi.cn/Article/details/gt2ncqsqxpo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cucudq.cn/Article/details/gt2oynctylo.html

[S10] C：指针与解引用
来源：http://dali.ppjwa.cn/Article/details/gt2swxxjazi.html

int *p = &a;  *p = 5;
来源：http://dali.chenzaomai.com/Article/details/gt2efomitah.html

[S11] C：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gt2idvehnmp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dianchejie.cn/Article/details/gt2siywczcc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2icsibxjh.html

fclose(f);
来源：http://dali.hnqzz.top/Article/details/gt2vwylhusd.html

[S12] C：写文件
来源：http://dali.zhongyouzk.top/Article/details/gt2klnmdatr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gt2rkhhhckg.html

[S13] C：宏定义
来源：http://dali.feifeiyinyue.top/Article/details/gt2jaquwjvi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258888.top/Article/details/gt2uwylerqo.html

[S14] C：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gt2iznrqqvm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dashuyun.cn/Article/details/gt2nflzuwdo.html

[S15] C：类型转换
来源：http://dali.smart0.xyz/Article/details/gt2cgqhvtal.html

(double) a / b
来源：http://dali.havefunace.top/Article/details/gt2mlrcqebm.html

[S16] C：位操作置位
来源：http://dali.yj202588.top/Article/details/gt2adtsgvqp.html

x |= (1 << 3);
来源：http://dali.yj202588.top/Article/details/gt2endqhpll.html

[S17] C：安全拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gt2cnuaeenu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ehwqpu.com/Article/details/gt2kxdufkis.html

[S18] C：命令行参数
来源：http://dali.zhixingplan.top/Article/details/gt2iylhienl.html

int main(int argc, char **argv)
来源：http://dali.nwbrower.top/Article/details/gt2xozjpvoa.html

[S19] C：快速排序
来源：http://dali.xinyue.icu/Article/details/gt2jpouulwu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gt2wmezmhiv.html

[S20] C：二分查找
来源：http://dali.hfpthk.cn/Article/details/gt2xgjzolfr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gt2ssiqdmqm.html

[S21] C：字符类别判断
来源：http://dali.zhengqikj.top/Article/details/gt2gzzthcgh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xziqi.cn/Article/details/gt2vvbfugfs.html

[S22] C：字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gt2bunqmszc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dianchejie.cn/Article/details/gt2lwumtlkt.html

[S23] C：随机数
来源：http://dali.zdqjudy.top/Article/details/gt2kekntayq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhixingplan.top/Article/details/gt2ekwmfpsh.html

[S24] C：获取本地时间
来源：http://dali.feifeiyinyue.top/Article/details/gt2znddbyvm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gt2yamykuez.html

[S25] C：内存拷贝
来源：http://dali.yj20258.top/Article/details/gt2hfsekvyl.html

memcpy(dst, src, n);
来源：http://dali.yj202588.top/Article/details/gt2eetyljov.html

[S26] C：内存清零
来源：http://dali.mhx1999.top/Article/details/gt2dwesypft.html

memset(a, 0, sizeof a);
来源：http://dali.quarkkingdee.top/Article/details/gt2mwosnkjm.html

[S27] C：定义常量
来源：http://dali.xuanzx.com/Article/details/gt2bmgxbzpx.html

const double PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2joyfygid.html

[S28] C：静态变量
来源：http://dali.fzhhl.top/Article/details/gt2pzyefklq.html

static int counter = 0;
来源：http://dali.fzhhl.top/Article/details/gt2aqufrikh.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gt2toxajnlt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgufenzy.top/Article/details/gt2uhevwovi.html

[S30] C：头文件保护
来源：http://dali.fzhhl.top/Article/details/gt2raqgkohe.html

#ifndef X_H
来源：http://dali.nanxinkj.top/Article/details/gt2pyjpaawc.html

#define X_H
来源：http://dali.jqgufenzy.top/Article/details/gt2kvqoknoe.html

#endif
来源：http://dali.xziqi.cn/Article/details/gt2twrionjh.html

[S31] C++：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2tyvnkbtr.html

#include <iostream>
来源：http://dali.xuetiantiany.cn/Article/details/gt2btqnezkv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2beruvzof.html

[S32] C++：字符串
来源：http://dali.0kj1m.cn/Article/details/gt2hgjfmfmv.html

std::string s = "hi";  s += "!";
来源：http://dali.cheryme.top/Article/details/gt2frdahjao.html

[S33] C++：vector 增删
来源：http://dali.yonumen.top/Article/details/gt2ccmdhniv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tianlin.xyz/Article/details/gt2euotarrj.html

[S34] C++：遍历 vector
来源：http://dali.mhx1999.top/Article/details/gt2auylxbfq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uikdqsir.html

[S35] C++：map
来源：http://dali.hywenlv.cn/Article/details/gt2cprpfrqk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gt2xochkori.html

[S36] C++：unordered_map
来源：http://dali.sufxvd.cn/Article/details/gt2plobhvxe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2kemkpqow.html

[S37] C++：set
来源：http://dali.shangyingyoupin.top/Article/details/gt2fuskmfkb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2rlwkteca.html

[S38] C++：排序
来源：http://dali.jinqigfzy.top/Article/details/gt2rdbhuptk.html

std::sort(v.begin(), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gt2zdejeoce.html

[S39] C++：自定义比较器排序
来源：http://dali.xziqi.cn/Article/details/gt2qrescwlf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pyctleqt.html

[S40] C++：查找元素
来源：http://dali.meibo888.top/Article/details/gt2jhctbhiw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.0kj1m.cn/Article/details/gt2kjsnsgzd.html

[S41] C++：类与构造函数
来源：http://dali.yj202588.top/Article/details/gt2xbhbwbni.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.iojbl.cn/Article/details/gt2prbfjmma.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigufen.top/Article/details/gt2zxzolfdf.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenjidiqi.icu/Article/details/gt2awactipf.html

[S43] C++：智能指针
来源：http://dali.gzhubu.top/Article/details/gt2jrazylaf.html

auto p = std::make_unique<int>(5);
来源：http://dali.ybcxt.top/Article/details/gt2bknvqvfc.html

[S44] C++：引用传参
来源：http://dali.nwbrower.top/Article/details/gt2rrczxmuh.html

void inc(int &x) { ++x; }
来源：http://dali.daria6918.cn/Article/details/gt2vhqfbgfo.html

[S45] C++：lambda
来源：http://dali.0kj1m.cn/Article/details/gt2lkdbmlew.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2pkzvmeqv.html

[S46] C++：函数模板
来源：http://dali.sysykeji.top/Article/details/gt2pmifcqeq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2uvnrpfmy.html

[S47] C++：结构化绑定遍历
来源：http://dali.xziqi.cn/Article/details/gt2qfqbwjsa.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2modvemgp.html

[S48] C++：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gt2yrofyjbn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ivvv.top/Article/details/gt2cnmgnwgm.html

while (std::getline(in, line)) { }
来源：http://dali.haohaochexian.top/Article/details/gt2hjzjafer.html

[S49] C++：写文件
来源：http://dali.smart0.xyz/Article/details/gt2wdhmlxef.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dianchejie.cn/Article/details/gt2rcnmbnnj.html

[S50] C++：格式化数字
来源：http://dali.jianghu66.top/Article/details/gt2uusqgssz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tanke756.top/Article/details/gt2umemzopw.html

[S51] C++：显式类型转换
来源：http://dali.hfpthk.cn/Article/details/gt2jarokazb.html

static_cast<double>(a) / b
来源：http://dali.haohaochexian.top/Article/details/gt2ythxtghe.html

[S52] C++：const 与 noexcept
来源：http://dali.smart0.xyz/Article/details/gt2xmxdyrhu.html

int size() const noexcept { return n_; }
来源：http://dali.sufxvd.cn/Article/details/gt2yanbypjg.html

[S53] C++：移动语义
来源：http://dali.jqgfzy.top/Article/details/gt2xzbbuqve.html

std::vector<int> w = std::move(v);
来源：http://dali.kuanghao11.cn/Article/details/gt2ejaciabo.html

[S54] C++：异常处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2fgleqpqa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj202588.top/Article/details/gt2gqboilqx.html

[S55] C++：结构化绑定
来源：http://dali.iojbl.cn/Article/details/gt2sjspeahe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2wzerxrdb.html

[S56] C++：optional
来源：http://dali.feifeiyinyue.top/Article/details/gt2weimuekw.html


<!-- 参考信息 -->