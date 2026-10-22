代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.zdqjudy.top/Article/details/gtvlbyqxkm.html

[Q69] 查看执行计划
来源：http://dali.jinghuilouyu.cn/Article/details/gtltpptpqv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jqgufenzy.top/Article/details/gtfiolxbqu.html

[Q70] 更新统计信息
来源：http://dali.nwbrower.top/Article/details/gtpcstueyr.html

ANALYZE TABLE users;
来源：http://dali.jyoumei.cn/Article/details/gtbjqiejhr.html

[Q71] 查看建表语句
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkoobtpck.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.aizwys.cn/Article/details/gtpckhqmjd.html

[Q72] 查看索引
来源：http://dali.wangdashe.top/Article/details/gtyyszwapu.html

SHOW INDEX FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtjcjsulro.html

[Q73] 查看表状态
来源：http://dali.sweek.top/Article/details/gtfypihssz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhoulong.xyz/Article/details/gthgmtdpfj.html

[Q74] 强制使用索引
来源：http://dali.shangyingyoupin.top/Article/details/gtgpbwzwno.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhoulong.xyz/Article/details/gtfexhdfdv.html

[Q75] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gtxqannnno.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtepllzrvf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tanke756.top/Article/details/gtvgbhcdgx.html

[Q76] 按天统计
来源：http://dali.hnqzz.top/Article/details/gtxwrgsxde.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258.top/Article/details/gtxlfookfl.html

[Q77] 时间加减
来源：http://dali.guowangkeji.top/Article/details/gtpfmytaiu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nwbrower.top/Article/details/gtppltbqrk.html

[Q78] 当前时间
来源：http://dali.sufxvd.cn/Article/details/gtbycssyfu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuanzhike.top/Article/details/gttznzeroj.html

[Q79] 字符串拼接
来源：http://dali.c1oappe.top/Article/details/gthtbyxrqx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gogol.net.cn/Article/details/gtjecqqgtr.html

[Q80] 字符串截取
来源：http://dali.xylfe.cn/Article/details/gtcxvujozw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yonumen.top/Article/details/gtbefcdpax.html

[Q81] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gtqpumuvnr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtbhvaxrpl.html

[Q82] 字符长度与字节长度
来源：http://dali.cqqwz.cn/Article/details/gtwegnconw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpdgeuwc.html

[Q83] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gtalxqafpb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtokrhorbf.html

[Q84] 去除首尾空格
来源：http://dali.guowangkeji.top/Article/details/gtuqltogxa.html

SELECT TRIM(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtebymbsis.html

[Q85] 数值取整
来源：http://dali.xuetiantiany.cn/Article/details/gtzxjdfguk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.meibo888.top/Article/details/gtuqudbold.html

[Q86] 读取 JSON 字段
来源：http://dali.chenjidiqi.icu/Article/details/gtmnklmzyu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daxiang520.top/Article/details/gtfpzhdend.html

[Q87] JSON 字段做条件
来源：http://dali.cucudq.cn/Article/details/gtwijflzga.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.bjfxy.top/Article/details/gtuwhfgory.html

[Q88] 行转列（条件聚合）
来源：http://dali.bjfxy.top/Article/details/gtqbfygtcw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gotoacloud.top/Article/details/gtdbukpihb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jianghu66.top/Article/details/gtlqrliarn.html

[Q89] 判断表是否存在
来源：http://dali.jiagoushi.top/Article/details/gtlryohqjr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gthystubcb.html

[Q90] 生成序号列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezehxxve.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jqgfzy.top/Article/details/gtbfyjarto.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gthwqvgqzl.html

R. Bash 专题
来源：http://dali.jinqigufen.top/Article/details/gtluvuqzpb.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gthrdybaqq.html

[R01] shebang 与严格模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwwywzrx.html

#!/usr/bin/env bash
来源：http://dali.cucudq.cn/Article/details/gtqpzeeppc.html

set -euo pipefail
来源：http://dali.shzxlz.cn/Article/details/gtglrawryc.html

[R02] 变量赋值与使用
来源：http://dali.pengpengdd.cyou/Article/details/gtbzxktulh.html

name="Tom"; echo "$name"
来源：http://dali.jinqigfzy.top/Article/details/gthkyomrdh.html

[R03] 只读变量
来源：http://dali.dianchejie.cn/Article/details/gtfxexdwuo.html

readonly PI=3.14
来源：http://dali.jiagoushi.top/Article/details/gtqgefhxys.html

[R04] 位置参数
来源：http://dali.9152youxi.cn/Article/details/gtqfabntjd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhengqikj.top/Article/details/gtwmiwndrf.html

[R05] 参数默认值
来源：http://dali.hnqzz.top/Article/details/gtiswrzspo.html

name="${1:-default}"
来源：http://dali.iojbl.cn/Article/details/gtimqthtaj.html

[R06] 判断命令是否存在
来源：http://dali.ehwqpu.com/Article/details/gthfguoejs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gtqhzcwuko.html

[R07] if 判断文件
来源：http://dali.sufxvd.cn/Article/details/gtuylsyupd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.mhx1999.top/Article/details/gtiakxoseh.html

[R08] 数值比较
来源：http://dali.zhengqikj.top/Article/details/gttouwqias.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtinjjpgwb.html

[R09] 字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gtpvfdjvgl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuanzx.com/Article/details/gtgrznpcpy.html

[R10] 正则匹配
来源：http://dali.tian-w.cn/Article/details/gtycxsbfju.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hywenlv.cn/Article/details/gtnxlttwsm.html

[R11] case 多分支
来源：http://dali.gogol.net.cn/Article/details/gtiyegnsmm.html

case "$1" in
来源：http://dali.hfpthk.cn/Article/details/gtmyukdxri.html

start) echo "启动" ;;
来源：http://dali.aizwys.cn/Article/details/gtrttjklak.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gtlwjyikkv.html

*)     echo "未知命令" ;;
来源：http://dali.pycfn.com/Article/details/gtjdwjgpjp.html

esac
来源：http://dali.ybcxt.top/Article/details/gtfafkjfxm.html

[R12] for 遍历文件
来源：http://dali.hongshengwenyu.top/Article/details/gtgbxyohfd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuxming.cn/Article/details/gtmokxybkb.html

[R13] for 计数循环
来源：http://dali.hnqzz.top/Article/details/gtrtneemsz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gtxrnduaqi.html

[R14] C 风格 for
来源：http://dali.bjfxy.top/Article/details/gtekayrrnm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtbaswjqnf.html

[R15] while 逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtfdshmbdg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tian-w.cn/Article/details/gtrkagxoxv.html

[R16] until 等待条件
来源：http://dali.sweek.top/Article/details/gtngnlhjue.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gtikoduvmy.html

[R17] 数组定义与取值
来源：http://dali.yongpay.top/Article/details/gtztaypgtv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.mhx1999.top/Article/details/gtkiktstbi.html

[R18] 遍历数组
来源：http://dali.jinqigfzy.top/Article/details/gtjugbwhag.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jyoumei.cn/Article/details/gtbmzhhbmp.html

[R19] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gtnednjtik.html

echo "${#arr[@]}"
来源：http://dali.tanke756.top/Article/details/gtfroktqtc.html

[R20] 关联数组（字典）
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrivmaop.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.redwolf501.top/Article/details/gtsncgbxrj.html

[R21] 字符串长度
来源：http://dali.yonumen.top/Article/details/gtmmxbceqg.html

echo "${#s}"
来源：http://dali.xuanzx.com/Article/details/gtsddhktmf.html

[R22] 截取子串
来源：http://dali.ydzc1.top/Article/details/gttcexjtat.html

echo "${s:0:5}"
来源：http://dali.yongpay.top/Article/details/gthwdldeiq.html

[R23] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gtsymbqxsy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.316326.xyz/Article/details/gtkmnubqle.html

[R24] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gtfbiyuiak.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cqqwz.cn/Article/details/gtfljyanqo.html

[R25] 去后缀 / 去前缀
来源：http://dali.daxiang520.top/Article/details/gtttvvzlkl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yangfankeji.com/Article/details/gtuwtjgvfr.html

[R26] 命令替换
来源：http://dali.aibaodan.cn/Article/details/gtzotzqxuh.html

now=$(date +%F); echo "$now"
来源：http://dali.tianlin.xyz/Article/details/gtpphbczin.html

[R27] 算术展开
来源：http://dali.wangdashe.top/Article/details/gtuazbmyfd.html

echo $((1 + 2 * 3))
来源：http://dali.iojbl.cn/Article/details/gtucbeqtwd.html

[R28] 浮点运算
来源：http://dali.hnqzz.top/Article/details/gtgmcnzsab.html

echo "scale=2; 10/3" | bc
来源：http://dali.aizwys.cn/Article/details/gtnvrdwyoy.html

[R29] 定义函数
来源：http://dali.jinqigfzy.top/Article/details/gtykanqmpv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yongpay.top/Article/details/gtvwuwasdb.html

[R30] 函数返回状态码
来源：http://dali.cashguo.top/Article/details/gtkxqoywph.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jlsjyb.cn/Article/details/gtrcvpxzzv.html

[R31] 局部变量
来源：http://dali.shzxlz.cn/Article/details/gtvuubhdxr.html

f() { local x=1; echo "$x"; }
来源：http://dali.fengsongda.top/Article/details/gtwofyuphg.html

[R32] 参数个数校验
来源：http://dali.dashuyun.cn/Article/details/gtqhxfhmgr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gtdfqqxwfx.html

[R33] 捕获错误并提示行号
来源：http://dali.jlsjyb.cn/Article/details/gtrsiqdgno.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sysykeji.top/Article/details/gtdmhbwbag.html

[R34] 退出时清理
来源：http://dali.shuidangran.top/Article/details/gtmynxpsir.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gtxvfcjupp.html

[R35] 后台执行并等待
来源：http://dali.xylfe.cn/Article/details/gtriryrnsp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hongshengwenyu.top/Article/details/gtbguqhahp.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gtgketxgpl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gogol.net.cn/Article/details/gtqtuwywax.html

[R37] 把输出赋给变量
来源：http://dali.ppjwa.cn/Article/details/gtjdwixotm.html

files=$(ls -1)
来源：http://dali.0kj1m.cn/Article/details/gtwpvbqdwr.html

[R38] 管道串联
来源：http://dali.yj202588.top/Article/details/gtxvnemubz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.mhx1999.top/Article/details/gtgqzhvlku.html

[R39] 重定向标准输出与错误
来源：http://dali.gotoacloud.top/Article/details/gtwlnufgir.html

cmd > out.log 2>&1
来源：http://dali.9152youxi.cn/Article/details/gtzafdnpib.html

[R40] 追加写日志
来源：http://dali.cdnleiting.top/Article/details/gtboftbbut.html

echo "log" >> out.log
来源：http://dali.yongpay.top/Article/details/gtdbgfiszu.html

[R41] 丢弃输出
来源：http://dali.316326.xyz/Article/details/gtidvfkiwn.html

cmd >/dev/null 2>&1
来源：http://dali.aizwys.cn/Article/details/gtxuntcfzw.html

[R42] 输入重定向
来源：http://dali.dianchejie.cn/Article/details/gtbtvaqrmd.html

wc -l < a.txt
来源：http://dali.gzhubu.top/Article/details/gtwspzkwjm.html

[R43] 按名字查找文件
来源：http://dali.daxiang520.top/Article/details/gtuwmjmfkf.html

find . -name "*.log" -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjzcftgu.html

[R44] 按修改时间查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfrwfrlu.html

find . -mtime -7 -type f
来源：http://dali.zhengqikj.top/Article/details/gttugzcmdp.html

[R45] 批量删除
来源：http://dali.meibo888.top/Article/details/gtcvqjyjeh.html

find . -name "*.tmp" -delete
来源：http://dali.feifeiyinyue.top/Article/details/gtcbbmhbnt.html

[R46] 递归替换文件内容
来源：http://dali.daria6918.cn/Article/details/gtynabpzty.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cdnleiting.top/Article/details/gtsskglukz.html

[R47] sed 单行替换
来源：http://dali.feifeiyinyue.top/Article/details/gtthodjslx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtcrbugtgx.html

[R48] awk 取指定列
来源：http://dali.nwbrower.top/Article/details/gtchmlmxxd.html

awk '{print $1, $3}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gttphqazrz.html

[R49] awk 带条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusywadwd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sufxvd.cn/Article/details/gtrwlfnrnf.html

[R50] awk 求和
来源：http://dali.vqdsnc.cn/Article/details/gttlmiqtdi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtdlatbpuv.html

[R51] 排序去重取前几
来源：http://dali.shangyingyoupin.top/Article/details/gtwzlugzqz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jianghu66.top/Article/details/gtsjgrdbfu.html

[R52] 统计行数
来源：http://dali.0kj1m.cn/Article/details/gtpzxulydy.html

wc -l a.txt
来源：http://dali.yuanzhike.top/Article/details/gtbojkfnvy.html

[R53] 查看文件头与实时尾
来源：http://dali.xuanzx.com/Article/details/gtufqatavz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxpitekn.html

[R54] 比较两个文件
来源：http://dali.ehwqpu.com/Article/details/gtwohixwhp.html

diff a.txt b.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtypousmbt.html

[R55] 压缩与解压
来源：http://dali.aibaodan.cn/Article/details/gtxsbjbylg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.wangshuangyany.cn/Article/details/gtjgfoaavs.html

[R56] 远程拷贝
来源：http://dali.yonumen.top/Article/details/gtnzcdhass.html

scp file user@host:/path/
来源：http://dali.tianlin.xyz/Article/details/gtizeqsvnc.html

[R57] 远程执行命令
来源：http://dali.shzxlz.cn/Article/details/gthjzytfvt.html

ssh user@host 'uptime'
来源：http://dali.daria6918.cn/Article/details/gtepcklkxn.html

[R58] 下载文件
来源：http://dali.yj202588.top/Article/details/gtmfubtina.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nwbrower.top/Article/details/gtidkwtpol.html

[R59] 发 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtyfapfiaq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yangfankeji.com/Article/details/gtkivrpdbb.html

[R60] 只看 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtzhufoogq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258.top/Article/details/gtcvokqfct.html

[R61] 磁盘占用
来源：http://dali.zhoulong.xyz/Article/details/gtbaebhzol.html

df -h;  du -sh *
来源：http://dali.havefunace.top/Article/details/gtsxvdhdkw.html

[R62] 找最占空间的文件
来源：http://dali.hysaishi.cn/Article/details/gtvjsbpmoa.html

du -ah . | sort -rh | head -10
来源：http://dali.yuanzhike.top/Article/details/gtdivcyuqm.html

[R63] 内存与进程
来源：http://dali.chenlongwang.top/Article/details/gtdzvhqiuq.html

free -h;  ps aux | grep nginx
来源：http://dali.xuanzx.com/Article/details/gttixyqakl.html

[R64] 结束进程
来源：http://dali.vqdsnc.cn/Article/details/gtkduzvmkb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenjidiqi.icu/Article/details/gtglpcipty.html

[R65] 查看端口占用
来源：http://dali.xylfe.cn/Article/details/gtbqxgjckq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.feifeiyinyue.top/Article/details/gtznogemwh.html

[R66] 定时任务
来源：http://dali.svipenyu.cn/Article/details/gtvnabjien.html

crontab -e;  crontab -l
来源：http://dali.havefunace.top/Article/details/gtxufqoqct.html

[R67] 生成随机十六进制串
来源：http://dali.hnxiangtu.top/Article/details/gtscgdwyak.html

openssl rand -hex 16
来源：http://dali.cucudq.cn/Article/details/gtyknthybs.html

[R68] 计算文件校验值
来源：http://dali.fengsongda.top/Article/details/gtlmdtrqcb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.9152youxi.cn/Article/details/gtlekmwpxk.html

[R69] 生成随机密码
来源：http://dali.jinqigfzy.top/Article/details/gtpxjuoqun.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxinkj.top/Article/details/gtntwwaafa.html

[R70] 时间戳与互转
来源：http://dali.xuanzx.com/Article/details/gtutsykbmj.html

date +%s;  date -d @1700000000
来源：http://dali.yuxming.cn/Article/details/gtkmonluku.html

[R71] 日期格式化
来源：http://dali.hammf.cn/Article/details/gtfmailvvk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hysaishi.cn/Article/details/gtavjhwkch.html

[R72] 等待端口就绪
来源：http://dali.pycfn.com/Article/details/gtmepcyjzo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gtyjbdibjg.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gtgaxmqdha.html

split -l 1000 big.log part_
来源：http://dali.hnxiangtu.top/Article/details/gtgfnzdmsy.html

[R74] 批量重命名
来源：http://dali.sweek.top/Article/details/gtsqsekwao.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuanzx.com/Article/details/gtapjyykcz.html

[R75] 导出环境变量
来源：http://dali.hnqzz.top/Article/details/gtijuirnrx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.smart0.xyz/Article/details/gthdjhmbqy.html

[R76] 使用临时文件
来源：http://dali.jqgufenzy.top/Article/details/gttmefyjes.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gtsdwayndm.html

[R77] 读取用户输入
来源：http://dali.sufxvd.cn/Article/details/gtxwlrnrns.html

read -rp "请输入: " ans
来源：http://dali.jinqigfzy.top/Article/details/gtbijdnapj.html

[R78] 交互式菜单
来源：http://dali.shzxlz.cn/Article/details/gtbaxolhav.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj202588.top/Article/details/gtfiuzsuix.html

[R79] 解析命令行选项
来源：http://dali.gogol.net.cn/Article/details/gtvsvvjnuk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzgoviyf.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbljjjba.html

time ./run.sh
来源：http://dali.cucudq.cn/Article/details/gtwlppbami.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtnobjrkqg.html

S. C / C++ 专题
来源：http://dali.zhongyouzk.top/Article/details/gtwhlwlwzw.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gttvnlqjnu.html

[S01] C：Hello World
来源：http://dali.nwbrower.top/Article/details/gtygwbviop.html

#include <stdio.h>
来源：http://dali.zhixingplan.top/Article/details/gtczrxjmup.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cheryme.top/Article/details/gtcyshbwck.html

[S02] C：变量与格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gtxjrmjinm.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258.top/Article/details/gtyigvpjbd.html

[S03] C：读入整数
来源：http://dali.yanxiufei.cn/Article/details/gtjuvdosfl.html

int x; scanf("%d", &x);
来源：http://dali.tianlin.xyz/Article/details/gtozsibsvh.html

[S04] C：字符串复制
来源：http://dali.shangyingyoupin.top/Article/details/gtmmbrwins.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sweek.top/Article/details/gtlpdvdyav.html

[S05] C：字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtdovnkwtg.html

strlen(s)
来源：http://dali.quarkkingdee.top/Article/details/gtwrwtkjvi.html

[S06] C：字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gtaordjfwr.html

strcmp(a, b) == 0
来源：http://dali.gaohongyu789.top/Article/details/gtdexefmny.html

[S07] C：数组遍历求和
来源：http://dali.jqgufenzy.top/Article/details/gtjjjnldsl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ehwqpu.com/Article/details/gtippwcnlj.html

[S08] C：动态内存分配与释放
来源：http://dali.yanxiufei.cn/Article/details/gtqzwlwkjd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pengpengdd.cyou/Article/details/gtgpvvxcje.html

[S09] C：结构体定义与初始化
来源：http://dali.aibaodan.cn/Article/details/gtzvomdezh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cqqwz.cn/Article/details/gtllbuyslc.html

[S10] C：指针与解引用
来源：http://dali.iojbl.cn/Article/details/gtqfuvepdk.html

int *p = &a;  *p = 5;
来源：http://dali.sweek.top/Article/details/gtrkdkcigu.html

[S11] C：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtxxvcrqzq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.haohaochexian.top/Article/details/gtnokkwzdo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.vqdsnc.cn/Article/details/gteekjdcws.html

fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gthjvgyzzv.html

[S12] C：写文件
来源：http://dali.snrcjt.cn/Article/details/gtoqcegnhy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtkzlaxgqo.html

[S13] C：宏定义
来源：http://dali.jinqigfzy.top/Article/details/gtrxowuibi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xziqi.cn/Article/details/gtdtwbltll.html

[S14] C：枚举
来源：http://dali.cheryme.top/Article/details/gtlujrbcpb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjraqzkk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gtukqeohok.html

(double) a / b
来源：http://dali.shuidangran.top/Article/details/gtyhqufoga.html

[S16] C：位操作置位
来源：http://dali.hnqzz.top/Article/details/gtxfpuoeik.html

x |= (1 << 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtdkrxvulx.html

[S17] C：安全拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gtgbycksqe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258.top/Article/details/gtfhoxnhez.html

[S18] C：命令行参数
来源：http://dali.cashguo.top/Article/details/gtgovpykih.html

int main(int argc, char **argv)
来源：http://dali.xziqi.cn/Article/details/gtjxqmryft.html

[S19] C：快速排序
来源：http://dali.yanxiufei.cn/Article/details/gteqwqwfcy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gttseknvyv.html

[S20] C：二分查找
来源：http://dali.yongpay.top/Article/details/gtzplwlmxr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gtiftdzevf.html

[S21] C：字符类别判断
来源：http://dali.birdmap.top/Article/details/gtgwkteopu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gzhubu.top/Article/details/gtdckvqgki.html

[S22] C：字符串转数字
来源：http://dali.tianlin.xyz/Article/details/gtgxtipavt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yueranfly.top/Article/details/gtjpagsfii.html

[S23] C：随机数
来源：http://dali.yonumen.top/Article/details/gtbzbkvqnl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigfzy.top/Article/details/gtifoxydso.html

[S24] C：获取本地时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfotapby.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenlongwang.top/Article/details/gtqoeelwrt.html

[S25] C：内存拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtuwdnnqpe.html

memcpy(dst, src, n);
来源：http://dali.snrcjt.cn/Article/details/gtbpbwlynw.html

[S26] C：内存清零
来源：http://dali.yuxming.cn/Article/details/gtxccdxnrc.html

memset(a, 0, sizeof a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlohwvmha.html

[S27] C：定义常量
来源：http://dali.daria6918.cn/Article/details/gtbddrctez.html

const double PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtqbzngdzm.html

[S28] C：静态变量
来源：http://dali.nanxinkj.top/Article/details/gtxlznzsbw.html

static int counter = 0;
来源：http://dali.haohaochexian.top/Article/details/gtymoxummo.html

[S29] C：变参函数
来源：http://dali.daria6918.cn/Article/details/gtfagtuenm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yueranfly.top/Article/details/gtayawreii.html

[S30] C：头文件保护
来源：http://dali.quarkkingdee.top/Article/details/gtsklgviqu.html

#ifndef X_H
来源：http://dali.feifeiyinyue.top/Article/details/gtdfndolbk.html

#define X_H
来源：http://dali.snrcjt.cn/Article/details/gtirnuqqsv.html

#endif
来源：http://dali.pengpengdd.cyou/Article/details/gtidkbwlwy.html

[S31] C++：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtrdlthykq.html

#include <iostream>
来源：http://dali.shuidangran.top/Article/details/gtnzcvqnfe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jiagoushi.top/Article/details/gthluevhul.html

[S32] C++：字符串
来源：http://dali.bjfxy.top/Article/details/gthekmhpfp.html

std::string s = "hi";  s += "!";
来源：http://dali.cheryme.top/Article/details/gthqtlllcb.html

[S33] C++：vector 增删
来源：http://dali.birdmap.top/Article/details/gtkaveieta.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xinyue.icu/Article/details/gtitaoxsck.html

[S34] C++：遍历 vector
来源：http://dali.9152youxi.cn/Article/details/gtmwocsbmr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtahyxorha.html

[S35] C++：map
来源：http://dali.guowangkeji.top/Article/details/gtpzkgwfio.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtnhuwehpf.html

[S36] C++：unordered_map
来源：http://dali.ydzc1.top/Article/details/gtvzfpxdza.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtmhjnytkx.html

[S37] C++：set
来源：http://dali.yueranfly.top/Article/details/gtjojvbyro.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tian-w.cn/Article/details/gtrydizjgv.html

[S38] C++：排序
来源：http://dali.sufxvd.cn/Article/details/gtrmhzmcqw.html

std::sort(v.begin(), v.end());
来源：http://dali.meibo888.top/Article/details/gttvgjyuuc.html


<!-- 参考信息 -->