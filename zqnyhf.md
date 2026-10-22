代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.gotoacloud.top/Article/details/gtmqtofazo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gttnjlruux.html

[Q83] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtagdntcng.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtmafedkno.html

[Q84] 去除首尾空格
来源：http://dali.pengpengdd.cyou/Article/details/gtqufwqzyc.html

SELECT TRIM(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtgykdrepl.html

[Q85] 数值取整
来源：http://dali.0kj1m.cn/Article/details/gtfbqgaejq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhengqikj.top/Article/details/gtlbdtwdby.html

[Q86] 读取 JSON 字段
来源：http://dali.zhiwuduotai.top/Article/details/gtpgkdolkw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gotoacloud.top/Article/details/gtqcbemvfo.html

[Q87] JSON 字段做条件
来源：http://dali.sxryk.cn/Article/details/gthwxpmnfr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.haohaochexian.top/Article/details/gtwrollsqg.html

[Q88] 行转列（条件聚合）
来源：http://dali.c1oappe.top/Article/details/gtzrxlwitj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xinyue.icu/Article/details/gtlvtzjqim.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtcvuogpjo.html

[Q89] 判断表是否存在
来源：http://dali.ivvv.top/Article/details/gtmxabghaa.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jyoumei.cn/Article/details/gtvnxkqrpi.html

[Q90] 生成序号列
来源：http://dali.mhx1999.top/Article/details/gtsbipolkx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ivvv.top/Article/details/gtdablhjmw.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtohbswzcd.html

R. Bash 专题
来源：http://dali.kuanghao11.cn/Article/details/gtjzwmffmd.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtpwzmmyys.html

[R01] shebang 与严格模式
来源：http://dali.xuetiantiany.cn/Article/details/gtklijopjr.html

#!/usr/bin/env bash
来源：http://dali.zycfv.cn/Article/details/gtfinganls.html

set -euo pipefail
来源：http://dali.daria6918.cn/Article/details/gtkcfzwiqm.html

[R02] 变量赋值与使用
来源：http://dali.hammf.cn/Article/details/gtiopuptlu.html

name="Tom"; echo "$name"
来源：http://dali.hywenlv.cn/Article/details/gtbmikxaxc.html

[R03] 只读变量
来源：http://dali.chenjidiqi.icu/Article/details/gtabvwugin.html

readonly PI=3.14
来源：http://dali.gaohongyu789.top/Article/details/gtojavmols.html

[R04] 位置参数
来源：http://dali.zhiwuduotai.top/Article/details/gtlbyluwzs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xziqi.cn/Article/details/gtxkxlssvv.html

[R05] 参数默认值
来源：http://dali.jqgfzy.top/Article/details/gttsxhtuet.html

name="${1:-default}"
来源：http://dali.cheryme.top/Article/details/gtjuczcgqp.html

[R06] 判断命令是否存在
来源：http://dali.andypj.xyz/Article/details/gtwwcguqej.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gtykdhzwir.html

[R07] if 判断文件
来源：http://dali.cucudq.cn/Article/details/gtwlvzqzhg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jiagoushi.top/Article/details/gtnenawxwj.html

[R08] 数值比较
来源：http://dali.yj202588.top/Article/details/gtohudhksn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhongyouzk.top/Article/details/gttscjyavi.html

[R09] 字符串比较
来源：http://dali.zhengqikj.top/Article/details/gtzfcpqwdo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258.top/Article/details/gtsrehcmlq.html

[R10] 正则匹配
来源：http://dali.jinqigfzy.top/Article/details/gtwjlylwcw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnqzz.top/Article/details/gtnhmjndtm.html

[R11] case 多分支
来源：http://dali.yanxiufei.cn/Article/details/gtitmkvobp.html

case "$1" in
来源：http://dali.zhiwuduotai.top/Article/details/gtoexyrhrx.html

start) echo "启动" ;;
来源：http://dali.fzhhl.top/Article/details/gtqxqbhzyq.html

stop)  echo "停止" ;;
来源：http://dali.tanke756.top/Article/details/gtjycswtbc.html

*)     echo "未知命令" ;;
来源：http://dali.cashguo.top/Article/details/gtacphpwrw.html

esac
来源：http://dali.hysaishi.cn/Article/details/gtpmzjixvf.html

[R12] for 遍历文件
来源：http://dali.andypj.xyz/Article/details/gtcmkcoflv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstgqnxyw.html

[R13] for 计数循环
来源：http://dali.pengpengdd.cyou/Article/details/gtxwtcflug.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gtghhfayap.html

[R14] C 风格 for
来源：http://dali.hywenlv.cn/Article/details/gtpgaqdtxf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gteiqoiiem.html

[R15] while 逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtptzgmtnf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sxryk.cn/Article/details/gtjyxeestd.html

[R16] until 等待条件
来源：http://dali.mhx1999.top/Article/details/gtqbnntrym.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtfmopkjua.html

[R17] 数组定义与取值
来源：http://dali.daxiang520.top/Article/details/gtukakxmhx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.0kj1m.cn/Article/details/gtebxaelba.html

[R18] 遍历数组
来源：http://dali.ppjwa.cn/Article/details/gtwnqxdsjx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yangfankeji.com/Article/details/gtabxfuvpd.html

[R19] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gtesrsmcfp.html

echo "${#arr[@]}"
来源：http://dali.hywenlv.cn/Article/details/gtlfoymluc.html

[R20] 关联数组（字典）
来源：http://dali.shangyingyoupin.top/Article/details/gtdayxrvjh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhoulong.xyz/Article/details/gtkyapawup.html

[R21] 字符串长度
来源：http://dali.fzhhl.top/Article/details/gtvyulglgp.html

echo "${#s}"
来源：http://dali.dianchejie.cn/Article/details/gtohvclayw.html

[R22] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gtpwjnbgyd.html

echo "${s:0:5}"
来源：http://dali.nanxuanxn.top/Article/details/gtvkiouogc.html

[R23] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gtdvqgtpjb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.iojbl.cn/Article/details/gtofqexpms.html

[R24] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtjkbusthf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gogol.net.cn/Article/details/gteaotdipk.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gtszfadgaf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhixingplan.top/Article/details/gtrexasazy.html

[R26] 命令替换
来源：http://dali.ybcxt.top/Article/details/gtpxbmcpkq.html

now=$(date +%F); echo "$now"
来源：http://dali.jyoumei.cn/Article/details/gtbjiwcdtd.html

[R27] 算术展开
来源：http://dali.bjfxy.top/Article/details/gtlaltgcno.html

echo $((1 + 2 * 3))
来源：http://dali.hfpthk.cn/Article/details/gttxrdfjzn.html

[R28] 浮点运算
来源：http://dali.hongshengwenyu.top/Article/details/gtbydwxiaf.html

echo "scale=2; 10/3" | bc
来源：http://dali.quarkkingdee.top/Article/details/gtbjxtpihy.html

[R29] 定义函数
来源：http://dali.316326.xyz/Article/details/gtmmiugpbu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xziqi.cn/Article/details/gtzkffnaef.html

[R30] 函数返回状态码
来源：http://dali.andypj.xyz/Article/details/gtdrsmzdbu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.aizwys.cn/Article/details/gtvxuubebf.html

[R31] 局部变量
来源：http://dali.cqqwz.cn/Article/details/gtzvtfizlm.html

f() { local x=1; echo "$x"; }
来源：http://dali.xziqi.cn/Article/details/gtshfxfxtx.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangtech.top/Article/details/gttcnjmwkx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gtzbyxbzzo.html

[R33] 捕获错误并提示行号
来源：http://dali.ppjwa.cn/Article/details/gtdukhqjbe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jqgfzy.top/Article/details/gtgqufepol.html

[R34] 退出时清理
来源：http://dali.chenzaomai.com/Article/details/gtpmyywhzs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnfqnbyn.html

[R35] 后台执行并等待
来源：http://dali.svipenyu.cn/Article/details/gtihqyanmp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgfzy.top/Article/details/gtavpotafx.html

[R36] 并发执行多个任务
来源：http://dali.andypj.xyz/Article/details/gtkukhuirj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aizwys.cn/Article/details/gtwpeseqec.html

[R37] 把输出赋给变量
来源：http://dali.redwolf501.top/Article/details/gtwfedyhrj.html

files=$(ls -1)
来源：http://dali.ehwqpu.com/Article/details/gtccqgnmfi.html

[R38] 管道串联
来源：http://dali.hammf.cn/Article/details/gtqjhslmmc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shangyingyoupin.top/Article/details/gtqejrvtbn.html

[R39] 重定向标准输出与错误
来源：http://dali.kuanghao11.cn/Article/details/gttziekrxx.html

cmd > out.log 2>&1
来源：http://dali.sysykeji.top/Article/details/gtclbohbpa.html

[R40] 追加写日志
来源：http://dali.quarkkingdee.top/Article/details/gtskogfvuv.html

echo "log" >> out.log
来源：http://dali.shangyingyoupin.top/Article/details/gttvjgpiat.html

[R41] 丢弃输出
来源：http://dali.xuetiantiany.cn/Article/details/gtyulpaxxy.html

cmd >/dev/null 2>&1
来源：http://dali.yvedp.cn/Article/details/gtivrmpguw.html

[R42] 输入重定向
来源：http://dali.jlsjyb.cn/Article/details/gtmbmordeg.html

wc -l < a.txt
来源：http://dali.andypj.xyz/Article/details/gttjyinexg.html

[R43] 按名字查找文件
来源：http://dali.guannengcc.top/Article/details/gtfbfngzuf.html

find . -name "*.log" -type f
来源：http://dali.yuanzhike.top/Article/details/gtbjftvevg.html

[R44] 按修改时间查找
来源：http://dali.chenzaomai.com/Article/details/gtucitbwfm.html

find . -mtime -7 -type f
来源：http://dali.ppjwa.cn/Article/details/gtwuhzgcts.html

[R45] 批量删除
来源：http://dali.hnqzz.top/Article/details/gteoegymef.html

find . -name "*.tmp" -delete
来源：http://dali.yangfankeji.com/Article/details/gthktekrxq.html

[R46] 递归替换文件内容
来源：http://dali.ehwqpu.com/Article/details/gtevmrlpdw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yonumen.top/Article/details/gtcovdqxgl.html

[R47] sed 单行替换
来源：http://dali.xinyue.icu/Article/details/gtkjmntfuz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtzpqvzbbl.html

[R48] awk 取指定列
来源：http://dali.zdqjudy.top/Article/details/gtduqedepo.html

awk '{print $1, $3}' a.txt
来源：http://dali.smart0.xyz/Article/details/gtttodgond.html

[R49] awk 带条件
来源：http://dali.meibo888.top/Article/details/gtfuiavwjj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gtfvxadvvw.html

[R50] awk 求和
来源：http://dali.bjfxy.top/Article/details/gtvjofezfc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtjacxqgrt.html

[R51] 排序去重取前几
来源：http://dali.kuanghao11.cn/Article/details/gtpyerxdaf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cheryme.top/Article/details/gtznwubuzt.html

[R52] 统计行数
来源：http://dali.jqgufenzy.top/Article/details/gtlmkunujt.html

wc -l a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtehlxrgks.html

[R53] 查看文件头与实时尾
来源：http://dali.gzhubu.top/Article/details/gtzmafgslm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.c1oappe.top/Article/details/gttiegswgg.html

[R54] 比较两个文件
来源：http://dali.yangfankeji.com/Article/details/gtnwusckuo.html

diff a.txt b.txt
来源：http://dali.zhixingplan.top/Article/details/gtiijxdxgw.html

[R55] 压缩与解压
来源：http://dali.chenzaomai.com/Article/details/gtsgvaqdzn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.wangshuangyany.cn/Article/details/gtgqcbqbzt.html

[R56] 远程拷贝
来源：http://dali.vqdsnc.cn/Article/details/gtnqbslneq.html

scp file user@host:/path/
来源：http://dali.tian-w.cn/Article/details/gtqyywcmbe.html

[R57] 远程执行命令
来源：http://dali.yanxiufei.cn/Article/details/gtdcjqsqoh.html

ssh user@host 'uptime'
来源：http://dali.jiagoushi.top/Article/details/gtkpbvttxe.html

[R58] 下载文件
来源：http://dali.zdqjudy.top/Article/details/gtizqdhrqx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hnxiangtu.top/Article/details/gtufzaxici.html

[R59] 发 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gtfvdoesil.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ppjwa.cn/Article/details/gttubuprut.html

[R60] 只看 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gtghwzgrcb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yangfankeji.com/Article/details/gteunloxrm.html

[R61] 磁盘占用
来源：http://dali.hnqzz.top/Article/details/gtnxsfvadj.html

df -h;  du -sh *
来源：http://dali.jiagoushi.top/Article/details/gtclirfxde.html

[R62] 找最占空间的文件
来源：http://dali.jinqigfzy.top/Article/details/gtpovnbwrs.html

du -ah . | sort -rh | head -10
来源：http://dali.316326.xyz/Article/details/gtwywcwzqy.html

[R63] 内存与进程
来源：http://dali.yj20258.top/Article/details/gtvuntoimg.html

free -h;  ps aux | grep nginx
来源：http://dali.9152youxi.cn/Article/details/gtkzhwbjsc.html

[R64] 结束进程
来源：http://dali.nanxuanxn.top/Article/details/gtdzscqqid.html

kill -9 $(pgrep -f app.py)
来源：http://dali.snrcjt.cn/Article/details/gtavbenmcr.html

[R65] 查看端口占用
来源：http://dali.gzhubu.top/Article/details/gtwydliiry.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.snrcjt.cn/Article/details/gtzpbgnpbs.html

[R66] 定时任务
来源：http://dali.xylfe.cn/Article/details/gtehoghekx.html

crontab -e;  crontab -l
来源：http://dali.hywenlv.cn/Article/details/gtqkhkpzfm.html

[R67] 生成随机十六进制串
来源：http://dali.havefunace.top/Article/details/gtiuxcyedp.html

openssl rand -hex 16
来源：http://dali.iojbl.cn/Article/details/gtllwyijvp.html

[R68] 计算文件校验值
来源：http://dali.ybcxt.top/Article/details/gtpqnntyha.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xinyue.icu/Article/details/gtaxpcpgsg.html

[R69] 生成随机密码
来源：http://dali.sufxvd.cn/Article/details/gtrljjmvfs.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj20258.top/Article/details/gtfubbpxbu.html

[R70] 时间戳与互转
来源：http://dali.shangyingyoupin.top/Article/details/gtojrvqdyr.html

date +%s;  date -d @1700000000
来源：http://dali.dashuyun.cn/Article/details/gtntdvgrmp.html

[R71] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gtgwksrqxx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.havefunace.top/Article/details/gtybuuidpd.html

[R72] 等待端口就绪
来源：http://dali.yonumen.top/Article/details/gtltadhlpg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gttavnelcr.html

[R73] 分割大日志
来源：http://dali.wangshuangyany.cn/Article/details/gtuejrynxo.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfokivpgi.html

[R74] 批量重命名
来源：http://dali.ppjwa.cn/Article/details/gtsjocantb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jiagoushi.top/Article/details/gtrxluroqv.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gtkzjnqgri.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hammf.cn/Article/details/gtbxtvqpwp.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gtsvptkvzf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenlongwang.top/Article/details/gtqxpdvvvj.html

[R77] 读取用户输入
来源：http://dali.chenlongwang.top/Article/details/gthagaaurp.html

read -rp "请输入: " ans
来源：http://dali.hnxiangtu.top/Article/details/gthymjtlzp.html

[R78] 交互式菜单
来源：http://dali.feifeiyinyue.top/Article/details/gtbcurhptt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hysaishi.cn/Article/details/gtjezyerfz.html

[R79] 解析命令行选项
来源：http://dali.zycfv.cn/Article/details/gtmwjgqeal.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nwbrower.top/Article/details/gtcrpkakmj.html

[R80] 查看脚本执行耗时
来源：http://dali.zycfv.cn/Article/details/gtxiuyeghj.html

time ./run.sh
来源：http://dali.ivvv.top/Article/details/gtrxbguubi.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gthueamvib.html

S. C / C++ 专题
来源：http://dali.zhongyouzk.top/Article/details/gtsrwndghc.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtyxuyehlo.html

[S01] C：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtvbhbhdrq.html

#include <stdio.h>
来源：http://dali.chenjidiqi.icu/Article/details/gtkounfspo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jyoumei.cn/Article/details/gtvkkwyhcw.html

[S02] C：变量与格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtafjlbcyn.html

int a = 10; printf("%d\n", a);
来源：http://dali.guannengcc.top/Article/details/gtnkddcues.html

[S03] C：读入整数
来源：http://dali.gotoacloud.top/Article/details/gthqeqaajj.html

int x; scanf("%d", &x);
来源：http://dali.yueranfly.top/Article/details/gticcqdjzu.html

[S04] C：字符串复制
来源：http://dali.gogol.net.cn/Article/details/gtvmlwdpim.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yonumen.top/Article/details/gtszzdelie.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gtkjljhtxo.html

strlen(s)
来源：http://dali.shzxlz.cn/Article/details/gtsemuvqvu.html

[S06] C：字符串比较
来源：http://dali.mhx1999.top/Article/details/gtgmvwgvwo.html

strcmp(a, b) == 0
来源：http://dali.yonumen.top/Article/details/gtuipaicuz.html

[S07] C：数组遍历求和
来源：http://dali.yj202588.top/Article/details/gtqnnghtub.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjbbnxrv.html

[S08] C：动态内存分配与释放
来源：http://dali.snrcjt.cn/Article/details/gtzrmpqagi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fengsongda.top/Article/details/gtxfmobums.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdnetcuj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhoulong.xyz/Article/details/gttpwahiim.html

[S10] C：指针与解引用
来源：http://dali.nwbrower.top/Article/details/gtpcbufiea.html

int *p = &a;  *p = 5;
来源：http://dali.mhx1999.top/Article/details/gthsarhwlr.html

[S11] C：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtmwzsmaki.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ydzc1.top/Article/details/gtnhyrunsh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sysykeji.top/Article/details/gtbazuxpfe.html

fclose(f);
来源：http://dali.yj20258888.top/Article/details/gtvxhspvya.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gtmeeudyhi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gthviozcyq.html

[S13] C：宏定义
来源：http://dali.meibo888.top/Article/details/gtmflgmvwm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fzhhl.top/Article/details/gtdewigyxb.html

[S14] C：枚举
来源：http://dali.birdmap.top/Article/details/gtwyfqsgmd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jqgufenzy.top/Article/details/gtcjshdqex.html

[S15] C：类型转换
来源：http://dali.fengsongda.top/Article/details/gtpwskenom.html

(double) a / b
来源：http://dali.haohaochexian.top/Article/details/gtyvkthrhj.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gtdrnseemo.html

x |= (1 << 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gttyzxxtqv.html

[S17] C：安全拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtpjigmjpt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigfzy.top/Article/details/gtkukysnvj.html

[S18] C：命令行参数
来源：http://dali.shuidangran.top/Article/details/gtxqdmywit.html

int main(int argc, char **argv)
来源：http://dali.andypj.xyz/Article/details/gttdjwlzzk.html

[S19] C：快速排序
来源：http://dali.jinqigfzy.top/Article/details/gtfcezjufz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nanxinkj.top/Article/details/gtndcfiwzt.html

[S20] C：二分查找
来源：http://dali.hammf.cn/Article/details/gtgooqhikd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtlotawnes.html

[S21] C：字符类别判断
来源：http://dali.jqgufenzy.top/Article/details/gtiorxmptq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gtadgjjsea.html

[S22] C：字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gtjinexgzt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cheryme.top/Article/details/gtekliqxxz.html

[S23] C：随机数
来源：http://dali.hfpthk.cn/Article/details/gtbgvyxplh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenlongwang.top/Article/details/gtewwlbrge.html

[S24] C：获取本地时间
来源：http://dali.aibaodan.cn/Article/details/gtixwizrqs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigufen.top/Article/details/gtjjrlyiji.html

[S25] C：内存拷贝
来源：http://dali.vqdsnc.cn/Article/details/gtrzxpfgfa.html

memcpy(dst, src, n);
来源：http://dali.nanxinkj.top/Article/details/gtemyhmbyt.html

[S26] C：内存清零
来源：http://dali.dashuyun.cn/Article/details/gtckqehtfe.html

memset(a, 0, sizeof a);
来源：http://dali.birdmap.top/Article/details/gtmavrhdfx.html

[S27] C：定义常量
来源：http://dali.jyoumei.cn/Article/details/gtsgkfhdmw.html

const double PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gthuyasqvg.html

[S28] C：静态变量
来源：http://dali.ppjwa.cn/Article/details/gtikdudgiq.html

static int counter = 0;
来源：http://dali.hongshengwenyu.top/Article/details/gtnqlxnrvb.html

[S29] C：变参函数
来源：http://dali.xuanzx.com/Article/details/gtsmhffrku.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.quarkkingdee.top/Article/details/gtbjrrqntw.html

[S30] C：头文件保护
来源：http://dali.daria6918.cn/Article/details/gtzbvpqavd.html

#ifndef X_H
来源：http://dali.haohaochexian.top/Article/details/gtqvwhrkub.html

#define X_H
来源：http://dali.havefunace.top/Article/details/gttncwfnil.html

#endif
来源：http://dali.jiagoushi.top/Article/details/gtxxsbvsau.html

[S31] C++：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtylvqzfuh.html

#include <iostream>
来源：http://dali.chenlongwang.top/Article/details/gtlsyqjpde.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ppjwa.cn/Article/details/gtgbljpktt.html

[S32] C++：字符串
来源：http://dali.andypj.xyz/Article/details/gtstjrverj.html

std::string s = "hi";  s += "!";
来源：http://dali.dianchejie.cn/Article/details/gtplwdrtof.html

[S33] C++：vector 增删
来源：http://dali.hysaishi.cn/Article/details/gttdlcvvtu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtuarvzseh.html

[S34] C++：遍历 vector
来源：http://dali.iojbl.cn/Article/details/gtjrtujklq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ydzc1.top/Article/details/gtcfomaktm.html

[S35] C++：map
来源：http://dali.hongshengwenyu.top/Article/details/gtfzfaowgn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtpyjfqdjq.html

[S36] C++：unordered_map
来源：http://dali.nanxinkj.top/Article/details/gtiwyxvxah.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtuglrvhlg.html

[S37] C++：set
来源：http://dali.chenlongwang.top/Article/details/gtqczzkegy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgthdtsyq.html

[S38] C++：排序
来源：http://dali.hongshengwenyu.top/Article/details/gtghugrite.html

std::sort(v.begin(), v.end());
来源：http://dali.dianchejie.cn/Article/details/gtwvzugmzk.html

[S39] C++：自定义比较器排序
来源：http://dali.316326.xyz/Article/details/gtzhewanml.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gtrfbpvxzm.html

[S40] C++：查找元素
来源：http://dali.wangshuangyany.cn/Article/details/gtdncekjyd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.andypj.xyz/Article/details/gtzqnglgii.html

[S41] C++：类与构造函数
来源：http://dali.meibo888.top/Article/details/gtkfylrzee.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hfpthk.cn/Article/details/gtxtyflyto.html

[S42] C++：继承与虚函数
来源：http://dali.hammf.cn/Article/details/gttvxfubut.html

class B : public Base { public: void f() override {} };
来源：http://dali.fengsongda.top/Article/details/gtfynjwdul.html

[S43] C++：智能指针
来源：http://dali.yuanzhike.top/Article/details/gtvfgzfmyn.html

auto p = std::make_unique<int>(5);
来源：http://dali.cqqwz.cn/Article/details/gteqoprywq.html

[S44] C++：引用传参
来源：http://dali.gzhubu.top/Article/details/gthdnuenhi.html

void inc(int &x) { ++x; }
来源：http://dali.zycfv.cn/Article/details/gtkxfocaoj.html

[S45] C++：lambda
来源：http://dali.meibo888.top/Article/details/gtuxrttawi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cashguo.top/Article/details/gtayicflkl.html

[S46] C++：函数模板
来源：http://dali.vqdsnc.cn/Article/details/gtmcdyztoe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hammf.cn/Article/details/gtpzdsjvgr.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gtuxfmtuca.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.haohaochexian.top/Article/details/gtpnhamgyf.html

[S48] C++：逐行读文件
来源：http://dali.yj20258.top/Article/details/gtusdnafwg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpubwctbl.html

while (std::getline(in, line)) { }
来源：http://dali.birdmap.top/Article/details/gtwnxefwrp.html

[S49] C++：写文件
来源：http://dali.zhixingplan.top/Article/details/gtkobccppd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.pycfn.com/Article/details/gteqrwvlyx.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gtmkrwxyzm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtcwylcmip.html

[S51] C++：显式类型转换
来源：http://dali.aizwys.cn/Article/details/gtzkuvjgqk.html

static_cast<double>(a) / b
来源：http://dali.fengsongda.top/Article/details/gtkjjqznqc.html

[S52] C++：const 与 noexcept
来源：http://dali.gzhubu.top/Article/details/gtplapdzii.html


<!-- 参考信息 -->