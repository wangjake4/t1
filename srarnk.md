代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.jianghu66.top/Article/details/gtbczgdkbr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtqwklzjcw.html

[Q83] 大小写转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjuedmha.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtdldvzphs.html

[Q84] 去除首尾空格
来源：http://dali.daxiang520.top/Article/details/gtgfueorzr.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtgdgijqmt.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gtoyxovteh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guowangkeji.top/Article/details/gtylhzivad.html

[Q86] 读取 JSON 字段
来源：http://dali.xinyue.icu/Article/details/gtlvyeclyq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ivvv.top/Article/details/gthrwjxuzw.html

[Q87] JSON 字段做条件
来源：http://dali.yj202588.top/Article/details/gttqfzfxyb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xuetiantiany.cn/Article/details/gtrtmveaob.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gtopmzdwyu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yueranfly.top/Article/details/gtxetqufzt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fzhhl.top/Article/details/gtdbgqhnhp.html

[Q89] 判断表是否存在
来源：http://dali.xylfe.cn/Article/details/gtobnsdsjs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zdqjudy.top/Article/details/gtbmymwzoh.html

[Q90] 生成序号列
来源：http://dali.fengsongda.top/Article/details/gtijlzonys.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ybcxt.top/Article/details/gtfozbjxhc.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtbdxeoely.html

R. Bash 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtommzggsw.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtiyzuprut.html

[R01] shebang 与严格模式
来源：http://dali.hongshengwenyu.top/Article/details/gtuwfmhgym.html

#!/usr/bin/env bash
来源：http://dali.jinqigufen.top/Article/details/gtruikotxy.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gtqzqdenaz.html

[R02] 变量赋值与使用
来源：http://dali.snrcjt.cn/Article/details/gtwbrxeutj.html

name="Tom"; echo "$name"
来源：http://dali.shangyingyoupin.top/Article/details/gtrvhzimyz.html

[R03] 只读变量
来源：http://dali.ydzc1.top/Article/details/gtcukvkatz.html

readonly PI=3.14
来源：http://dali.cheryme.top/Article/details/gtnhwvjktm.html

[R04] 位置参数
来源：http://dali.tian-w.cn/Article/details/gtvvctavbn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgapyafs.html

[R05] 参数默认值
来源：http://dali.pengpengdd.cyou/Article/details/gtawuyvhpv.html

name="${1:-default}"
来源：http://dali.tianlin.xyz/Article/details/gtdmwvvckn.html

[R06] 判断命令是否存在
来源：http://dali.nwbrower.top/Article/details/gtwfppsnup.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gtsprvyzzr.html

[R07] if 判断文件
来源：http://dali.yj202588.top/Article/details/gtkqlaqpme.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jyoumei.cn/Article/details/gtyaeptoqa.html

[R08] 数值比较
来源：http://dali.nanxuanxn.top/Article/details/gtrnormizh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.c1oappe.top/Article/details/gterxyupki.html

[R09] 字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gthiywfbry.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ydzc1.top/Article/details/gtaikihfrb.html

[R10] 正则匹配
来源：http://dali.hywenlv.cn/Article/details/gtqweopmxx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cheryme.top/Article/details/gtfhdktouz.html

[R11] case 多分支
来源：http://dali.ydzc1.top/Article/details/gtgcdfbkow.html

case "$1" in
来源：http://dali.aizwys.cn/Article/details/gthiwkicem.html

start) echo "启动" ;;
来源：http://dali.hammf.cn/Article/details/gtybvkahvo.html

stop)  echo "停止" ;;
来源：http://dali.xinyue.icu/Article/details/gtilwtwfkg.html

*)     echo "未知命令" ;;
来源：http://dali.gzhubu.top/Article/details/gtnrbcbebo.html

esac
来源：http://dali.jinqigfzy.top/Article/details/gtjlehlipz.html

[R12] for 遍历文件
来源：http://dali.svipenyu.cn/Article/details/gtdmrlbmaz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.snrcjt.cn/Article/details/gtomkwgvbt.html

[R13] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gtdzobceks.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gotoacloud.top/Article/details/gtbvlaztgo.html

[R14] C 风格 for
来源：http://dali.aibaodan.cn/Article/details/gtevszdgfj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtecpjjouy.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtfsdivqzq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sysykeji.top/Article/details/gtrakgzfyv.html

[R16] until 等待条件
来源：http://dali.yj20258888.top/Article/details/gtunxvtolh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhixingplan.top/Article/details/gttygwynuu.html

[R17] 数组定义与取值
来源：http://dali.hongshengwenyu.top/Article/details/gtmwkbgzge.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xinyue.icu/Article/details/gttxwzlvwg.html

[R18] 遍历数组
来源：http://dali.hammf.cn/Article/details/gtqcfhxwve.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gtwbhjogzb.html

[R19] 数组长度
来源：http://dali.cucudq.cn/Article/details/gtcnnfeasy.html

echo "${#arr[@]}"
来源：http://dali.smart0.xyz/Article/details/gtzsoiedwi.html

[R20] 关联数组（字典）
来源：http://dali.havefunace.top/Article/details/gtyoowebju.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtssvdegbi.html

[R21] 字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtvensbhis.html

echo "${#s}"
来源：http://dali.snrcjt.cn/Article/details/gtpumsezxt.html

[R22] 截取子串
来源：http://dali.andypj.xyz/Article/details/gtpkbfuhod.html

echo "${s:0:5}"
来源：http://dali.daxiang520.top/Article/details/gtpdsydacw.html

[R23] 字符串替换
来源：http://dali.cucudq.cn/Article/details/gtqbujtpil.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.vqdsnc.cn/Article/details/gtbqpczzvq.html

[R24] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtozmwayhe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.bjfxy.top/Article/details/gtvpiduuth.html

[R25] 去后缀 / 去前缀
来源：http://dali.meibo888.top/Article/details/gtymqcrvmo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.svipenyu.cn/Article/details/gtktkstsig.html

[R26] 命令替换
来源：http://dali.redwolf501.top/Article/details/gtmtkvmpof.html

now=$(date +%F); echo "$now"
来源：http://dali.9152youxi.cn/Article/details/gtfkjylfnq.html

[R27] 算术展开
来源：http://dali.gogol.net.cn/Article/details/gtqiimjiok.html

echo $((1 + 2 * 3))
来源：http://dali.sufxvd.cn/Article/details/gtbhupkcnz.html

[R28] 浮点运算
来源：http://dali.gzhubu.top/Article/details/gtynzbbxnp.html

echo "scale=2; 10/3" | bc
来源：http://dali.bjfxy.top/Article/details/gtwrhyonfj.html

[R29] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gtmkuxcumx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258888.top/Article/details/gtcdmrpbjm.html

[R30] 函数返回状态码
来源：http://dali.gzhubu.top/Article/details/gtysjrqnrm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jyoumei.cn/Article/details/gttknwtmsa.html

[R31] 局部变量
来源：http://dali.havefunace.top/Article/details/gtcwzppbzn.html

f() { local x=1; echo "$x"; }
来源：http://dali.jianghu66.top/Article/details/gtrasgplns.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gtbghjovdo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gtrrwsivdx.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgufenzy.top/Article/details/gtglsidwat.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.redwolf501.top/Article/details/gtjtnnvwfu.html

[R34] 退出时清理
来源：http://dali.hysaishi.cn/Article/details/gtnylftvyg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gtsxzhvccb.html

[R35] 后台执行并等待
来源：http://dali.zhixingplan.top/Article/details/gtnactrmmg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.feifeiyinyue.top/Article/details/gtvtdgbdzd.html

[R36] 并发执行多个任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcccznvzi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskewxptq.html

[R37] 把输出赋给变量
来源：http://dali.kuanghao11.cn/Article/details/gthdrelfip.html

files=$(ls -1)
来源：http://dali.ydzc1.top/Article/details/gtbxnjacdv.html

[R38] 管道串联
来源：http://dali.zhixingplan.top/Article/details/gtovvamipw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fzhhl.top/Article/details/gtzeneuxik.html

[R39] 重定向标准输出与错误
来源：http://dali.hnxiangtu.top/Article/details/gtmryvkzdz.html

cmd > out.log 2>&1
来源：http://dali.hysaishi.cn/Article/details/gtvmjvxujj.html

[R40] 追加写日志
来源：http://dali.ehwqpu.com/Article/details/gtftmgtonm.html

echo "log" >> out.log
来源：http://dali.jinqigfzy.top/Article/details/gtqxpdoetb.html

[R41] 丢弃输出
来源：http://dali.andypj.xyz/Article/details/gtpghdosjr.html

cmd >/dev/null 2>&1
来源：http://dali.gogol.net.cn/Article/details/gtqckvglss.html

[R42] 输入重定向
来源：http://dali.zhiwuduotai.top/Article/details/gtgvcsphrn.html

wc -l < a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtfugyornw.html

[R43] 按名字查找文件
来源：http://dali.hnxiangtu.top/Article/details/gtxrinxivq.html

find . -name "*.log" -type f
来源：http://dali.gaohongyu789.top/Article/details/gtahjudoyx.html

[R44] 按修改时间查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnjdnisl.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdlomwii.html

[R45] 批量删除
来源：http://dali.yvedp.cn/Article/details/gtknjnggoi.html

find . -name "*.tmp" -delete
来源：http://dali.jqgfzy.top/Article/details/gtiipbzjke.html

[R46] 递归替换文件内容
来源：http://dali.hnqzz.top/Article/details/gtusklzugm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sxryk.cn/Article/details/gteyoosmwn.html

[R47] sed 单行替换
来源：http://dali.ybcxt.top/Article/details/gtkyhoousk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj202588.top/Article/details/gtahgwdqrl.html

[R48] awk 取指定列
来源：http://dali.wangdashe.top/Article/details/gtadgrrdlq.html

awk '{print $1, $3}' a.txt
来源：http://dali.andypj.xyz/Article/details/gtmslwwayb.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gtozfoubkc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jlsjyb.cn/Article/details/gtximedhbj.html

[R50] awk 求和
来源：http://dali.yangfankeji.com/Article/details/gttwvlenvy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guannengcc.top/Article/details/gtqyapbwmf.html

[R51] 排序去重取前几
来源：http://dali.jqgufenzy.top/Article/details/gtmvxsocir.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gtawoeojbl.html

[R52] 统计行数
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgjyaydg.html

wc -l a.txt
来源：http://dali.havefunace.top/Article/details/gttfgdcfyf.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258888.top/Article/details/gtnkayfvqu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ehwqpu.com/Article/details/gtbcujunlc.html

[R54] 比较两个文件
来源：http://dali.xinyue.icu/Article/details/gtcqoducjj.html

diff a.txt b.txt
来源：http://dali.yvedp.cn/Article/details/gtvwrzscry.html

[R55] 压缩与解压
来源：http://dali.chenjidiqi.icu/Article/details/gtqyuoftab.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuetiantiany.cn/Article/details/gtosocpbpy.html

[R56] 远程拷贝
来源：http://dali.hnqzz.top/Article/details/gtizztposq.html

scp file user@host:/path/
来源：http://dali.gotoacloud.top/Article/details/gtyhbtqyot.html

[R57] 远程执行命令
来源：http://dali.c1oappe.top/Article/details/gtbjomkfbk.html

ssh user@host 'uptime'
来源：http://dali.nanxuanxn.top/Article/details/gtnevsefyk.html

[R58] 下载文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkplagjpq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxuanxn.top/Article/details/gtptjdcfyv.html

[R59] 发 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gtljsehsno.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.mhx1999.top/Article/details/gtczfsvnfl.html

[R60] 只看 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gtozuhnaol.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ehwqpu.com/Article/details/gtyhififyw.html

[R61] 磁盘占用
来源：http://dali.jyoumei.cn/Article/details/gtumjcguaf.html

df -h;  du -sh *
来源：http://dali.quarkkingdee.top/Article/details/gtwuhkacfm.html

[R62] 找最占空间的文件
来源：http://dali.zhiwuduotai.top/Article/details/gtgzgxfone.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigfzy.top/Article/details/gtccchvawh.html

[R63] 内存与进程
来源：http://dali.sysykeji.top/Article/details/gtykaabwga.html

free -h;  ps aux | grep nginx
来源：http://dali.xinyue.icu/Article/details/gtauiqomtp.html

[R64] 结束进程
来源：http://dali.aizwys.cn/Article/details/gtfznysivr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzbgafwmu.html

[R65] 查看端口占用
来源：http://dali.yuanzhike.top/Article/details/gthozjsvom.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkxlgicf.html

[R66] 定时任务
来源：http://dali.meibo888.top/Article/details/gtmxrsekzr.html

crontab -e;  crontab -l
来源：http://dali.wangshuangyany.cn/Article/details/gtovjlkgms.html

[R67] 生成随机十六进制串
来源：http://dali.hfpthk.cn/Article/details/gtmswguesr.html

openssl rand -hex 16
来源：http://dali.zhongyouzk.top/Article/details/gtlpfdjpyr.html

[R68] 计算文件校验值
来源：http://dali.dianchejie.cn/Article/details/gtcgpkikji.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daria6918.cn/Article/details/gtvosquwjn.html

[R69] 生成随机密码
来源：http://dali.havefunace.top/Article/details/gtzxssimcw.html

head -c 16 /dev/urandom | base64
来源：http://dali.quarkkingdee.top/Article/details/gtpxuuqove.html

[R70] 时间戳与互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuiqwayl.html

date +%s;  date -d @1700000000
来源：http://dali.quarkkingdee.top/Article/details/gtjrcmuhvx.html

[R71] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gteewmsimf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dashuyun.cn/Article/details/gtmhnolorg.html

[R72] 等待端口就绪
来源：http://dali.c1oappe.top/Article/details/gtukooqmis.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gtkvczrrhf.html

[R73] 分割大日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtjowxlqgv.html

split -l 1000 big.log part_
来源：http://dali.mhx1999.top/Article/details/gtqghijvlf.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gtqskuejml.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxinkj.top/Article/details/gtcvcmwsgq.html

[R75] 导出环境变量
来源：http://dali.hnqzz.top/Article/details/gtixobnsdb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgufenzy.top/Article/details/gtbdbcuqro.html

[R76] 使用临时文件
来源：http://dali.zhiwuduotai.top/Article/details/gterjucjhc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gtfhxrdxyi.html

[R77] 读取用户输入
来源：http://dali.yj20258.top/Article/details/gtzzdyqhim.html

read -rp "请输入: " ans
来源：http://dali.gaohongyu789.top/Article/details/gtgnaiufln.html

[R78] 交互式菜单
来源：http://dali.zhengqikj.top/Article/details/gtifyvnrks.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pycfn.com/Article/details/gtapqxhkha.html

[R79] 解析命令行选项
来源：http://dali.xylfe.cn/Article/details/gtrocesoce.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yanxiufei.cn/Article/details/gtbvnsdtvs.html

[R80] 查看脚本执行耗时
来源：http://dali.jiagoushi.top/Article/details/gtfyfkigkd.html

time ./run.sh
来源：http://dali.andypj.xyz/Article/details/gthuunsyko.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxovjoiyp.html

S. C / C++ 专题
来源：http://dali.andypj.xyz/Article/details/gtfohpplls.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtwwqmckwb.html

[S01] C：Hello World
来源：http://dali.ehwqpu.com/Article/details/gteldgikue.html

#include <stdio.h>
来源：http://dali.feifeiyinyue.top/Article/details/gtxfutusyn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgfzy.top/Article/details/gtxtlkgmbj.html

[S02] C：变量与格式化输出
来源：http://dali.shuidangran.top/Article/details/gtmhjrfjrh.html

int a = 10; printf("%d\n", a);
来源：http://dali.haohaochexian.top/Article/details/gtjmjmqzom.html

[S03] C：读入整数
来源：http://dali.xuanzx.com/Article/details/gtuazvqhtm.html

int x; scanf("%d", &x);
来源：http://dali.shzxlz.cn/Article/details/gtpcdcfvwk.html

[S04] C：字符串复制
来源：http://dali.redwolf501.top/Article/details/gtuhijdrzr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guowangkeji.top/Article/details/gtbopdeirc.html

[S05] C：字符串长度
来源：http://dali.jiagoushi.top/Article/details/gtftnufqpt.html

strlen(s)
来源：http://dali.ehwqpu.com/Article/details/gtcjwjaxav.html

[S06] C：字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtfpggvquc.html

strcmp(a, b) == 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzywqccqu.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzpqndcj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhongyouzk.top/Article/details/gtgphxlyjf.html

[S08] C：动态内存分配与释放
来源：http://dali.ydzc1.top/Article/details/gtaehgvtxo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gotoacloud.top/Article/details/gtkpyhmpva.html

[S09] C：结构体定义与初始化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhmtfwru.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dashuyun.cn/Article/details/gthzyktbgy.html

[S10] C：指针与解引用
来源：http://dali.sweek.top/Article/details/gtbjaspyvg.html

int *p = &a;  *p = 5;
来源：http://dali.aibaodan.cn/Article/details/gtaywuxivc.html

[S11] C：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtfvydsyhy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fengsongda.top/Article/details/gtwivwjgbf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aibaodan.cn/Article/details/gtlgbpiekq.html

fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gtmnndhmdx.html

[S12] C：写文件
来源：http://dali.ydzc1.top/Article/details/gtszgzwdnh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gtonqejugb.html

[S13] C：宏定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqojyrifh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cqqwz.cn/Article/details/gtgsyvhamg.html

[S14] C：枚举
来源：http://dali.ehwqpu.com/Article/details/gtendbcjll.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gogol.net.cn/Article/details/gtujnhjnmk.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdrgcrsx.html

(double) a / b
来源：http://dali.xziqi.cn/Article/details/gtxfgjqguj.html

[S16] C：位操作置位
来源：http://dali.pycfn.com/Article/details/gtfbwehezp.html

x |= (1 << 3);
来源：http://dali.andypj.xyz/Article/details/gtbfeaxocj.html

[S17] C：安全拼接字符串
来源：http://dali.cheryme.top/Article/details/gtigfcecmy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jianghu66.top/Article/details/gtgecjsdul.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gtlttkhtxv.html

int main(int argc, char **argv)
来源：http://dali.tian-w.cn/Article/details/gtiyatyzpl.html

[S19] C：快速排序
来源：http://dali.9152youxi.cn/Article/details/gtmekrgdxg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtrfokswxh.html

[S20] C：二分查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqrtkaoy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gtmlrustze.html

[S21] C：字符类别判断
来源：http://dali.pengpengdd.cyou/Article/details/gthhoswcdn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.mhx1999.top/Article/details/gthuxfmoxp.html

[S22] C：字符串转数字
来源：http://dali.shuidangran.top/Article/details/gtmhmkjxld.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aibaodan.cn/Article/details/gtiovliqhr.html

[S23] C：随机数
来源：http://dali.xuetiantiany.cn/Article/details/gtobptjbuq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhixingplan.top/Article/details/gtjrfggtrl.html

[S24] C：获取本地时间
来源：http://dali.xuetiantiany.cn/Article/details/gttsdurwht.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jyoumei.cn/Article/details/gtyssiibuu.html

[S25] C：内存拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcypuvmnu.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gtpjvwrxle.html

[S26] C：内存清零
来源：http://dali.redwolf501.top/Article/details/gtwgqqzqon.html

memset(a, 0, sizeof a);
来源：http://dali.gogol.net.cn/Article/details/gtlvpfmrww.html

[S27] C：定义常量
来源：http://dali.yongpay.top/Article/details/gttamwzjic.html

const double PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjakwczkx.html

[S28] C：静态变量
来源：http://dali.zycfv.cn/Article/details/gttgofkael.html

static int counter = 0;
来源：http://dali.jlsjyb.cn/Article/details/gtzwoobdbg.html

[S29] C：变参函数
来源：http://dali.hywenlv.cn/Article/details/gtquagytic.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daxiang520.top/Article/details/gtbwokdqge.html

[S30] C：头文件保护
来源：http://dali.feifeiyinyue.top/Article/details/gtkgafwzcb.html

#ifndef X_H
来源：http://dali.yj202588.top/Article/details/gtgnxdukhp.html

#define X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgyyngyfw.html

#endif
来源：http://dali.sweek.top/Article/details/gtuetnsfvt.html

[S31] C++：Hello World
来源：http://dali.guannengcc.top/Article/details/gtfynxomae.html

#include <iostream>
来源：http://dali.jinghuilouyu.cn/Article/details/gtxikkuoeg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cashguo.top/Article/details/gtaygtfihe.html

[S32] C++：字符串
来源：http://dali.cdnleiting.top/Article/details/gtcdksxjyv.html

std::string s = "hi";  s += "!";
来源：http://dali.gaohongyu789.top/Article/details/gtwrfzffnp.html

[S33] C++：vector 增删
来源：http://dali.feifeiyinyue.top/Article/details/gtchvzpgoc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtoatcaxjg.html

[S34] C++：遍历 vector
来源：http://dali.hysaishi.cn/Article/details/gttasjvjle.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tanke756.top/Article/details/gtvuufbbqc.html

[S35] C++：map
来源：http://dali.0kj1m.cn/Article/details/gtqjcgxnio.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtnyghnfra.html

[S36] C++：unordered_map
来源：http://dali.cqqwz.cn/Article/details/gtycbyflmv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gtolkaaflt.html

[S37] C++：set
来源：http://dali.guannengcc.top/Article/details/gtdntndflr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtbxbrsvnv.html

[S38] C++：排序
来源：http://dali.daxiang520.top/Article/details/gtgbeqfpzf.html

std::sort(v.begin(), v.end());
来源：http://dali.hnxiangtu.top/Article/details/gtonxphzrw.html

[S39] C++：自定义比较器排序
来源：http://dali.gogol.net.cn/Article/details/gtirvapuhc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuanzhike.top/Article/details/gtjrukaufl.html

[S40] C++：查找元素
来源：http://dali.shuidangran.top/Article/details/gtpufvcgzb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hfpthk.cn/Article/details/gtszngvejc.html

[S41] C++：类与构造函数
来源：http://dali.shzxlz.cn/Article/details/gtlkkjyedw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.smart0.xyz/Article/details/gtbcoomlgv.html

[S42] C++：继承与虚函数
来源：http://dali.zycfv.cn/Article/details/gtnkkstzdl.html

class B : public Base { public: void f() override {} };
来源：http://dali.birdmap.top/Article/details/gtyevosrke.html

[S43] C++：智能指针
来源：http://dali.vqdsnc.cn/Article/details/gtcyljuqdj.html

auto p = std::make_unique<int>(5);
来源：http://dali.daria6918.cn/Article/details/gtydkmbmuc.html

[S44] C++：引用传参
来源：http://dali.wangshuangyany.cn/Article/details/gtvbohzgdf.html

void inc(int &x) { ++x; }
来源：http://dali.hfpthk.cn/Article/details/gtvserziwr.html

[S45] C++：lambda
来源：http://dali.cdnleiting.top/Article/details/gtayfiseoj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgufenzy.top/Article/details/gtdavetzjy.html

[S46] C++：函数模板
来源：http://dali.ehwqpu.com/Article/details/gtzorhttej.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yueranfly.top/Article/details/gtcdvrxqds.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gtjvjdaytm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cheryme.top/Article/details/gtkmtnjiob.html

[S48] C++：逐行读文件
来源：http://dali.cashguo.top/Article/details/gtcgpnniyn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shuidangran.top/Article/details/gtnfgqbazr.html

while (std::getline(in, line)) { }
来源：http://dali.ehwqpu.com/Article/details/gtlhgymndw.html

[S49] C++：写文件
来源：http://dali.yonumen.top/Article/details/gtvrpfttzt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xylfe.cn/Article/details/gtvtknwncp.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gtlermxtuk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtuqyjdmil.html

[S51] C++：显式类型转换
来源：http://dali.yvedp.cn/Article/details/gtoxeizkzx.html

static_cast<double>(a) / b
来源：http://dali.yueranfly.top/Article/details/gtgrkvvipc.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gtdosfxsnw.html


<!-- 参考信息 -->