代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.chenjidiqi.icu/Article/details/gtyaetgzun.html

SELECT TRIM(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtobamlddb.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gtaqorekmz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sweek.top/Article/details/gtymbrdhzp.html

[Q86] 读取 JSON 字段
来源：http://dali.nwbrower.top/Article/details/gtkdzcedxh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuanzhike.top/Article/details/gtahyqqufy.html

[Q87] JSON 字段做条件
来源：http://dali.hnxiangtu.top/Article/details/gtgzxpgbru.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258.top/Article/details/gtquokflmc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhoulong.xyz/Article/details/gtvvooahqg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenzaomai.com/Article/details/gtcxibzipl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtqvkyqagi.html

[Q89] 判断表是否存在
来源：http://dali.cqqwz.cn/Article/details/gtokhquakm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.0kj1m.cn/Article/details/gtiqreeacn.html

[Q90] 生成序号列
来源：http://dali.jianghu66.top/Article/details/gtdubudmbc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.haohaochexian.top/Article/details/gtzfcbbkwn.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtfttdpvur.html

R. Bash 专题
来源：http://dali.mhx1999.top/Article/details/gtkfbfghfw.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtqopwsdkz.html

[R01] shebang 与严格模式
来源：http://dali.shangyingyoupin.top/Article/details/gtrgrvghrq.html

#!/usr/bin/env bash
来源：http://dali.gzhubu.top/Article/details/gtjwodcacu.html

set -euo pipefail
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjurqdeur.html

[R02] 变量赋值与使用
来源：http://dali.sysykeji.top/Article/details/gtpyokspit.html

name="Tom"; echo "$name"
来源：http://dali.zycfv.cn/Article/details/gtgwjsgfbp.html

[R03] 只读变量
来源：http://dali.zhoulong.xyz/Article/details/gtpkyakcof.html

readonly PI=3.14
来源：http://dali.meibo888.top/Article/details/gtmnhwkxgb.html

[R04] 位置参数
来源：http://dali.snrcjt.cn/Article/details/gtwwqwayji.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxqozqsn.html

[R05] 参数默认值
来源：http://dali.havefunace.top/Article/details/gtmqdudovk.html

name="${1:-default}"
来源：http://dali.0kj1m.cn/Article/details/gtuabesphp.html

[R06] 判断命令是否存在
来源：http://dali.aizwys.cn/Article/details/gtkkmuvmof.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hammf.cn/Article/details/gtgulthqun.html

[R07] if 判断文件
来源：http://dali.zhiwuduotai.top/Article/details/gtpeukxutc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvbiwufn.html

[R08] 数值比较
来源：http://dali.xziqi.cn/Article/details/gtumtgufzn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guannengcc.top/Article/details/gtdfqkrqqz.html

[R09] 字符串比较
来源：http://dali.iojbl.cn/Article/details/gtnszuftxk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.316326.xyz/Article/details/gtbxlvdzda.html

[R10] 正则匹配
来源：http://dali.hysaishi.cn/Article/details/gtqfspxkzi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.316326.xyz/Article/details/gttasxvtia.html

[R11] case 多分支
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydpfrica.html

case "$1" in
来源：http://dali.mhx1999.top/Article/details/gtyfvnklrc.html

start) echo "启动" ;;
来源：http://dali.yonumen.top/Article/details/gtghtyfkjf.html

stop)  echo "停止" ;;
来源：http://dali.daria6918.cn/Article/details/gtobknwjje.html

*)     echo "未知命令" ;;
来源：http://dali.ppjwa.cn/Article/details/gtmshpxdrk.html

esac
来源：http://dali.hywenlv.cn/Article/details/gthdxwsthm.html

[R12] for 遍历文件
来源：http://dali.haohaochexian.top/Article/details/gtafidsddb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hfpthk.cn/Article/details/gtawwunnql.html

[R13] for 计数循环
来源：http://dali.316326.xyz/Article/details/gtyavjpopw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gtkomitjop.html

[R14] C 风格 for
来源：http://dali.wangdashe.top/Article/details/gtjxsgnpkh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gtmdkvkgns.html

[R15] while 逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtkcvarvuf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tanke756.top/Article/details/gthpctxvkr.html

[R16] until 等待条件
来源：http://dali.tian-w.cn/Article/details/gtdybszjvf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gtnmsccrny.html

[R17] 数组定义与取值
来源：http://dali.zycfv.cn/Article/details/gtsodeppkd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtrywdtcdi.html

[R18] 遍历数组
来源：http://dali.yuanzhike.top/Article/details/gtxxccnrpp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.vqdsnc.cn/Article/details/gtwgoczhbb.html

[R19] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gtftqsvucp.html

echo "${#arr[@]}"
来源：http://dali.yuanzhike.top/Article/details/gtsmncbgem.html

[R20] 关联数组（字典）
来源：http://dali.chenjidiqi.icu/Article/details/gtoadschsw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtinuiualr.html

[R21] 字符串长度
来源：http://dali.ybcxt.top/Article/details/gtbwjxiddn.html

echo "${#s}"
来源：http://dali.svipenyu.cn/Article/details/gtkhzbznaf.html

[R22] 截取子串
来源：http://dali.xuanzx.com/Article/details/gtnoamczck.html

echo "${s:0:5}"
来源：http://dali.sxryk.cn/Article/details/gtcokiyivc.html

[R23] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndlgrvpl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.redwolf501.top/Article/details/gtpqbblyge.html

[R24] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtuqesbbeh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tianlin.xyz/Article/details/gtljswskmg.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangshuangyany.cn/Article/details/gtklmkcccc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gtyyfxdhzu.html

[R26] 命令替换
来源：http://dali.tianlin.xyz/Article/details/gtuuutnvly.html

now=$(date +%F); echo "$now"
来源：http://dali.aizwys.cn/Article/details/gtajayrdht.html

[R27] 算术展开
来源：http://dali.hnqzz.top/Article/details/gterkshskz.html

echo $((1 + 2 * 3))
来源：http://dali.zhiwuduotai.top/Article/details/gtujfnekkd.html

[R28] 浮点运算
来源：http://dali.shangyingyoupin.top/Article/details/gtpysscebg.html

echo "scale=2; 10/3" | bc
来源：http://dali.vqdsnc.cn/Article/details/gtamyjrlnf.html

[R29] 定义函数
来源：http://dali.ybcxt.top/Article/details/gtmiglfqdm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.snrcjt.cn/Article/details/gtmqqdpfmf.html

[R30] 函数返回状态码
来源：http://dali.hysaishi.cn/Article/details/gtgjbmadrt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.snrcjt.cn/Article/details/gtqmfndqpo.html

[R31] 局部变量
来源：http://dali.fzhhl.top/Article/details/gtatrhiprc.html

f() { local x=1; echo "$x"; }
来源：http://dali.aizwys.cn/Article/details/gtpsfunxfk.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetluqtgf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gtevqkvsbh.html

[R33] 捕获错误并提示行号
来源：http://dali.havefunace.top/Article/details/gtdlvqxuch.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hywenlv.cn/Article/details/gtluafsoyb.html

[R34] 退出时清理
来源：http://dali.tianlin.xyz/Article/details/gtymfmctth.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtuqlrdoba.html

[R35] 后台执行并等待
来源：http://dali.kuanghao11.cn/Article/details/gtfknvdysv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuxming.cn/Article/details/gthmfnkczu.html

[R36] 并发执行多个任务
来源：http://dali.haohaochexian.top/Article/details/gtzspvebsr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.kuanghao11.cn/Article/details/gtxfksochm.html

[R37] 把输出赋给变量
来源：http://dali.hysaishi.cn/Article/details/gtlpidxncz.html

files=$(ls -1)
来源：http://dali.xinyue.icu/Article/details/gtobiqkhna.html

[R38] 管道串联
来源：http://dali.xuetiantiany.cn/Article/details/gtmkdxtjxb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zdqjudy.top/Article/details/gtgiasrxep.html

[R39] 重定向标准输出与错误
来源：http://dali.sxryk.cn/Article/details/gtussizkij.html

cmd > out.log 2>&1
来源：http://dali.zhixingplan.top/Article/details/gtkcezsbep.html

[R40] 追加写日志
来源：http://dali.hywenlv.cn/Article/details/gtahkexftd.html

echo "log" >> out.log
来源：http://dali.ydzc1.top/Article/details/gtekiphldz.html

[R41] 丢弃输出
来源：http://dali.nanxuanxn.top/Article/details/gtvqqjkbbe.html

cmd >/dev/null 2>&1
来源：http://dali.gzhubu.top/Article/details/gtmsaazusc.html

[R42] 输入重定向
来源：http://dali.quarkkingdee.top/Article/details/gttzsmsvck.html

wc -l < a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsfgzfud.html

[R43] 按名字查找文件
来源：http://dali.yuanzhike.top/Article/details/gttwisruru.html

find . -name "*.log" -type f
来源：http://dali.yonumen.top/Article/details/gtcbywkliv.html

[R44] 按修改时间查找
来源：http://dali.wangshuangyany.cn/Article/details/gtvvkglayc.html

find . -mtime -7 -type f
来源：http://dali.vqdsnc.cn/Article/details/gtydrybshp.html

[R45] 批量删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtiaqyzjrk.html

find . -name "*.tmp" -delete
来源：http://dali.fzhhl.top/Article/details/gtceifjrll.html

[R46] 递归替换文件内容
来源：http://dali.yj20258.top/Article/details/gtuwjyaytn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258.top/Article/details/gtsyearhis.html

[R47] sed 单行替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefpuaxwh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtthqgzkss.html

[R48] awk 取指定列
来源：http://dali.jlsjyb.cn/Article/details/gtnofynkfb.html

awk '{print $1, $3}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxteamxsp.html

[R49] awk 带条件
来源：http://dali.pycfn.com/Article/details/gtfiorejxd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvpxrdfz.html

[R50] awk 求和
来源：http://dali.gotoacloud.top/Article/details/gtlxhwcggx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gtlcksdltl.html

[R51] 排序去重取前几
来源：http://dali.guannengcc.top/Article/details/gtyypmbunu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangtech.top/Article/details/gtepxgrpyi.html

[R52] 统计行数
来源：http://dali.hnqzz.top/Article/details/gtryrvjugm.html

wc -l a.txt
来源：http://dali.pycfn.com/Article/details/gtilmggrbb.html

[R53] 查看文件头与实时尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcsvpcza.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgufenzy.top/Article/details/gtembecdfg.html

[R54] 比较两个文件
来源：http://dali.9152youxi.cn/Article/details/gtzwtiicro.html

diff a.txt b.txt
来源：http://dali.aizwys.cn/Article/details/gtemxgiles.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gtiexhqzod.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.havefunace.top/Article/details/gtuyermejo.html

[R56] 远程拷贝
来源：http://dali.haohaochexian.top/Article/details/gtiiknbezv.html

scp file user@host:/path/
来源：http://dali.cqqwz.cn/Article/details/gtmipqddtt.html

[R57] 远程执行命令
来源：http://dali.nanxuanxn.top/Article/details/gthqidzmbt.html

ssh user@host 'uptime'
来源：http://dali.gogol.net.cn/Article/details/gtagambxfk.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gtzofwosgm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hongshengwenyu.top/Article/details/gtgpwujzzw.html

[R59] 发 POST JSON
来源：http://dali.mhx1999.top/Article/details/gttmeezxex.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.havefunace.top/Article/details/gtnspbtspx.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gthmznspfq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jianghu66.top/Article/details/gtnmcwpglz.html

[R61] 磁盘占用
来源：http://dali.vqdsnc.cn/Article/details/gtkwveutxm.html

df -h;  du -sh *
来源：http://dali.316326.xyz/Article/details/gtxrigrgww.html

[R62] 找最占空间的文件
来源：http://dali.nanxuanxn.top/Article/details/gtpyeqcgjd.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangtech.top/Article/details/gthhvrmqfc.html

[R63] 内存与进程
来源：http://dali.guannengcc.top/Article/details/gtnwqqpwlo.html

free -h;  ps aux | grep nginx
来源：http://dali.gzhubu.top/Article/details/gtwdrbcbks.html

[R64] 结束进程
来源：http://dali.yj20258.top/Article/details/gtfpgthtza.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tanke756.top/Article/details/gtvlvoaefn.html

[R65] 查看端口占用
来源：http://dali.kuanghao11.cn/Article/details/gtiozdqwxu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hywenlv.cn/Article/details/gtbcvxskcy.html

[R66] 定时任务
来源：http://dali.cdnleiting.top/Article/details/gtirvapizc.html

crontab -e;  crontab -l
来源：http://dali.iojbl.cn/Article/details/gtlxdcrzfz.html

[R67] 生成随机十六进制串
来源：http://dali.vqdsnc.cn/Article/details/gtfxynooxq.html

openssl rand -hex 16
来源：http://dali.yanxiufei.cn/Article/details/gtbgljaahp.html

[R68] 计算文件校验值
来源：http://dali.tianlin.xyz/Article/details/gtwvlwzxmo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tian-w.cn/Article/details/gtoooqckux.html

[R69] 生成随机密码
来源：http://dali.xuanzx.com/Article/details/gtclztuwsr.html

head -c 16 /dev/urandom | base64
来源：http://dali.mhx1999.top/Article/details/gtknnknivw.html

[R70] 时间戳与互转
来源：http://dali.sysykeji.top/Article/details/gtmongoczl.html

date +%s;  date -d @1700000000
来源：http://dali.cashguo.top/Article/details/gtajbejpwp.html

[R71] 日期格式化
来源：http://dali.daxiang520.top/Article/details/gtsfhwzloi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sysykeji.top/Article/details/gtklmcfllb.html

[R72] 等待端口就绪
来源：http://dali.dashuyun.cn/Article/details/gttfjshspm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gtbimqkjgd.html

[R73] 分割大日志
来源：http://dali.havefunace.top/Article/details/gtrqkxhuot.html

split -l 1000 big.log part_
来源：http://dali.jyoumei.cn/Article/details/gtkuapdgle.html

[R74] 批量重命名
来源：http://dali.hywenlv.cn/Article/details/gtfalctjxz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.vqdsnc.cn/Article/details/gttqskktzz.html

[R75] 导出环境变量
来源：http://dali.cdnleiting.top/Article/details/gtjbvcystg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.snrcjt.cn/Article/details/gtmpefpaft.html

[R76] 使用临时文件
来源：http://dali.pengpengdd.cyou/Article/details/gtquhpoqxx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gttkritkqw.html

[R77] 读取用户输入
来源：http://dali.nwbrower.top/Article/details/gtpetvvrnz.html

read -rp "请输入: " ans
来源：http://dali.jinqigfzy.top/Article/details/gtofixxgyh.html

[R78] 交互式菜单
来源：http://dali.tanke756.top/Article/details/gtvbzqsavu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnxiangtu.top/Article/details/gtdtgoyeal.html

[R79] 解析命令行选项
来源：http://dali.aibaodan.cn/Article/details/gtzqoalzql.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.andypj.xyz/Article/details/gtsjfqwktj.html

[R80] 查看脚本执行耗时
来源：http://dali.cucudq.cn/Article/details/gtidnotoil.html

time ./run.sh
来源：http://dali.sysykeji.top/Article/details/gtpkhmrpcs.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtxpitmdtz.html

S. C / C++ 专题
来源：http://dali.yuxming.cn/Article/details/gtzmarwigz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gthrogpvgo.html

[S01] C：Hello World
来源：http://dali.havefunace.top/Article/details/gthactshxr.html

#include <stdio.h>
来源：http://dali.chenzaomai.com/Article/details/gtlcgdxhqe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenjidiqi.icu/Article/details/gthqehutgz.html

[S02] C：变量与格式化输出
来源：http://dali.bjfxy.top/Article/details/gtzsolgwgi.html

int a = 10; printf("%d\n", a);
来源：http://dali.cashguo.top/Article/details/gtufwbxfie.html

[S03] C：读入整数
来源：http://dali.chenjidiqi.icu/Article/details/gtarihdwpy.html

int x; scanf("%d", &x);
来源：http://dali.wangdashe.top/Article/details/gtdtazdskj.html

[S04] C：字符串复制
来源：http://dali.fengsongda.top/Article/details/gtbhhjnoia.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sysykeji.top/Article/details/gtahmtndje.html

[S05] C：字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqiqtjxu.html

strlen(s)
来源：http://dali.tian-w.cn/Article/details/gtanqsiwmf.html

[S06] C：字符串比较
来源：http://dali.hfpthk.cn/Article/details/gtqmoxikyh.html

strcmp(a, b) == 0
来源：http://dali.jqgfzy.top/Article/details/gtpkkwarun.html

[S07] C：数组遍历求和
来源：http://dali.yongpay.top/Article/details/gtnmtjkvty.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guannengcc.top/Article/details/gthpgeshdk.html

[S08] C：动态内存分配与释放
来源：http://dali.ppjwa.cn/Article/details/gtasouevma.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sysykeji.top/Article/details/gtibptjyvj.html

[S09] C：结构体定义与初始化
来源：http://dali.jianghu66.top/Article/details/gtuopdzean.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sufxvd.cn/Article/details/gtskarulwr.html

[S10] C：指针与解引用
来源：http://dali.yanxiufei.cn/Article/details/gtcyyoppoi.html

int *p = &a;  *p = 5;
来源：http://dali.birdmap.top/Article/details/gtcbfckbhd.html

[S11] C：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtvnqxfipi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gotoacloud.top/Article/details/gtucymdrct.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhixingplan.top/Article/details/gtawgrplgh.html

fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyopzbltl.html

[S12] C：写文件
来源：http://dali.jiagoushi.top/Article/details/gtgiggmdru.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gttfczysde.html

[S13] C：宏定义
来源：http://dali.ivvv.top/Article/details/gtrmdmynem.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbsgjzee.html

[S14] C：枚举
来源：http://dali.jqgfzy.top/Article/details/gtnhelabnr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ppjwa.cn/Article/details/gtwxwdvmrc.html

[S15] C：类型转换
来源：http://dali.cashguo.top/Article/details/gtnczivcft.html

(double) a / b
来源：http://dali.jinqigfzy.top/Article/details/gtmfeigjsl.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gtvlcpngbb.html

x |= (1 << 3);
来源：http://dali.kuanghao11.cn/Article/details/gtdapjjxqa.html

[S17] C：安全拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtqrjyftdz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guannengcc.top/Article/details/gtlwfwocyn.html

[S18] C：命令行参数
来源：http://dali.yonumen.top/Article/details/gtppayddpf.html

int main(int argc, char **argv)
来源：http://dali.iojbl.cn/Article/details/gtpjjubvst.html

[S19] C：快速排序
来源：http://dali.jlsjyb.cn/Article/details/gthcmgcdlo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gtjuilbajb.html

[S20] C：二分查找
来源：http://dali.yuxming.cn/Article/details/gtyqhrhpif.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gttmmapazf.html

[S21] C：字符类别判断
来源：http://dali.pycfn.com/Article/details/gtlgnsyefe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pengpengdd.cyou/Article/details/gtuosudupi.html

[S22] C：字符串转数字
来源：http://dali.hfpthk.cn/Article/details/gtnmrbttov.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.kuanghao11.cn/Article/details/gtcfpyimyr.html

[S23] C：随机数
来源：http://dali.birdmap.top/Article/details/gtuajztauo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yanxiufei.cn/Article/details/gtjvvvxztb.html

[S24] C：获取本地时间
来源：http://dali.cheryme.top/Article/details/gtquiofwqy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.bjfxy.top/Article/details/gtovfrbyjb.html

[S25] C：内存拷贝
来源：http://dali.ivvv.top/Article/details/gtvalewtdr.html

memcpy(dst, src, n);
来源：http://dali.tanke756.top/Article/details/gtbyrojrmf.html

[S26] C：内存清零
来源：http://dali.ivvv.top/Article/details/gtpbqkfcyi.html

memset(a, 0, sizeof a);
来源：http://dali.316326.xyz/Article/details/gtxkqiholo.html

[S27] C：定义常量
来源：http://dali.svipenyu.cn/Article/details/gtkgqqxqct.html

const double PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtxqvgobpr.html

[S28] C：静态变量
来源：http://dali.jinqigufen.top/Article/details/gtoozkjmfc.html

static int counter = 0;
来源：http://dali.fzhhl.top/Article/details/gtghanxmuz.html

[S29] C：变参函数
来源：http://dali.yonumen.top/Article/details/gtiuxpcyvb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.haohaochexian.top/Article/details/gtjotbzzwh.html

[S30] C：头文件保护
来源：http://dali.tianlin.xyz/Article/details/gtkbbekniw.html

#ifndef X_H
来源：http://dali.yuxming.cn/Article/details/gtdmqdnmax.html

#define X_H
来源：http://dali.tanke756.top/Article/details/gtuoakrgbd.html

#endif
来源：http://dali.hnqzz.top/Article/details/gtyzjwdqvm.html

[S31] C++：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxrkvmly.html

#include <iostream>
来源：http://dali.xuetiantiany.cn/Article/details/gtezzodltb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zdqjudy.top/Article/details/gtecvlfkcx.html

[S32] C++：字符串
来源：http://dali.dianchejie.cn/Article/details/gtsedazibt.html

std::string s = "hi";  s += "!";
来源：http://dali.hysaishi.cn/Article/details/gtzqllkpqm.html

[S33] C++：vector 增删
来源：http://dali.cheryme.top/Article/details/gteogwfmxl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yangfankeji.com/Article/details/gtvjjxjnhi.html

[S34] C++：遍历 vector
来源：http://dali.hnqzz.top/Article/details/gtjsmwfmcp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xinyue.icu/Article/details/gthjezhzlg.html

[S35] C++：map
来源：http://dali.nanxuanxn.top/Article/details/gtmghwianw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtxgxcmhof.html

[S36] C++：unordered_map
来源：http://dali.haohaochexian.top/Article/details/gtsoznkwpg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtfoepgefy.html

[S37] C++：set
来源：http://dali.svipenyu.cn/Article/details/gtkjtbxgxu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tanke756.top/Article/details/gtcubjenuq.html

[S38] C++：排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajvtelap.html

std::sort(v.begin(), v.end());
来源：http://dali.jianghu66.top/Article/details/gtszexwtym.html

[S39] C++：自定义比较器排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgimqmlha.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gogol.net.cn/Article/details/gtdmzddest.html

[S40] C++：查找元素
来源：http://dali.ppjwa.cn/Article/details/gtzpmxajmp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nwbrower.top/Article/details/gtdiescbee.html

[S41] C++：类与构造函数
来源：http://dali.yj202588.top/Article/details/gtwewygikr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sufxvd.cn/Article/details/gtsgvaisde.html

[S42] C++：继承与虚函数
来源：http://dali.xylfe.cn/Article/details/gtojpumacj.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258.top/Article/details/gtnqptnhct.html

[S43] C++：智能指针
来源：http://dali.yvedp.cn/Article/details/gtocnblctx.html

auto p = std::make_unique<int>(5);
来源：http://dali.bjfxy.top/Article/details/gtqbvfeeqi.html

[S44] C++：引用传参
来源：http://dali.gotoacloud.top/Article/details/gtaxtbmtpl.html

void inc(int &x) { ++x; }
来源：http://dali.jianghu66.top/Article/details/gtzbxnndny.html

[S45] C++：lambda
来源：http://dali.mhx1999.top/Article/details/gtvryzqpnw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.meibo888.top/Article/details/gthapnlzip.html

[S46] C++：函数模板
来源：http://dali.gogol.net.cn/Article/details/gttfmsdrld.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqszshsk.html

[S47] C++：结构化绑定遍历
来源：http://dali.gotoacloud.top/Article/details/gteoxhvicg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yueranfly.top/Article/details/gtblkmcopl.html

[S48] C++：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtrnhlppxe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nwbrower.top/Article/details/gtyfmllpxt.html

while (std::getline(in, line)) { }
来源：http://dali.yonumen.top/Article/details/gtoaokoiok.html

[S49] C++：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gtpcpuxeum.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.fzhhl.top/Article/details/gtldjgukad.html

[S50] C++：格式化数字
来源：http://dali.jinqigfzy.top/Article/details/gtaqnwtlhr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtddojsnuj.html

[S51] C++：显式类型转换
来源：http://dali.gogol.net.cn/Article/details/gtjnikmyeu.html

static_cast<double>(a) / b
来源：http://dali.iojbl.cn/Article/details/gttbwmaoof.html

[S52] C++：const 与 noexcept
来源：http://dali.smart0.xyz/Article/details/gtvthqhvwn.html

int size() const noexcept { return n_; }
来源：http://dali.jianghu66.top/Article/details/gtflmawtrb.html

[S53] C++：移动语义
来源：http://dali.birdmap.top/Article/details/gtlkykkqws.html

std::vector<int> w = std::move(v);
来源：http://dali.guannengcc.top/Article/details/gtmygqbrbg.html

[S54] C++：异常处理
来源：http://dali.zhiwuduotai.top/Article/details/gtuuxgeegt.html


<!-- 参考信息 -->